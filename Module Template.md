# Module Template — AI Tools Research Course

References: `Initial Prompt - Prompt.md`, `Onboarding Research and Orientation (AI).md`

Use this template to create a new module that braids: AI Fluency (4D), Prompting skill, NotebookLM capability, and a creative/applied task. Keep module outputs source-grounded in NotebookLM.

---

## 1) Module Metadata
- **Module Title**: [4D Focus - Module Name]
- **Theme strands**:
  - **AI Fluency (4D)**: [Delegation | Description | Discernment | Diligence]
  - **Prompting skill**: [e.g., 3P’s; few-shot; structured output; tool-use]
  - **NotebookLM capability**: [e.g., Q&A with citations; Study Guide; Mind Map; Audio/Video Overview; Briefing; FAQ; Timeline]
  - **Creative/applied task**: [e.g., image set; short video; micro-app; briefing]

## 2) Setup
- **Tools to install/open**: [ChatGPT / Claude / Gemini / Perplexity / MidJourney / Runway / Replit / Notion / Otter / etc.]
- **Accounts & logins**: [Google (NotebookLM), OpenAI, Anthropic, Discord, Microsoft, etc.]
- **Cost**: [Free | Credits | $X/mo]

## 3) Learning Goals (What/Why)
- [Goal 1 aligned to 4D]
- [Goal 2 aligned to prompting skill]
- [Goal 3 aligned to NotebookLM capability]
- [Goal 4 aligned to creative/applied output]

## 4) Sources to Add to NotebookLM (Repository Protocol)
Add at least 2 factual/citable sources and operate NotebookLM features for study:
- [Anthropic AI Fluency material relevant this module]
- [Official tool docs/help page(s) for this module’s tool]
- [Optional: 1 primary article/PDF relevant to the module topic]
Then in NotebookLM:
- Generate a **Study Guide**; answer ≥3 quiz Qs; save unknown glossary terms
- Ask ≥2 **Q&A** queries and click citations to verify
- Tag notes: `#<Category> #<4D> #<Tool> #<Capability>`

## 5) Tool-Specific Prompting Guide
- **Official links**:
  - [OpenAI — Text generation best practices](https://platform.openai.com/docs/guides/text-generation)
  - [Anthropic — Effective prompting](https://docs.anthropic.com/claude/docs/effective-prompting) / [Prompt Library](https://docs.anthropic.com/claude/prompt-library)
  - [Google — Gemini prompting best practices](https://ai.google.dev/gemini-api/docs/prompting)
  - [Microsoft Learn — Prompt engineering](https://learn.microsoft.com/azure/ai-services/openai/concepts/prompt-engineering)
  - [Midjourney Docs — Prompting](https://docs.midjourney.com/docs/prompting) / [Parameters](https://docs.midjourney.com/docs/parameters)
  - [Perplexity — Citations](https://support.perplexity.ai/hc/en-us/articles/18538513167899-Citations) / [How to Ask Questions](https://support.perplexity.ai/hc/en-us/articles/18538527972251-How-to-Ask-Questions)
  - [Runway — Gen-2 Text-to-Video](https://help.runwayml.com/hc/en-us/articles/19154045736347-Text-to-Video-Gen-2)
- **3–5 line distilled guidance (this module’s tool/task)**:
  - [One-liner 1]
  - [One-liner 2]
  - [One-liner 3]
- **Patterns to practice**:
  - [Pattern 1]
  - [Pattern 2]
  - [Pattern 3]
- **Common pitfalls & anti-loop SOP**:
  - If repeating, summarize goal in one sentence and ask a new clarifying question
  - Switch strategy (outline → step-by-step → example-first) after one repeat
  - Add a break condition: if stuck, ask user to choose [restate | provide data | start fresh]

## 6) Prompt Skeletons (copy, fill, iterate)
- **ChatGPT / Claude (single-shot, structured)**
```text
You are [role]. Task: [task].
Context (delimited):
<<<CONTEXT
[brief facts/example]
CONTEXT>>>
Requirements:
- Output format: JSON with keys [keys]
- Constraints: [tone, length, citations if any]
- Steps: think step-by-step but return only JSON
Self-check: verify the output meets [criteria]; if not, revise once.
```

- **Perplexity (cited, source-diverse query)**
```text
Query: [narrow question].
Requirements: provide 3–5 bullet points with inline citations; prioritize diverse, reputable sources; include 1 counterpoint if applicable.
```

- **MidJourney (/imagine)**
```text
/imagine "[subject], [style/movement], [composition/framing], [lighting], [medium/render], [mood/details] --ar W:H --stylize S --seed SEED [--tile/--niji/etc]"
```

- **Runway Gen-2 (text-to-video)**
```text
[subject/action], [camera movement], [shot type], [environment], [lighting], [style]; duration ~4–6s; minimal adjectives; 1–2 motions.
```

- **Gemini mobile (voice-first)**
```text
Goal: [task]. Constraints: [time/format].
Please repeat back a 3-step plan as a checklist; then ask one clarifying question before proceeding.
```

## 7) Activities & Tasks (with times)
- [5–10m] Setup & accounts
- [15–20m] Prompting practice (use skeletons)
- [25–35m] NotebookLM: add sources, Study Guide, Q&A with citations
- [15–25m] Creative/applied task (iterate once)
- [10m] Reflection and repository updates

## 8) Definition of Done (DoD)
- [Artifact saved/shared: link/screenshot]
- [NotebookLM: sources added, Study Guide done, ≥2 cited Q&A captured]
- [Prompt(s) final version recorded]
- [4D reflection completed]

## 9) Assessment Rubric (quick)
- **Clarity (prompting)**: clear, constrained, testable (0–2)
- **Grounding (citations)**: verified, source-diverse (0–2)
- **Iteration quality**: meaningful, minimal-change deltas (0–2)
- **Output fit**: meets acceptance criteria (0–2)
- **Diligence**: ethics/safety considered (0–2)

## 10) NotebookLM Use (this module)
- Feature focus: [Q&A | Study Guide | Mind Map | Audio/Video Overview | Briefing | FAQ | Timeline]
- Save outputs (audio/video/briefing/FAQ) and link inside the module section

## 11) Reflection (4D)
- **Delegation**: What did you delegate to AI vs keep?
- **Description**: Which prompt elements moved the needle?
- **Discernment**: Where did citations change conclusions?
- **Diligence**: Any risks, rights, or biases you addressed?

## 12) Accessibility & Mobile
- [Voice input fallback; small-screen steps; low-bandwidth options]

## 13) Data Ethics & Safety
- [Usage rights for images/audio; privacy for transcripts; transparency notes]

## 14) Appendices
- **Anti-loop SOP snippets**
```text
If I repeat a request or ask the same question twice, pause and:
1) Summarize the goal in one sentence
2) Propose 3 interpretations to choose from
3) Offer: [A] restate goal, [B] provide missing data, [C] start fresh
```
- **Module checklists**
  - Setup ✅  | Sources ✅  | Q&A ✅  | Study Guide ✅  | Artifact ✅  | DoD logged ✅

---

Instructions: Duplicate this template for each new module. Ensure the official prompting links and distilled guidance match the tool(s) in focus, and add those sources to NotebookLM per the Repository Protocol.
