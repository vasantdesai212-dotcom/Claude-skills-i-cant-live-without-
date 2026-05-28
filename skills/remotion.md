---
name: remotion
trigger: /remotion
description: >
  Create programmatic video trailers, launch videos, and brand clips using Remotion
  (a React-based video framework). Use this skill whenever you want to auto-generate
  a video from a website, brand assets, or written brief — no video editing required.
  Trigger with /remotion.
---

# Remotion Skill

A skill for generating launch videos, brand trailers, and promo clips using Remotion
— a framework that creates videos programmatically with React and code.

## What It Does

This skill takes a URL, brand brief, or set of assets and produces a complete video
using Remotion. It accesses your website or provided assets, pulls relevant visuals
and copy, and renders a polished video — typically in under 10 minutes.

No video editing software. No After Effects. Just a prompt.

## How to Use

1. Type `/remotion` in Claude
2. Provide one of the following:
   - A website URL (Claude will access and extract assets)
   - A brand brief (name, tagline, colors, key messages)
   - Existing image/logo assets
3. Specify video type (trailer, launch, product demo, etc.)
4. Claude builds the Remotion composition and renders the video

## Example

> **User:** Use the Remotion skill to create a trailer for my brand. helloisan.com
>
> *(~8 minutes later)*
>
> **Output:** A fully rendered video trailer using assets pulled from the website,
> with animated text, transitions, and brand-consistent styling.

## Video Types Supported

- **Brand Trailer** — Short cinematic intro for a brand or product
- **Launch Video** — Announcement-style video for a product or feature release
- **Course/Channel Intro** — Animated opener for YouTube or course platforms
- **Social Clip** — Vertical or square video for Instagram/TikTok/LinkedIn
- **Explainer** — Animated walkthrough of a concept or product

## Output

- Rendered `.mp4` video file
- Remotion source code (React/TypeScript) — reusable and editable
- Asset manifest

## Requirements

- Node.js and Remotion CLI installed (for local rendering)
- OR Claude handles rendering in-session if environment supports it

## Tips

- Provide brand colors and fonts for more on-brand output
- Share your logo as an SVG or PNG for best quality
- Specify aspect ratio: 16:9 (YouTube), 9:16 (Reels/TikTok), 1:1 (Feed)
- The more context you give, the better the video

---

*Trigger this skill with `/remotion` followed by your brand URL or brief.*
