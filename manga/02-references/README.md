# Canonical Manga References

This directory stores reusable semantic and visual authorities required for stable manga generation.

References are **demand-driven**. Do not generate a character, location, object, or effect package until an approved story/chapter actually needs it.

## Structure

- `approved-webp/` — centralized approved reusable final WebP visual authorities
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

## Reader-Visible Language Safety

Story-page language authority is:

`manga/01-style/reader-visible-language-lock.md`

Reference assets control identity, design or geometry. They do **not** control reader-visible language.

If an approved character/environment/style WebP contains readable text, symbols, labels or writing, **do not copy that text into story pages or layout references**.

Final story pages use exact approved **English-only** wording from their page-production MD.

Layout references use empty balloons and zero readable text by default.

## Current Approved Chapter 001 WebPs

- `approved-webp/series-manga-style-reference-a.webp`
- `approved-webp/series-manga-style-reference-b.webp`
- `approved-webp/nari-canonical.webp`
- `approved-webp/nari-apartment-master-atlas.webp`
- `approved-webp/nari-workplace-master-atlas.webp`

Style A/B remain reference-development assets and are not default Chapter 001 story-page attachments.

## Generation Rule

Before generating any subject or page, open:

`generation-attachment-map.md`

Then attach exactly the listed files. More references are not automatically better; attach only authorities that directly control something being generated.

A production page/reference may use only visual authorities whose register status is `APPROVED`.

Never let text visible inside an attached image override the English-only page script.
