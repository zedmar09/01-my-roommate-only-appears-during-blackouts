# Character References

Create one folder per recurring character only after the approved story requires that character.

Character folders store semantic authorities:

```text
characters/<character-id>/
├── canon.md
├── <character-id>-reference-generation-prompt.md
└── variants/   # optional scripted state notes
```

Approved final character WebPs are centralized in:

`manga/02-references/approved-webp/`

Naming:

`<character-id>-canonical.webp`

Example:

`manga/02-references/approved-webp/nari-canonical.webp`

Generate PNG first, review it, then manually convert the exact approved PNG to the centralized WebP.

Character identity must remain stable across pages while pose, expression, temporary clothing, injuries and scene-specific state come from the page-production MD.

Before generating/regenerating a character, consult `manga/02-references/generation-attachment-map.md` for exact required WebP attachments.
