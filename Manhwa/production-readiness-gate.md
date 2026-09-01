# Manhwa Production Readiness Gate

The Manhwa pipeline is the permanent production format.

A chapter is **PRODUCTION COMPLETE** only when every mandatory gate passes in the current post-correction state. Earlier PASS labels never substitute for a fresh final audit.

## Mandatory Gates

1. vertical beat plan + strip manifest locked
2. story/event/timeline/causality coherent
3. exact dialogue/narration/thought/device/note text + ownership locked
4. SFX source→action→sound→timing→placement→state/consequence verified
5. current approved character WebPs exist
6. required environment WebPs exist
7. required recurring object WebPs exist
8. attached WebPs treated as permanent authority, not inspiration
9. previous strip used only for temporary state/seam; never overrides permanent canon
10. any derived micro-detail is minimal, canon-compatible, temporary chapter continuity only, never permanent canon
11. every strip has deterministic START → ALLOWED CHANGES → END state
12. meaningful result follows real-world cause → visible action → result
13. critical actions visibly prove mechanism/contact point
14. hand occupancy/body support is physically possible; no extra-hand prop handling
15. continuity-critical anatomical hand identity is conserved across reverse shots until visible transfer/release
16. story-critical object provenance is continuous; no object appears at new location without visible/legal route
17. adjacent vertical slices preserve micro-continuity
18. conserved local prop topology preserves relative physical sides/order across reverse shots
19. distinct evidence locations remain distinct until visible movement changes them
20. wall unplugging removes plug BODY from WALL socket; appliance-side cord remains attached
21. any locally derived outlet detail remains subordinate to canonical room geometry and cannot move/redefine architecture
22. character↔environment interaction physically believable
23. narration design+placement follows scenario, not one repeated box/top-left tag
24. NO reader-visible production metadata (`V-*`, P/strip/beat/panel/scene/shot/QA/layout labels)
25. every technical strip generated/approved sequentially
26. strict flat 2D human-drawn style passes actual pixel inspection
27. power/light/candle/rain/device states physically coherent and contained
28. helpful/hostile effect signatures correct
29. black read-slice + diagonal-divider grammar correct
30. no purposeless dead bottom/double-gap seams
31. mobile lettering readable and does not cover continuity-critical evidence
32. stitched chapter has no seams, duplicate transitions, topology resets, geometry jumps, power/light jumps
33. final ending matches locked script exactly
34. fresh final clean-room audit finds zero unresolved mandatory findings

## Attached-Reference Failure — BLOCKING

Reject if generated art modifies a permanent attached reference-controlled feature rather than scripted temporary state.
Examples: mirrored apartment, recast character, redesigned TV/speaker/fridge, altered key/manual/mask, moved fixture/socket.
Recompose/regenerate; never accept canon drift for visual convenience.

## Previous-Strip / Derived-Detail Authority Failure — BLOCKING

Previous strip controls temporary pose, hand occupancy, food amount, pushed chair, open cabinet, current power/light, temporary prop locations, seam composition.

A derived micro-detail may cover only the smallest practical detail omitted from canon, such as exact outlet faceplate or ordinary utensil storage, and only within existing canonical geometry.

Neither may redefine permanent face/hair/proportions, architecture, furniture/appliance, recurring object construction, wall geometry, or canonical environment relationships.

If canonical evidence conflicts, canonical wins and affected art must be corrected deliberately.

## Action-Proof Failure — BLOCKING

Critical action is not proven if decisive mechanism/contact is hidden/cropped and art jumps directly to result.
Reject examples:
- lock SFX but no lock/door operation
- key in hand/tray with pickup/placement omitted
- unplugged appliance with no wall plug/socket proof
- knife sheathed without blade/sheath contact
- knife on floor without release/fall/impact
- standing without chair/body mechanics
- cabinet open without handle/hinge action
- candle out without real reach/blow relation
- tablet visible through closed opaque bag
- phone/notebook appears in hand without pickup
- packet changes floor→table without visible pickup
- door becomes closed only after a time cut with no closing action

If framing cannot prove mechanism, change camera.

## Hand Identity / Occupancy Failure — BLOCKING

Reject if characters require impossible extra hands, props float unsupported, or a continuity-critical item silently changes anatomical hand because the camera reverses.

Examples:
- handbag + binder + key ring + detached key all gripped impossibly
- phone + umbrella + earbuds + watch simultaneously handheld
- open binder + phone + page turning with impossible fingers
- moving box floating while lock/door is operated
- `KNIFE HAND` switching physical side without a visible transfer

Chapter 1: the hand used for the Strip 016 knife draw remains the same physical hand through Strip 023 release; the wrist caught/released in Strips 023–024 belongs to that same arm.

## Prop Provenance Failure — BLOCKING

A recurring/story-critical object must have a continuous source and route.
Reject if:
- empty packet appears without earlier establishment
- packet suddenly moves floor→table
- clean chopsticks appear from nowhere/new invented furniture
- phone disappears at seam or reappears elsewhere
- lid/towels change location without handling
- pen vanishes when attention shifts to TV
- key/knife/notebook jumps locations
- phone appears in hand after a time cut without an established source point when the strip requires its handling

## Prop Topology / Distinct Evidence Failure — BLOCKING

Reverse shots cannot swap physical story-world sides/order of conserved arrangements.
Reject if:
- candle changes physical side of pot
- folded cloth moves to other pot handle
- used/clean chopsticks swap rest points
- packet/wrapper table positions swap
- pushed chair shifts side/angle without action
- storage-pot lid/towel/speaker arrangement changes while untouched
- separate knife and outer-packet floor spots overlap/merge/move without action

Chapter 1 after Strip 023:
- practical knife = one distinct `CLANG` floor spot
- empty spicy-seafood outer packet = separate nudged floor spot
These remain separate until their later pickups.

## Wall-Socket / Derived-Outlet Failure — BLOCKING

When unplugged:
- plug BODY removed from WALL socket
- appliance-side cord stays attached
- loose plug persists
- socket empty
- no cable pulling/appliance-side disconnect

If canonical WebP visibly establishes outlet, use it exactly.
If exact faceplate is not visible, derive only the smallest canon-compatible temporary Chapter 1 outlet detail inside existing room geometry. It never becomes permanent canon.

Reject if a later strip:
- moves outlet to another wall/height/orientation
- distorts/moves canonical wall/furniture to expose outlet
- treats generated outlet placement as authority over canonical WebPs
- silently re-plugs appliance

For Chapter 1, Strip 031 must visually prove active TV remains wall-unplugged while respecting canonical room geometry.

## Lighting-Containment Failure — BLOCKING

Supernatural accents remain contained to their scripted source.
Reject if:
- tiny fridge pixels light the room after candle-out
- Strip 022 blue candle core becomes a blue room wash, large aura, bloom, rim light, spotlight, or second functional light source
- blackout readability is achieved with invented powered/cinematic light

## Micro-Continuity Failure — BLOCKING

Camera cut cannot erase/reset story state. Reject adjacent slices when object/body/food/hand state changes without visible/legal cause.
Examples: noodle vanishes, chopsticks/pot disappear, seated→standing jump, chair resets, knife/packet spots move, cabinet opens early, wrist switches, tools return ambiguously.

## Narration / Technical-Label Failure — BLOCKING

Reject if:
- one identical narration box forced across unrelated situations
- captions repeatedly default to small top-left technical-tag look
- narration mimics device UI/handwriting/production labels
- any `V01`, V/P/strip/beat/panel/scene/shot label appears
- legitimate time caption resembles production metadata

## Repository Image Format Rule

Reference prompts may generate PNG first locally. After approval, manually convert accepted PNG to WebP and commit/store WebP. Production Markdown references exact WebP. Intermediate/deleted PNG is not authority.

## Missing-Asset Rule — BLOCKING

Required WebP missing/stale/wrong-path/unapproved → not production-ready for that strip. Stop; no improvised substitute.

If rendered strip images do not exist, actual pixel-level style, identity fidelity, hand mechanics, provenance, topology, outlet accuracy, lettering, seams/dead-space remain unverified. Prompt quality cannot pass rendered gates.

## Completion Language

Use `PRODUCTION COMPLETE` only after all mandatory rendered/stitch/final-audit gates pass.

Accurate intermediate statuses include:
- `FOURTH FULL HARDENED PREPRODUCTION GATE PASS — READY TO RETEST STRIP GENERATION`
- `VISUAL QA FAILED — REPAIR / REGENERATE BEFORE NEXT STRIP`
- `VISUAL QA IN PROGRESS — NOT PRODUCTION COMPLETE`
- `BLOCKED — REQUIRED CANONICAL VISUAL AUTHORITY MISSING`

Do not reintroduce retired page-grid pipeline.
