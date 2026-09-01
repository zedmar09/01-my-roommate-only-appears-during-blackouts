# Manhwa Generation Workflow

## Production Authority

`Manhwa/` is the sole active visual-production pipeline. Converted/audited Manhwa chapter files are self-contained production authority. `Source-Archives/` is reference-only material for chapters not yet converted.

## Character Card Authority — Absolute

Recurring human characters use reusable canonical character-card PNGs generated from `Character-References/` under `Character-References/character-card-standard.md`.

The approved card controls face, age presentation, body proportions, hair geometry/color, permanent marks, permanent accessories, and primary silhouette from all camera angles and expressions.

If a character's current PNG predates the card standard, treat it as provisional and regenerate/approve it before using it as final identity authority. Nari's previous short-hair PNG is obsolete after the long-hair redesign and must be replaced by the newly approved long-hair card before new strips rely on her canonical identity.

## Sequential Production

1. Read the current strip prompt and chapter manifest.
2. Confirm the current strip file itself explicitly lists all required attachments.
3. Attach required **current approved character-card canonical PNG(s)** for physically visible characters.
4. Attach the smallest relevant approved reusable environment canonical set listed in the current strip.
5. Attach relevant approved reusable object canonical(s) listed in the current strip.
6. For Strip 002 onward, attach the immediately previous APPROVED strip.
7. If a required canonical is missing, stale, or unapproved, stop and create/regenerate/approve it; never improvise a substitute.
8. Generate one tall vertical technical strip.
9. QA exact script/source ownership, character identity, movement, object routes/counts, environment geometry, power state, lighting, object states, lettering/SFX, and seam behavior.
10. QA character-card consistency from the current camera angle: face, hair length/silhouette, build, accessories, outfit identity, and expression must remain the same person.
11. QA the **black read-slice grammar**: small black gutter between distinct vertical slices; diagonal/slanted black divider between separate side-by-side views; no giant black bands.
12. QA lower 20–25% for dead/unused canvas.
13. Reject/regenerate before proceeding if any mandatory item fails.
14. Only an APPROVED Strip N becomes temporary continuity authority for Strip N+1.
15. After the last strip passes, stitch in order, crop intentional overlaps, run seam QA, then uniformly resize for publishing.

## Reference Priority

Story/current strip > current approved character card > environment geometry > object identity/state vocabulary > previous strip temporary state.

If an approved previous strip conflicts with a newly approved character/environment/object canonical, do not propagate the drift. The canonical controls permanent identity/geometry; the previous strip controls only temporary story state.

## Reuse Rule

Characters, Unit 2407, residential building shared areas, and recurring story objects are reusable canonicals. Future chapters returning to the same person/place/object must reuse them instead of creating chapter-specific duplicates.

## Black Slice vs Technical Seam

A small black gutter marks a DISTINCT reader-facing slice inside a strip.
A diagonal black slash separates two distinct camera slices sharing a row.
A technical A/E seam is invisible production plumbing; do not add a black bar there if the artwork/effect is meant to continue across files.

## No-Dead-Bottom Rule

Reject huge unused white/neutral/black tails. Never invent filler text/SFX. Prefer existing canonical environment, action/reaction, atmosphere, reveal timing, or compact seam buffer.

## Automatic Reject Rules

Reject for stale/wrong/missing character-card references, face/hair/body identity drift across angles, wrong/missing reference attachments, wrong/missing text, invented reader-facing text, wrong source ownership, environment/object redesign, teleporting movement/props, duplicated objects/bags/devices, wrong power state, missing/incorrect black slice separators, missing diagonal divider in side-by-side separate shots, giant black gutter used as filler, visible technical seam, wrong helpful/hostile signature, or glossy/photoreal/3D rendering.
