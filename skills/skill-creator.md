---
name: skill-creator
trigger: /skill-creator
description: >
  Create any custom Claude skill from scratch by answering a series of guided questions.
  Use this skill whenever you want to build a new skill, automate a workflow, or turn
  a repeating task into a reusable Claude command. Trigger with /skill-creator.
---

# Skill Creator

A skill for creating brand-new Claude skills through a guided interview process.

## What It Does

When triggered, the Skill Creator asks you a series of targeted questions to understand:
- What you want the skill to do
- When it should trigger (what phrases or contexts activate it)
- What the expected output looks like
- Any edge cases, dependencies, or example inputs/outputs

Once enough context is gathered, it writes a complete `SKILL.md` file — the structured Markdown file that defines how Claude should behave when that skill is active.

## How to Use

1. Type `/skill-creator` in Claude
2. Answer the questions Claude asks about your desired skill
3. Review the generated `SKILL.md`
4. Iterate and refine as needed

## Example

> **User:** I want a skill that scans YouTube channels and finds brand sponsorship opportunities from the last 6 months.
>
> **Skill Creator:** What kind of channels do you want to scan? How should results be ranked? What output format do you prefer?
>
> *(After a few questions, it produces a complete SKILL.md for "YouTube Brand Scout")*

## Output

A complete `SKILL.md` file with:
- YAML frontmatter (name, trigger, description)
- Step-by-step instructions for Claude
- Edge case handling
- Output format specification

## Tips

- Be as specific as possible about what you want the skill to do
- Mention any tools, MCPs, or external services the skill should use
- You can always iterate — run `/skill-creator` again to refine an existing skill

---

*Pre-installed with Claude. Access anytime via `/skill-creator`.*
