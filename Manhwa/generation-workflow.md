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

Recurring human characters use reusable approved canonical character-card WebPs stored under `Character-References/` and generated from prompts that follow `Character-References/character-card-standard.md`.

The approved card controls face, age presentation, body proportions, hair geometry/color, permanent marks, permanent accessories, and primary silhouette from all camera angles and expressions.

Image generation may produce PNG first as a local intermediate. After approval, manually convert to WebP, commit/store the approved WebP, and use that exact `.webp` path in production Markdown. A deleted/intermediate PNG is not production authority.

Nari's retired short-hair design is obsolete. Her current approved identity uses long dark-plum hair at approximately mid-back length, loose by default, with the yellow scrunchie on one wrist.

## Attached Visual References Are Binding — Absolute

Approved attached WebPs are permanent visual authority, not inspiration.

Production must preserve the attached character identity, environment geometry, furniture/appliance placement, object construction, cable/plug identity, materials, proportions, recurring prop details, and physically valid reverse-angle relationships.

If an intended composition conflicts with an approved reference, recompose the shot/action. **Never modify canon to make generation easier.**

Previous-strip artwork controls temporary state only. It cannot override a permanent character/environment/object canonical.

## Real-Scenario Cause / Action / Consequence — Absolute

Every meaningful physical state change must pass:

`START STATE → CAUSE → VISIBLE PHYSICAL ACTION → RESULT → END STATE THAT PERSISTS`

Audit small actions too: reach, grip, hand occupancy, step count, sit/stand mechanics, door/cabinet hinges, object placement, food handling, cord routing, plug removal, knife drop, bowl/chopstick state, chair movement, eyeline, and body support.

A camera cut cannot be used to hide a teleport or reset.

## Wall-Socket / Appliance-Cord Rule — Absolute

Unless a script explicitly says a detachable appliance-side cable is removed, **UNPLUG means removing the electrical plug from the WALL-MOUNTED SOCKET / OUTLET.**

Required:
- socket is physically on the wall at the canonical location
- appliance-side cord remains attached to the appliance
- same cord leads to same wall plug
- hand acts at the wall plug/socket for the unplugging beat
- after unplugging, loose plug remains attached to cord and wall socket is empty
- subsequent views preserve the same disconnected wall-end state until an explicit re-plug action

Reject if the cable is pulled out of the TV/speaker/appliance body instead of the wall socket, if the wall socket moves, if the plug disappears, or if the appliance silently becomes plugged again.

## Micro-Continuity / Persistence Ledger — Absolute

A visible story-world state persists through the next visual slice and through the next strip unless a visible action or legal time/location cut changes it.

Track at minimum:
- hands and held items
- food/noodle amount and location
- bowl/pot/chopsticks/packet counts
- cords/plugs/wall-socket state
- key/manual/note/pen/notebook state
- phone/tablet/bag state
- knife/sheath state
- candle/holder/flame state
- chair position/occupancy
- cabinet/stockpot/lid/towels/speaker state
- character feet, facing, distance, and room position

Occlusion is not disappearance. A new camera angle does not authorize a reset.

## Character ↔ Environment Physical Interaction — Absolute

For every slice verify:
- feet/body have believable support
- seated anatomy aligns to actual chair geometry
- reach distance to prop/plug/candle/cabinet is physically possible
- eyeline points to the real target location
- door/cabinet swing respects hinges/walls
- movement route fits the canonical floor plan
- characters do not pass through furniture/walls/appliances
- object and character scale match the attached environment
- reverse angles are derived from canon, not mirrored for convenience

## Narration Design By Scenario — Absolute

Narration wording remains exact, but narration **visual treatment must respond to the specific purpose, event, pacing, and emotional pressure of the beat**. Do not reuse one identical caption design for the whole chapter.

Use a coherent family with context-sensitive variants, for example:
- neutral time/location setup → clean compact editorial caption
- ordinary observation → restrained unobtrusive caption
- rule/procedural warning → firmer utilitarian treatment
- investigative/evidence narration → compact report-like treatment
- ominous realization → sparse higher-contrast treatment
- suspense/listening/reveal delay → minimal footprint so silence/art dominates

Narration must never imitate speech balloons, screen UI, handwritten notes, or production labels. It must not cover faces, hands, wall plugs/sockets, food continuity, clues, or canonical environment anchors.

## No Reader-Visible Production Labels — Absolute

Never render production metadata anywhere, especially not at the top-left of a vertical slice.

Forbidden examples:
- `V01`, `V-01`, `V##`
- `P1`, `P001`, `P##`
- `Strip 001`, `strip-001`
- `BEAT`, `SCENE`, `PANEL`, `SHOT`, `REFERENCE`, `DRAFT`, `LAYOUT`
- circled panel numbers, crop marks, QA notes, technical headers/footers

Any `V-*` or similar technical label in the actual artwork is an automatic rejection.

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
2. Confirm the current strip file itself explicitly lists all required character/environment/object/previous-strip attachments by **exact current repository path and filename**.
3. Attach required **current approved character-card canonical WebP(s)** for physically visible characters.
4. Attach the smallest relevant approved reusable environment WebP set listed in the current strip.
5. Attach relevant approved reusable object WebP(s) listed in the current strip.
6. For Strip 002 onward, attach the immediately previous APPROVED rendered strip.
7. If a required canonical WebP is missing, stale, wrong-path, or unapproved, **STOP** and create/regenerate/approve it; never improvise a substitute and never mark the strip production-ready.
8. Before generation, write/check the strip's START STATE, ALLOWED CHANGES, and END STATE ledger.
9. Generate one tall vertical technical strip without any reader-visible production IDs.
10. QA exact script/source ownership, character identity, movement, object routes/counts, environment geometry, power state, lighting, object states, lettering/SFX, and seam behavior.
11. QA every adjacent slice for micro-continuity: hands, food, held props, cords/plugs/sockets, body position, chair state, open/closed state, and object persistence.
12. QA any unplugging beat against the wall-socket rule.
13. QA character-card consistency from the current camera angle: face, hair length/silhouette, build, accessories, outfit identity, and expression must remain the same person.
14. QA strict flat 2D human-drawn style in the actual image against `Manhwa/style-guide.md`.
15. QA SFX as a physical chain: source → action → sound → timing → placement → state change/consequence.
16. QA narration treatment for the actual scenario; reject one-template narration styling that ignores beat function.
17. QA the **black read-slice grammar**: small black gutter between distinct vertical slices; diagonal/slanted black divider between separate side-by-side views; no giant black bands.
18. QA lower 20–25% for dead/unused canvas.
19. Reject/regenerate before proceeding if any mandatory item fails.
20. Re-audit the corrected strip after every correction, then cross-audit adjacent strips for regressions.
21. Only an APPROVED Strip N becomes temporary continuity authority for Strip N+1.
22. After the last strip passes, stitch in order, crop intentional overlaps, run seam QA, then uniformly resize for publishing.
23. Run one fresh clean-room chapter audit from Strip 001 through Strip 032 after all corrections. Do not trust earlier PASS labels.

## Reference Priority

1. current user instruction
2. current chapter/current strip story script
3. current approved character-card WebP
4. approved environment WebP geometry
5. approved object WebP identity/state vocabulary
6. previous approved strip temporary state

If an approved previous strip conflicts with a character/environment/object canonical, do not propagate the drift. The canonical controls permanent identity/geometry; the previous strip controls only temporary story state.

## Reuse Rule

Characters, Unit 2407, residential building shared areas, and recurring story objects are reusable canonicals. Future chapters returning to the same person/place/object must reuse their approved repository WebPs instead of creating chapter-specific duplicates.

## Black Slice vs Technical Seam

A small black gutter marks a DISTINCT reader-facing slice inside a strip.
A diagonal black slash separates two distinct camera slices sharing a row.
A technical A/E seam is invisible production plumbing; do not add a black bar there if the artwork/effect is meant to continue across files.

## No-Dead-Bottom Rule

Reject huge unused white/neutral/black tails. Never invent filler text/SFX. Prefer existing canonical environment, action/reaction, atmosphere, reveal timing, or compact seam buffer.

## Automatic Reject Rules

Reject for:
- stale/wrong/missing character-card WebP reference
- missing/unapproved/wrong-path required environment or object WebP
- attached-reference redesign or environment mirroring
- face/hair/body identity drift across angles
- wrong/missing reference attachments
- wrong/missing text or invented reader-facing text
- any `V-*`, strip, beat, panel, scene, or production label rendered in artwork
- wrong source ownership
- one fixed narration-box design forced onto unrelated scenario types
- environment/object redesign
- teleporting movement/props
- object/food/hand state disappearing between adjacent slices without cause
- unplugging a cord from an appliance body instead of its wall-mounted socket
- silent re-plugging after a confirmed unplug
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
