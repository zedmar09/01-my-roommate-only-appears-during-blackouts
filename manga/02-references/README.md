# Canonical Manga References

This directory stores reusable semantic and visual authorities required for stable manga generation.

References are **demand-driven**. Do not generate a character, location, object, or effect package until an approved story/chapter actually needs it.

## Structure

- `approved-webp/` — **all approved reusable final WebP visual authorities, centralized in one place**
- `characters/` — character canon and generation-prompt MDs
- `environments/` — environment canon and generation-prompt MDs
- `objects/` — object canon and generation-prompt MDs
- `effects/` — effect canon and generation-prompt MDs
- `reference-register.md` — approval/status gate
- `generation-attachment-map.md` — exact WebP attachment sets for generation
- `image-format-workflow.md` — PNG review → manual WebP conversion workflow
- `reference-package-standard.md` — package rules

## Core Rule

Semantic authority stays with each subject's Markdown files.

Reusable visual authority is always the approved WebP in:

`manga/02-references/approved-webp/`

Do not scatter duplicate approved WebPs across character/environment folders.

## Current Approved Chapter 001 WebPs

- `approved-webp/series-manga-style-reference-a.webp`
- `approved-webp/series-manga-style-reference-b.webp`
- `approved-webp/nari-canonical.webp`

## Generation Rule

Before generating any subject, open:

`generation-attachment-map.md`

Then attach exactly the listed WebPs plus the subject's canon/prompt MDs. More references are not automatically better; attach only authorities that directly control something being generated.

A production page/reference may use only visual authorities whose register status is `APPROVED`.
