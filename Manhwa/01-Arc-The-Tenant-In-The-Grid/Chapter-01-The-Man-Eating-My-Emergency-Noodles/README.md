# Manhwa Chapter 1 — Full Vertical Production

This is the active production package for Chapter 1.

Current prompt/reference status: **EIGHTH FULL HARDENED PREPRODUCTION GATE PASS — READY TO RETEST FROM STRIP 001 — NOT PRODUCTION COMPLETE.**

The current Strip 001–032 package has been clean-room re-audited eight times under `manhwa-2d-production-auditor`. The seventh PASS was deliberately not accepted as proof. After eighth repairs, every current Strip 001→032 prompt was read again from the beginning before this status was assigned. Earlier problematic renders remain rejected.

## Chapter Shape

- one continuous reader-visible vertical chapter
- 146 internal read beats (`V01–V146`)
- 32 technical production strips (`001–032`)
- no reader-visible beat/strip/page numbering
- begins with Nari moving into Unit 2407
- ends with the wall-unplugged TV displaying `NEW TENANT CONFIRMED` while Unit 2407 remains powered

## Approved Reusable Visual Authorities

### Character WebPs
- `Character-References/nari-canonical-flat2d.webp`
- `Character-References/hyunwoo-canonical-flat2d.webp`
- `Character-References/mrs-na-canonical-flat2d.webp`
- `Character-References/seungjae-canonical-flat2d.webp`

### Environment WebP packs
- `../../Environment-References/Unit-2407/`
- `../../Environment-References/Building-Shared-Areas/`

### Object WebPs
- `../../Object-References/smart-speaker-canonical-reference.webp`
- `../../Object-References/tv-canonical-reference.webp`
- `../../Object-References/refrigerator-canonical-reference.webp`
- `../../Object-References/electrical-operation-guide-canonical-reference.webp`
- `../../Object-References/brass-backup-key-canonical-reference.webp`

Reference prompts may generate PNG first locally. After approval, the manually converted WebP is repository production authority.

## Production Authority

1. current user instruction
2. `chapter-01-continuous-scroll-plan.md`
3. `chapter-01-strip-manifest.md`
4. current `Production-Strips/strip-###-...md`
5. approved character WebPs
6. approved environment/object WebPs
7. current global hardening rules/addenda
8. previous APPROVED rendered strip for temporary state/seam only
9. canon-compatible derived micro-detail only

Previous strip and derived detail never override permanent canonical WebPs.

Always binding:
- `../../style-guide.md`
- `../../lettering-sfx-guide.md`
- `../../seam-continuity-protocol.md`
- `../../vertical-scroll-layout-guide.md`
- `../../generation-workflow.md`
- `../../production-readiness-gate.md`
- `../../seventh-hardening-visual-logic-addendum.md`
- `../../eighth-hardening-presentation-integrity-addendum.md`

## Eighth-Pass Production Locks

All previous hardening remains binding. The eighth pass adds a presentation-integrity layer:

### Perspective / Lens
- ordinary manhwa perspective only
- no fisheye/ultra-wide/forced-perspective warping of canonical architecture or body/object proportions
- dramatic framing cannot change world-space geometry

### Mobile-Scale Proof
Continuity-critical evidence must be understandable at normal mobile size, not merely technically present. This includes wall-socket proof, key transfer, Section16→18 page proof, tool return, food path, foot/packet contact, chair mechanics, mask hardware, knife fall/impact, wrist contact, cabinet reveal, handwriting and the final TV message.

### Crop / Gutter / Divider Safety
Decisive contact and enough context must remain safely inside frame. Crop edges, black gutters, diagonal dividers and technical seams may not amputate a critical hand, foot, plug/socket, cord, knife, packet, chair leg, mask/wrist contact, page edge/spine, cabinet hinge, notebook or exact text.

### Lighting / Shadow Direction
Within one unchanged lighting state, the source direction remains coherent. Candle-derived light ends after `PFF`; fridge/TV/speaker pixels are not room lights; restored powered lighting remains one stable baseline after return; one flicker returns to that baseline.

### Top-to-Bottom Reader Order
Action/dialogue/SFX/device/narration layout must preserve the exact scripted causal order. A result or SFX cannot visually read before its physical cause.

### Limb/Object Ownership
Close-ups keep enough context to prove the hand/foot/plug/knife/page belongs to the same physical body/object and the same anatomical side/route.

### Readable In-World Text
Story-critical exact device/page/note/notebook wording must be legible at intended mobile scale and remain on the actual carrier plane. Use SAME-OBJECT details rather than enlarging the story-world object.

## Eighth Local Strip Rewrites

The eighth pass required deterministic local presentation rewrites to:
- **001** — smart-lock/door/box mobile proof, ordinary perspective, causal SFX order
- **002** — door/binder/key crop-safe proof and V11 reading order
- **004** — key/door proof, mobile-readable `19°C`, morning lighting/order
- **006** — wall-socket proof must clearly show WALL + faceplate + empty socket + plug-body grip + attached appliance cord at mobile size
- **010** — mobile-readable physical Section16→page turn→Section18 proof
- **019** — lower-body/STEP FOOT/packet contact ownership and safe framing
- **020** — mobile-readable seated→chair push→stand mechanics and candle-shadow consistency
- **023** — complete `PFF → KIIIIII → knife release → fall → CLANG → wrist catch → WARM` order, crop safety and post-candle lighting transition
- **025** — mobile-readable comparable Hyun-woo presence→absence proof and blackout→powered lighting transition
- **028** — mobile-readable phone→cabinet→lid→towel→speaker/cord/plug→knife sequence
- **031** — mobile-readable handwriting/pen release + real wall-socket proof before/with TV activation
- **032** — exact final message mobile-readable on TV plane, distortion-free hero framing, final reveal order

The other **20 strips** were re-read under the eighth global rules and did not require a new deterministic local rewrite.

## Wall-Socket Rule — Absolute

`UNPLUGGED` means plug BODY removed from a **WALL-MOUNTED socket** while appliance-side cord remains attached.
The wall/faceplate/socket context must be visible enough to prove this is a wall outlet, not an appliance-side port. Same cord, loose plug and empty socket persist until explicit re-plug. Cord remains physically continuous with believable gravity/slack and no clipping.

## Strict Flat 2D Human-Drawn Style — Absolute

Every canonical, strip, repair and stitched output must visibly comply with `../../style-guide.md`: strict flat 2D human-drawn Korean manhwa/webtoon, clean line art, flat colors, restrained hard-edged cel shading, matte materials, stable anatomy and natural hands. Reject photoreal/3D/glossy/cinematic/painterly/airbrushed/bloom/DOF/over-rendered output.

Prompt wording alone does not pass this gate; rendered output must be visually inspected.

## Required-Asset Blocking Rule

Missing/stale/wrong-path/unapproved required WebP → STOP before strip generation. Never improvise a substitute.

## Existing Approved Strip Rule

A previous rendered strip becomes continuity authority only after it passes the **current eighth-pass visual QA**. Earlier rejected/pre-eighth attempts must not be attached merely because they exist.

## Audit Rule

After every correction, re-audit corrected scope and adjacent dependencies. After all corrections, run a fresh clean-room Strip 001→032 audit; never inherit earlier PASS labels without checking current files.

## Current Next Action

1. generate a brand-new Strip 001 using its current eighth-pass prompt + exact approved WebPs
2. deep-audit actual pixels against all current gates
3. reject/fix/regenerate until Strip 001 passes
4. only then attach newly APPROVED Strip 001 to Strip 002
5. continue sequentially through Strip 032
6. stitch and run a fresh final visual clean-room audit

`PRODUCTION COMPLETE` is forbidden until every rendered/stitch/final mandatory gate passes.
