# Manhwa Pilot Workspace

`Manhwa/` is the experimental vertical-scroll production pipeline for `My Roommate Only Appears During Blackouts`.

## Isolation Rule — Absolute

The existing `Comics/` directory remains untouched and remains the current story/continuity authority during this test. Nothing in `Manhwa/` automatically replaces, renames, deletes, or weakens the existing comic production package.

Only after the manhwa pilot is proven effective and the user explicitly approves promotion may we plan a replacement/migration of the old comic presentation.

## Current Pilot Lock

The first manhwa test is **Manhwa Chapter 1**, adapting only source Comic Chapter 1 Pages **001–009**.

Production target:
- one reader-visible continuous vertical chapter
- exactly **70 internal vertical read beats** for planning/QA
- exactly **15 tall technical production strips** for this pilot
- all strips use one fixed width and stitch into one seamless scroll
- beat IDs and strip IDs are production-only and never appear in reader-facing artwork
- no circled panel numbers or page numbers

The source comic Pages 010–018 are reserved for a later Manhwa Chapter 2 and are outside this pilot.

## Reference Goal

The supplied Asura-style reader example is used to study the professional Korean webtoon/manhwa reading behavior: one continuous chapter, sequential same-width image delivery, variable vertical pacing, long suspense gaps, large reveal compositions, clean mobile lettering, integrated SFX, and image boundaries that can continue the same artwork into the next file.

Do not copy another title's exact artwork, characters, poses, panel compositions, backgrounds, dialogue, or proprietary visual assets.

## Core Files

- `reference-vibe-profile.md` — target reading behavior and visual density.
- `style-guide.md` — manhwa rendering rules.
- `vertical-scroll-layout-guide.md` — continuous layout and spacing.
- `seam-continuity-protocol.md` — cross-strip continuation rules.
- `lettering-sfx-guide.md` — dialogue, narration, device text, and SFX.
- `generation-workflow.md` — sequential production/approval workflow.
- `prompt-template.md` — template for technical strip prompts.
- `pilot-promotion-gate.md` — rules before this experiment can replace the existing comic pipeline.

## Pilot Chapter

`Manhwa/01-Arc-The-Tenant-In-The-Grid/Chapter-01-The-Man-Eating-My-Emergency-Noodles/`

The folder name identifies the source comic chapter. The manhwa pilot itself adapts only source Pages 001–009 and ends at the 12:43 A.M. citywide blackout hook.
