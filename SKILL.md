---
name: leo-landing-html
description: "Use when converting a Markdown analysis or documentation file into a branded HTML landing page in the leogistics style, especially when the request mentions Style_leogistics.html, 220201_Leo_Guidelines_V4, Leo CI colors, logo placement, or a Leo landing page."
---

# Leo Landing HTML Skill

## Purpose
Create a polished HTML landing page from an existing Markdown document using the leogistics visual language.

## Source of Truth
Use these project assets as the design basis:
- `Style_leogistics.html` for structure, spacing, component treatment, and hierarchy
- `220201_Leo_Guidelines_V4.pptx` for color palette, typography, logo usage, and brand tone
- Existing Leo logo assets in the workspace when available

## Required Brand Rules
- Use the Leo color system:
  - Blue `#39769F`
  - Deep blue `#172436`
  - Yellow `#EFD100`
  - Grey `#727272`
- Prefer `Raleway` for headlines and `Roboto` for body text.
- Keep backgrounds clean and high contrast.
- Use the Leo logo prominently in the hero/header and again in the footer when appropriate.
- Keep the layout professional, structured, and slightly editorial.
- Avoid purple accents, generic SaaS styling, and non-Leo palettes.

## Workflow
1. Read the Markdown source and identify the core message, sections, tables, and code blocks.
2. Mirror the structure into a landing page with:
   - a strong hero section
   - a sticky or prominent navigation area
   - clear content sections
   - a compact sidebar or meta area when useful
   - a branded footer
3. Preserve technical content faithfully, but rewrite it for a presentation-friendly HTML layout.
4. Convert tables, code snippets, and reference lists into HTML components with consistent styling.
5. If the document contains multiple conceptual layers, separate them into distinct sections with numbered headings.
6. Highlight the main takeaway near the top so the page reads like a landing page, not a raw document dump.

## HTML Expectations
- Use semantic HTML5.
- Keep CSS self-contained in the page unless the task explicitly requests external assets.
- Make navigation anchors smooth and reliable.
- Use responsive layout behavior for desktop and mobile.
- Keep typography readable and spacing generous.
- Use callouts or answer boxes only where they add clarity.

## Validation Checklist
Before finishing, confirm:
- the page opens cleanly in a browser
- headings and anchors match the content structure
- the Leo palette is used consistently
- the logo is legible and correctly contrasted
- the page feels like a branded landing page rather than a plain documentation export

## When Not to Use
Do not use this skill for unrelated HTML work that does not involve Leo branding or Markdown-to-landing-page conversion.
