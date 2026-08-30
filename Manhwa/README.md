# Manhwa Pilot Workspace

`Manhwa/` is the experimental vertical-scroll production pipeline for `My Roommate Only Appears During Blackouts`.

## Isolation Rule — Absolute

The existing `Comics/` directory remains untouched and remains the current story/continuity authority during this test. Nothing in `Manhwa/` automatically replaces, renames, deletes, or weakens the existing comic production package.

Only after the pilot is proven effective and the user explicitly approves promotion may we plan a replacement/migration of the old comic presentation.

## Current Pilot Lock

The first test is **Manhwa Chapter 1**, adapting source Comic Chapter 1 Pages **001–009**.

Production target:
- one reader-visible continuous vertical chapter
- exactly **70 internal vertical read beats** for planning/QA
- exactly **15 tall technical production strips**
- one fixed strip width and invisible stitching
- beat/strip IDs never appear in reader-facing artwork
- no circled panel numbers or page numbers

Source Comic Pages 010–018 are reserved for later Manhwa Chapter 2.

## Conversion Philosophy

Source comic pages are story/script authorities, not layout templates.

The manhwa version may freely recompose approved source material into borderless art, tall reveals, close-ups, montage clusters, varied gutters, and continuing compositions, but it must preserve the complete assigned story content.

**Strip 001 is the pilot example:** it now adapts ALL of source Comic Page 1, including the speaker `BLIP`, `WELCOME HOME, YOON NARI.`, and Nari's `GREAT. IT TALKS.` before handing off to the later-evening scene.

## Negative Space Rule — Absolute

White/neutral scroll space is valid when it performs a clear storytelling function: narration/time transition, silence, hesitation, suspense, reveal anticipation/aftermath, or continuing atmosphere.

A huge empty bottom area with no storytelling purpose is **not** valid manhwa pacing. It is dead canvas and must be rejected/regenerated.

For ordinary technical seams use only a small controlled buffer, or continue actual environment/background/atmosphere to the edge. Never create giant blank padding merely because a strip is tall.

## Reference Goal

The supplied Asura-style reader example is used for professional Korean webtoon/manhwa reading behavior: one continuous chapter, sequential same-width image delivery, variable vertical pacing, large reveal compositions, clean mobile lettering, integrated SFX, and image boundaries that can continue the same artwork into the next file.

Do not copy another title's exact artwork, characters, poses, panel compositions, backgrounds, dialogue, or proprietary visual assets.

## Core Files

- `reference-vibe-profile.md` — target reading behavior and visual density
- `style-guide.md` — manhwa rendering rules
- `vertical-scroll-layout-guide.md` — continuous layout, gutter, and no-dead-space rules
- `seam-continuity-protocol.md` — cross-strip continuation rules
- `lettering-sfx-guide.md` — dialogue, narration, device text, and SFX
- `generation-workflow.md` — sequential production/approval workflow
- `prompt-template.md` — technical-strip template
- `pilot-promotion-gate.md` — rules before replacing the existing comic pipeline

## Pilot Chapter

`Manhwa/01-Arc-The-Tenant-In-The-Grid/Chapter-01-The-Man-Eating-My-Emergency-Noodles/`

The folder identifies the source comic chapter. The manhwa pilot adapts only source Pages 001–009 and ends at the 12:43 A.M. citywide blackout hook.
