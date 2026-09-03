# Approved WebP Visual Authorities

This folder is the **single centralized location for all approved final WebP visual authorities** used by the manga pipeline.

## Format Rule

- ChatGPT / image generation produces a `.png` review candidate first.
- The PNG is reviewed.
- The user manually converts the exact approved PNG to `.webp`.
- Only the approved WebP is committed here and treated as canonical visual authority.

Do not store review PNGs here.

## Current Approved Visuals

- `series-manga-style-reference-a.webp` — approved series style authority A
- `series-manga-style-reference-b.webp` — approved series style authority B
- `nari-canonical.webp` — approved Yoon Nari character authority

## Planned Chapter 001 Visuals

When approved and converted, add them to this same folder:

- `nari-apartment-master-atlas.webp`
- `nari-apartment-floor-plan.webp` — only if a separate floor-plan image is actually needed
- `nari-workplace-master-atlas.webp`
- future Hyejin canonical only if Chapter 001 visibly requires her after her role/design is approved

## Attachment Rule

Generation prompts must list the exact WebP files that should be attached. Do not rely on vague instructions such as “attach the style reference.”

See `manga/02-references/generation-attachment-map.md` for the current exact attachment sets.
