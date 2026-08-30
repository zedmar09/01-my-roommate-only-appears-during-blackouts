# Manhwa Generation Workflow

## Pilot Isolation

`Comics/` remains untouched and authoritative during the test.

The manhwa pilot adapts source Comic Chapter 1 Pages 001–009 only.

## Fixed Pilot Plan

- 1 continuous reader-visible chapter
- 70 internal read beats (`V01`–`V70`), not printed
- 15 technical strips (`strip-001`–`strip-015`), not printed
- one fixed width across all generated strips

## Sequential Production

1. Read the current strip prompt.
2. Attach only canonical PNGs for characters visibly present in that strip.
3. For Strip 002 onward, attach the immediately previous APPROVED manhwa strip.
4. Generate one tall vertical strip using the full available canvas.
5. QA script, identity, environment, vertical pacing, seam type, lettering, SFX, and style.
6. Reject/regenerate before proceeding if any mandatory item fails.
7. Only an APPROVED Strip N becomes continuity authority for Strip N+1.
8. After Strip 015 passes, stitch all approved strips in order.
9. Crop intentional overlap regions only during final assembly.
10. Run one seam-by-seam full-chapter QA.
11. Uniformly resize the completed master for publishing.

## Character References

- Nari: `Character-References/nari-canonical-flat2d.png`
- Mrs. Na: `Character-References/mrs-na-canonical-flat2d.png`
- Seungjae: `Character-References/seungjae-canonical-flat2d.png`

Hyun-woo is never physically visible in this Manhwa Chapter 1 pilot. Do not attach `hyunwoo-canonical-flat2d.png`; his first human-sounding voice remains audio/device-only.

## Source Comic Usage

Use source Comic Pages 001–009 as exact story/script/prop-rule authority, not as page-layout templates.

Do not recreate the old six/eight/nine-panel page grids. Recompose those events into continuous scroll pacing.

## Strip Failure Rules

Automatic reject for:
- wrong or missing source text
- invented dialogue/SFX
- wrong speaker/source
- canonical identity drift
- physical Hyun-woo
- apartment geography reset
- missing/moved continuity prop without story action
- visible strip label/beat number
- uniform page-grid layout
- obvious seam
- text split at seam
- helpful/hostile device signature swapped
- glossy/photoreal/3D rendering

## Pilot Test Strategy

Generate Strip 001 first and evaluate the actual visual density, bubble size, line/shadow treatment, and vertical pacing. The 15-strip manifest is already planned so the production thread has a stable roadmap, but do not propagate an unsatisfactory Strip 001 style downstream.
