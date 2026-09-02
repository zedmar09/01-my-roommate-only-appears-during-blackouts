# Manhwa Chapter 1 — Full Vertical Production

This is the active production package for Chapter 1.

Current prompt/reference status: **SEVENTH FULL HARDENED PREPRODUCTION GATE PASS — READY TO RETEST FROM STRIP 001 — NOT PRODUCTION COMPLETE.**

The current Strip 001–032 package has been clean-room re-audited seven times under `manhwa-2d-production-auditor`. The sixth PASS was deliberately not accepted as proof. After seventh repairs, the current Strip 001→032 prompts were read again before this status was assigned. Earlier problematic renders remain rejected.

## Chapter Shape

- one continuous reader-visible vertical chapter
- 146 internal read beats (`V01–V146`)
- 32 technical production strips (`001–032`)
- no reader-visible beat/strip/page numbering
- begins with Nari moving into Unit 2407
- ends with the visibly wall-unplugged TV displaying `NEW TENANT CONFIRMED` while Unit 2407 remains powered

Historical P001–P018 mapping is story shorthand only.

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

Reference prompts may generate PNG first locally. After approval, manually converted WebP is repository production authority.

## Production Authority

1. current user instruction
2. `chapter-01-continuous-scroll-plan.md`
3. `chapter-01-strip-manifest.md`
4. current `Production-Strips/strip-###-...md`
5. current approved character WebPs
6. approved environment/object WebPs
7. previous approved rendered strip for temporary state/seam only
8. canon-compatible derived micro-detail only

Previous strip and derived detail never override permanent canonical WebPs.

Always-binding global rules:
- `../../style-guide.md`
- `../../lettering-sfx-guide.md`
- `../../seam-continuity-protocol.md`
- `../../vertical-scroll-layout-guide.md`
- `../../generation-workflow.md`
- `../../production-readiness-gate.md`
- `../../seventh-hardening-visual-logic-addendum.md`

A strip may be stricter but never looser.

## Seventh-Pass Production Locks

All previous hardening remains binding. The seventh pass adds another mandatory layer:

### Camera Axis / Eyeline
- same uninterrupted conversation/action preserves world-space sides
- reverse shots may flip screen-left/right but may not silently exchange physical positions
- Nari/Mrs. Na/Hyun-woo/Seungjae must look toward the actual story-world speaker/device/object
- if the 180° axis is crossed, a neutral reorientation view must establish it first

### Physical Text Planes
- TV/fridge/tablet/phone/smart-lock text stays inside the actual screen plane
- binder/note/notebook text stays on the actual physical page plane
- text follows carrier perspective and cannot float as detached UI/narration in room space

### Reflection / Shadow False-Duplicate Ban
- no reflected duplicate Nari/Hyun-woo/Mrs. Na/Seungjae/unknown person unless explicitly scripted
- no shadow-person, reflected face/hand, or duplicate evidence object
- shadows must correspond to real current light sources
- after candle-out, candle shadows disappear; fridge pixels do not generate human shadows

### Grip / Finger Ergonomics
- critical grips use physically usable fingers/thumbs
- plug body, key/ring, knife handle, pen, chopsticks, phone, umbrella/bag handle, mask hardware, cabinet/door handle, packet/lid/tools cannot fuse with or pass through fingers
- knife is never held by blade; plug never by prongs/cable

### Worn Item / Strap Attachment
- scrunchie physically encircles SAME wrist
- headphones rest physically around Nari's neck/hoodie
- bag straps follow correct shoulder/body contour
- watch/earbuds physically occupy same wrist/ears
- Hyun-woo mask straps/hardware stay on real head/hair route
- hair/clothing/accessories cannot clip through each other

### Audio Source Direction
- speaker voice, cabinet chimes, `SLURP`, appliance sounds and SFX stay at the real story-world source
- reaction gaze/body direction must turn toward that source

### Weather / Glass Boundary
- rain remains outside after the building threshold is crossed
- glass may have restrained environmental sheen but no reflected human doubles

## Sixth-Pass Physical Mechanics Remain Binding

- orientation/hinge/handle/track cannot flip
- world-space scale and actual container/support fit remain stable
- 2D overlap is not contact
- cords/cloth/loose/falling objects obey gravity and no-clipping
- STORAGE POT and NOODLE POT remain distinct
- cabinet lid rests on a real referenced support plane
- Hyun-woo absence uses comparable space, not a crop that simply excludes him
- final hero composition preserves real room scale/depth

## Wall-Socket Rule — Absolute

`UNPLUGGED` means plug BODY removed from a WALL-MOUNTED socket while appliance-side cord remains attached.
Same cord, loose plug and empty socket persist until explicit re-plug.
Cord route remains physically continuous with believable gravity/slack and no clipping.

## Strict Flat 2D Human-Drawn Style — Absolute

Every canonical, strip, repair and stitched output must visibly comply with `../../style-guide.md`:
- strict flat 2D human-drawn Korean manhwa/webtoon
- clean line art
- flat colors
- restrained hard-edged cel shading only
- matte materials
- stable canonical anatomy/proportions and natural hands
- no photoreal/semi-photoreal, 3D/CGI, glossy/plastic/wet, painterly, airbrushed, cinematic, DOF, bloom, lens flare, excessive rim light, mirror-like reflection, or AI-polished over-rendering

Prompt wording alone does not pass this gate; rendered output must be visually inspected.

## Required-Asset Blocking Rule

Missing/stale/wrong-path/unapproved required WebP → STOP before strip generation. Never improvise a substitute.

Approved Chapter 1 character/environment/object WebPs are present. The remaining gate is sequential rendered Strip 001–032 generation and actual visual QA.

## Existing Approved Strip Rule

A previous strip becomes continuity authority only after it passes the **current seventh-pass visual QA**. Earlier rejected/pre-seventh attempts must not be attached merely because they exist.

Previous-strip temporary state can never override permanent canonical identity, geometry, orientation, scale, text-plane logic, reflection/shadow rules, or recurring object construction.

## No-Dead-Space Rule

Large vertical spacing must perform a real story function. No giant empty tails and no filler text/SFX.

## Audit Rule

After every correction, re-audit corrected scope and adjacent dependencies. After all corrections, run a fresh clean-room Strip 001→032 audit; never inherit earlier PASS labels without checking current files.

## Current Next Action

1. generate a brand-new Strip 001 using its current seventh-pass prompt + exact approved WebPs
2. deep-audit actual pixels against all current gates
3. reject/fix/regenerate until Strip 001 passes
4. only then attach newly APPROVED Strip 001 to Strip 002
5. continue sequentially through Strip 032
6. stitch and run a fresh final visual clean-room audit

`PRODUCTION COMPLETE` is forbidden until every rendered/stitch/final mandatory gate passes.
