# Manhwa Generation Workflow

## Pilot Isolation

`Comics/` remains untouched and authoritative during the test.

The current manhwa pilot adapts source Comic Chapter 1 Pages 001–009 only.

## Fixed Pilot Plan

- 1 continuous reader-visible chapter
- 70 internal read beats (`V01`–`V70`), never printed
- 15 tall technical strips (`strip-001`–`strip-015`), never printed
- one fixed width across all generated strips
- no reader-visible page/strip boundaries

## Source Preservation Rule

The source comic controls exact reader-facing wording, speaker/source, event order, object state, movement logic, supernatural rules, and character knowledge.

The manhwa conversion changes only presentation: camera, panel shape, scroll distance, montage structure, crop, rendering density, and seam placement.

Do not drop source content merely to make a strip shorter. Do not add filler merely to make a strip taller.

## Sequential Production

1. Read the current strip prompt plus the shared manhwa guides.
2. Attach only canonical PNGs for characters visibly present in that strip.
3. For Strip 002 onward, attach the immediately previous APPROVED manhwa strip.
4. Generate one tall vertical strip using the available canvas efficiently.
5. QA script, identity, environment, vertical pacing, lettering, SFX, seam behavior, and whitespace usage.
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

## Previous-Strip Continuity Rule

The immediately previous approved manhwa strip controls current visual reality: wardrobe, environment geometry, object state, lighting, direction of travel, and seam atmosphere. It does not force identical camera angles when the story moves.

## NO DEAD BOTTOM SPACE — PRODUCTION GATE

Before approving any strip, inspect the last portion of the image.

APPROVE bottom space only when it clearly functions as:
- narration/time-transition breathing room,
- suspense or silence,
- reveal anticipation/aftermath,
- continuing rain/darkness/background/environment,
- or a small controlled seam zone.

REJECT if the image simply stops and leaves a huge empty white/neutral tail with no narrative purpose.

Do not solve a seam by adding giant blank space. Do not add large blank space at both the end of Strip N and the beginning of Strip N+1.

If a strip has excess unused height, use the canvas for the assigned story: enlarge meaningful compositions, extend the environment, preserve a purposeful pause, or include the next beat if the manifest assigns it to that strip.

## Strip 001 Special Rule

Strip 001 now adapts the COMPLETE source Comic Page 1 in vertical manhwa form, including:
- move-in
- apartment reveal
- smart-home scan
- speaker `BLIP`
- `WELCOME HOME, YOON NARI.`
- Nari `GREAT. IT TALKS.`

Do not stop Strip 001 before the source Page 1 ending merely to create a seam.

## Source Comic Usage

Use source Comic Pages 001–009 as exact story/script/prop-rule authority, not as page-layout templates. Recompose events into continuous scroll pacing; never recreate the old rigid page grids.

## Automatic Reject

Reject for wrong/missing source text, invented dialogue/SFX, wrong speaker/source, identity drift, physical Hyun-woo, geography reset, missing/moved continuity prop without action, visible production ID, rigid page grid, obvious seam, text split at seam, swapped device signature, glossy/photoreal/3D rendering, or huge purposeless bottom whitespace.

## Pilot Strategy

Regenerate Strip 001 using the revised complete-Page-1 prompt and whitespace rules. Approve its rendering density, bubble size, vertical pacing, and seam behavior before propagating that style into Strip 002.
