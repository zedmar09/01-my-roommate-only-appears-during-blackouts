# Canonical Manga References

This directory stores reusable visual authorities required for stable manga generation.

References are **demand-driven**. Do not generate a character, location, object, or effect package until an approved story/chapter actually needs it.

## Reference Types

- `characters/`
- `environments/`
- `objects/`
- `effects/`

Every recurring reference package combines text canon (`.md`) with one or more approved black-and-white visual authorities (`.webp`). See `reference-package-standard.md`.

`reference-register.md` records which references are approved and safe for production.

A production page may reference only files whose status is APPROVED. Exact repository paths must be copied into the page reference manifest; never rely on a vague character/location name.
