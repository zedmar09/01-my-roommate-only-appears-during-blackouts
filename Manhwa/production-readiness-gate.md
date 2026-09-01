# Manhwa Production Readiness Gate

The Manhwa pipeline is the permanent production format.

A chapter is **PRODUCTION COMPLETE** only when every mandatory gate below passes in current post-correction state. Earlier PASS labels do not substitute for fresh final audit.

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
10. every strip has deterministic START → ALLOWED CHANGES → END state
11. meaningful result follows real-world cause → visible action → result
12. critical actions visibly prove mechanism/contact point
13. hand occupancy/body support is physically possible; no extra-hand prop handling
14. story-critical object provenance is continuous; no object appears at new location without visible/legal route
15. adjacent vertical slices preserve micro-continuity
16. conserved local **prop topology** preserves relative physical sides/order across reverse shots
17. wall unplugging removes plug BODY from WALL socket; appliance-side cord remains attached
18. wall outlets are canonical/frozen local environment landmarks and do not move/reorient across later strips
19. character↔environment interaction physically believable
20. narration design+placement follows scenario, not one repeated box/top-left tag
21. NO reader-visible production metadata (`V-*`, P/strip/beat/panel/scene/shot/QA/layout labels)
22. every technical strip generated/approved sequentially
23. strict flat 2D human-drawn style passes actual pixel inspection
24. power/light/candle/rain/device states physically coherent
25. helpful/hostile effect signatures correct
26. black read-slice + diagonal-divider grammar correct
27. no purposeless dead bottom/double-gap seams
28. mobile lettering readable and does not cover continuity-critical evidence
29. stitched chapter has no seams, duplicate transitions, topology resets, geometry jumps, power/light jumps
30. final ending matches locked script exactly
31. fresh final clean-room audit finds zero unresolved mandatory findings

## Attached-Reference Failure — BLOCKING

Reject if generated art modifies permanent attached reference-controlled feature rather than scripted temporary state.
Examples: mirrored apartment, recast character, redesigned TV/speaker/fridge, altered key/manual/mask, moved fixture/socket.
Recompose/regenerate; never accept canon drift for visual convenience.

## Previous-Strip Authority Failure — BLOCKING

Previous strip may control temporary pose, hand occupancy, food amount, pushed chair, open cabinet, current power/light, knife floor spot, seam composition.
It may not redefine permanent face/hair/proportions, architecture, fixed furniture/appliance, wall outlet landmark, recurring object construction.

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
- chopsticks appear without physical source

If framing cannot prove mechanism, change camera.

## Hand-Occupancy Failure — BLOCKING

Reject if characters require impossible extra hands or props float unsupported.
Examples:
- handbag + binder + key ring + detached key all gripped impossibly
- phone + umbrella + earbuds + watch simultaneously handheld
- open binder + phone + page turning with impossible fingers/hands
- bag/tablet support impossible

Use body/shoulder/forearm support, visible setting-down, pocketing, sequential checking, or hand transfer as physically required.

## Prop Provenance Failure — BLOCKING

A recurring/story-critical object must have a continuous source and route.
Reject if:
- empty packet appears in later strip without earlier establishment
- packet suddenly moves floor→table
- clean chopsticks appear from nowhere
- phone disappears at seam or reappears elsewhere
- lid/towels change location without handling
- pen vanishes when character turns
- key/knife/notebook jumps locations

Legal time/location cuts may change ordinary temporary clutter only when story does not require persistent state.

## Prop Topology Failure — BLOCKING

Reverse shots cannot swap physical story-world sides/order of conserved local arrangements.
Reject if:
- candle changes physical side of pot
- folded cloth moves to other pot handle
- used chopsticks move to another rest point without action
- packet/wrapper/table positions swap
- pushed chair shifts to another side
- knife impact point moves
- storage-pot lid/towel/speaker arrangement changes while supposedly untouched

Screen-left/right may reverse; story-world topology may not.

## Wall-Socket / Fixed-Outlet Failure — BLOCKING

When unplugged:
- plug BODY removed from WALL socket
- appliance-side cord stays attached
- loose plug persists
- socket empty
- no cable pulling/appliance-side disconnect

Outlet itself is environment landmark. Reject if later strip changes:
- physical wall
- height
- faceplate/socket orientation
- furniture/appliance relationship
- cord-route family
without canonical supersession/visible renovation (none in Chapter 1).

For Chapter 1, Strip006 TV outlet/state persists through Strip007 and final 031–032. Strip031 must visibly prove active TV remains wall-unplugged.

## Micro-Continuity Failure — BLOCKING

Camera cut cannot erase/reset story state. Reject adjacent slices when object/body/food/hand state changes without visible/legal cause.
Examples: noodle vanishes, chopsticks/pot disappear, seated→standing jump, chair resets, knife floor spot moves, cabinet opens early, wrist switches, tools return ambiguously.

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

Use `PRODUCTION COMPLETE` only after all mandatory rendered/stitch/final audit gates pass.

Accurate intermediate statuses include:
- `THIRD FULL HARDENED PREPRODUCTION GATE PASS — READY TO RETEST STRIP GENERATION`
- `VISUAL QA FAILED — REPAIR / REGENERATE BEFORE NEXT STRIP`
- `VISUAL QA IN PROGRESS — NOT PRODUCTION COMPLETE`
- `BLOCKED — REQUIRED CANONICAL VISUAL AUTHORITY MISSING`

Do not reintroduce retired page-grid pipeline.
