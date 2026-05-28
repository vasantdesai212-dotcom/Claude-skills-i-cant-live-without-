---
name: karpathy-guidelines
trigger: /karpathy-guidelines
description: >
  Apply Andrej Karpathy's engineering principles to any Claude Code project for
  cleaner, more efficient, and better-structured code. Use this skill at the start
  of any coding project or to audit existing code against these principles. Reduces
  token usage, speeds up execution, and produces maintainable output.
  Trigger with /karpathy-guidelines.
---

# Karpathy Guidelines

A skill that applies Andrej Karpathy's software engineering principles to Claude Code
projects — producing cleaner code, fewer wasted tokens, and faster execution.

## What It Does

When applied to a project, Claude reviews and enforces four core engineering principles
derived from Karpathy's approach to building software. It audits existing code,
identifies violations, and either fixes them or tells you exactly what to change.

This skill is especially valuable in Claude Code, where good structure saves credits
and improves output quality.

## The Four Principles

### 1. Think Before Coding
- Don't assume. Don't hide confusion.
- Surface trade-offs before writing a single line
- Ask clarifying questions upfront rather than guessing mid-way
- State your plan explicitly before executing

### 2. Simplicity First
- The simplest solution that works is the right solution
- Avoid premature abstraction
- No unnecessary layers, wrappers, or indirection
- If it can be done in 10 lines, don't write 50

### 3. Surgical Changes
- Touch only what you must
- Don't refactor code you weren't asked to touch
- Clean up only your own mess — leave existing code as-is unless it blocks your task
- Targeted edits > rewrites

### 4. Goal-Driven Execution
- Define success criteria before starting
- Loop until the goal is verified — not just until the code "looks right"
- Test outputs against the actual requirement, not your interpretation of it
- Ship when done, not when perfect

## How to Use

### At Project Start
```
/karpathy-guidelines — I'm building a [describe project]
```
Claude will internalize these principles and apply them throughout the session.

### To Audit Existing Code
```
/karpathy-guidelines — review this project against the guidelines
```
Claude will scan the codebase, identify violations across all four principles,
and provide a prioritized fix list.

### In Ongoing Sessions
Simply reference it at the start of any Claude Code session:
```
Use the Karpathy guidelines for this project.
```

## Example Output (Audit Mode)

> **Violations Found:**
> - `utils/helpers.js` — Over-abstracted. Three wrapper functions that call one native method. (Principle 2)
> - `api/routes.js` — Assumes JSON body without checking Content-Type. (Principle 1)
> - `README.md` — No defined success criteria for the auth module. (Principle 4)
>
> **Fixes Applied:** Collapsed wrapper functions, added Content-Type guard, added acceptance criteria to README.

## Why It Matters

In Claude Code, every unnecessary token costs credits and slows down execution.
This skill has been reported to save up to 40% of session credits by keeping
Claude focused, minimal, and goal-oriented — while also producing higher-quality code.

It's a must-have for anyone building seriously with Claude Code.

---

*Trigger this skill with `/karpathy-guidelines` at the start of any coding project.*
