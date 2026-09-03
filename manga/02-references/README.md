# Canonical Manga References

This directory stores reusable semantic and visual authorities required for stable manga generation.

References are **demand-driven**. Do not attach or generate more references than a task actually needs.

## Structure

- `approved-webp/` — centralized approved reusable visual authorities
- `characters/` — character canon and reference-generation prompts
- `environments/` — environment canon and reference-generation prompts
- `objects/` — object canon and prompts
- `effects/` — effect canon and prompts
- `reference-register.md` — approval/status gate
- `generation-attachment-map.md` — exact attachment policy
- `image-format-workflow.md` — PNG review → manual WebP conversion
- `reference-package-standard.md` — package rules

## Current Approved Chapter 001 WebPs

- `approved-webp/series-manga-style-reference-a.webp`
- `approved-webp/series-manga-style-reference-b.webp`
- `approved-webp/nari-canonical.webp`
- `approved-webp/nari-apartment-master-atlas.webp`
- `approved-webp/nari-workplace-master-atlas.webp`

## Important Story-Page Rule

An asset being approved does **not** mean it should be attached to every story page.

For Chapter 001 story-page production:

- Style A/B are not default page attachments
- Nari canonical is used when Nari is visible
- apartment/workplace atlas is used when that canonical environment is visible
- layout references are page-local composition authorities stored under `04-production/`, not centralized reusable references

Always follow:

`manga/02-references/generation-attachment-map.md`

More references are not automatically better.

## Authority Rule

Semantic identity/design facts remain in each subject's canon Markdown.

Reusable visual identity/geometry authority is the approved WebP under:

`manga/02-references/approved-webp/`

Final story-page rendering quality comes from:

- `manga/01-style/manga-style-lock.md`
- exact page-production Markdown

A production page/reference may require only visual authorities whose register status is `APPROVED`.