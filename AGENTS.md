# Codex instruction brief for Sela's Creations

## Goal
Create a single experimental branch update for my small static portfolio site that performs only the requested structural and content changes **without changing its core identity or adding unsolicited redesign choices**.

## What this site is
This is a minimalist personal portfolio / digital business-card website for **Sela's Creations**. It represents a person who works across **programming** and **screenwriting**. The site is intentionally simple, lightweight, and handcrafted.

## Core concept to preserve
- Keep the **business-card** feel.
- Keep the **actual sizing ratios** based on Australian business card proportions for landscape content boxes/cards.
- Preserve the card-like dimensions as part of the brand concept, not just the vibe.
- Keep the **minimalist** layout.
- Keep the **dark, elegant, slightly creative** visual tone.
- Keep the existing **colour palette / branding direction**.
- Keep the **handwritten logo** as the main personality element.
- Keep the rest of the typography clean and restrained.
- Keep the site **static and lightweight**.
- Do **not** introduce a framework.
- Do **not** make it flashy, generic, overly corporate, or template-like.

## Main tasks
Please do all of the following in one experimental pass, and do not add extra creative changes beyond these requests:

1. **Refactor duplicated CSS**
   - Move all shared styles currently repeated across pages into a single external stylesheet.
   - Use something like `assets/style.css`.
   - Preserve the current look unless a small improvement is needed.
   - Leave only page-specific styles where appropriate.

2. **Improve responsiveness and spacing**
   - Fix obvious mobile layout and spacing issues.
   - Make the layout behave better on smaller screens.
   - Preserve the current design concept while making it more robust.

3. **Polish typography**
   - Keep the current system font stack for site text.
   - Improve sizing, spacing, hierarchy, alignment, and readability.
   - Do not introduce decorative fonts for the general UI.
   - The logo should remain the expressive part; the rest should stay clean.

4. **Add restrained hover states / interaction polish**
   - Add subtle hover/focus states for navigation and links.
   - Keep effects smooth, minimal, and professional.
   - No flashy animations.

5. **Add two project pages now**
   - Create separate pages for:
     - Programming Projects
     - Screenwriting Projects
   - Use the same overall visual language and card proportions as the existing site.
   - Keep them simple.
   - In the centre of each card, place a small tasteful note saying `Coming Soon`.
   - Add navigation links to these pages in a clean way that matches the existing style.

6. **Use the logo properly**
   - Change the site to use the SVG logo as the primary version.
   - Ensure the whole logo scales proportionally as one unit across screen sizes.
   - Prevent separate parts of the logo from resizing inconsistently.
   - Keep the PNG logo as a fallback if the SVG fails to load.
   - Do not change the logo design itself.

## Style direction
Aim for:
- consistency
- faithful execution of the existing concept
- clean implementation
- restrained presentation
- handmade rather than template-driven
- simple and intentional

## Things not to do
- Do not redesign the brand from scratch.
- Do not make subjective 'improvements' unless directly required to complete the requested tasks.
- Do not reinterpret the brief creatively.
- Do exactly what is asked, no more and no less.
- Do not change the overall concept into a standard portfolio template.
- Do not add heavy effects, big animations, or trendy gimmicks.
- Do not replace the system font stack with random web fonts.
- Do not introduce React, a CSS framework, or other unnecessary tooling.
- Do not overcomplicate the codebase.

## Code style and commenting requirements
- Learn and match my existing commenting style from the current files.
- Keep comments consistent with my established tone and formatting.
- I write comments in **third person** voice.
- Maximum line length for both code and comments is **79 characters**.
- I comment heavily and intentionally.
- Comments should explain both:
  - the purpose of code blocks / elements
  - how the code works in practical detail
- Non-trivial code should be commented thoroughly.
- Important design choices may also be commented for future developers.
- Do not remove useful existing comments.
- Do not rewrite comments for unchanged code just to reword them.
- If code is changed, update nearby comments only as needed for accuracy.
- If new code is added, add matching comments in the same style.
- Preserve consistency of spelling, tone, spacing, and structure.

## Deliverables
Please:
1. make the requested changes only
2. summarise exactly what you changed
3. explain any technical decisions required to complete the requests
4. list which files were modified
5. flag any decisions you were unsure about
6. list any requested item you could not complete

## Optional extra
If you see a clearly better wording option for any page copy, suggest it separately rather than silently rewriting the whole voice.

## Current priorities
Priority order:
1. shared stylesheet / CSS cleanup
2. correct SVG logo behaviour with PNG fallback
3. add Programming and Screenwriting pages with Coming Soon placeholders
4. preserve Australian business card proportions
5. mobile spacing and responsiveness

## Important note
This is an **experimental branch pass**, so it is okay to make multiple coordinated improvements at once, but the result should still feel recognisably like the same site — just better executed.

