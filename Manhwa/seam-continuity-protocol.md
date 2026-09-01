# Seam Continuity Protocol

## Purpose

Technical image boundaries must disappear after stitching. The reader should never be able to identify where `strip-###` ends.

## Canonical Anchor Rule

Before evaluating a seam, compare both strips against relevant approved character/environment/core-object WebPs.

A seam is invalid even if Strip N visually matches Strip N+1 when both have drifted away from canonical identity/room/object design. Do not preserve a mistake merely because it is consistent across two generated strips.

For apartment seams verify fixed landmarks such as walls, doors, windows, table, fridge, TV zone, cabinet, desk, hallway axis, wall sockets/outlets, and relevant object bodies against canonical reference pack.

## Approved Previous-Strip Rule — Absolute

For every strip after 001, attach the immediately previous **CURRENTLY APPROVED** manhwa strip plus relevant canonical environment/object references.

A rejected, superseded, or pre-hardening render is NOT continuity authority and must not be attached as “approved previous strip.”

For the current Chapter 1 retest, generation restarts at Strip 001 under the deeply hardened prompts. Only a new Strip N that passes current hardening QA may become temporary continuity authority for Strip N+1.

## Seam Types

### G — Gutter Seam
Use only when natural quiet transition exists. Gutter must be compact or meaningfully paced; it is not permission for unused blank tail.

### A — Artwork-Continuation Seam
Lower portion of Strip N and upper portion of Strip N+1 depict same continuing environment/composition/action.

### E — Effect/Atmosphere Seam
Use for rain, darkness, glitch fragments, city lights, candle smoke, hostile pixels, or other continuing fields.

## Start/End State Handoff — Absolute

Before generating Strip N+1, explicitly compare Strip N's approved END STATE to Strip N+1's hardened START STATE.

Every state not changed by the seam must match exactly:
- character position/facing/distance/seated-standing state
- hand occupancy
- wardrobe/hair/accessories
- food/noodle amount and path
- pot/bowl/chopsticks/packet/wrapper state
- key/manual/note/pen/notebook/phone/tablet/bag state
- knife/sheath/floor-impact state
- cord/plug/WALL-socket connection state
- chair pushed/occupied state
- candle/holder/flame state
- cabinet/stockpot/lid/towels/speaker state
- device display text/effect state
- power/lighting state
- canonical environment geometry

A strip boundary is not a time cut unless script explicitly defines one. Technical file boundaries do not reset objects.

## Wall-Socket Seam Rule — Absolute

If Strip N ends with a corded appliance unplugged from a wall socket, Strip N+1 inherits:
- appliance-side cord still attached to appliance body
- same cord route family
- same loose wall-end plug
- same wall-mounted socket location
- socket remains empty

Do not silently convert this into an appliance-side disconnect or re-plug at the next strip.

Chapter 1 critical handoffs:
- Strip 006→007: TV remains unplugged FROM WALL
- that same TV remains physically unplugged through powered aftermath and final Strip 031→032 activation
- stored speaker remains unplugged with attached cord/loose plug through storage and borrowed-current scenes

## Food / Small-Prop Seam Rule — Absolute

Food and small props do not disappear at strip boundaries.

Examples:
- visible noodles/chopsticks/pot at Strip 017 end must carry into Strip 018 until visible mask/eating action changes them
- dropped knife floor position Strip 023 persists through 024–027 until Strip 028 pickup
- Nari's clean chopsticks/food state from Strip 029 carries into 030/031 if still physically present
- notebook + pen Strip 030→031→032 remain same objects

Occlusion is not disappearance.

## Character ↔ Environment Seam Rule — Absolute

For A/E and continuous G seams preserve:
- camera axis/perspective when intended to continue
- character scale and floor support
- actual chair/body relationship
- reachability and eyeline
- object scale
- wall/floor/background alignment
- door/cabinet hinge state
- power/lighting baseline

Do not mirror room or move fixed architecture at seam to make next composition easier.

## No-Dead-Space Seam Rule — Absolute

Never create seam by simply leaving huge empty lower area.

If story beat needs pause, pause must read intentionally through existing narration, scripted SFX, reaction, canonical environmental continuation, atmosphere, or reveal timing.

If no such purpose, continue artwork closer to technical edge and use only small buffer. Never solve blank space by inventing narration/dialogue/SFX.

Reject double-gap join where Strip N has excessive empty bottom and Strip N+1 excessive empty top.

## Overlap Strategy

When practical, repeat a small lower-edge continuity zone from Strip N at top of Strip N+1 and crop duplicate during stitching. Recommended concept: roughly 10–20% of transition area, never reader-visible repeated panel.

Do not repeat dialogue/SFX inside overlap. Any repeated objects/body portions must match exactly; overlap is not permission for a second duplicate story-world object.

## Text Seam Rule — Absolute

Never split across seam: speech balloon, narration box, handwritten message, device text, critical SFX word, or face if mismatch would be obvious.

Background, body below face, furniture, rain, dark room, city field, or tall effect may continue when reliable.

Never introduce a V/P/strip/beat/panel/scene production label at the start of a new file. Technical seam must remain invisible to reader.

## Seam QA — Full Hardened Checklist

Before approval compare bottom of Strip N to top of Strip N+1:
- width identical
- exact canonical environment landmarks correct
- character identity/hair/wardrobe/accessories unchanged unless scripted
- character position/scale/pose handoff physically continuous
- hand occupancy consistent
- food/noodle/chopstick/pot state consistent
- recurring object body/state canonical
- cord/plug/wall-socket state identical unless explicit action changes it
- key/manual/phone/notebook/knife/candle/chair/cabinet small states persist
- no accidental horizontal white/black technical line
- no duplicated/missing text
- no missing floor/wall segment
- no changed appliance geometry
- no power/lighting jump unless scripted
- no pose/object teleport
- no narration-style reset that looks like a technical new-file header
- no `V-*` or other production metadata
- no excessive dead bottom/top gap

If join is obvious at normal phone-scroll speed, violates hardened state handoff, or conflicts with canonical reference, reject/regenerate newer strip.
