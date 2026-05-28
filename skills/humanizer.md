---
name: humanizer
trigger: /humanizer
description: >
  Transform generic AI-generated text into natural, human-sounding writing that
  avoids common AI tells (em dashes, filler phrases, robotic structure). Use this
  skill whenever you want to write emails, messages, posts, or any content that
  should sound like a real person wrote it. Includes Gmail send integration.
  Trigger with /humanizer.
---

# Humanizer

A skill that converts AI-generated slop into clean, direct, human-sounding writing.

## What It Does

Humanizer takes any prompt or AI-generated draft and rewrites it to:
- Sound like a real human with a clear voice and intent
- Remove AI tells: no em dashes, no "certainly!", no generic filler
- Match the tone you specify (casual, warm, confident, formal, etc.)
- Get straight to the point without padding or hedging

It then offers to send the result directly via Gmail (when Gmail MCP is connected).

## How to Use

1. Type `/humanizer` in Claude
2. Describe what you want to write, OR paste a draft to rewrite
3. Specify tone if needed (e.g., "confident but warm", "direct", "casual")
4. Review the 2–3 generated variants
5. Click **Send via Gmail** to send directly, or copy and paste

## Example

> **User:** `/humanizer` Generate a catchy email for a brand I want to reach out to,
> asking them to sponsor my hackathon.
>
> **Humanizer:** Who are you reaching out to?
>
> **User:** Publicity, OpenAI, Anthropic — around AI agents and workflows. Title sponsor.
>
> **Output:** Three email variants — direct, human, no em dashes, straight to the value prop.

## What Gets Removed

| AI Writing Tell | Human Replacement |
|----------------|-------------------|
| Em dashes (—) | Commas or restructured sentences |
| "Certainly!" / "Great question!" | Direct response, no preamble |
| Passive hedging ("It might be worth considering...") | Direct statement |
| Over-explanation | Concise, purposeful sentences |
| Formulaic structure | Natural flow matching the goal |

## Tone Options

You can specify any tone. Common options:
- `confident and warm` — for outreach and partnerships
- `casual` — for peer messages and community posts
- `direct` — for follow-ups and asks
- `professional` — for formal business communication
- `no-nonsense` — for internal Slack or quick updates

## Output

- 2–3 human-sounding variants of the requested content
- Each labeled by approach (e.g., "Lead with value", "Short and punchy")
- Optional: one-click Gmail send via MCP integration

## Tips

- Mention the recipient's name and context for a more personalized result
- Reference a specific piece of their work or content for outreach that gets replies
- Pair with Whisper Flow (voice-to-text) for the fastest workflow: speak → humanize → send

---

*Trigger this skill with `/humanizer` and describe what you want to write.*
