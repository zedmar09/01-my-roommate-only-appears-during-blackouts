# Manhwa Chapter 1 — Full Vertical Production

This is the active production package for Chapter 1.

Current prompt/reference status: **NINTH FULL HARDENED PREPRODUCTION GATE PASS — READY TO RETEST FROM STRIP 001 — NOT PRODUCTION COMPLETE.**

The current Strip 001–032 package has been clean-room re-audited nine times under `manhwa-2d-production-auditor`. The eighth PASS was deliberately not accepted as proof. The ninth pass found a new character-topology/identity failure class, repaired it, then re-read the current post-repair Strip 001→032 package again before this status was assigned. Earlier problematic renders remain rejected.

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

## Ninth-Pass Production Locks

All previous hardening remains binding. The ninth pass adds another mandatory character-identity layer.

### Whole-Body Anatomical Topology
- one coherent human body per character
- no extra/missing/duplicated arms, hands, legs, feet, ears, fingers or detached body parts
- close-up limbs must physically connect to the same character body shown in adjacent views
- impossible elbow/knee/wrist/ankle/shoulder/hip topology is blocking

### Limb Ownership / Anatomical Side
- a close-up hand/wrist/foot/arm/leg remains the SAME character and SAME physical side
- reverse shots may flip screen-left/right but may not switch anatomical ownership
- sleeve/glove/tattoo/scrunchie/body cues must remain compatible with ownership when continuity depends on them

### Permanent Character Landmarks
- **Nari:** exactly one beauty mark beside the anatomical LEFT corner of her mouth; long dark-plum mid-back hair remains stable
- **Hyun-woo:** same anatomical tattoo-map relationships, same matte-black technical mask construction, same long low-tied black hair
- **Mrs. Na:** same jade earrings, same analog-watch wrist, same dark gloves unless explicitly removed
- **Seungjae:** exactly age 30, same medium-brown hair part/silhouette, same watch wrist and earbud-ear identities

### Face / Age / Build / Hair
Expressions, darkness, close-ups and reverse shots cannot recast a character. Nari cannot revert to short hair; Hyun-woo cannot slim/shorten hair/change mask/tattoos; Mrs. Na cannot become young/glamorous; Seungjae cannot age into a paternal/executive/middle-aged man.

### Wardrobe / Local Color / Material
Within a continuous scene, wardrobe construction and signature local colors remain stable. Lighting may change value, not identity hue/material. Character rendering remains flat matte—no glossy skin/hair/mask/jewelry close-up or neon tattoo drift.

### Clothing / Body Occlusion
Sleeves, trousers, coat, hoodie, hair, headphones, bags and straps must attach to one continuous body. Occlusion cannot hide an extra/missing limb or impossible body connection.

### Speaking / Listening / Mouth State
Visible acting must agree with source ownership. Listeners cannot mouth another character's line. Narration, internal thought, device text and speaker audio do not become visible human speech. Masked Hyun-woo's lower face is not exposed merely to show dialogue.

## Ninth Local Strip Rewrites

The ninth pass required deterministic local rewrites to **12 strips**:
- **001** — first-image Nari identity/body topology, anatomical-left beauty mark, box-support vs smart-lock hand ownership, narration/audio mouth-state
- **002** — Mrs. Na dark gloves/watch/jade earrings/body ownership during binder/key-ring/key handling; Nari landmark lock
- **006** — Nari unplugging-hand ownership connected to same body, beauty mark/hair identity, no generic detached wall-plug hand
- **012–013** — Seungjae exactly age 30, youthful face/hair/outfit, watch/earbud/umbrella/phone limb ownership and speaking-state logic
- **014** — Nari identity/body topology/local colors preserved through blackout rather than redrawn by darkness
- **017–018** — Hyun-woo broad build, anatomical tattoo map, mask hardware, long low-tied hair and same-body chopstick→mask hand continuity
- **023–024** — Nari FREE HAND/KNIFE HAND/feet ownership and Hyun-woo connected catching-arm/tattoo-side ownership through wrist catch/release
- **031–032** — Nari writing/reaction anatomy, no third writing/stabilizing hand, beauty-mark/hair identity, device/written text not mouthed

The other **20 strips** were re-read under the ninth global rules and required no additional deterministic local rewrite.

## Previous Eighth-Pass Presentation Gates Remain Binding

- ordinary non-fisheye perspective
- mobile-readable physical proof
- crop/gutter/divider safe margins
- stable lighting-source/shadow direction
- exact top-to-bottom causal reading order
- close-up ownership context
- readable exact in-world text

## Wall-Socket Rule — Absolute

`UNPLUGGED` means plug BODY removed from a **WALL-MOUNTED socket** while appliance-side cord remains attached.
The wall/faceplate/socket context must be visible enough to prove this is a wall outlet, not an appliance-side port. Same cord, loose plug and empty socket persist until explicit re-plug. Cord remains physically continuous with believable gravity/slack and no clipping.

## Strict Flat 2D Human-Drawn Style — Absolute

Every canonical, strip, repair and stitched output must visibly comply with `../../style-guide.md`: strict flat 2D human-drawn Korean manhwa/webtoon, clean line art, flat colors, restrained hard-edged cel shading, matte materials, stable character topology/identity and natural hands.
Reject photoreal/3D/glossy/cinematic/painterly/airbrushed/bloom/DOF/over-rendered output.

Prompt wording alone does not pass this gate; rendered output must be visually inspected.

## Required-Asset Blocking Rule

Missing/stale/wrong-path/unapproved required WebP → STOP before strip generation. Never improvise a substitute.

## Existing Approved Strip Rule

A previous rendered strip becomes continuity authority only after it passes the **current ninth-pass visual QA**. Earlier rejected/pre-ninth attempts must not be attached merely because they exist.

## Audit Rule

After every correction, re-audit corrected scope and adjacent dependencies. After all corrections, run a fresh clean-room Strip 001→032 audit; never inherit earlier PASS labels without checking current files.

## Current Next Action

1. generate a brand-new Strip 001 using its current ninth-pass prompt + exact approved WebPs
2. deep-audit actual pixels against all current gates
3. reject/fix/regenerate until Strip 001 passes
4. only then attach newly APPROVED Strip 001 to Strip 002
5. continue sequentially through Strip 032
6. stitch and run a fresh final visual clean-room audit

`PRODUCTION COMPLETE` is forbidden until every rendered/stitch/final mandatory gate passes.
