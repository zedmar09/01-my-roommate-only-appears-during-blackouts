# Manhwa Chapter 1 — Full Vertical Production

This is the active production package for Chapter 1.

Current prompt/reference status: **SIXTH FULL HARDENED PREPRODUCTION GATE PASS — READY TO RETEST FROM STRIP 001 — NOT PRODUCTION COMPLETE.**

The current Strip 001–032 package has been clean-room re-audited six times under `manhwa-2d-production-auditor`. The fifth PASS was not accepted as proof; after sixth repairs the full current Strip 001→032 package was re-read again before the sixth status was assigned. Earlier problematic renders remain rejected.

## Chapter Shape

- one continuous reader-visible vertical chapter
- 146 internal read beats (`V01–V146`)
- 32 technical production strips (`001–032`)
- no reader-visible beat/strip/page numbering
- begins with Nari moving into Unit 2407
- ends with the visibly wall-unplugged TV displaying `NEW TENANT CONFIRMED` while Unit 2407 remains powered

Historical P001–P018 mapping is story shorthand only. There is no active page-grid dependency.

## Approved Reusable Visual Authorities

### Character WebPs
- `Character-References/nari-canonical-flat2d.webp`
- `Character-References/hyunwoo-canonical-flat2d.webp`
- `Character-References/mrs-na-canonical-flat2d.webp`
- `Character-References/seungjae-canonical-flat2d.webp`

### Environment WebP packs
- `../../Environment-References/Unit-2407/`
- `../../Environment-References/Building-Shared-Areas/`

Each strip must attach the exact `.webp` filenames listed in its own prompt.

### Object WebPs
- `../../Object-References/smart-speaker-canonical-reference.webp`
- `../../Object-References/tv-canonical-reference.webp`
- `../../Object-References/refrigerator-canonical-reference.webp`
- `../../Object-References/electrical-operation-guide-canonical-reference.webp`
- `../../Object-References/brass-backup-key-canonical-reference.webp`

Reference prompts may still generate PNG first locally. After approval the manually converted WebP is repository production authority.

## Production Authority

1. current user instruction
2. `chapter-01-continuous-scroll-plan.md`
3. `chapter-01-strip-manifest.md`
4. current `Production-Strips/strip-###-...md`
5. current approved character WebPs
6. approved environment/object WebPs
7. previous approved rendered strip for temporary state/seam continuity only
8. canon-compatible derived micro-detail for chapter continuity only

Previous strip and derived detail never override permanent canonical WebPs.

Always-binding global rules:
- `../../style-guide.md`
- `../../lettering-sfx-guide.md`
- `../../seam-continuity-protocol.md`
- `../../vertical-scroll-layout-guide.md`
- `../../generation-workflow.md`
- `../../production-readiness-gate.md`

A strip may be stricter but never looser.

## Sixth-Pass Production Locks

The current package blocks all earlier failure classes plus the following sixth-pass classes:

### Orientation / Mechanics
- front door hinge/handle/smart-lock side cannot flip
- cabinet hinge/handle/open direction cannot flip
- building entrance/elevator door mechanism cannot change
- binder spine/rings/page-turn direction cannot mirror
- knife blade/sheath-mouth axis cannot reverse
- pot handle/cloth side, chair front/back and appliance cord-origin side remain stable

### Stable World-Space Scale / Fit
- close-up magnification never changes story-world size
- speaker/towels/cord/lid must physically fit the real stockpot/cabinet
- flashlight/radio/sheathed knife must fit the real emergency tray
- notebook remains true A5-like footprint inside NOTEBOOK ZONE
- TV/table/chairs/pots/phones/tablets/keys/packets/candle retain stable scale

### Real Depth / Contact
- 2D overlap alone is not grip/contact
- seated bodies align actual chairs
- mask hardware physically travels
- wrist grip visibly wraps the wrist
- elevator/building entry crosses real thresholds
- Hyun-woo's protective block is true floor-plan order `refrigerator → Hyun-woo → Nari`

### Gravity / No Clipping
- loose plugs/cords have plausible slack/support
- cords cannot pass through stands/walls/cabinets/furniture/appliances
- towels/cloth cannot occupy the same solid volume as speaker/pot/lid/cabinet
- knife/chopsticks/packets follow unobstructed physical paths
- loose props rest on real support planes rather than hovering

### Same-Object / Anatomical / Worn State
Close-up/inset is the same physical object. KNIFE HAND, PHONE HAND, WRITING HAND, SCRUNCHIE WRIST, STEP FOOT, CANDLE FOOT, BAG SHOULDER, UMBRELLA HAND and PHONE POCKET remain same physical side until their scripted expiry. These labels never render.
Nari's blackout-night scrunchie stays on the same wrist and headphones remain around her neck through the ending because no removal is scripted.

### Real Evidence / Object Identity
- exact two-stick landing configuration persists 005→006
- STORAGE POT and NOODLE POT are two different pots from Strip029 onward
- cabinet lid after Strip028 rests on a real referenced support plane, never an invented shelf
- Hyun-woo absence is shown with comparable space, not merely a crop that excludes him
- `TUG` in Strip026 leaves the front door closed/latched
- final hero composition preserves room scale/depth rather than turning into a poster collage

## Wall-Socket Rule — Absolute

`UNPLUGGED` means plug BODY removed from a WALL-MOUNTED socket while the appliance-side cord remains attached.
The same cord, loose plug and empty socket persist until an explicit re-plug.
Cord route must remain physically continuous with believable gravity/slack and no clipping through geometry.

## Strict Flat 2D Human-Drawn Style — Absolute

Every Chapter 1 canonical, strip, repair and stitched output must visibly comply with `../../style-guide.md`:
- strict flat 2D human-drawn Korean manhwa/webtoon
- clean intentional line art
- flat colors
- restrained hard-edged cel shading only
- matte skin/hair/fabrics/materials/architecture/appliances/screens
- stable canonical anatomy/proportions and natural hands
- no photoreal/semi-photoreal, 3D/CGI/game-render, glossy/plastic/wet, painterly, airbrushed, cinematic, DOF, bloom, lens flare, excessive rim light, mirror-like reflection or over-rendered AI polish

Prompt wording alone does not pass this gate; rendered output must be visually inspected.

## Required-Asset Blocking Rule

Missing/stale/wrong-path/unapproved required WebP → STOP before strip generation. Never improvise a substitute.

The approved Chapter 1 character/environment/object WebPs are present. The remaining gate is sequential rendered Strip 001–032 production and actual visual QA.

## Existing Approved Strip Rule

A previous strip becomes continuity authority only after it passes the **current sixth-pass visual QA**. Earlier rejected/pre-sixth attempts must not be attached merely because they already exist.

Previous-strip temporary state can never override permanent canonical identity, geometry, orientation, scale or recurring object construction.

## No-Dead-Space Rule

Large vertical spacing must perform a real story function. No giant empty tails and no filler text/SFX.

## Audit Rule

After every correction, re-audit corrected scope and adjacent dependencies. After all corrections, run a fresh clean-room Strip 001→032 audit; never inherit earlier PASS labels without checking current files.

## Current Next Action

1. generate a brand-new Strip 001 using its current sixth-pass prompt + exact approved WebPs
2. deep-audit the actual pixels against all current gates
3. reject/fix/regenerate until Strip 001 passes
4. only then attach that newly APPROVED Strip 001 to Strip 002
5. continue sequentially through Strip 032
6. stitch and run a fresh final visual clean-room audit

`PRODUCTION COMPLETE` is forbidden until every rendered/stitch/final mandatory gate passes.
