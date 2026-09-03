# Manga Production

Production is intentionally **single-file per chapter**.

## Structure

```text
04-production/
└── arc-01/
    └── chapter-001/
        ├── chapter-001-production.md
        └── pages/                     # appears when approved page WebPs exist
            ├── page-001.webp
            ├── page-002.webp
            └── ...
```

Each chapter folder has exactly **one production Markdown file**. Do not create separate page blueprints, page prompts, page reference manifests, page QA files, chapter manifests, or chapter production notes.

## Master Chapter File

`chapter-###-production.md` must be self-contained for generation. It compiles all approved production requirements into one place:

- chapter purpose and continuity lock
- complete generation-ready chapter script
- chronology and parallel events
- exact `.md` + `.webp` reference inventory
- chapter-wide black-and-white manga rules
- complete page map
- page-by-page panel/script blueprints
- exact per-page attach/reference sets
- complete per-page image-generation instructions
- per-page continuity in/out
- per-page QA and approval status
- final chapter QA

The story files under `03-story/` remain the narrative source of truth. The production file is an exact generation-ready compilation of those approved story authorities and must not silently rewrite them.

## Artwork Storage

The optional `pages/` directory contains **approved final page images only**. No Markdown belongs inside it.

Canonical character/environment/object/effect references stay under `02-references/`; do not duplicate their WebPs into chapter folders.

Missing required approved reference = STOP generation rather than improvise.
