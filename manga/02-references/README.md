# Canonical Manga References

This directory stores reusable visual authorities required for stable manga generation.

References are **demand-driven**. Do not generate a character, location, object, or effect package until an approved story/chapter actually needs it.

## Reference Types

- `characters/`
- `environments/`
- `objects/`
- `effects/`

## Image Format Workflow

All reference images use the workflow defined in `image-format-workflow.md`:

1. ChatGPT/image generation creates a `.png` candidate.
2. The PNG is visually reviewed.
3. If approved, the user manually converts that exact PNG to `.webp`.
4. Only the approved WebP is stored in the repository as visual authority.

So `.png` is an intermediate review file; `.webp` is the final approved repository authority.

Every recurring reference package combines text canon (`.md`) with one or more approved black-and-white visual authorities (`.webp`). See `reference-package-standard.md`.

`reference-register.md` records which references are approved and safe for production.

A production page may reference only files whose status is `APPROVED`. Exact repository paths must be copied into that page's single `page-###-production.md`; never rely on a vague character/location name.
