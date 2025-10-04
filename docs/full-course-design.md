---
title: Full Course Design & All Modules
layout: default
nav_order: 4
---

# **Designing a Modular AI Tools Course for a Beginner Research Assistant**

In this plan, we outline a **beginner-friendly, task-based course** that teaches a student how to leverage modern AI tools for research and creativity. The course is modular – lessons can be taken in any order – but we **recommend starting with AI Fluency foundations**. Each lesson introduces new AI tools or concepts with scaffolded, hands-on tasks. The student will capture outputs and reflections in **NotebookLM** (and optionally Notion) to practice using it as a research notebook. Over the course, the student will gain a solid foundation in **when and how to use AI tools**, core prompting skills (including meta-prompting and refinement), and critical evaluation of AI outputs.

## **Course Framework and Objectives**

**Learning Goals:**

* To be interesting, engaging, educational, and fun  
* Develop **AI fluency** using Anthropic’s 4D framework: **Delegation, Description, Discernment, Diligence**  . This means learning to strategically decide what tasks to give to AI, craft clear prompts, critically review AI outputs, and use AI **responsibly and ethically**  .  
* Introduce the **AI tool landscape**: text-based assistants (ChatGPT, Claude, Google’s Gemini, Perplexity, Notion AI), image generators (MidJourney, DALL·E), video generators (Runway Gen-2, Pika, Google Veo), coding copilots (Replit’s Ghostwriter, Lovable.dev), and others (speech-to-text apps, music generators, etc.).  
* Emphasize **research and study tools**: using AI for summarizing articles, gathering information with sources, and maintaining a well-organized research notebook (NotebookLM and/or Notion).  
* Teach **structured workflows** for complex tasks by chaining tools (for example: transcribe audio → refine text with ChatGPT → verify facts with Perplexity → compile notes in NotebookLM).  
* Build **practical skills** in prompt writing (e.g. providing context and examples), using advanced AI features, and recognizing AI hallucinations or biases.  
* By the end, the student will have a **comprehensive NotebookLM or Notion workspace** documenting her learning journey – including notes, AI outputs, images created, and reflections – essentially a portfolio of her AI experiments and research.

**Mobile-Friendly Approach:** The student primarily uses an **iPhone (iOS)**, so lessons highlight mobile-accessible tools. We include tips for using mobile apps or mobile web for each tool (e.g. ChatGPT app for iOS with voice input, Notion mobile app, Discord for MidJourney on mobile, etc.) where possible.

**Definition of Done:** Each lesson includes clearly defined tasks and an expected *output* (e.g. *“Summarize an article using NotebookLM and save the summary in your notebook”*). This makes it clear when the student has successfully completed the lesson. Many lessons also include a short reflection or quiz task (using NotebookLM’s features) to reinforce learning.

**Integration of NotebookLM:** NotebookLM (Google’s AI-powered research notebook) will be used throughout:

* Early lessons: as a simple **note-taking and Q\&A tool** – e.g. logging what was learned, asking it comprehension questions about course content.

* Middle lessons: as a **study companion** – e.g. uploading a PDF or web article and using NotebookLM to summarize or answer questions about it (demonstrating its *source-grounded* answers ).

* Later lessons: using NotebookLM’s advanced features (mind maps, automated summaries, etc.) to organize and present research findings.

* By the end, the student will be comfortable using NotebookLM for **all its core features** – study aid, comprehension Q\&A, multi-source analysis, and sharing results.

Next, we detail the **features of NotebookLM** and ensure we incorporate them into lessons, then outline the lessons and their tasks.

## **NotebookLM Capabilities and Role in the Course**

**What is NotebookLM?** NotebookLM (formerly Google’s Project Tailwind) is an AI research tool and “thinking partner” by Google . It allows you to create a digital notebook on a topic, upload various sources (Google Docs, PDFs, websites, YouTube transcripts, etc.), and then interact with an AI that has **read and indexed all those sources** . Unlike general chatbots, NotebookLM’s answers are **always grounded in your uploaded sources**, greatly reducing hallucinations and increasing trustworthiness . Key features we will leverage:

* **Source-grounded Q\&A:** The student can ask questions about the uploaded materials and get **cited answers** pointing to the sources  . This is perfect for learning how to verify AI answers.

* **Summarization & Study Guides:** NotebookLM can summarize long documents or even generate a **“study guide”** with quiz questions and a glossary from the sources  . We will use this to help the student learn how to extract key points and test herself.

* **Mind Map (Big Picture):** It can create an **interactive mind map** of key concepts across all sources in a notebook  . We’ll introduce this feature so she can visually see connections in her research.

* **Audio Podcast & Video Overviews:** One of the most exciting features is turning research into an **“AI-Generated Podcast”**, where two AI hosts discuss the content in a natural dialogue  . NotebookLM even allows an interactive mode where you can pause the podcast to ask questions and get clarification . It can also produce an **automated slideshow video** with AI narration and visuals drawn from your sources  . We will incorporate these *advanced* features in a later lesson to show creative ways to review material.

* **Briefing and FAQ documents:** It can produce a concise **briefing document** (2-3 page summary with citations) of all your notes , generate FAQs by identifying common questions in the material , and even create a chronological **timeline** of events from sources . These features will be demonstrated in context (e.g. timeline for a history research task).

* **Multi-source analysis:** NotebookLM can handle **up to 50 sources (25 million words)** in one notebook  . We will teach the student to aggregate sources on a topic and let the AI cross-analyze them – for example, comparing findings from multiple articles or videos. It can transcribe YouTube videos you add and make them searchable  , and extract content from web URLs.

* **Collaboration & Sharing:** Notebooks can be shared like Google Docs . In the final lesson, the student will share her NotebookLM or export content to demonstrate this capability.

*NotebookLM in Practice:* By weaving NotebookLM into each lesson, the student will gradually use all these features. For instance, early on she might simply **ask NotebookLM questions** about a study tip sheet (learning the Q\&A interface), whereas later she might **upload multiple sources on a topic and generate a mind map or briefing document** to synthesize them. This not only teaches NotebookLM itself, but also reinforces skills like verifying answers against sources and organizing information.

## **AI Tool Landscape Overview**

Before diving into specific lessons, it’s important to give the student a **lay of the land** of AI tools – what categories exist and what each tool is best for. Below is a brief overview, which we will cover in the course (likely as part of an early lesson):

* **Generative Text Assistants:** These are AI chatbots that can generate or analyze text.

  * **ChatGPT (OpenAI):** A versatile chatbot, great for brainstorming, writing drafts, explaining concepts, and coding help. *GPT-4* (in ChatGPT Plus) offers more advanced reasoning, while *GPT-3.5* is faster and available free. ChatGPT can also use **plugins or browsing** to fetch information (if enabled), and the mobile app supports **voice conversations** (you can speak to it and it talks back).

  * **Claude (Anthropic):** Another powerful chatbot, known for its *large context window* (it can read very long documents or chats) and helpfulness in detailed analyses. Good for processing longer texts (like entire PDF reports) in one go. There’s a free version at claude.ai (with some limits) and premium via API or partners.

  * **Google’s Gemini Assistant:** Google’s new AI assistant available via the **Gemini app** on iOS/Android  . It integrates with Google services and can handle tasks like writing, planning, brainstorming with access to your Gmail, Calendar, etc. (if you permit) . It’s essentially the next-gen Google Assistant with generative AI . *Use case:* quick help on your phone (“Gemini, summarize this email” or “draft a to-do list”). We’ll include a lesson where she tries the Gemini app for some daily task.

  * **Perplexity AI:** A chatbot that **searches the web** for you and provides answers with cited sources. Useful for research questions where up-to-date or factual info is needed. (No login required for basic use; has an iOS app). We will use this to practice verifying information and finding references, addressing *Discernment* (checking AI output) by seeing sources .

* **Image Generation AIs:** Tools that create images from text prompts.

  * **MidJourney:** A popular AI image generator known for high-quality, artistic images. It’s used via Discord (the student will need to **sign up for Discord and the MidJourney bot**, and a subscription \~$10/month, since free trial is limited). We will have a creative lesson where she **prompts MidJourney to create an image** (e.g. an illustration for a project or just something fun) and iterates on the prompt to get a desired style.

  
  * **Mobile use:** Both MidJourney, Chat GPT and Leonardo can be used on mobile. We’ll ensure instructions are mobile-friendly.

* **Video Generation AIs:**

  * **Runway Gen-2:** A tool that can generate short videos (a few seconds) from text prompts or from an image prompt. It’s available via a web app (with an **iOS app** for Gen-2 as well). Free tier allows a limited number of generations. We will include a task like “Create a 5-second video of X using Runway” to expose her to video AI.

  * **Pika Labs:** Another text-to-video tool (often accessed via their Discord). Could be mentioned as alternative to Runway. If accessible, she can try it to see different styles.

  * **Google Veo:** A cutting-edge Google AI for video (e.g. Veo 3\) which can create 8-second videos with sound from text or images . It’s usually accessed through Google’s AI Studio or Vertex AI platform , which might be advanced to set up. We may simply **demonstrate or show an example** rather than require her to use it, unless a simple interface is available. (If the student has a Google AI Pro account, Veo might be available .)

  * *Use case:* We might suggest a fun task like turning one of her MidJourney images into a short video with Runway or adding motion to a photo (if she’s interested in media).

* **Coding / App-Building AIs:**

  * **Replit’s Ghostwriter:** Replit is an in-browser coding environment. Ghostwriter is its AI assistant that can generate code and even generate whole projects. If the student wants to create a simple app, we could have a lesson using Replit \+ Ghostwriter (Replit has a free tier, Ghostwriter is paid but may have a free trial or limited use). Alternatively, using **ChatGPT’s Code Interpreter** (if available) or just GPT-4 to write code which she runs in Replit could work.

  * **Lovable.dev:** An AI app builder that can create full-stack apps from natural language prompts  . This is a no-code approach: you describe the app (e.g. “I want an app that tracks my study hours and shows a chart”), and Lovable generates it. We can include an optional project where she tries Lovable to scaffold an app idea.

  * **Vercel AI templates:** (Optional) Vercel is for deploying web apps; it has some AI starter templates. Possibly mention if she builds something in Replit, she can deploy it on Vercel.

  * *We will treat coding/apps as an optional or later module*, since it’s more advanced and might not be of primary interest. But exposure to the idea that AI can help build software is good, especially if she has a personal project idea like a website.

* **AI Discovery & Evaluation:**

  * **TAAFT (“There’s An AI For That”)** : A website that aggregates AI tools. It’s great for discovering new tools in various categories. We will have a short activity where she uses TAAFT (or a similar directory) to **find a new AI tool** related to her interests and evaluate it. This teaches her how to stay up-to-date in the fast-moving AI landscape and critically assess new tools.

  * **Product Hunt or AI news:** We might encourage occasional browsing of sites like Product Hunt (AI section) or following AI newsletters to know what’s new, as part of being *diligent* and staying current.

* **AI Assistants on Mobile:**

  * **Notion AI (as an assistant):** Notion now has features like an **“Ask a question”** or **“Help me write”** inside any page. On mobile, she can use the Notion app to ask Notion AI to summarize text or generate ideas in her notes.

  * **Gemini App:** Already mentioned under text assistants – this is effectively an AI assistant on the phone that can do some tasks via voice or chat. We’ll likely have her compare using **Gemini vs Siri vs ChatGPT app** for a simple task (to illustrate differences – e.g. Siri can do phone commands but is not generative, Gemini/ChatGPT can do creative answers but maybe not phone integration yet).

  * **Voice Input/Output:** Both ChatGPT and Gemini mobile apps support voice. So for “AI on the go,” we highlight she can **dictate questions** instead of typing, and have AI read out answers – useful when walking or multitasking.

* **Speech-to-Text Tools:**

  * **Otter.ai:** A popular transcription service with an iPhone app. She can record voice notes or even live meetings and get transcriptions. Free plan offers limited minutes per month. We plan a task where she **records a short audio (like describing her research idea), uses Otter to transcribe it, and then feeds that text to an AI for refinement**. This demonstrates an end-to-end workflow from voice to refined text.

  * **Whisper:** An open-source speech-to-text by OpenAI. There are apps or shortcuts on iOS that use Whisper for high-quality transcription (though a bit technical to set up offline). We might mention that **NotebookLM can transcribe audio files automatically** if uploaded , which is an interesting alternative – e.g. she could upload a podcast mp3 to NotebookLM and then query it.

  * **Google Recorder app:** (Pixel-only, so not for iOS) – skip since she’s on iOS. Instead, mention iPhone’s built-in voice dictation for quick notes and the new Live Voicemail transcription in iOS 17 as fun facts.

  * The focus is: **capture information on the go** (voice or photo) and bring it into her research workflow.

* **Music Generation AIs:**

  * **Suno’s Chirp or Bark** (for voice and music), **Udio**, **Boomy**, **AIVA** for music composition. We won’t go deep here, but perhaps one lesson or the final project can let her explore a music AI if she’s interested (e.g. “compose a theme song for your project using Boomy” or use AIVA to generate background music). Cost: Boomy has free track credits; AIVA has a free tier for non-commercial use.

  * These are mostly optional/fun, to show creative possibilities.

This landscape overview will be presented in the course (likely as a cheat-sheet or a mind map) so the student understands the breadth of AI tools and when to use each.

## **Module-Based Curriculum**

Each module braids four threads: (1) AI Fluency (4D), (2) Prompting skill, (3) NotebookLM capability, (4) Creative or applied task. This avoids front-loading theory while ensuring consistent hands-on progress.

### Course Structure

**Foundation Track** (Complete first, in order):
1. Module: Foundations Part 1 - Setup & Voice Workflows
2. Module: Foundations Part 2 - Delegation in Practice

**Core Skills Track** (Complete after Foundation, any order):
3. Module: Description - Visual Creativity & Image Generation
4. Module: Discernment - Source-Grounded Research
5. Module: Diligence - Synthesis & Long Context

**Applied Workflows Track** (Complete after Foundation, any order):
6. Module: Delegation & Description - End-to-End Research Workflow
7. Module: Description - Video & Multimedia Creation
8. Module: Delegation - Mobile Productivity
9. Module: Description & Diligence - Build Something Small

**Capstone Track** (Complete after Foundation + 3 other modules):
10. Module: All 4Ds - Personal Project & Portfolio

### NotebookLM Repository Protocol (applies to every module)

- Maintain notebooks organized by module or use a master notebook with module sections
- Add at least 2 factual, citable sources per module (official docs, transcripts, reputable articles, standards). Prefer primary/original sources.
- For each new source:
  - Run a Study Guide; answer at least 3 quiz questions, note any misses; ask 2 Q&A queries and click citations to verify.
  - Tag notes with module category and 4D focus (e.g., #CoreSkill #Description #Creative, #Foundation #Delegation #Applied).
- Use advanced features as scheduled (Mind Map, Audio/Video Overview, Briefing, FAQ, Timeline) and save outputs.
- End-of-module: write a 4D reflection and list prompts used (with final versions) in the notebook.

### **Module: Foundations Part 1 - Setup & Voice Workflows**

**Focus**: Install core AI tools, master voice interfaces, create NotebookLM portfolio, learn AI Fluency basics
**Key Activities**:
- Install NotebookLM, ChatGPT, Claude, and Otter on iPhone
- Set up voice capture workflows
- Study pre-Delegation AI Fluency sections
- Practice voice Q&A with 10 exchanges (5 ChatGPT, 5 Claude)
**Prerequisites**: None (entry point)

📄 **[Complete Module: Foundations Part 1 - Setup & Voice Workflows](Module%20-%20Foundations%20Part%201%20-%20Setup%20&%20Voice%20Workflows.md)**

### **Module: Foundations Part 2 - Delegation in Practice**

**Focus**: Apply Delegation principle through travel planning, verification exercises, first AI creations, critical feedback
**Key Activities**:
- Learn Delegation theory and travel context
- Complete 48-hour itinerary creation task with ChatGPT
- Conduct lunch hunt verification experiment (4 methods)
- Create AI travel card with DALL-E/Bing
- Submit critical course feedback
**Prerequisites**: Complete Foundations Part 1

📄 **[Complete Module: Foundations Part 2 - Delegation in Practice](Module%20-%20Foundations%20Part%202%20-%20Delegation%20in%20Practice.md)**

---

## **Additional Modules**
*(The following are detailed outlines - individual module files are created but content is being finalized)*

### **Module: Description - Visual Creativity & Image Generation**

**Focus**: Master descriptive prompting for AI image generation

- **What you learn (why)**: Description (the second D). Image prompting forces specificity; you practice translating intent into parameters.
- **Tools to install**: Discord app + MidJourney subscription (if funded) OR use Bing/DALL·E free; keep NotebookLM.
- **Prompting focus**: Apply 3P's to image prompts; iterate (subject, style, lighting, camera, post-process).
- **NotebookLM skill**: Upload your prompt/outputs as a mini case; use NotebookLM to summarize your prompt changes and outcomes.
- **Creative/applied**: Produce at least 2 image iterations (MidJourney or DALL·E); compare results, note what changed.
- **Definition of done**: 2+ images with prompts; brief note on which prompt tokens materially affected style; NotebookLM entry summarizing the experiment.
- **Accounts/Cost**: MidJourney ~$10/mo if used; otherwise free via Bing/DALL·E.
- **Sources to add this module**: Anthropic "Description" lesson transcript; MidJourney user guide or DALL·E usage/policy page.
- **AI Fluency study (NotebookLM)**: Study Guide on "Description" lesson; extract 3 best practices for clearer prompts and test them in image prompting.
- **Prompting guide (sources)**: Midjourney Docs — [Prompting](https://docs.midjourney.com/docs/prompting) and [Parameters](https://docs.midjourney.com/docs/parameters); OpenAI (DALL·E via ChatGPT) — see [Image generation overview](https://platform.openai.com/docs/guides/images). Summary: structure prompts as subject + style + composition + lighting + medium; iterate with parameters (`--ar`, `--stylize`, `--seed`) or provide image references; keep each change minimal to see causal effects.

**Lesson Ideas:**
- **Creative Exploration – Generating Images with AI**: Learn image prompting, iterative refinement, and ethical considerations. Tools: MidJourney, DALL·E, Bing Image Creator, Canva AI. NotebookLM: Document prompts, reflections, and compare outputs across tools.

### **Module: Discernment - Source-Grounded Research**

**Focus**: Develop critical evaluation skills for AI outputs and source verification

- **What you learn (why)**: Discernment (third D). Use Perplexity for cited answers and NotebookLM for study; learn to value sources over style.
- **Tools to install**: Perplexity (iOS/web), Notion (optional) for comparison.
- **Prompting focus**: Fact queries with constraints: "Answer with 3 bullet points and cite 2 diverse sources."
- **NotebookLM skill**: Q&A on uploaded article; generate a Study Guide; verify one fact via citation.
- **Creative/applied**: Summarize one article in NotebookLM, then compare with Notion AI or ChatGPT; record differences and which you trust (why).
- **Definition of done**: Study Guide generated; 1 verified citation; a short compare-and-trust note saved.
- **Accounts/Cost**: Free.
- **Sources to add this module**: Anthropic "Discernment" lesson transcript; 1 primary article relevant to your topic; Perplexity help page on citations.
- **AI Fluency study (NotebookLM)**: Study Guide on Discernment; log one example where a non-cited answer differed from a cited one and why you trusted the latter.
- **Prompting guide (sources)**: Perplexity Help — [How citations work](https://support.perplexity.ai/hc/en-us/articles/18538513167899-Citations) and [Ask better questions](https://support.perplexity.ai/hc/en-us/articles/18538527972251-How-to-Ask-Questions); Microsoft Learn — [Prompt engineering](https://learn.microsoft.com/azure/ai-services/openai/concepts/prompt-engineering). Summary: ask narrowly scoped, source-demanding questions; constrain format (bullets, table) and request diverse sources; verify through cited passages.

**Lesson Ideas:**
- **AI Fluency Foundations – The 4D Framework**: Introduction to structured AI thinking using Anthropic's 4D Framework. Tools: ChatGPT, Perplexity, Claude. NotebookLM: Store 4D summaries, test source-grounded Q&A, build initial notebook structure.
- **AI for Research – Summarizing and Studying Information**: Master research-oriented AI use for summarization, extraction, active reading. Tools: NotebookLM (central), Notion AI, ChatGPT, Scholarcy. NotebookLM: Generate Study Guides, Mind Maps, verify citations, compare AI summaries.

### **Module: Diligence - Synthesis & Long Context**

**Focus**: Handle long documents and create comprehensive syntheses

- **What you learn (why)**: Diligence (part 1) and handling longer materials; synthesize concepts across a source.
- **Tools to install**: Claude (web) for long inputs; maintain NotebookLM.
- **Prompting focus**: Prompt scaffolding for long text: section-by-section summaries → synthesis → open questions.
- **NotebookLM skill**: Create a Mind Map from your sources; generate an Audio Overview; capture one insight discovered via the visualization.
- **Creative/applied**: Turn your previous research sources into a 60–90 sec audio overview and share a takeaway.
- **Definition of done**: Mind Map explored (screenshot or note), Audio Overview generated, 1 synthesis paragraph recorded.
- **Accounts/Cost**: Free.
- **Sources to add this module**: Anthropic “Diligence” (ethics/risks) transcript; one long-form PDF (report/whitepaper) to test long-context synthesis.
- **AI Fluency study (NotebookLM)**: Use Study Guide on Diligence and produce a short FAQ from NotebookLM for ethical use scenarios you’re likely to face.
- **Prompting guide (sources)**: Anthropic — [Effective prompting with Claude](https://docs.anthropic.com/claude/docs/effective-prompting) and [Prompt Library](https://docs.anthropic.com/claude/prompt-library); Google — [Gemini prompting best practices](https://ai.google.dev/gemini-api/docs/prompting). Summary: break long tasks into sectional prompts, summarize then synthesize, and explicitly request citations or open questions; set role, constraints, and evaluation criteria.

**Lesson Ideas:**
- **AI Fluency Foundations – The 4D Framework** (Diligence component): Focus on ethical AI use, responsibility, bias checking. Tools: ChatGPT, Claude. NotebookLM: Create AI usage statement, document diligence practices.

### **Module: Delegation & Description - End-to-End Research Workflow**

**Focus**: Complete research pipeline from audio capture to final document

- **What you learn (why)**: Full chain builds operational fluency and error-spotting across steps.
- **Tools to install**: Otter (iOS) or Whisper via a web tool, Runway (web/app) for a short creative clip.
- **Prompting focus**: Refinement prompts: “Convert transcript to structured notes (headings, bullets, quotes). Flag uncertain claims.”
- **NotebookLM skill**: Upload transcript + 1 corroborating article; generate a Briefing Document (with citations) and optionally a Timeline.
- **Creative/applied**: Make a 4–6 sec Runway video related to your topic.
- **Definition of done**: Transcript captured; refined notes; 1 fact cross-checked with Perplexity; Briefing Document created; short video link saved.
- **Accounts/Cost**: Mostly free; Runway uses free credits (keep under quota).
- **Sources to add this module**: Your recorded lecture/podcast transcript; at least one corroborating peer-reviewed or reputable article; any Perplexity-cited reference you actually used.
- **AI Fluency study (NotebookLM)**: Combine your week’s sources and generate a Briefing Document; highlight where diligence (verification) changed your summary.
- **Prompting guide (sources)**: OpenAI — [Function calling](https://platform.openai.com/docs/guides/function-calling) (for tool use and structured outputs); Runway — [Gen-2 prompting tips](https://help.runwayml.com/hc/en-us/articles/19154045736347-Text-to-Video-Gen-2) (or search the Help Center). Summary: use refinement prompts to structure transcripts, flag uncertainties, then ground with retrieval/tools; for video, keep prompts concise, describe motion, camera, and style; iterate with seed for control.

**Lesson Ideas:**
- **Advanced Research Workflow – Combining Tools**: Complete workflow from unstructured input to organized summary. Tools: Otter/Whisper, ChatGPT, Perplexity, NotebookLM. NotebookLM: Central hub for transcript, fact-checking, Briefing Document generation.

### **Module: Delegation - Mobile Productivity**

- **What you learn (why)**: Sustainable habits; voice and capture flows reduce friction and increase adherence.
- **Tools to install**: Gemini app (iOS), Notion app + Web Clipper, ensure ChatGPT voice enabled.
- **Prompting focus**: Voice-first prompting: succinct task framing and confirmation prompts (“repeat back plan as checklist”).
- **NotebookLM skill**: Try Video Overview on an existing notebook; add saved mobile-clipped pages as sources.
- **Creative/applied**: Quick storyboard: 6-slide outline in NotebookLM or Notion; optionally narrate with Audio Overview.
- **Definition of done**: 1 voice session log; 1 clipped article added; Video Overview generated; storyboard saved.
- **Accounts/Cost**: Free.
- **Sources to add this module**: Gemini help/documentation page; at least one mobile-clipped article relevant to your ongoing topic.
- **AI Fluency study (NotebookLM)**: Turn previous module's Briefing into a Video Overview; self-quiz using Study Guide and note weak spots to revisit.
- **Prompting guide (sources)**: Google — [Gemini prompting best practices](https://ai.google.dev/gemini-api/docs/prompting); OpenAI — [Text generation best practices](https://platform.openai.com/docs/guides/text-generation). Summary: for voice-first, front-load task, constraints, and output format; ask the model to repeat back the plan as a checklist; use short, incremental turns on mobile.

**Lesson Ideas:**
- **Getting to Know AI Tools – Chatbots and When to Use Them**: Compare text-based AI assistants for different tasks. Tools: ChatGPT, Claude, Perplexity, Gemini. NotebookLM: Store comparisons, copy outputs, test multi-source search.
- **Personal Workflow and "AI on the Go"**: Mobile-optimized workflows, voice-first productivity. Tools: Gemini, ChatGPT voice, mobile-specific features. NotebookLM: Mobile source capture, voice note integration.

### **Module: Description & Diligence - Build Something Small**

- **What you learn (why)**: Agency through making; practice specification, iteration, and minimal deployment.
- **Tools to install**: Replit account (web) and/or Lovable.dev; Vercel (optional) for deploy.
- **Prompting focus**: Test-driven prompting: define acceptance criteria before asking for code/content.
- **NotebookLM skill**: Multi-source synthesis — aggregate brief specs, prompts, and outputs; query gaps (“What requirements remain unmet?”).
- **Creative/applied**: Ship a tiny artifact (web page, micro-tool, or visual asset) and share a link or screenshot.
- **Definition of done**: Artifact running or viewable; acceptance criteria checklist with pass/fail; NotebookLM synthesis note.
- **Accounts/Cost**: Free.
- **Sources to add this module**: Minimal spec (your own doc), a concise tutorial/reference for the chosen tool (Replit/Lovable), and any licensing/usage policy relevant to your artifact.
- **AI Fluency study (NotebookLM)**: Generate an FAQ from your spec + notes; answer FAQs and adjust prompts/spec accordingly (Description + Discernment in practice).
- **Prompting guide (sources)**: OpenAI Cookbook — [Techniques to improve reliability](https://github.com/openai/openai-cookbook); Replit — [Ghostwriter overview](https://help.replit.com/en/articles/6892199-ghostwriter-overview); Lovable — [Docs](https://docs.lovable.dev/). Summary: define acceptance criteria first; ask for code that satisfies tests/spec; require structured diffs or file lists; iterate with minimal changes per turn.

**Lesson Ideas:**
- **AI for Coding and App Creation**: Agency through making, specification, iteration, deployment. Tools: Replit, Lovable.dev, Vercel. NotebookLM: Multi-source synthesis, gap analysis, spec documentation.

### **Module: All 4Ds - Personal Project & Portfolio**

- **What you learn (why)**: Integrate 4D end-to-end; demonstrate verified, ethical use; present work.
- **Tools to install**: None new; ensure any subscriptions (MidJourney) still valid if needed.
- **Prompting focus**: Project plan prompts (Delegation matrix), revision prompts, and reflection prompts mapped to 4D.
- **NotebookLM skill**: Consolidate a shareable notebook (sources, briefs, overviews); export/share link.
- **Creative/applied**: Execute chosen project (research report, image set, micro-app, or short video) and present.
- **Definition of done**: Shareable NotebookLM portfolio; project artifact; 4D reflection (what you delegated, how you described, how you discerned, how you were diligent).
- **Accounts/Cost**: Reuse existing; minimal/no added cost.
- **Sources to add this module**: All final project sources (articles, transcripts, docs), plus your project plan and final reflection; ensure citations are complete.
- **AI Fluency study (NotebookLM)**: Create a comprehensive Briefing Document of your project notebook; pass a self-made quiz (10 Qs) from the Study Guide.
- **Prompting guide (sources)**: Microsoft Research — [Guidelines for Human-AI Interaction](https://www.microsoft.com/research/publication/guidelines-for-human-ai-interaction/). Summary: plan for clarification, error handling, escalation, and learning over time; add anti-loop prompts (reset/repair) to your project playbook.

**Lesson Ideas:**
- **Capstone Project – Design Your Own AI-Assisted Project**: Integrate all 4D skills in personal project. Tools: Various (student choice). NotebookLM: Portfolio consolidation, comprehensive Briefing Document, shareable notebook.
- **Finding and Evaluating New AI Tools**: Tool discovery, evaluation, responsible testing. Tools: TAAFT directories, various trial tools. NotebookLM: Tool comparison matrix, evaluation criteria documentation.

