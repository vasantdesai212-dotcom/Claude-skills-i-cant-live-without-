---
name: find-skills
trigger: /find-skills
description: >
  Automatically find the best Claude skill for any task or problem by searching
  skills.sh — a directory of popular community-built Claude skills. Use this skill
  whenever you don't know which skill to use, want to discover new skills, or want
  Claude to automatically pick and apply the right skill for a given problem.
  Trigger with /find-skills.
---

# Find Skills

A skill that finds the right Claude skill for any problem — by searching the
skills.sh directory and automatically applying the best match.

## What It Does

Find Skills acts as a meta-skill: when you don't know which skill to use (or didn't
know a skill existed for your task), just describe your problem and Find Skills will:

1. Search [skills.sh](https://skills.sh) for relevant community skills
2. Identify the best match for your specific task
3. Apply that skill directly to solve your problem

It's the fastest way to discover and use the expanding ecosystem of Claude skills.

## How to Use

1. Type `/find-skills` in Claude
2. Describe the problem you want to solve (as naturally as you'd describe it to a person)
3. Find Skills searches skills.sh and identifies the right skill(s)
4. Claude applies the found skill and completes your task

## Example

> **User:** `/find-skills` — Write a LinkedIn post about the rise of the melody
> toffee and the parlay share
>
> **Find Skills:**
> 1. Searches skills.sh for content creation and LinkedIn skills
> 2. Finds the relevant story (PM Modi and Georgia Melanie context)
> 3. Identifies: `viral-script-writer` + `hook-forge` as best match
> 4. Generates hook options → writes the full LinkedIn post

## When to Use Find Skills

- You have a task but don't know if a skill exists for it
- You want the best possible skill for a specific content or workflow task
- You're new to Claude skills and exploring what's available
- You want Claude to handle skill selection automatically
- You're building a workflow and want to discover the ideal skill for each step

## What skills.sh Is

[skills.sh](https://skills.sh) is a community-maintained directory of Claude skills
covering hundreds of use cases — from content creation to data analysis, outreach,
coding, business planning, research, and more.

Find Skills uses it as its search index, so it always has access to the latest
available skills — not just the ones pre-installed.

## Output

- The skill(s) identified as best for your task
- A brief explanation of why that skill was chosen
- The completed task output using that skill

## Tips

- The more context you give, the better the skill match
- You can say "what skill should I use for X?" to get a recommendation without executing
- Combine with `/skill-creator` if no existing skill fits — build one
- Use it regularly to discover skills you didn't know existed

---

*Trigger this skill with `/find-skills` followed by your problem or task.*
