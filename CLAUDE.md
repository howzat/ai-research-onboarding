# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.


## Project Overview

This repository contains an AI onboarding course designed for research assistants to learn AI tools through practical tasks. The course uses a flexible module-based approach with NotebookLM as the central knowledge management tool.

## Course Structure

The course follows a flexible module-based curriculum:

**Foundation Track** (Complete first, in order):
- Module: Foundations Part 1 - Setup & Voice Workflows
- Module: Foundations Part 2 - Delegation in Practice

**Core Skills Track** (Complete after Foundation, any order):
- Module: Description - Visual Creativity & Image Generation
- Module: Discernment - Source-Grounded Research
- Module: Diligence - Synthesis & Long Context

**Applied Workflows Track** (Complete after Foundation, any order):
- Module: Delegation & Description - End-to-End Research Workflow
- Module: Description - Video & Multimedia Creation
- Module: Delegation - Mobile Productivity
- Module: Description & Diligence - Build Something Small

**Capstone Track** (Complete after Foundation + 3 other modules):
- Module: All 4Ds - Personal Project & Portfolio

Key frameworks:
- **4D Framework**: Delegation, Description, Discernment, Diligence (from Anthropic's AI Fluency)
- **Mobile-first**: Designed for iOS users with emphasis on voice workflows
- **Task-based**: Each module includes practical tasks with clear "Definition of Done"

## Key Files

- `Initial Prompt - Prompt.md`: Course requirements and high-level design
- `Module - Foundations Part 1 - Setup & Voice Workflows.md`: Setup, voice workflows, initial AI Fluency sections
- `Module - Foundations Part 2 - Delegation in Practice.md`: Delegation practice, travel planning tasks
- `Onboarding Research and Orientation (AI).md`: Comprehensive course design with all modules detailed
- `Module Template.md`: Template for creating new modules

## Development Guidelines

When modifying course content:

1. **Mobile-first design**: All tasks must be completable on iPhone
2. **NotebookLM integration**: Every week requires adding sources, using Study Guides, and Q&A features
3. **Voice workflows**: Prioritize voice input methods (ChatGPT voice, iOS Dictation, Otter)
4. **Clear task completion**: Each task needs explicit "Definition of Done" criteria
5. **NO time estimates**: Never include time estimates for tasks - they vary significantly based on user context, mobile connection, prior knowledge, and work style. Students work at their own pace.
6. **Critical feedback**: Week modules should include reflection/feedback sections

## Course Architecture

The course braids four threads throughout each week:
1. AI Fluency (4D Framework)
2. Prompting skill development
3. NotebookLM capability exploration
4. Creative/applied tasks

## Tools & Accounts

Core tools used across the course:
- **NotebookLM** (Google account required)
- **ChatGPT** (iOS app with voice)
- **Claude** (iOS app with Dictation)
- **Otter** (transcription)
- **Perplexity** (research with citations)
- **MidJourney/DALL-E** (image generation)
- **Runway** (video generation)

## Common Commands

Since this is a course content repository (not code), typical development commands don't apply. However:

```bash
# To review course structure
find . -name "*.md" -type f | sort

# To check word count for timing estimates
wc -w "Module - Foundations Part 1 - Setup & Voice Workflows.md"
```

## Important Notes

- Course is designed for a student who is traveling through Europe
- Emphasis on practical research skills and AI tool evaluation
- Foundation modules must be completed first; other modules are flexible in order
- Each module focuses on specific 4D skills (Delegation, Description, Discernment, Diligence)
- Cost considerations are included (most tools have free tiers)
- Critical feedback is explicitly requested to improve the course


# Claude Code Session Preferences

**IMPORTANT**: These are the user's explicit preferences. Read this file at the start of every session.

## Commit Message Rules

### ❌ DO NOT ADD:
- **NO emojis** in commit messages (unless explicitly requested)
- **NO Claude Code attribution footer** (🤖 Generated with [Claude Code]...)
- **NO Co-Authored-By: Claude** footer

### ✅ DO ADD:
- Conventional commit format (feat:, fix:, refactor:, docs:, etc.)
- Clear, descriptive commit messages
- Implementation details in commit body

### Rules for Creating Great Commit Messages:
1. **Limit subject line to 50 characters**
2. **Capitalize the subject/description line**
3. **Do not end subject line with a period**
4. **Separate subject from body with a blank line**
5. **Wrap body at 72 characters**
6. **Use body to explain what and why** (not how - code shows how)
7. **Use imperative mood in subject** (like giving a command)
    - Good: "Add unit tests for authentication"
    - Bad: "Added unit tests" or "Adds unit tests"

## Example Correct Commit:

```
feat: Implement certificate management for CDP

Add CDP-compliant certificate management for MongoDB and HTTP
clients:

- Scan TRUSTSTORE_* environment variables for custom CAs
- Load base64-encoded PEM certificates with error handling
- Create SSLContext combining JVM defaults with CDP certificates
- Configure MongoDB client with custom SSL for AWS IAM auth
- Configure RestClient and RestTemplate with custom SSL
```

Note: Subject is 47 characters, imperative mood, capitalized, no
period. Body wrapped at 72 characters and explains what/why.
- Whenever using git commands or gh tool, you MUST remember to apply the git commit rules we've established in CLAUDE.md