# Manhwa Generation Workflow

## Production Authority

`Manhwa/` is the sole active visual-production pipeline. Converted/audited Manhwa chapter files are self-contained story authority. `Source-Archives/` is reference-only material for chapters not yet converted.

The following global production rules are **always binding on every active strip**, even when an individual strip attachment list does not repeat them:
- `Manhwa/style-guide.md`
- `Manhwa/lettering-sfx-guide.md`
- `Manhwa/seam-continuity-protocol.md`
- `Manhwa/vertical-scroll-layout-guide.md`
- this workflow

A chapter/strip may make these rules stricter but may never loosen them.

## Character Card Authority — Absolute

Recurring human characters use reusable canonical character-card PNGs generated from `Character-References/` under `Character-References/character-card-standard.md`.

The approved card controls face, age presentation, body proportions, hair geometry/color, permanent marks, permanent accessories, and primary silhouette from all camera angles and expressions.

If a character's current PNG predates the card standard, treat it as provisional and regenerate/approve it before using it as final identity authority. Nari's previous short-hair PNG is obsolete after the long-hair redesign and must be replaced by an approved long-hair canonical before new strips rely on her final identity authority.

## Strict Flat 2D Human-Drawn Gate — Absolute

Every generated or repaired strip must satisfy `Manhwa/style-guide.md` in actual pixels, not merely in prompt wording.

Required appearance:
- strict flat 2D human-drawn Korean manhwa/webtoon illustration
- clean intentional line art
- flat colors
- restrained simple hard-edged cel shading only
- matte characters, objects, architecture, furniture, appliances, screens, glass, and floors
- stable canonical anatomy/proportions
- natural hands
- mobile-readable composition

Reject photoreal/semi-photoreal, 3D/CGI/game-render, painterly, airbrushed, glossy/plastic/wet, beauty-ad shine, mirror-like reflections, excessive specular highlights, cinematic color grading, depth-of-field blur, bloom, rim light, lens flare, or over-rendered AI-polished output.

Do not propagate style drift from the previous strip. Permanent style authority outranks temporary strip-to-strip visual drift.

## Sequential Production

1. Read the current chapter beat plan, manifest, current strip prompt, and the binding global production rules above.
2. Confirm the current strip file itself explicitly lists all required character/environment/object/previous-strip attachments.
3. Attach required **current approved character-card canonical PNG(s)** for physically visible characters.
4. Attach the smallest relevant approved reusable environment canonical set listed in the current strip.
5. Attach relevant approved reusable object canonical(s) listed in the current strip.
6. For Strip 002 onward, attach the immediately previous APPROVED strip.
7. If a required canonical is missing, stale, or unapproved, **STOP** and create/regenerate/approve it; never improvise a substitute and never mark the strip production-ready.
8. Generate one tall vertical technical strip.
9. QA exact script/source ownership, character identity, movement, object routes/counts, environment geometry, power state, lighting, object states, lettering/SFX, and seam behavior.
10. QA character-card consistency from the current camera angle: face, hair length/silhouette, build, accessories, outfit identity, and expression must remain the same person.
11. QA strict flat 2D human-drawn style in the actual image against `Manhwa/style-guide.md`.
12. QA SFX as a physical chain: source → action → sound → timing → placement → state change/consequence.
13. QA the **black read-slice grammar**: small black gutter between distinct vertical slices; diagonal/slanted black divider between separate side-by-side views; no giant black bands.
14. QA lower 20–25% for dead/unused canvas.
15. Reject/regenerate before proceeding if any mandatory item fails.
16. Re-audit the corrected strip after every correction, then cross-audit adjacent strips for regressions.
17. Only an APPROVED Strip N becomes temporary continuity authority for Strip N+1.
18. After the last strip passes, stitch in order, crop intentional overlaps, run seam QA, then uniformly resize for publishing.
19. Run one fresh clean-room chapter audit from Strip 001 through Strip 032 after all corrections. Do not trust earlier PASS labels.

## Reference Priority

1. current user instruction
2. current chapter/current strip story script
3. current approved character card
4. approved environment geometry
5. approved object identity/state vocabulary
6. previous approved strip temporary state

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

Reject for:
- stale/wrong/missing character-card references
- missing/unapproved required environment or object canonical PNGs
- face/hair/body identity drift across angles
- wrong/missing reference attachments
- wrong/missing text or invented reader-facing text
- wrong source ownership
- environment/object redesign
- teleporting movement/props
- duplicated objects/bags/devices
- wrong power state
- unclear or physically unsupported SFX
- missing/incorrect black slice separators
- missing diagonal divider in side-by-side separate shots
- giant black gutter used as filler
- visible technical seam
- wrong helpful/hostile signature
- photoreal, semi-photoreal, 3D, CGI, glossy, cinematic, painterly, airbrushed, mirror-like, or over-rendered visual drift

## Production-Complete Rule

A prompt-only package is not production-complete. `PRODUCTION COMPLETE` requires all required canonical visual authorities to exist and be approved, every sequential rendered strip to pass, the stitched chapter to pass seam QA, and a fresh final clean-room visual audit to find zero unresolved mandatory defects.