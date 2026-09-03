# Page Package Standard

Create a page folder only after the corresponding page exists in the approved Chapter page map.

```text
pages/page-001/
├── page-001-blueprint.md
├── page-001-reference-manifest.md
├── page-001-image-prompt.md
├── page-001-qc.md
└── page-001.webp                 # appears only after visual approval
```

## `page-###-blueprint.md`

Story/composition authority for the page: purpose, panel sequence, panel hierarchy, camera intent, character blocking, dialogue/SFX, continuity in/out, and page-turn role.

## `page-###-reference-manifest.md`

Exact dependency list. Include repository paths for every required Markdown and every required WebP. Separate REQUIRED from OPTIONAL references. If a required WebP is missing or not APPROVED in `02-references/reference-register.md`, stop generation.

## `page-###-image-prompt.md`

Deterministic generation instruction compiled from the approved blueprint and authorities. It must contain an exact ATTACH/REFERENCE set and must not silently rewrite story facts.

## `page-###-qc.md`

Visual/continuity audit: character identity, environment geometry, prop state, panel order, text accuracy, hand/anatomy quality, manga style, screentone/hatching quality, page readability, and seam continuity.

## `page-###.webp`

Only the approved final page receives this filename. Rejected generations must not replace it.
