# Manhwa Chapter 1 — Full Vertical Production

This is the active production package for Chapter 1.

Current prompt/reference status: **TENTH / FINAL FULL HARDENED PREPRODUCTION GATE PASS — READY TO RETEST FROM STRIP 001 — NOT PRODUCTION COMPLETE.**

The current Strip 001–032 package has completed ten clean-room `manhwa-2d-production-auditor` hardening passes. The ninth PASS was deliberately not accepted as proof. The tenth/final pass added pose/performance/relative-scale continuity, repaired the high-risk performance anchors, then re-read the complete current Strip 001→032 package. No deterministic textual/reference defect remains. Earlier problematic renders remain rejected.

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
- `../../ninth-hardening-character-topology-identity-addendum.md`
- `../../tenth-hardening-pose-performance-continuity-addendum.md`

## Tenth / Final Production Locks

All prior hardening remains binding. The final pass additionally requires:

### Pose / Facing
- camera cuts do not reset standing/seated/crouched/walking/leaning/shielding state
- shoulder/hip/torso/feet direction stays story-world coherent
- head-only turns do not silently become full-body turns
- gestures persist until visibly released or changed

### Relative Height / Build
- Nari remains medium-height/slim
- Hyun-woo remains clearly taller/broader than Nari when both stand on the same floor plane
- Seungjae remains a lean-to-average same-generation peer, less broad/intimidating than Hyun-woo
- Mrs. Na keeps stable older-adult proportions
- camera framing never resizes characters for intimidation, romance, comedy or drama

### Emotion / Performance
- move-in = dry/practical/mildly amused
- early evidence = skeptical/analytical/increasingly uneasy
- Seungjae = ordinary social warmth/awkwardness → mild device concern, never sinister
- blackout = controlled alertness → guarded caution
- Hyun-woo interrogation = wary Nari + guarded/calm/dry Hyun-woo
- hostile fridge = focused protective urgency
- knife/wrist event = acute localized shock
- powered aftermath = shaken but functional/investigative
- final message = controlled dread, not screaming melodrama

### Clothing Layer / Hair Motion
- hood/jacket/coat/sleeve/bag/headphones/mask wear state cannot change at a reverse shot
- flexible hair/garment motion may sway but cannot redesign length, part, tie, silhouette or construction

### Seam Performance
Every strip boundary carries the last valid pose, body facing, gesture, relative scale, emotional intensity and clothing-layer state until a legal cut or visible first action changes it.

## Tenth Local Strip Rewrites

The final pass required local performance rewrites to **9 strips**:
- **005** — ordinary annoyance → short startle → wary/disbelieving freeze
- **009** — startled evidence discovery → controlled analytical testing
- **012** — grounded after-work social warmth; stable Nari/Seungjae relative scale; mild concern only after phone failure
- **016** — controlled listening → practical knife draw → slow guarded approach → tense teaser stop
- **017** — wary defensive Nari vs guarded/calm/dry Hyun-woo; stable relative scale
- **020** — fridge threat causes focused protective rise; standing reveals canonical height/build without camera enlargement
- **021** — protective crossing remains protective, not domineering/villainous/romantic; body-facing block preserved
- **025** — controlled dark conversation → functional light-shield reflex → stunned-but-functional absence reaction
- **032** — final controlled dread/stillness; no scream/collapse/new gesture/pose reset

The other **23 strips** were re-read under the tenth/final global gate and required no additional deterministic local rewrite.

## Wall-Socket Rule — Absolute

`UNPLUGGED` means plug BODY removed from a **WALL-MOUNTED socket** while appliance-side cord remains attached. The wall/faceplate/socket context must be readable enough to prove this is a wall outlet, not an appliance-side port. Same cord, loose plug and empty socket persist until explicit re-plug. Cord remains physically continuous with believable gravity/slack and no clipping.

## Strict Flat 2D Human-Drawn Style — Absolute

Every canonical, strip, repair and stitched output must visibly comply with `../../style-guide.md`: strict flat 2D human-drawn Korean manhwa/webtoon, clean line art, flat colors, restrained hard-edged cel shading, matte materials, stable character topology/identity/pose and natural hands.
Reject photoreal/3D/glossy/cinematic/painterly/airbrushed/bloom/DOF/over-rendered output.

Prompt wording alone does not pass this gate; rendered output must be visually inspected.

## Required-Asset Blocking Rule

Missing/stale/wrong-path/unapproved required WebP → STOP before strip generation. Never improvise a substitute.

## Existing Approved Strip Rule

A previous rendered strip becomes continuity authority only after it passes the **current tenth/final visual QA**. Earlier rejected/pre-tenth attempts must not be attached merely because they exist.

## Current Next Action

1. generate a brand-new Strip 001 using its current tenth/final prompt + exact approved WebPs
2. deep-audit actual pixels against all current gates
3. reject/fix/regenerate until Strip 001 passes
4. only then attach newly APPROVED Strip 001 to Strip 002
5. continue sequentially through Strip 032
6. stitch and run a fresh final visual clean-room audit

`PRODUCTION COMPLETE` is forbidden until every rendered/stitch/final mandatory gate passes.
