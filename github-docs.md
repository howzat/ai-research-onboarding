# Adding Just the Docs to Your Existing Repository

You have two methods:

## Method 1: Remote Theme (Easiest - No Gemfile needed)

This is the simplest approach for GitHub Pages.

### Step 1: Create `_config.yml` in your repository root

Create a new file called `_config.yml` with this content:

```yaml
# Site settings
title: AI Tools Onboarding Course
description: A mobile-first introduction to AI tools for researchers
baseurl: "/Onboarding" # the subpath of your site, e.g. /blog
url: "https://yourusername.github.io" # Replace with YOUR GitHub username

# Theme
remote_theme: just-the-docs/just-the-docs

# Enable search
search_enabled: true

# Aux links (optional - top right corner links)
aux_links:
  "View on GitHub":
    - "https://github.com/yourusername/Onboarding"
```

### Step 2: Add frontmatter to your existing markdown files

Edit each of your existing `.md` files to add frontmatter at the very top:

For your index/home page (create `index.md` if you don't have one):
```yaml
---
title: Home
layout: home
nav_order: 1
---

# Your content here
```

For each module:
```yaml
---
title: Foundations Part 1 - Setup & Voice Workflows
layout: default
nav_order: 2
---

# Your existing content here
```

### Step 3: Enable GitHub Pages

1. Go to repository Settings
2. Click "Pages" in sidebar
3. Under "Build and deployment" > "Source": Select **"Deploy from a branch"**
4. Branch: Select **"main"** (or whatever your default branch is)
5. Folder: Select **"/ (root)"** OR **"/docs"** if your markdown files are in a docs folder
6. Click Save

### Step 4: Wait for deployment (2-10 minutes)
- Go to Actions tab to watch the build
- Your site will be live at: `https://yourusername.github.io/Onboarding`

---

## Method 2: GitHub Actions (More control)

If you want more control, use GitHub Actions workflow:

### Step 1: Create the same `_config.yml` as above

### Step 2: Create GitHub Actions workflow

Create this file: `.github/workflows/pages.yml`

```yaml
name: Deploy Jekyll site to Pages

on:
  push:
    branches: ["main"]
  workflow_dispatch:

permissions:
  contents: read
  pages: write
  id-token: write

concurrency:
  group: "pages"
  cancel-in-progress: false

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - name: Checkout
        uses: actions/checkout@v4
      - name: Setup Pages
        uses: actions/configure-pages@v4
      - name: Build with Jekyll
        uses: actions/jekyll-build-pages@v1
      - name: Upload artifact
        uses: actions/upload-pages-artifact@v3

  deploy:
    environment:
      name: github-pages
      url: ${{ steps.deployment.outputs.page_url }}
    runs-on: ubuntu-latest
    needs: build
    steps:
      - name: Deploy to GitHub Pages
        id: deployment
        uses: actions/deploy-pages@v4
```

### Step 3: In GitHub Pages settings
- Source: Select **"GitHub Actions"**

### Step 4: Commit and push
- The workflow will automatically build and deploy

---

## Quick File Checklist

For your existing repository, you need to add:

```
Onboarding/
├── _config.yml                    (CREATE THIS - site config)
├── index.md                       (ADD frontmatter to existing or create)
├── Module - Foundations Part 1... (ADD frontmatter to top)
├── Module - Foundations Part 2... (ADD frontmatter to top)
├── CLAUDE.md                      (ADD nav_exclude: true to hide from site)
└── .github/
    └── workflows/
        └── pages.yml              (OPTIONAL - only for Actions method)
```

---

## Frontmatter Template for Your Files

**For files you want visible in navigation:**
```yaml
---
title: Page Title Here
layout: default
nav_order: 2
---
```

**For files you want to hide (like CLAUDE.md or README.md):**
```yaml
---
nav_exclude: true
---
```

---

## What About Your Current Filenames?

Your current files like:
- `Module - Foundations Part 1 - Setup & Voice Workflows.md`

Will work fine! Just add frontmatter to the top of each. The filename doesn't matter - the `title` in frontmatter is what appears in navigation.

You could optionally rename them to simpler names:
- `foundations-1.md`
- `foundations-2.md`

But it's not required.

---

## Recommendation for Your Repo

Since you already have the repository set up in Google Drive, I recommend:

1. **Create a GitHub repository** from your existing Onboarding folder
2. **Add `_config.yml`** (3 minutes)
3. **Add frontmatter to your 2 existing modules** (5 minutes)
4. **Enable GitHub Pages with "Deploy from branch"** (2 minutes)
5. **Done** - site goes live

Total time: ~15 minutes

---

## Understanding GitHub Pages vs Just the Docs

**GitHub Pages** = The hosting platform (the service that makes your files visible as a website)

**Just the Docs** = A theme/template that makes your markdown look good (navigation, search, mobile-friendly design)

Think of it like:
- **GitHub Pages** = The restaurant kitchen (where the cooking happens)
- **Just the Docs** = The recipe (how to make it look professional)

### Why Use Just the Docs?

Since your researcher needs to:
- Read on mobile (iPhone)
- Navigate between multiple modules
- Have a good reading experience

Just the Docs template adds:
- 📱 Mobile-friendly navigation (hamburger menu)
- 🔍 Search functionality
- 📚 Sidebar with all your modules listed
- ✨ Professional appearance

---

## What Gets Published vs What Stays Private

### ✅ Published to Website:
- All `.md` files in the repository root (unless excluded)
- Any files in Jekyll folders (`_includes/`, `_layouts/`, etc.)
- Files without `nav_exclude: true`

### ❌ NOT Published (Hidden from Website):
- Files you mark with `nav_exclude: true` won't appear in navigation
- Anything in `.gitignore`
- `README.md` is NOT shown on the site (only on GitHub)

### 🔒 To Keep Files Private:
**Don't add them to this repository at all.**

If you have notes, drafts, or private planning docs:
- Keep them in your Google Drive
- Keep them in a separate private GitHub repository
- Don't commit them to the public course repository

---

## Critical Pre-Publishing Checklist

Before you make the repository public:

- [ ] Remove any personal information (names, emails, addresses)
- [ ] Remove any company-confidential information
- [ ] Remove any API keys, passwords, or credentials
- [ ] Check all files for sensitive data
- [ ] Verify links work and don't point to internal/private resources

Based on your course content review: **Your current files look clean for public release** - they're instructional content without sensitive data.

---

## Updating the Site After Publishing

**To add/edit content:**

1. Edit markdown files directly on GitHub (click file > pencil icon)
2. OR clone repository, edit locally, commit and push
3. Every commit triggers automatic rebuild (1-3 minutes)
4. Changes appear on the live site automatically

**No build process on your computer needed** - GitHub handles everything.
