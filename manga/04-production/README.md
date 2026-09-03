# Manga Production

Production is intentionally **single-file per manga page**.

## Structure

```text
04-production/
└── arc-01/
    └── chapter-001/
        ├── page-001-production.md
        ├── page-001.webp                 # appears only after visual approval
        ├── page-002-production.md
        ├── page-002.webp
        └── ...
```

There is no master chapter-production Markdown file.

Each manga page receives exactly **one generation-authority Markdown file**. That page file contains every instruction needed to generate, verify, and approve that specific page. Do not split one page into separate prompt, blueprint, reference-manifest, script, or QA Markdown files.

## One-Page / One-MD Rule

`page-###-production.md` must be self-contained for that page and must include:

- page identity and approval status
- exact page canvas/output dimensions and aspect ratio
- page purpose, event thread, chronology, time, location, scenario, and page-turn role
- continuity input from the preceding approved page and required continuity output for the next page
- exact required attachment/reference paths for all `.md` and `.webp` authorities
- character state, wardrobe, expression, pose, and blocking requirements
- environment geometry and camera/view requirements
- object/prop state and supernatural/effect state
- panel count, reading order, panel sizes, approximate placements, hierarchy, and gutters
- complete panel-by-panel script
- exact dialogue, narration, SFX, silence, and lettering requirements
- panel-by-panel actions, reactions, events, camera framing, and scenario details
- complete deterministic image-generation instruction for the whole page
- style prohibitions and anti-drift rules
- page-specific QA/acceptance checklist
- exact approved output filename

The story files under `03-story/` remain the narrative source of truth. A page-production file is the exact generation-ready compilation of the approved story material for that page and must not silently rewrite it.

## References

Canonical character, environment, object, effect, and style references stay under `01-style/` and `02-references/`. Do not duplicate canonical WebPs into chapter folders.

Every page-production MD must list the exact repository paths of the references that must be attached for that page. A required visual authority must be approved in `02-references/reference-register.md` before generation.

Missing required approved reference = **STOP**. Do not improvise a substitute.

## Artwork Storage

The approved page WebP sits beside its production Markdown:

```text
page-001-production.md
page-001.webp
```

Rejected/intermediate generations are not canonical repository authorities and must not replace the approved page WebP.

See `page-production-standard.md` for the required internal structure of every page-production file.
