# Manhwa Production Workspace

This directory is a **separate vertical-scroll manhwa production system** for `My Roommate Only Appears During Blackouts`.

It does not replace or modify `Comics/`. The existing comic-page production remains the canonical source for story continuity, dialogue, character identity, supernatural rules, prop state, and apartment geography unless a manhwa adaptation file explicitly changes only presentation/pacing.

## Goal

Test Arc 1, Chapter 1 as a modern full-color vertical-scroll manhwa with the reading energy of current Korean webtoon/manhwa releases: strong vertical pacing, variable gutters, full-width reveals, close reaction shots, detailed establishing panels, embedded SFX, clean speech balloons, and controlled atmosphere.

The reference material is used for **format, pacing, composition rhythm, lettering behavior, SFX hierarchy, and rendering density only**. Do not copy another series' exact panels, character designs, poses, compositions, props, text, effects, or backgrounds.

## Directory Structure

- `reference-vibe-profile.md` — what visual/scroll qualities we are testing.
- `style-guide.md` — art/rendering target for the manhwa version.
- `vertical-scroll-layout-guide.md` — panel widths, gutters, pacing, and stitching rules.
- `lettering-sfx-guide.md` — dialogue, narration, device text, and sound-effect rules.
- `generation-workflow.md` — generation/approval workflow.
- `prompt-template.md` — base prompt structure for future scroll slices.
- `01-Arc-The-Tenant-In-The-Grid/` — Arc 1 manhwa adaptations.

## Production Philosophy

1. **Story canon comes first.** Do not change lore or character knowledge merely to create a dramatic panel.
2. **Vertical space is part of the storytelling.** Silence, hesitation, dread, and reveals use scroll distance instead of squeezing everything into page grids.
3. **No circled panel-order markers in final manhwa artwork.** Reading order is top-to-bottom.
4. **Character canon remains shared with the comic.** Existing approved canonical PNGs control identity.
5. **Previous approved manhwa slice is the visual continuity reference for the next slice.** It controls current wardrobe/environment/object state, but does not force the same camera angle.
6. **No brand/logo clutter.** Office/device packaging remains generic.
7. **No exact imitation of the reference title.** Capture the professional vertical-manwha reading experience, not its proprietary artwork.

## Pilot Scope

The first test is:

`Manhwa/01-Arc-The-Tenant-In-The-Grid/Chapter-01-The-Man-Eating-My-Emergency-Noodles/`

The pilot includes a full Chapter 1 scroll map plus the first three generation-ready scroll prompts. Approve the pilot visual language before expanding the remaining Chapter 1 scroll prompts.
