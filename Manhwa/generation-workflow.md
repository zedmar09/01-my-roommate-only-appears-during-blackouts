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

A story may require a small practical detail not clearly readable in existing canonical WebPs, such as exact outlet faceplate, ordinary utensil-storage point, or minor non-plot fitting.

When this happens:
- exhaust attached floor plan, wides/details, object reference, and angle atlas first
- derive ONLY smallest necessary micro-detail inside already-canonical geometry
- do not add/move wall, cabinet, counter, appliance, furniture, doorway, shelf, architecture
- place detail where real-world function/existing geometry allow
- derived detail is temporary chapter continuity, never permanent canon and never outranks WebPs
- once correctly established in APPROVED strip, preserve it during that chapter unless canonical explicitly supersedes it
- later canonical conflict → canonical wins and affected strip is deliberately corrected

Do not let generated art create new permanent architecture authority merely because a reference omitted a small practical detail.

## Legal Time / Location Cut Rule — Absolute

A legal time/location cut may change ordinary noncritical clutter, routine body position, or mundane object placement when the story does not require its prior state.

It does **not** automatically erase story-critical continuity.
If an object/state is already evidence, plot-critical, or explicitly required after the cut, preserve it or define a new physically plausible post-cut state explicitly.

Examples:
- a temporary comedy cable may be cleaned up after a multi-day cut
- dropped chopsticks may be cleaned after an explicit later-time cut if no longer plot evidence
- a plot note and its exact supernatural handwriting/pen rest state must survive an overnight cut when the next scene investigates it
- a phone may receive an ordinary post-cut starting location only when no prior story-critical phone state requires preservation; that new location must be explicit and non-duplicative

Never use “time passed” as permission to reset canon, erase evidence needed by the next scene, or create a second copy.

## Real-Scenario Cause / Action / Consequence — Absolute

Every meaningful state change must pass:
`START STATE → CAUSE → VISIBLE PHYSICAL ACTION → RESULT → END STATE THAT PERSISTS`

Audit small actions too: reach, grip, hand occupancy, step count, sit/stand, hinges, placement, food handling, cord routing, plug removal, knife drop, chopstick state, chair movement, eyeline, body support.
A camera cut cannot hide teleport/reset.

## Deterministic Single-Mechanism Rule — Absolute

When a continuity-critical action needs one physically valid solution, do not leave multiple contradictory alternatives inside the same prompt.

Choose one authoritative mechanism and carry it through every section of that strip.
Examples:
- if a character must free one hand for a smart lock, define exactly which bag is placed where and when it is picked back up
- if a character remains crouched after unplugging, do not later call the same pose “crouched/standing” without a visible rise
- if a phone is pocketed, define the same pocket for later retrieval rather than allowing arbitrary pockets/hands

Optional alternatives are acceptable only when they are genuinely equivalent and cannot change continuity-critical state. If alternatives would produce different object/hand/body states, choose one.

## Mandatory Action-Proof Framing — Absolute

When an action establishes a continuity-critical fact, artwork must visually prove the mechanism—not just before-state/result.

Frame contact/source/result in same slice or immediately adjacent causally continuous detail slices. Examples:
- hand gripping plug BODY at WALL socket → plug leaves socket → loose plug + empty socket
- hand picking/placing key → old location empty → new location same key
- blade entering sheath → visible alignment/insertion → sheathed knife remains
- knife leaving fingers → fall path → one impact spot
- seated body + actual chair → push/clearance → stand beside same moved chair
- hand on cabinet handle/hinge → cabinet opens
- reach/breath relative to same candle → flame extinguishes
- fingers part bag opening → tablet physically inside
- hand/foot contacts packet/prop before SFX/state change

Do not crop decisive contact point. SFX/reaction/narration/later state cannot substitute. If contact cannot be shown clearly, change camera angle—not action/canon.

## Same-Object Representation / Insert Rule — Absolute

A close-up, inset, magnified detail, device-screen insert, page detail, plug/socket detail, reaction insert, or side-by-side view does **not** create another physical copy.

When wide + detail show one continuity-critical object/person:
- both views refer to SAME physical object/person unless script explicitly establishes another
- same-moment views must show compatible state
- a later action slice may advance state exactly once
- do not leave earlier state physically true after the action has completed
- if composition visually reads as two copies, recompose

Examples:
- key close-up in hand does not leave second key in tray
- plug/socket detail does not create second plug/outlet
- knife fall detail does not leave another knife in hand
- phone-screen insert is same phone Nari holds/placed
- binder-page detail is same binder on same surface
- notebook-writing insert is same notebook in same table zone
- one character shown from two camera views is still one person, never two bodies in world space

QA same-object representation separately from ordinary object-count continuity.

## Micro-Continuity / Persistence Ledger — Absolute

Visible story-world state persists through next slice/strip unless visible action or legal cut changes it.
Track at minimum:
- hands and held items
- worn accessories and anatomical side
- feet/step marks and body support
- food/noodle amount/location
- bowl/pot/chopstick/packet/wrapper counts
- cords/plugs/wall-socket state
- key/manual/note/pen/notebook
- phone/tablet/bag/pockets
- knife/sheath
- candle/holder/flame/wick
- chair position/occupancy
- cabinet/stockpot/lid/towels/speaker
- facing/distance/room position
- device display/power/light state

Occlusion is not disappearance. New camera angle does not authorize reset.

### Camera-Cut Conservation Rule — Absolute

Close-up, reverse shot, reaction insert, gutter, diagonal split, or strip boundary cannot silently change quantity, anatomical ownership, orientation, connection state, or location. Off-frame objects still exist at last valid state until visible/legal change.

## Temporary Anatomical-Side Identity — When Applicable

When a continuity-critical temporary state remains on one physical anatomical side, establish a production-only identity and preserve it across reverse shots/seams until visible transfer or expiry.

May apply to:
- `KNIFE HAND`
- `PHONE HAND`
- `SCRUNCHIE WRIST`
- `STEP FOOT`
- `CANDLE FOOT`
- `BAG SHOULDER`
- `UMBRELLA HAND`
- `PHONE POCKET`
- one specific ear used for an earbud check

Rules:
- screen-left/right may reverse; anatomical side may not
- silent hand/foot/wrist/shoulder/pocket transfer is forbidden
- any transfer must be scripted and visibly shown
- temporary label expires only when object/state is visibly released/placed or scene no longer requires it
- production-only labels are NEVER reader-facing text

Do not over-label trivial states; use this only where reverse-shot drift could materially break continuity.

## Worn-Accessory Persistence — Absolute

If a worn accessory is established and no removal/transfer is scripted, it remains on same body location through close-ups/reverse shots.
Examples: scrunchie wrist, headphones around neck, watch wrist, earbuds, bag shoulder.
Partial occlusion is allowed; disappearance, side swap, duplication, move to another body location/surface is not.

## Prop Topology / Relative-Placement Conservation — Absolute

Continuity includes where an object is relative to nearby anchors.
Once a continuity-critical arrangement is established, preserve story-world topology until visible movement changes it.

Examples:
- pot same trivet/table location
- cloth same hot-handle side
- candle same side/position relative to pot/chair
- used/clean chopsticks same rest points
- wrapper/packet same floor/table spots
- lid same shelf side when removed
- pushed chair same displaced angle
- knife same impact point
- separate floor evidence stays separate
- notebook zone stays clear of existing table evidence

Reverse shot may change screen-left/right but must not swap physical story-world sides/order.

## Character ↔ Environment Physical Interaction — Absolute

For every slice verify:
- feet/body believable support
- seated anatomy actual chair geometry
- reach distance possible
- eyeline real target location
- door/cabinet swing respects hinges/walls
- route fits floor plan
- bodies do not pass through furniture/walls/appliances/other fixed evidence
- object/character scale matches references
- reverse angles derive from canon, never mirror for convenience

Routes must account for temporary floor obstacles/evidence. Do not let characters walk through, kick, or cover evidence unless scripted.

## Wall-Socket / Appliance-Cord Rule — Absolute

Unless script explicitly says detachable appliance-side cable is removed, **UNPLUG means electrical plug removed from WALL-MOUNTED SOCKET/OUTLET.**

Required:
- socket physically on wall at canonical or canon-subordinate derived location
- appliance-side cord remains attached
- same cord leads same wall plug
- fingers grip plug BODY, never cable
- hand acts at wall plug/socket
- after unplugging loose plug remains attached and socket empty
- disconnected wall-end state persists until explicit re-plug
- critical unplug action visibly proves hand + plug + wall socket

Reject appliance-side disconnect, cable tug, moved socket, disappearing plug, cropped socket interaction, silent re-plug.

## Fixed Local Wall-Outlet Continuity — Canon-Subordinate

Wall outlets are environment details, never movable props.
When canonical refs visibly establish outlet, use exact canonical location.
If required outlet not clear:
- derive smallest plausible placement from canonical wall/counter/appliance geometry under Derived Micro-Detail Rule
- do NOT relocate/add architecture
- once APPROVED strip establishes compatible chapter micro-detail, later chapter strips preserve same wall, height, faceplate/socket orientation, nearby furniture relationship, cord-route family
- local detail remains subordinate to WebPs
- canonical conflict later → canonical wins and affected strips corrected deliberately

Reverse shots cannot move outlet to another wall/height or invent convenient socket.

## Lettering / Balloon / SFX Evidence Safety — Absolute

Reader-facing text is not allowed to hide the physical proof needed to understand the scene.

Speech balloons/tails, thoughts, narration, device text, handwriting overlays, and SFX must not cover/sever:
- contact between hand/foot/body and continuity-critical object
- plug/socket/loose-plug proof
- key pickup/placement
- knife/sheath/fall/impact
- chair sit/stand mechanics
- cabinet handle/hinge
- candle reach/flame state
- food/noodle/chopstick path
- packet pickup/step contact
- phone/notebook pickup/placement
- exact device text or environment anchor needed for route

If text conflicts with proof, reflow text/art composition. Never move/hide physical mechanism to accommodate lettering.
Balloon tails must clearly identify actual speaker and not cross another speaker confusingly.

## Narration Design By Scenario — Absolute

Narration wording exact; treatment **and placement** respond to purpose/event/pacing/emotional pressure. Do not reuse one identical caption design/default position.

Functional variants:
- time/location → clean compact editorial
- ordinary observation → restrained unobtrusive
- rule/procedure → firmer utilitarian
- investigation/evidence → compact report-like
- ominous realization → sparse higher-contrast
- suspense/listening/reveal → minimal footprint

Do not default every caption top-left. Legitimate time caption may use upper area when appropriate but must not resemble technical tag.
Narration never imitates speech balloons, screen UI, handwriting, production labels; never covers continuity evidence.

## No Reader-Visible Production Labels — Absolute

Never render production metadata anywhere, especially top-left:
- V/P IDs
- strip IDs
- BEAT/SCENE/PANEL/SHOT/REFERENCE/DRAFT/LAYOUT/QA
- temporary state names such as KNIFE HAND, STEP FOOT, NOTEBOOK ZONE
- circled panel numbers, crop marks, technical headers/footers

Any production/state label in artwork = automatic rejection.

## Strict Flat 2D Human-Drawn Gate — Absolute

Every generated/repaired strip must satisfy `style-guide.md` in actual pixels.
Required: strict flat 2D human-drawn Korean manhwa/webtoon, clean line art, flat colors, restrained hard-edged cel shading, matte materials, stable anatomy/proportions, natural hands, mobile readability.

Reject photoreal/semi-photoreal, 3D/CGI/game render, painterly, airbrushed, glossy/plastic/wet, beauty-ad shine, mirror-like excessive specular, cinematic grading, DOF blur, bloom, rim light, lens flare, over-rendered AI-polished output.
Never propagate style drift from previous strip.

## Sequential Production

1. Read chapter beat plan, manifest, current strip prompt, binding global rules.
2. Confirm exact required canonical/previous-strip attachments.
3. Attach approved character WebPs for visible characters.
4. Attach smallest relevant environment set.
5. Attach relevant object WebPs.
6. Strip 002 onward: previous APPROVED strip = temporary state/seam only.
7. Missing/stale/wrong/unapproved canonical → STOP.
8. Check START/ALLOWED/END, legal-cut persistence, deterministic single mechanism, action-proof, same-object representation, anatomical-side identities, worn accessories, prop topology, derived detail/outlet.
9. Generate one tall strip with no production IDs.
10. QA exact script/source ownership, identity, movement, object routes/counts, geometry, power/light, object states, lettering/SFX, seams.
11. QA adjacent slices for micro-continuity.
12. QA same-object wide/detail representation for duplicate/incompatible states.
13. QA temporary anatomical-side identities when applicable.
14. QA worn accessories.
15. QA prop topology/relative sides across reverse shots.
16. QA every critical action for visible proof.
17. QA routes against floor obstacles/evidence.
18. QA unplugging against wall-socket/canon-subordinate outlet rules.
19. QA derived micro-detail remains minimal/subordinate.
20. QA permanent canon separately from previous-strip state.
21. QA character card consistency.
22. QA strict flat 2D pixels.
23. QA SFX physical chain.
24. QA lettering/balloon evidence safety.
25. QA narration treatment/placement.
26. QA black read-slice/diagonal divider grammar.
27. QA lower-canvas dead space.
28. Reject/regenerate if any mandatory item fails.
29. Re-audit correction + adjacent seams.
30. Only APPROVED Strip N becomes temporary continuity authority for N+1.
31. After Strip032 passes, stitch/seam QA/uniform resize.
32. Run fresh clean-room 001→032 audit; never trust earlier PASS labels.

## Reference Priority

1. current user instruction
2. current chapter/current strip script
3. approved character card
4. approved environment geometry
5. approved object identity/state
6. previous approved strip temporary state
7. canon-compatible derived micro-detail only

Previous strip or derived detail cannot override permanent canon.

## Reuse Rule

Characters, Unit 2407, building shared areas, recurring objects are reusable canonicals. Future chapters reuse approved WebPs instead of chapter-specific duplicates.

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
- previous-strip/derived-detail drift propagated over canon
- identity/environment/object drift
- wrong/missing/invented reader text
- any production/temp-state label appears
- wrong source ownership
- one fixed narration design/repetitive top-left placement
- teleporting movement/props
- illegal time-cut reset of story-critical evidence
- contradictory alternative action mechanisms inside same strip
- adjacent-slice state disappearance
- same-object close-up/inset creates duplicate/incompatible state
- hand/foot/wrist/shoulder/pocket silently swaps anatomical side
- worn accessory disappears/swaps/duplicates
- prop topology swaps physical sides
- route crosses/kicks floor evidence without script
- continuity-critical mechanism hidden/cropped
- lettering/SFX hides physical proof
- appliance cable removed instead of wall plug
- cable pulled instead of plug body
- outlet moved/reinvented against canon
- generated outlet treated permanent canon
- silent re-plug
- duplicated objects/bags/devices
- wrong power state
- unsupported SFX
- missing black/diagonal divider
- giant dead canvas
- visible technical seam
- wrong helpful/hostile signature
- photoreal/3D/glossy/cinematic/painterly/airbrushed/over-rendered drift

## Production-Complete Rule

Prompt-only package is not production-complete. `PRODUCTION COMPLETE` requires all canonical authorities approved, every sequential rendered strip passing, stitched chapter seam QA passing, and fresh final clean-room visual audit with zero unresolved mandatory defects.
