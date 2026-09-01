# Manhwa Production Readiness Gate

The Manhwa pipeline is the permanent production format.

A chapter is **PRODUCTION COMPLETE** only when every mandatory gate below passes in the current post-correction state. Earlier PASS labels do not substitute for a fresh final audit.

## Mandatory Gates

1. full vertical beat plan and strip manifest locked
2. story logic, event order, timeline, and causality coherent
3. exact reader-facing dialogue/narration/thought/device/note text and source ownership locked
4. SFX verified as physical SOURCE → ACTION → SOUND → TIMING → PLACEMENT, including state change/consequence where applicable
5. required character canonical WebPs exist, are current, and are approved
6. all recurring environment canonical WebP packs required by the chapter exist and are approved
7. all plot-critical recurring object canonical/state WebP packs required by the chapter exist and are approved
8. every technical strip is generated and approved sequentially
9. real-life movement and body mechanics are believable; no unexplained teleporting or pose jumps
10. carried-object routes, counts, handoffs, placements, pickups, and persistent states remain coherent
11. environment geometry, room axes, furniture/appliance positions, and physically possible camera angles remain canonical
12. character identity, proportions, hair, wardrobe/state, accessories, and permanent marks remain canonical
13. strict **flat 2D human-drawn** style passes actual visual inspection: flat colors, restrained simple cel shading, matte materials, clean line art, stable anatomy, natural hands, no photoreal/3D/glossy/cinematic/painterly/airbrushed/over-rendered drift
14. blackout/restored-power/device/candle/rain lighting states remain physically and stylistically coherent without cinematic glow or unexplained light
15. helpful/hostile signatures and object-specific effects remain correct
16. black read-slice grammar and side-by-side diagonal divider rules remain correct
17. no huge purposeless bottom whitespace or double-gap seams remain
18. mobile lettering remains readable and no production metadata leaks into artwork
19. the stitched chapter has no visible seams, duplicated transition content, geometry jumps, or unplanned power/lighting jumps
20. final chapter ending matches the locked script exactly
21. a fresh clean-room audit from the beginning finds zero unresolved BLOCKER, MAJOR, correction-requiring MINOR, or unexplained WARNING findings

## Repository Image Format Rule

Image-generation prompts may request PNG as the first local generation output. That is allowed and does not need to be rewritten merely because GitHub stores WebP.

After a reference image is visually approved:
- manually convert the accepted PNG to WebP
- commit/store the approved `.webp` file in GitHub
- update production Markdown to reference the exact repository `.webp` path

The committed WebP is the production attachment authority. A deleted/intermediate PNG path is not.

## Missing-Asset Rule — BLOCKING

If a strip lists a required canonical WebP that is missing, stale, wrong-path, or unapproved, the chapter is **not production-ready for that strip**. Stop before generating that strip; never improvise a substitute and never treat a Markdown reference prompt as an approved visual canonical.

If rendered strip images do not yet exist, actual strip style, character/object/environment consistency, seam quality, lettering legibility, dead-space, and final stitched-chapter gates are **not yet verifiable**. Prompt/script quality and reference availability alone cannot pass those rendered-output gates.

## Chapter 1 Current Intermediate State

Chapter 1 currently has its approved reusable character, Unit 2407, building-shared-area, and plot-critical object WebP authorities present in the repository. After the Markdown reference migration is clean, the remaining production work is sequential Strip 001–032 rendering, per-strip visual QA/re-audit, stitching, and final clean-room visual audit.

This is a preproduction/reference-ready state, not `PRODUCTION COMPLETE`.

## Completion Language

Use `PRODUCTION COMPLETE` only when all mandatory gates above pass after the final clean-room audit.

For a prompt-only or partially generated package, report the strongest accurate intermediate status instead, such as:
- `PREPRODUCTION REFERENCE GATE PASS — READY FOR SEQUENTIAL STRIP PRODUCTION`
- `BLOCKED — REQUIRED CANONICAL VISUAL AUTHORITY MISSING`
- `VISUAL QA IN PROGRESS — NOT PRODUCTION COMPLETE`

Do not reintroduce the retired traditional manga/page-grid production pipeline.
