---
name: claude-style-illustration
license: MIT
compatibility: Requires an image-generation tool and image viewing.
description: "Create original raster editorial illustrations inspired by Claude's warm humanist visual language: one clear metaphor, flat solid marker forms with hand-drawn wobble, spacious composition, and muted backgrounds. Use for Claude-style article art, sparse conceptual illustrations, and related visual series."
---

# Claude-style Editorial Illustration

Turn one idea into one warm, restrained editorial image. This is an independent visual recipe, not an official Anthropic style guide.

## Core idea

- Explain the theme through one concrete visual metaphor.
- Balance human warmth with a small amount of technical structure.
- Prefer curiosity, clarity, and restraint over spectacle.
- Treat reference images as visual grammar, then create a new composition.

## Visual language

- One dominant object, gesture, or system relationship.
- Draw everything with a thick felt-tip marker: flat solid ink, even saturation, laid down in one confident pass.
- The handmade feel lives in the forms themselves: circles come out lumpy and potato-like with gentle lobes, and every stroke swells and narrows along its length — thick where the gesture presses, slimmer as it travels and connects — with the heaviest contours running three to four times wider than the slimmest lines, and every stroke ending blunt and rounded.
- Repeated marks stay irregular: no two loops, fingers, bumps, or curves share the same width, spacing, or arc.
- Reduce every object to one solid mass or one continuous line. A hand is a few looped squiggles; an object is its simplest recognizable silhouette. Keep each form right at the edge of recognizability.
- Keep the whole image to a countable handful of marks: one dominant mass, one counter-mass, and at most two or three connecting lines, surrounded by generous quiet space.
- Warm ivory appears as large solid masses that interlock with the black forms, edged like cut paper — long straight segments meeting at subtle angles.
- The whole image uses exactly three colors: one flat low-saturation background from `design-system.json` or supplied by the user, ink `#141413`, and ivory `#FAF9F5`.
- Asymmetric composition and slightly unexpected scale or cropping.
- Hands are optional; when present, the gesture matters more than anatomy.

The image should feel thoughtful, bookish, approachable, and technically aware.

Before writing the prompt, inspect one to three close examples from [references/element-library.md](references/element-library.md) and use their element treatment, line-weight contrast, and spatial rhythm as visual guidance.

## Make the image

1. Summarize the concept as one object or as “A does B to C.”
2. Choose an object, relation, or system composition, then strip it down: each element becomes one solid mass or one continuous line, until the whole scene is a countable handful of marks.
3. Choose the background color; preserve an exact user color when supplied.
4. Write a concise image prompt describing the metaphor, the handful of forms, the composition, the felt-tip marker character, and the three colors by hex.
5. Generate a raster image with the available image-generation tool.

Default to 1:1 and no text when the user leaves those choices open. Match another ratio or medium when requested.

## Deliver

Return the generated image, the final prompt, and a short note naming the metaphor and palette.

Check only the essentials: the metaphor reads quickly, the marks stay few enough to count, every form reads as flat solid ink, and no unintended text or branding appears. One focused retry is enough; report any remaining color or rendering drift.

For design lineage or failure diagnosis, read [references/visual-language.md](references/visual-language.md).
