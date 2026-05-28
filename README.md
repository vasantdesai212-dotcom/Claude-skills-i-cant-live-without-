# 🧠 Claude Skills — 10 Skills You Should Be Using in 2026

> A curated collection of Claude skills for creators, builders, and founders.
> Drop any `.md` file into your Claude skills folder and unlock superpowers instantly.

<div align="center">

![Claude Skills](https://img.shields.io/badge/Claude-Skills-blueviolet?style=for-the-badge&logo=anthropic)
![Skills](https://img.shields.io/badge/Skills-10-brightgreen?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)
![Year](https://img.shields.io/badge/Updated-2026-orange?style=for-the-badge)

</div>

---

## 📖 What Are Claude Skills?

Claude Skills are structured Markdown files (`.md`) that give Claude a specific set of
instructions, a persona, and a workflow — triggered by a simple slash command like `/hookforge`
or `/humanizer`. Think of them as plugins for Claude's brain.

This repo packages **10 production-ready skills** covering content creation, coding best
practices, business planning, decision making, and more.
---

## 🗂️ Skills Index

| # | Skill | Trigger | What It Does |
|---|-------|---------|-------------|
| 01 | [Skill Creator](#-skill-creator) | `/skill-creator` | Build any new skill through a guided interview |
| 02 | [Hook Forge](#-hook-forge) | `/hookforge` | Generate scroll-stopping content hooks |
| 03 | [Remotion](#-remotion) | `/remotion` | Auto-create brand videos from a URL or brief |
| 04 | [Humanizer](#-humanizer) | `/humanizer` | Rewrite AI slop into human-sounding text |
| 05 | [Infographic Builder](#-infographic-builder) | `/infographic-builder` | Build interactive infographics for any platform |
| 06 | [Karpathy Guidelines](#-karpathy-guidelines) | `/karpathy-guidelines` | Apply Andrej Karpathy's coding principles |
| 07 | [Caveman](#-caveman) | `/caveman` | Ultra-concise mode — saves ~75% tokens |
| 08 | [Expand & Contract](#-expand--contract) | `/expand-and-contract` | Turn a business idea into a full plan |
| 09 | [Find Skills](#-find-skills) | `/find-skills` | Auto-discover the right skill for any task |
| 10 | [Decision Framer](#-decision-framer) | `/decision-framer` | Make better decisions with structured reasoning |

---

## 🚀 Installation

### Option 1 — One Skill at a Time

1. Download the `.md` file for the skill you want
2. Open Claude → **Settings → Skills → Add Skill**
3. Upload the `.md` file
4. Use the trigger command in any conversation

### Option 2 — Clone the Whole Repo

```bash
git clone https://github.com/vasantdesai212-dotcom/Claude-skills-i-cant-live-without-.git
cd Claude-skills-i-cant-live-without-
```

Then add each skill file from the `/skills` directory to your Claude settings.

### Option 3 — Direct Download

Click any skill file below → **Raw** → Save as `.md` → Upload to Claude.

---

## 📦 Skill Details

---

### 🛠 Skill Creator

**File:** `skills/skill-creator.md` | **Trigger:** `/skill-creator`

The meta-skill. Use it to build any other skill you can imagine. Asks you a series of
targeted questions about what you want Claude to do, when it should trigger, and what
the output should look like — then generates a complete, ready-to-install `SKILL.md`.

```
/skill-creator
```

> "I want a skill that scans my emails and drafts replies in my tone."
> → Skill Creator builds it for you.

---

### 🎣 Hook Forge

**File:** `skills/hook-forge.md` | **Trigger:** `/hookforge`

Generates 5–10 scroll-stopping hooks for any content using proven psychological angles:
curiosity, contrast, controversy, social proof, FOMO, and empathy.

```
/hookforge Five GitHub repos every developer should know about
```

> In the content game, the hook is everything. A great hook can 3–5× the reach
> of the exact same content with a weak opener.

---

### 🎬 Remotion

**File:** `skills/remotion.md` | **Trigger:** `/remotion`

Creates programmatic video trailers and launch clips using the Remotion framework
(React-based). Point it at a URL or give it a brand brief — get a rendered `.mp4`
back in ~8 minutes. No video editing required.

```
/remotion create a trailer for my brand. helloisan.com
```

---

### ✍️ Humanizer

**File:** `skills/humanizer.md` | **Trigger:** `/humanizer`

Strips out every AI tell — em dashes, filler phrases, robotic structure — and rewrites
your text to sound like a real person wrote it. Produces 2–3 variants with different
tones. Includes one-click Gmail send via MCP.

```
/humanizer write a cold outreach email to Anthropic for a hackathon sponsorship
```

---

### 📊 Infographic Builder

**File:** `skills/infographic-builder.md` | **Trigger:** `/infographic-builder`

Turns any topic, list, or dataset into a fully interactive HTML infographic — with hover
animations, scroll effects, and platform-specific dimensions (Instagram, LinkedIn,
A4, etc.) across multiple visual styles.

```
/infographic-builder psychological tactics brands use to make you buy things.
Instagram feed. Bold Pop. Interactive with motion.
```

---

### ⚙️ Karpathy Guidelines

**File:** `skills/karpathy-guidelines.md` | **Trigger:** `/karpathy-guidelines`

Applies Andrej Karpathy's four engineering principles to any Claude Code project:

1. **Think before coding** — surface trade-offs first
2. **Simplicity first** — no unnecessary abstraction
3. **Surgical changes** — touch only what you must
4. **Goal-driven execution** — define success, loop until verified

Reduces token usage, catches over-engineering early, and produces cleaner code.

```
/karpathy-guidelines — review my project against these principles
```

---

### 🦴 Caveman

**File:** `skills/caveman.md` | **Trigger:** `/caveman`

Forces Claude into ultra-concise mode — only the essential answer, zero fluff.
Saves approximately **75% of tokens per response**. Essential when you're approaching
your session or API credit limit.

```
/caveman summarise the book Thinking Fast and Slow
```

---

### 💡 Expand & Contract

**File:** `skills/expand-and-contract.md` | **Trigger:** `/expand-and-contract`

A structured business brainstorming skill. First expands your idea into every possible
direction (services, pricing, GTM, positioning), then contracts it down to a focused,
actionable scope through a guided Q&A. Ends with a one-page business summary.

```
/expand-and-contract I want to start a luxury concierge service for HNI families in India
```

---

### 🔍 Find Skills

**File:** `skills/find-skills.md` | **Trigger:** `/find-skills`

Don't know which skill to use? Describe your problem and Find Skills searches
[skills.sh](https://skills.sh) to identify the best available skill — then applies it
automatically. The fastest way to discover skills you didn't know existed.

```
/find-skills write a LinkedIn post about the rise of AI agents in operations
```

---

### ⚖️ Decision Framer

**File:** `skills/decision-framer.md` | **Trigger:** `/decision-framer`

Replaces "ask ChatGPT what to do" with a structured, multi-framework decision analysis.
Maps all your options (including ones you haven't considered), surfaces hidden trade-offs,
and delivers a clear recommendation with reasoning — not a wishy-washy "it depends."

```
/decision-framer should I go all-in on Claude and drop ChatGPT and Gemini entirely?
```

---

## 📁 Repository Structure

```
Claude-skills-i-cant-live-without-/
├── README.md
└── skills/
    ├── skill-creator.md
    ├── hook-forge.md
    ├── remotion.md
    ├── humanizer.md
    ├── infographic-builder.md
    ├── karpathy-guidelines.md
    ├── caveman.md
    ├── expand-and-contract.md
    ├── find-skills.md
    └── decision-framer.md
```

---

## 🤝 Contributing

Contributions are welcome. If you've built a skill that deserves to be here:

1. Fork this repo
2. Add your `skill-name.md` to the `/skills` directory
3. Follow the existing frontmatter format (`name`, `trigger`, `description`)
4. Open a PR with a short description of what the skill does and when to use it

For large or complex skills, include a `skills/skill-name/` folder with a `SKILL.md`
and any supporting `references/` or `assets/`.

---

## 📜 License

MIT — use these skills however you want, personally or commercially.
Attribution appreciated but not required.

---

<div align="center">

**If this repo saved you time, drop a ⭐ — it helps others find it.**

</div>
