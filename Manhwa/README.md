# Manhwa Production Workspace

This directory is a separate **continuous vertical-scroll manhwa** production system for `My Roommate Only Appears During Blackouts`.

It does not replace `Comics/`. Story canon, dialogue, character identity, supernatural rules, prop state, and apartment geography continue to come from the approved comic/story documents unless a manhwa file changes presentation only.

## Reader-Facing Format — ABSOLUTE

**One chapter = one continuous vertical scroll.**

Do not treat internal generation chunks as separate scroll episodes, pages, or mini-chapters.

The Asura-style reference reader may technically load a chapter as several sequential image assets, but the reader sees them stacked as one uninterrupted chapter. This repository follows that model.

### Fixed chapter geometry
- working/compositing width: **1080 px**
- final publishing width: **800 px**
- every technical strip uses the exact same width
- never scale one strip differently from another
- no visible strip seam
- no repeated title/header between strips
- no page numbers or circled panel numbers in story art
- strip boundaries must land in natural gutter space

## Directory Structure

- `ASURA-CONTINUOUS-SCROLL-NOTE.md` — short format correction and authority note.
- `reference-vibe-profile.md` — reference-derived reading/visual traits.
- `style-guide.md` — original commercial Korean-webtoon rendering target.
- `vertical-scroll-layout-guide.md` — one-scroll canvas, gutters, panels, and stitching rules.
- `lettering-sfx-guide.md` — speech balloons, narration, device text, and SFX hierarchy.
- `generation-workflow.md` — technical-strip generation and final assembly workflow.
- `prompt-template.md` — template for seamless production strips.
- `01-Arc-The-Tenant-In-The-Grid/` — Arc 1 continuous-scroll adaptations.

## Core Production Rules

1. Preserve original story canon and characters.
2. Recompose printed comic material for vertical reading; never stack old comic pages unchanged.
3. Use vertical distance as pacing: short gaps for dialogue, long gaps for hesitation/reveal/horror.
4. Panels may be full-width, centered narrow, borderless, or inset, but they all live inside one continuous 800 px reader column.
5. No reader-visible `Scroll 001`, `Scroll 002`, etc.
6. Technical `strip-###` files are only generation/assembly chunks.
7. Character canonical PNGs remain identity authority.
8. Previous approved strip controls environment/object continuity when the story is continuous.
9. Do not copy the reference series' exact artwork, panel compositions, character designs, backgrounds, text, or proprietary effects. Match only the broad professional vertical-webtoon reading language.

## Chapter 1 Test

The Chapter 1 test lives at:

`Manhwa/01-Arc-The-Tenant-In-The-Grid/Chapter-01-The-Man-Eating-My-Emergency-Noodles/`

It contains one continuous-scroll master plan and technical production strips for the top of the chapter. Approve the first assembled section before expanding the entire chapter.
