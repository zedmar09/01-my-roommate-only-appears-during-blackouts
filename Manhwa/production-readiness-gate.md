# Manhwa Production Readiness Gate

The Manhwa pipeline is the permanent production format.

A chapter is **PRODUCTION COMPLETE** only when every mandatory gate below passes in the current post-correction state. Earlier PASS labels do not substitute for a fresh final audit.

## Mandatory Gates

1. full vertical beat plan and strip manifest locked
2. story logic, event order, timeline, and causality coherent
3. exact reader-facing dialogue/narration/thought/device/note text and source ownership locked
4. SFX verified as physical SOURCE → ACTION → SOUND → TIMING → PLACEMENT, including state change/consequence where applicable
5. required character canonical PNGs exist, are current, and are approved
6. all recurring environment canonical PNG packs required by the chapter exist and are approved
7. all plot-critical recurring object canonical/state PNG packs required by the chapter exist and are approved
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

## Missing-Asset Rule — BLOCKING

If a strip lists a required canonical PNG that is missing, stale, or unapproved, the chapter is **not production-ready**. Stop before generating that strip; never improvise a substitute and never treat a Markdown reference prompt as an approved visual canonical.

If rendered strip images do not yet exist, visual style, actual character/object/environment consistency, seam quality, lettering legibility, dead-space, and final stitched-chapter gates are **not yet verifiable**. Prompt/script quality alone cannot pass those visual gates.

## Completion Language

Use `PRODUCTION COMPLETE` only when all mandatory gates above pass after the final clean-room audit.

For a prompt-only or partially generated package, report the strongest accurate intermediate status instead, such as:
- `PREPRODUCTION SCRIPT/PROMPT AUDIT PASS — VISUAL PRODUCTION NOT STARTED`
- `BLOCKED — REQUIRED CANONICAL VISUAL AUTHORITY MISSING`
- `VISUAL QA IN PROGRESS — NOT PRODUCTION COMPLETE`

Do not reintroduce the retired traditional manga/page-grid production pipeline.