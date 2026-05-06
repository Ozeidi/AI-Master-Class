# AI Master Class — Workshop Materials

Companion repository for the **AI Master Class** delivered on Wednesday, 6 May 2026.

> Run by **Omar Al Zeidi** · Practical AI for Work, Design & Development.

---

## 🚀 Start here

**👉 [Open the live workshop reference](https://ozeidi.github.io/AI-Master-Class/)**

This is the fastest way to get to the material. Open it, browse, copy prompts, run them in your tool of choice. No install needed.

If you'd rather run it offline, just open `index.html` from this repo in any modern browser — it works fully offline.

---

## 📊 Slide deck

**[AI Master Blueprint — Keynote slides (Google Slides)](https://docs.google.com/presentation/d/1ymnIp6hl4bmpMMDpy4G82aMr5upXhnhAq05ty-Snkis/edit?usp=sharing)**

The keynote walks through *why* AI matters (market size, ROI, job impact, energy footprint), the *skills and tools* landscape (prompt engineering, software dev, design, video, voice, workflow automation, agentic AI), and the *techniques* the top 1% use (cheat sheet, personalization, devil's advocate prompting). Use the slides for the narrative; use the HTML reference for the hands-on prompts.

---

## 📚 What's in this repo

| File | Purpose |
|------|---------|
| `index.html` | Interactive workshop reference — 19 ready-to-paste, gold-standard prompts mapped to the 7 workshop modules |
| `README.md` | This file |

The HTML is a single self-contained file. No build step, no dependencies, no backend. Drop it on any static host (GitHub Pages, S3, internal portal) or open it locally.

---

## 🧭 How to use the reference (`index.html`)

The reference is designed to work in three modes:

### 1. Live, during the workshop
- Project it on screen alongside the slides.
- The sticky sidebar lets you jump to any module in one click.
- Use the **filter chips** at the top to narrow down by module or by tool (Claude / ChatGPT / Gemini / NotebookLM) so the room only sees what's relevant to the current segment.

### 2. Hands-on, while you experiment
- Every gold-standard prompt has a **Copy** button — one click puts the full 4-part prompt (Persona / Context / Task / Format) on your clipboard.
- Where a prompt expects pasted content (an inbox to triage, raw meeting notes, rough status bullets, a logo brief), there's a **collapsed "Sample content for testing"** block right below it. Click to expand, copy the sample, paste it where the prompt says `[PASTE ... HERE]`. You can run every prompt end-to-end without using a single piece of real company data.
- Inline **⚠ Before you paste** notes flag where to anonymize PII before using public AI tools.

### 3. After the workshop, as a daily playbook
- Each use case is self-contained — find the one that matches your task, copy the prompt, customize the bracketed `[placeholders]`, run.
- The **Master Cheat Sheet** in Module 7 lists the six techniques (voice commands, iterative looping, negative constraints, meta-prompting, devil's advocate, personalization) with a one-line example for each.
- The closing **14-day mandate** (Module 7) is a self-coaching prompt — run it on day one and you'll have a 14-day micro-habit plan to embed AI into your daily work.

### Key features at a glance
- **Dark editorial design** — readable on screen for long sessions.
- **Single HTML file** — no JavaScript framework, no fonts beyond Google Fonts, no external assets you don't control.
- **Filter by module** — show only the use cases for the segment you're teaching.
- **Filter by tool** — show only Claude prompts, only ChatGPT prompts, etc.
- **Copy-to-clipboard** on every prompt and every sample.
- **Collapsible sample content** — opens on click, doesn't clutter the page when collapsed.
- **Sticky sidebar nav** — current section highlighted as you scroll.
- **Responsive** — sidebar collapses gracefully on narrow screens.

---

## 🗂️ The 7 modules at a glance

| # | Module | What you'll leave with |
|---|--------|------------------------|
| 01 | **Prompt Engineering essentials** | The 4-part structure as muscle memory, plus a Bad → Good → Gold rewrite drill |
| 02 | **The AI Landscape** | A clear "which tool when?" decision matrix — Claude, ChatGPT, Gemini, NotebookLM |
| 03 | **AI for Productivity** | Inbox triage, meeting minutes, weekly status, quick data analysis |
| 04 | **NotebookLM for document research** | Self-service policy bot, multi-PDF synthesis, onboarding podcasts |
| 05 | **AI for Design** | Posters, brand mini-systems, dashboard mockups |
| 06 | **AI for Web Development** | Leave calculators, internal landing pages, interactive dashboards — built without writing code |
| 07 | **Responsible AI + closing** | Six-point checklist, master cheat sheet, your 14-day mandate |

---

## 🎯 The closing mandate

> *"AI is not here to replace you — but the professional sitting next to you who masters these tools absolutely will."*

1. **Pick one tool.** Start using it today.
2. **Build a habit.** Use it for two weeks.
3. **Stack it.** Make it second nature.

---

## ✏️ Customizing for your team

If you want to adapt this for a different audience (Finance, Operations, IT, etc.):

1. Open `index.html` in any text editor.
2. The use-case scenarios and gold-standard prompts are plain text inside `<pre class="prompt-content">` blocks — find-and-replace any sector-specific framing with your function's reality.
3. The four sample-content blocks (UC 3.1, 3.2, 3.3, 5.2) live in `<pre class="sample-content">` — swap them for samples that match your function.
4. Keep the 4-part structure (Persona / Context / Task / Format) intact in every prompt — that's the whole point.

---

## 📜 License & credits

Workshop and materials by **Omar Al Zeidi**.

Free to reuse internally for non-commercial training and learning purposes. Attribution appreciated.

---

*Companion to the AI Master Blueprint keynote · 6 May 2026*
