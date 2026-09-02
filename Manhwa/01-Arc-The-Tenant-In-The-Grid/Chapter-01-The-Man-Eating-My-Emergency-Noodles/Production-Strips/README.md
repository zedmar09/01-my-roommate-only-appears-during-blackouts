# Chapter 1 Production Strips

This folder contains **32 technical image-generation prompts** for one continuous Manhwa Chapter 1.

Historical V/P/strip labels are production-only and must never appear in reader-facing artwork.

## Current Status

**DETERMINISTIC PRODUCTION-DIRECTOR PROMPT MIGRATION COMPLETE — STRIP 001–032 READY FOR SEQUENTIAL RENDER / VISUAL QA — NOT PRODUCTION COMPLETE**

Strip 001 is the reference implementation for the current generation-facing format. Strips 002–032 have now been migrated to the same production-director standard while preserving each strip's locked story mechanics and continuity requirements.

This is a **prompt-format / production-direction migration**, not another numbered hardening audit.

## Current Canonical Authority — Absolute

Use this order:

1. current user instruction
2. current strip story/script
3. current approved character WebP(s)
4. current approved environment WebP(s)
5. current approved object WebP(s)
6. current deterministic strip prompt
7. immediately previous **APPROVED rendered strip** for temporary continuity only
8. global physical/visual production rules
9. historical hardening/audit wording

If any historical text conflicts with a current approved character WebP, **the current WebP wins**.

### Current Nari Canon

Use `nari-canonical-flat2d.webp` as the permanent Nari authority.

Current Nari is the approved warm game-developer design: exactly 30, long layered very-dark warm-brown hair, current thin practical glasses state, current warm-cream/oatmeal hoodie / charcoal developer-casual visual language, dark-charcoal cargo trousers, current shoes/accessories/bag state as established by the canonical WebP and current scene.

Never restore the retired Nari design:
- dark-plum/purple hair
- mouth beauty mark
- yellow scrunchie
- headphones-around-neck identity
- old dark graphic hoodie + cropped utility-jacket primary design

## Deterministic Strip Standard

Each migrated prompt now uses the Strip-001 production-director approach as appropriate:

- **filename-only attachment sets**
- exact current canonical WebPs
- immediately previous APPROVED rendered strip
- explicit start state
- allowed changes
- exact end/seam state
- world-scale / proportion rules
- per-vertical camera and composition direction
- visible environment anchors
- character pose/facing/performance
- exact object count/state/orientation
- real physical action sequence
- physical text/audio-source ownership
- vertical height/rhythm guidance
- local reject conditions

A detailed story beat may not be replaced with a generic illustration.

## Sequential Production Rule — Absolute

Production order is:

`Strip 001 → visual QA → APPROVE → Strip 002 → visual QA → APPROVE → ... → Strip 032`

Only an actual passing rendered image becomes `APPROVED Strip N` and may be attached as temporary continuity authority for the next strip.

Do not reuse a rejected, obsolete, pre-migration, or merely existing image as previous-strip authority.

## Unit 2407 Continuity — Absolute

Permanent environment references control the apartment:
- TV/living = established LEFT
- dining = CENTER
- exactly TWO burgundy chairs
- kitchen/refrigerator = established RIGHT
- hallway/bedrooms behind
- corner windows fixed
- desk fixed
- entry/key tray fixed
- speaker-storage lower cabinet fixed

Do not mirror the room.
Do not invent a new kitchen island/counter for a close-up.
Do not create duplicate refrigerators or furniture.
Camera changes the **view**, not the room.

## Real-World Scale / Proportion — Absolute

Character ↔ object ↔ environment scale stays believable and stable.

- close-up magnification never changes world-space size
- Nari remains normal adult scale relative to doors/furniture/counters
- Hyun-woo remains clearly taller/broader than Nari when both stand on the same floor plane
- Seungjae remains leaner/less imposing than Hyun-woo
- speaker remains a small countertop object
- pots/tools/key/phone/tablet/notebook/TV/refrigerator retain stable real-world scale
- Unit 2407 remains a believable modern two-bedroom apartment, not a penthouse, mansion, luxury loft, hotel suite, or miniature set

## Wall-Socket Rule — Absolute

`UNPLUGGED` means the **plug BODY is removed from the WALL-MOUNTED socket** while the appliance-side cord remains attached.

When proof is required:
- real wall context
- wall faceplate/socket
- hand gripping plug body
- plug physically clears socket
- same appliance-side cord remains attached
- same continuous cord leads to same loose plug
- wall socket visibly empty
- gravity/slack/no-clipping remain believable

Never use appliance-side cable removal as unplug proof.

## Strict Style — Absolute

**STRICT FLAT 2D HUMAN-DRAWN KOREAN MANHWA / WEBTOON.**

Required:
- clean intentional line art
- flat matte colors
- restrained hard-edged cel shading
- stable adult anatomy
- natural hands
- matte materials
- ordinary manhwa perspective
- mobile readability

Reject photoreal/semi-photoreal, 3D/CGI/game render, painterly/airbrushed, glossy/wet/plastic, beauty-ad shine, cinematic grading/DOF/bloom/lens flare/volumetric light/excessive rim light/hypertexture/AI-polished over-rendering.

## Completion Rule

The migration does **not** certify artwork.

`PRODUCTION COMPLETE` is forbidden until:
- all 32 current rendered strips pass actual visual QA
- all seams/stitches pass
- mobile readability passes
- final stitched clean-room visual audit has zero unresolved mandatory defects
