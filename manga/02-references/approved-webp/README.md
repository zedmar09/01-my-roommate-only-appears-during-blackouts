# Approved WebP Visual Authorities

This folder is the centralized location for reusable approved WebP visual authorities.

## Format Rule

- image generation produces a `.png` review candidate first
- PNG is visually reviewed
- user manually converts the exact accepted PNG to `.webp`
- only the approved WebP becomes reusable visual authority

Do not store review PNGs here.

## Current Approved Visuals

- `series-manga-style-reference-a.webp` — approved reference-development style asset A
- `series-manga-style-reference-b.webp` — approved reference-development style asset B
- `nari-canonical.webp` — Yoon Nari identity authority
- `nari-apartment-master-atlas.webp` — apartment/common-route geometry authority
- `nari-workplace-master-atlas.webp` — publishing-workplace geometry authority

## Story-Page Attachment Rule

Approved does not mean automatically attached.

For Chapter 001 final story pages, Style A/B are **not default attachments**. Use them only if an exact page-production MD explicitly opts them in.

Character/environment WebPs should be attached only when they control something visible on the requested page.

Page-local layout references are stored beside production files under `manga/04-production/`; they do not belong in this centralized reusable-reference folder.

See:

`manga/02-references/generation-attachment-map.md`

for exact current attachment sets.