# Manga Production

Production is intentionally **single-file per manga page**.

## Structure

```text
04-production/
└── arc-01/
    └── chapter-001/
        ├── page-001-production.md
        ├── page-001.webp                 # final approved authority after PNG review + manual conversion
        ├── page-002-production.md
        ├── page-002.webp
        └── ...
```

There is no master chapter-production Markdown file.

Each manga page receives exactly **one generation-authority Markdown file**. That page file contains every instruction needed to generate, verify, and approve that specific page. Do not split one page into separate prompt, blueprint, reference-manifest, script, or QA Markdown files.

## Image Format Workflow

Actual manga pages use the same PNG-first workflow as reference images:

1. ChatGPT/image generation creates `page-###.png` as the review candidate.
2. The PNG is audited against its `page-###-production.md`.
3. If approved, the user manually converts that exact PNG to `page-###.webp`.
4. Only the WebP becomes repository/page continuity authority.

Rejected PNGs are not canon and must not replace an approved page WebP.

See `manga/02-references/image-format-workflow.md`.

## One-Page / One-MD Rule

`page-###-production.md` must be self-contained for that page and must include:

- page identity and approval status
- exact page canvas/output dimensions and aspect ratio
- **PNG generation candidate filename**
- **final approved WebP filename**
- page purpose, event thread, chronology, time, location, scenario, and page-turn role
- continuity input from the preceding approved page and required continuity output for the next page
- exact required attachment/reference paths for all approved `.md` and `.webp` authorities
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

The story files under `03-story/` remain the narrative source of truth. A page-production file is the exact generation-ready compilation of the approved story material for that page and must not silently rewrite it.

## References

Canonical character, environment, object, effect, and style references stay under `01-style/` and `02-references/`. Do not duplicate canonical WebPs into chapter folders.

Every page-production MD must list the exact repository paths of the approved WebP references that must be attached for that page. A required visual authority must be `APPROVED` in `02-references/reference-register.md` before generation.

Missing required approved reference = **STOP**. Do not improvise a substitute.

## Artwork Storage

Generation stage:

```text
page-001.png                    # intermediate review candidate, not repository authority
```

After approval + user's manual conversion:

```text
page-001-production.md
page-001.webp                   # final approved repository authority
```

See `page-production-standard.md` for the required internal structure of every page-production file.
