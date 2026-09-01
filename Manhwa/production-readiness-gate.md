# Manhwa Production Readiness Gate

The Manhwa pipeline is the permanent production format.

A chapter is **PRODUCTION COMPLETE** only when every mandatory gate below passes in the current post-correction state. Earlier PASS labels do not substitute for a fresh final audit.

## Mandatory Gates

1. full vertical beat plan and strip manifest locked
2. story logic, event order, timeline, and causality coherent
3. exact reader-facing dialogue/narration/thought/device/note text and source ownership locked
4. SFX verified as physical SOURCE → ACTION → SOUND → TIMING → PLACEMENT → STATE CHANGE → NEXT-BEAT CONSEQUENCE
5. required character canonical WebPs exist, are current, and are approved
6. all recurring environment canonical WebP packs required by chapter exist and are approved
7. all plot-critical recurring object canonical/state WebP packs required by chapter exist and are approved
8. every strip prompt explicitly treats attached WebPs as binding identity/geometry/object authority rather than inspiration
9. every strip has a coherent START STATE → ALLOWED CHANGES → END STATE ledger; anything not explicitly changed persists
10. every meaningful result follows real-world CAUSE → VISIBLE ACTION → RESULT; important actions are not hidden by camera cuts/SFX
11. adjacent vertical slices preserve micro-continuity for hands, held objects, food/noodles, chopsticks, pots/bowls, packet counts, cords/plugs/sockets, chair state, knife/sheath, candle, key/manual/note/phone/tablet/bag, cabinet/stockpot/lid/towels, notebook/pen, body positions, eyelines, and power/device state
12. corded-appliance unplugging is physically correct: plug removed from WALL-MOUNTED socket/outlet, appliance-side cord still attached, loose wall plug retained, wall socket empty, unplugged state persists until explicit re-plug
13. character ↔ environment interactions are physically believable: feet support, seated-chair alignment, reachability, hinge/swing, collision clearance, walking routes, scale, eyelines, and reverse angles all match attached canon
14. narration design follows scenario/event function rather than one repeated caption template; text types remain distinguishable
15. NO reader-visible production metadata appears anywhere: no `V-*`, P-number, strip ID, beat/panel/scene/shot labels, QA/layout headers, especially top-left vertical labels
16. every technical strip is generated and approved sequentially
17. strict **flat 2D human-drawn** style passes actual visual inspection: flat colors, restrained simple cel shading, matte materials, clean line art, stable anatomy, natural hands, no photoreal/3D/glossy/cinematic/painterly/airbrushed/over-rendered drift
18. blackout/restored-power/device/candle/rain lighting states remain physically and stylistically coherent without cinematic glow or unexplained light
19. helpful/hostile signatures and object-specific effects remain correct
20. black read-slice grammar and side-by-side diagonal divider rules remain correct
21. no huge purposeless bottom whitespace or double-gap seams remain
22. mobile lettering remains readable and does not cover continuity-critical evidence such as hands, food paths, plugs/sockets, impacts, or device clues
23. stitched chapter has no visible seams, duplicated transition content, micro-state resets, geometry jumps, or unplanned power/lighting jumps
24. final chapter ending matches locked script exactly
25. a fresh clean-room audit from beginning finds zero unresolved BLOCKER, MAJOR, correction-requiring MINOR, or unexplained WARNING findings

## Attached-Reference Failure — BLOCKING

If generated art modifies a permanent attached reference-controlled feature rather than merely changing a scripted temporary state, reject the strip even if the image is otherwise attractive.

Examples:
- apartment mirrored/moved fixtures
- character face/hair/build recast
- TV/speaker/refrigerator object redesign
- cord/wall-socket logic changed
- key/manual/mask/chair/pot identity altered

Recompose/regenerate the shot. Do not accept canonical drift as a production shortcut.

## Wall-Socket Failure — BLOCKING

When a story appliance is unplugged from power, reject if:
- cable is detached from appliance body instead of wall socket
- wall socket is missing/relocated/occupied when it should be empty
- loose plug disappears
- cord changes sides/count/routing without cause
- appliance silently becomes plugged again later

For Chapter 1, the Strip 006 TV unplug state persists through Strip 007 and through final Strips 031–032 because no re-plug action occurs.

## Micro-Continuity Failure — BLOCKING

A camera cut cannot erase or reset a story state. Reject adjacent slices when an object/body/food state changes with no visible or strongly inferable cause.

Examples:
- noodle strand/food visible then gone without bite/lowering
- chopsticks/bowl/pot vanish in dialogue close-up
- object jumps hand→surface/floor without placement/drop
- seated person becomes standing with no body/chair mechanics
- chair resets after being pushed
- knife changes floor spot
- cabinet opens before approach/handle action
- phone/key/notebook teleports

## Narration / Technical-Label Failure — BLOCKING

Reject if:
- one identical narration-box design is forced across unrelated situations in a way that ignores story function
- narration mimics device UI, physical handwriting, or production labels
- any `V01`, `V-01`, V/P/strip/beat/panel/scene/shot label appears in reader art
- a time caption is styled so it reads like production metadata rather than story narration

## Repository Image Format Rule

Image-generation prompts may request PNG as first local generation output. That is allowed.

After reference image is visually approved:
- manually convert accepted PNG to WebP
- commit/store approved `.webp`
- production Markdown references exact repository WebP path

Committed WebP is production attachment authority. Deleted/intermediate PNG is not.

## Missing-Asset Rule — BLOCKING

If a strip lists a required canonical WebP that is missing, stale, wrong-path, or unapproved, chapter is **not production-ready for that strip**. Stop before generation; never improvise substitute or treat Markdown prompt as visual canonical.

If rendered strip images do not yet exist, actual strip style, identity fidelity, micro-continuity, lettering, dead-space, seam, and final stitched gates are not yet verifiable. Prompt quality cannot pass rendered-output gates.

## Completion Language

Use `PRODUCTION COMPLETE` only when all mandatory gates pass after final clean-room audit.

Accurate intermediate statuses include:
- `FULL HARDENED PREPRODUCTION GATE PASS — READY TO RETEST STRIP GENERATION`
- `VISUAL QA FAILED — REPAIR / REGENERATE BEFORE NEXT STRIP`
- `VISUAL QA IN PROGRESS — NOT PRODUCTION COMPLETE`
- `BLOCKED — REQUIRED CANONICAL VISUAL AUTHORITY MISSING`

Do not reintroduce retired traditional manga/page-grid production pipeline.
