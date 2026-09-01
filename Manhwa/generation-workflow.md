# Manhwa Generation Workflow

## Production Authority

`Manhwa/` is the sole active visual-production pipeline. Converted/audited Manhwa chapter files are self-contained story authority. `Source-Archives/` is reference-only material for chapters not yet converted.

Always binding on every active strip:
- `Manhwa/style-guide.md`
- `Manhwa/lettering-sfx-guide.md`
- `Manhwa/seam-continuity-protocol.md`
- `Manhwa/vertical-scroll-layout-guide.md`
- this workflow

A chapter/strip may make these rules stricter but may never loosen them.

## Character Card Authority — Absolute

Recurring humans use approved canonical character-card WebPs under `Character-References/` generated from prompts following `character-card-standard.md`.

Approved card controls face, age presentation, body proportions, hair geometry/color, permanent marks/accessories, and primary silhouette from all angles/expressions.

Generation may produce PNG first locally. After visual approval, manually convert to WebP, commit/store the WebP, and use that exact `.webp` production path. Intermediate/deleted PNG is not production authority.

Nari's retired short-hair design is obsolete. Current identity uses long dark-plum hair approximately mid-back, loose by default, yellow scrunchie on one wrist.

## Attached Visual References Are Binding — Absolute

Approved attached WebPs are permanent visual authority, not inspiration.

Preserve character identity, environment geometry, furniture/appliance placement, object construction, cables/plugs, materials, proportions, recurring prop details, and physically valid reverse-angle relationships.

If intended composition conflicts with approved reference, recompose shot/action. **Never modify canon to make generation easier.**

### Permanent Canon vs Previous Strip — Absolute

Immediately previous APPROVED strip controls temporary story state only: pose, facing, held items, open/closed state, temporary prop placement, current power/light state, damage, food amount, seam continuity.

It does not outrank permanent canon. If previous rendered strip contains permanent drift in face, hair, proportions, room geometry, wall-socket location, appliance body, furniture placement, or recurring object construction, correct that permanent drift to attached canonical while preserving legitimate temporary state.

## Derived Micro-Detail Rule — Canon-Subordinate Only

A story may require a small practical detail that is not clearly readable in the existing canonical WebPs, such as an exact wall outlet faceplate, an ordinary utensil-storage drawer/caddy, or a minor non-plot household fitting.

When this happens:
- first exhaust the attached floor plan, room wides/details, object reference, and approved angle atlas before deriving anything
- derive ONLY the smallest necessary micro-detail inside already-canonical geometry
- do not add/move a wall, cabinet, counter, appliance, furniture item, doorway, shelf, or other architecture to make room for it
- place the detail where real-world function and existing geometry allow
- the derived detail is **temporary chapter continuity**, not new permanent canon and never outranks the approved WebPs
- once correctly established in an APPROVED strip, preserve that derived detail for later Chapter 1 continuity unless an approved canonical explicitly resolves/supersedes it
- if later canonical evidence conflicts, canonical wins and the affected strip must be deliberately corrected; never silently propagate the derived detail

Do not let a generated strip create new permanent architecture authority merely because a reference omitted a tiny functional detail.

## Real-Scenario Cause / Action / Consequence — Absolute

Every meaningful state change must pass:

`START STATE → CAUSE → VISIBLE PHYSICAL ACTION → RESULT → END STATE THAT PERSISTS`

Audit small actions too: reach, grip, hand occupancy, step count, sit/stand, hinges, placement, food handling, cord routing, plug removal, knife drop, chopstick state, chair movement, eyeline, body support.

A camera cut cannot hide teleport/reset.

## Mandatory Action-Proof Framing — Absolute

When an action establishes a continuity-critical fact, artwork must visually prove the mechanism—not just before-state and result.

Frame the physical contact point/source and result in same slice or immediately adjacent causally continuous detail slices. Examples:
- hand gripping plug BODY at WALL socket → plug leaves socket → loose plug + empty socket
- hand picking/placing key → old location empty → new location has same key
- blade entering sheath → visible alignment/insertion → sheathed knife remains
- knife leaving fingers → fall path → one impact spot
- seated body + actual chair → push/clearance → stand beside same moved chair
- hand on cabinet handle/hinge → cabinet opens
- reach/breath relative to same candle → flame extinguishes
- fingers part bag opening → tablet physically inside
- hand/foot contacts packet/prop before SFX/state change

Do not crop decisive contact point offscreen. SFX/reaction/narration/later state cannot substitute for mechanism. If contact cannot be shown clearly, change camera angle—not action/canon.

## Micro-Continuity / Persistence Ledger — Absolute

Visible story-world state persists through next visual slice and strip unless visible action or legal time/location cut changes it.

Track at minimum:
- hands and held items
- food/noodle amount/location
- bowl/pot/chopstick/packet/wrapper counts
- cords/plugs/wall-socket state
- key/manual/note/pen/notebook
- phone/tablet/bag
- knife/sheath
- candle/holder/flame/wick
- chair position/occupancy
- cabinet/stockpot/lid/towels/speaker
- feet/facing/distance/room position
- device display/power/light state

Occlusion is not disappearance. New camera angle does not authorize reset.

### Camera-Cut Conservation Rule — Absolute

Close-up, reverse shot, reaction insert, black gutter, diagonal split, or strip boundary cannot silently change quantity, hand ownership, orientation, connection state, or location. Off-frame objects still exist at last valid state and must re-enter in that same state unless a visible/legal change occurred.

### Temporary Hand Identity Conservation — When Applicable

If a continuity-critical object remains in one physical hand across multiple slices or strips, the first clear action establishes a production-only hand identity for that anatomical hand/arm.

Example: when Nari draws the blackout knife in Strip 016, that anatomical hand becomes `KNIFE HAND` until the knife is released.

Rules:
- reverse camera shots may flip screen-left/screen-right, but may NOT swap the object into the other physical hand
- a silent hand transfer is forbidden; any transfer must be scripted and visibly shown
- after release, later contact that refers to that arm/wrist must use the same anatomical side
- production-only hand identity labels are NEVER reader-facing text

## Prop Topology / Relative-Placement Conservation — Absolute

Continuity is not only “does the object still exist?” It also includes **where that object is relative to every nearby anchor**.

Once a strip establishes a continuity-critical local arrangement, preserve that story-world topology until visible movement changes it.

Examples:
- pot remains on same trivet at same table location
- folded cloth remains at same hot-handle side
- candle/holder remains at same side/position relative to pot/chair
- used chopsticks remain at same pot rest point
- wrapper/packet remain at their established floor/table spots
- lid remains on its established shelf side when removed from pot
- pushed chair remains at same displaced angle
- knife remains same impact point

A reverse shot may change what is screen-left/screen-right, but must **not swap physical sides in the room/table**. Do not mirror prop topology for composition convenience.

## Character ↔ Environment Physical Interaction — Absolute

For every slice verify:
- feet/body have believable support
- seated anatomy aligns actual chair geometry
- reach distance to prop/plug/candle/cabinet is possible
- eyeline points to real target location
- door/cabinet swing respects hinges/walls
- movement route fits canonical floor plan
- characters do not pass through furniture/walls/appliances
- object/character scale matches attached environment
- reverse angles derive from canon, never mirror for convenience

## Wall-Socket / Appliance-Cord Rule — Absolute

Unless script explicitly says a detachable appliance-side cable is removed, **UNPLUG means removing electrical plug from WALL-MOUNTED SOCKET/OUTLET.**

Required:
- socket physically on wall at canonical or canon-subordinate derived Chapter 1 location
- appliance-side cord remains attached
- same cord leads to same wall plug
- fingers grip plug BODY, never pull cable itself
- hand acts at wall plug/socket
- after unplugging, loose plug remains attached to cord and socket empty
- disconnected wall-end state persists until explicit re-plug
- critical unplug action visibly proves hand + plug + wall socket

Reject cable pulled out of appliance, cable tug instead of plug body, moved socket, disappearing plug, cropped socket interaction, silent re-plug.

## Fixed Local Wall-Outlet Continuity — Canon-Subordinate

Wall outlets are environment details and must never behave like movable props.

When approved environment/object references visibly establish an outlet location, use that exact canonical location.

If a story-required outlet is not clearly visible in the approved WebPs:
- derive the smallest physically plausible outlet placement from the already-canonical wall/counter/appliance geometry under the Derived Micro-Detail Rule
- do NOT relocate/add architecture or claim the generated placement is new permanent canon
- once an APPROVED Strip 006 establishes that canon-compatible Chapter 1 micro-detail, later Chapter 1 strips preserve the same story-world wall, height, faceplate/socket orientation, nearby furniture relationship, and cord-route family for continuity
- this local continuity detail always remains subordinate to approved environment/object WebPs
- if approved canonical evidence later resolves a different location, canonical wins and affected strips must be corrected deliberately

Later reverse shots may change screen position but cannot move the same outlet to another physical wall/height or invent a more convenient socket.

## Narration Design By Scenario — Absolute

Narration wording remains exact, but visual treatment **and placement** respond to purpose/event/pacing/emotional pressure. Do not reuse one identical caption design or default position.

Coherent functional variants:
- time/location setup → clean compact editorial
- ordinary observation → restrained unobtrusive
- rule/procedure → firmer utilitarian
- investigation/evidence → compact report-like
- ominous realization → sparse higher-contrast
- suspense/listening/reveal delay → minimal footprint

Placement follows composition. **Do not default every caption to top-left.** Legitimate time/location caption may use upper area when appropriate but must not resemble repetitive technical tag.

Narration never imitates speech balloons, screen UI, handwriting, production labels; never covers faces, hands, plugs/sockets, food paths, clues, environment anchors.

## No Reader-Visible Production Labels — Absolute

Never render production metadata anywhere, especially top-left:
- `V01`, `V-01`, `V##`
- `P1`, `P001`, `P##`
- `Strip 001`, `strip-001`
- `BEAT`, `SCENE`, `PANEL`, `SHOT`, `REFERENCE`, `DRAFT`, `LAYOUT`
- circled panel numbers, crop marks, QA notes, technical headers/footers

Any `V-*` or similar technical label in artwork = automatic rejection.

## Strict Flat 2D Human-Drawn Gate — Absolute

Every generated/repaired strip must satisfy `style-guide.md` in actual pixels.

Required: strict flat 2D human-drawn Korean manhwa/webtoon, clean line art, flat colors, restrained hard-edged cel shading only, matte materials, stable canonical anatomy/proportions, natural hands, mobile readability.

Reject photoreal/semi-photoreal, 3D/CGI/game render, painterly, airbrushed, glossy/plastic/wet, beauty-ad shine, mirror-like excessive specular, cinematic grading, DOF blur, bloom, rim light, lens flare, over-rendered AI-polished output.

Never propagate style drift from previous strip.

## Sequential Production

1. Read chapter beat plan, manifest, current strip prompt, binding global rules.
2. Confirm exact required character/environment/object/previous-strip attachments by current repository path.
3. Attach approved character WebPs for visible characters.
4. Attach smallest relevant approved environment set.
5. Attach relevant approved object WebPs.
6. Strip 002 onward: attach immediately previous APPROVED rendered strip for temporary state/seam only.
7. Missing/stale/wrong-path/unapproved canonical → STOP; no improvisation.
8. Before generation check START STATE, ALLOWED CHANGES, END STATE, action-proof, temporary-hand identity, prop topology, derived-micro-detail/outlet requirements.
9. Generate one tall technical strip with no production IDs.
10. QA exact script/source ownership, identity, movement, object routes/counts, geometry, power/light, object states, lettering/SFX, seams.
11. QA every adjacent slice for micro-continuity.
12. QA temporary hand identity across reverse shots/seams when applicable.
13. QA prop topology/relative physical sides across reverse shots.
14. QA every critical action for visible proof framing.
15. QA unplugging against wall-socket + canon-subordinate local-outlet rules.
16. QA any derived micro-detail remains minimal and subordinate to permanent canon.
17. QA permanent canon separately from previous-strip temporary state.
18. QA character-card consistency.
19. QA strict flat 2D style in pixels.
20. QA SFX source→action→sound→timing→placement→state consequence.
21. QA narration treatment/placement; reject one-template/top-left tag repetition.
22. QA black read-slice grammar/diagonal dividers.
23. QA lower canvas dead-space.
24. Reject/regenerate if any mandatory item fails.
25. Re-audit corrected strip + adjacent seams.
26. Only APPROVED Strip N becomes temporary continuity authority for N+1.
27. After Strip032 passes, stitch, seam QA, uniformly resize.
28. Run fresh clean-room chapter audit 001→032; never trust earlier PASS labels.

## Reference Priority

1. current user instruction
2. current chapter/current strip script
3. approved character card
4. approved environment geometry
5. approved object identity/state
6. previous approved strip temporary state

Previous strip or derived micro-detail cannot override permanent canon.

## Reuse Rule

Characters, Unit 2407, building shared areas, recurring objects are reusable canonicals. Future chapters reuse approved repository WebPs instead of chapter-specific duplicates.

## Black Slice vs Technical Seam

Small black gutter = distinct reader-facing slice.
Diagonal black slash = two distinct camera slices sharing row.
A/E technical seam = invisible production plumbing; no black bar when art/effect continues.

## No-Dead-Bottom Rule

Reject huge unused tails. Never invent filler text/SFX. Prefer canonical environment, action/reaction, atmosphere, reveal timing, compact seam buffer.

## Automatic Reject Rules

Reject for:
- stale/wrong/missing canonical attachment
- attached-reference redesign/environment mirroring
- previous-strip or derived-detail drift propagated over canon
- identity/environment/object drift
- wrong/missing text or invented reader-facing text
- any V/P/strip/beat/panel/scene/production label
- wrong source ownership
- one fixed narration design/repetitive top-left caption placement
- teleporting movement/props
- adjacent-slice object/food/hand disappearance without cause
- continuity-critical hand silently swaps across reverse camera/strip
- prop topology swapping physical sides across reverse shots
- continuity-critical mechanism hidden/cropped
- appliance cable removed instead of wall plug
- cable pulled instead of plug body
- outlet moved/reinvented against canonical geometry
- generated outlet treated as new permanent canon
- silent re-plug
- duplicated objects/bags/devices
- wrong power state
- unsupported SFX
- missing black separators/diagonal divider
- giant filler gutter/dead canvas
- visible technical seam
- wrong helpful/hostile signature
- photoreal/3D/glossy/cinematic/painterly/airbrushed/over-rendered drift

## Production-Complete Rule

Prompt-only package is not production-complete. `PRODUCTION COMPLETE` requires all canonical authorities approved, every sequential rendered strip passing, stitched chapter seam QA passing, and fresh final clean-room visual audit with zero unresolved mandatory defects.
