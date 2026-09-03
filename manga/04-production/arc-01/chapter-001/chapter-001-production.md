# Chapter 001 — Master Manga Production File

## Status

**BLOCKED — STORY REBUILD IN PROGRESS.**

This is the **single Markdown production authority** for Chapter 001. Do not create separate page blueprints, page prompts, page reference manifests, page QA Markdown files, or chapter reference-manifest Markdown files.

When Chapter 001 is ready, this one file must contain everything needed to generate and audit every manga page in the chapter.

## Source Authority

Compile this file only from approved current authorities:

1. current user instruction
2. `manga/00-series/` canon and continuity
3. `manga/03-story/arc-01/` arc and Chapter 001 story files
4. `manga/01-style/` manga visual rules and approved style-reference WebP(s)
5. `manga/02-references/reference-register.md`
6. approved `.md` + `.webp` reference packages under `manga/02-references/`
7. immediately previous approved page WebP for local seam continuity only

Retired Manhwa material and Git history are not active authority.

## Chapter Production Contract

Before any page is generated, this file must contain all of the following sections in final form.

### A. Chapter Lock

- chapter title
- chapter purpose
- chapter opening state
- chapter ending state / hook
- exact chronology and parallel-event timing
- character entry/exit states
- location changes
- prop and supernatural-state continuity

### B. Complete Chapter Script

Compile the approved Chapter 001 story into this file so generation never depends on reconstructing the story from scattered production notes. Include:

- scene sequence
- actions
- dialogue
- narration
- SFX
- silent beats
- page-turn reveals
- parallel-event cuts

The `03-story/` files remain the narrative source of truth. This production file is their exact generation-ready compilation and must not silently rewrite them.

### C. Complete Reference Inventory

List exact repository paths for every required authority. Each reusable visual subject should normally provide both semantic and visual authority.

Example structure:

```text
STYLE
- manga/01-style/manga-style-lock.md
- manga/01-style/reference-style/<approved-style-reference>.webp

CHARACTER — <character-id>
- manga/02-references/characters/<character-id>/canon.md
- manga/02-references/characters/<character-id>/<character-id>-canonical.webp

ENVIRONMENT — <location-id>
- manga/02-references/environments/<location-id>/canon.md
- manga/02-references/environments/<location-id>/<location-id>-master-atlas.webp
- manga/02-references/environments/<location-id>/<location-id>-floor-plan.webp   # if required

OBJECT — <object-id>
- manga/02-references/objects/<object-id>/canon.md
- manga/02-references/objects/<object-id>/<object-id>-canonical.webp

EFFECT — <effect-id>
- manga/02-references/effects/<effect-id>/canon.md
- manga/02-references/effects/<effect-id>/<effect-id>-atlas.webp
```

A required visual reference must be marked `APPROVED` in `manga/02-references/reference-register.md`. Missing required authority = STOP. Do not improvise a replacement.

### D. Chapter-Wide Visual / Generation Rules

- black-and-white manga only
- human-drawn pencil/ink impression
- variable line weight
- screentone, hatching, and solid blacks as appropriate
- natural anatomy and readable hands
- conventional manga-page storytelling
- variable panel count, size, shape, density, and hierarchy according to story rhythm
- no fixed panel template
- no full-color webtoon treatment
- no glossy finish
- no cinematic grading, bloom, lens flare, or depth-of-field styling
- no photorealism, CGI, 3D-render look, or painterly concept-art finish
- no production labels, filenames, panel IDs, QA notes, or metadata inside reader-facing artwork

### E. Page Master Plan

The complete approved chapter page map must be reproduced here before generation begins.

For each page define:

- page number
- page purpose
- panel count
- panel hierarchy / approximate layout
- reading order
- page-turn function
- required characters
- required environments
- required objects/effects
- continuity input
- continuity output

There is no fixed page panel count. A page may contain one full-page reveal, several dense dialogue panels, reaction cut-ins, irregular action panels, or another composition justified by the story.

## Per-Page Production Block

Create one block below for **every page in Chapter 001**. This replaces all separate page Markdown packages.

---

# PAGE 001

## Generation Status

`NOT READY`

Approved output when complete:
`manga/04-production/arc-01/chapter-001/pages/page-001.webp`

## Page Purpose

TBD after Chapter 001 story approval.

## Required References — Exact Attach Set

TBD. List the exact `.md` and `.webp` repository paths required for this page only.

## Continuity In

TBD.

## Panel / Script Blueprint

TBD. Include every panel in reader order with:

- panel size/hierarchy
- camera/framing
- characters and blocking
- environment geometry
- action
- expression/body language
- props and state
- dialogue/narration/SFX verbatim
- transition to next panel/page

## Deterministic Image-Generation Instruction

TBD. This section must become the **complete generation prompt for the entire manga page**, compiled from the approved page blueprint, chapter-wide rules, and exact reference set.

The generator must create exactly one complete manga page, not separate panel images unless a later explicit production decision requires otherwise.

## Page QA Gate

Before `page-001.webp` becomes approved, verify:

- story beat/order exactly matches the approved script
- all dialogue/narration/SFX is accurate
- character identity matches canonical WebPs
- environment geometry matches canonical atlas/floor plan
- objects/effects match approved references
- continuity from previous page is correct
- panel hierarchy/read order works
- hands/anatomy are acceptable
- black-and-white manga style is correct
- screentone/hatching/solid-black use is appropriate
- no color/glossy/cinematic/3D drift
- no unintended production text or metadata

Approval state: `NOT GENERATED`

---

## Additional Pages

After the Chapter 001 page map is approved, append `PAGE 002`, `PAGE 003`, and all later page blocks to this same Markdown file using the exact structure above. Do not create separate Markdown files for those pages.

## Generated Artwork Storage

Only approved final page images belong in:

```text
manga/04-production/arc-01/chapter-001/pages/
├── page-001.webp
├── page-002.webp
├── page-003.webp
└── ...
```

The `pages/` directory contains **images only**. No page-level Markdown belongs there.

Intermediate/rejected PNG, JPEG, or WebP generations are not canonical repository authorities unless explicitly approved and renamed to the canonical page path.

## Final Chapter QA

After every page is approved, audit the full Chapter 001 sequence for:

- story continuity
- chronology and parallel events
- character identity and wardrobe/state continuity
- environment geometry
- object/effect continuity
- dialogue accuracy
- page-to-page visual rhythm
- repeated/omitted story beats
- manga style consistency
- chapter-ending hook

## Final Status

`BLOCKED — NEW CHAPTER 001 STORY NOT YET APPROVED`
