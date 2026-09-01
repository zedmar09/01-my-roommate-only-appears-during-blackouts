# Seam Continuity Protocol

## Purpose

Technical image boundaries must disappear after stitching. Reader should never identify where `strip-###` ends.

## Canonical Anchor Rule

Before seam evaluation compare both strips against relevant approved character/environment/core-object WebPs.

Seam is invalid even if Strip N visually matches N+1 when both drift from canonical identity/room/object design. Do not preserve a mistake because it is consistent.

For apartment seams verify walls, doors, windows, table, fridge, TV zone, cabinet, desk, hallway axis, fixed wall outlets, and recurring object bodies.

## Approved Previous-Strip Rule — Absolute

For every strip after 001 attach immediately previous **CURRENTLY APPROVED** strip + relevant canonicals.

Rejected/superseded/pre-hardening render is NOT continuity authority.

For current Chapter1 retest generation restarts Strip001 under third-pass prompts. Only new Strip N passing current QA becomes temporary authority for N+1.

## Seam Types

### G — Gutter Seam
Natural quiet transition only. Compact/meaningful, never unused tail.

### A — Artwork-Continuation Seam
Lower Strip N and upper N+1 depict same continuing environment/composition/action.

### E — Effect/Atmosphere Seam
Rain, darkness, glitch, city lights, candle smoke, hostile pixels, continuing fields.

## Start/End State Handoff — Absolute

Before N+1, compare approved END STATE of N to hardened START STATE of N+1.

Every unchanged state must match:
- character position/facing/feet/distance/seated-standing
- hand occupancy/body support
- wardrobe/hair/accessories
- food/noodle amount/path
- pot/bowl/chopsticks/packet/wrapper
- key/manual/note/pen/notebook/phone/tablet/bag
- knife/sheath/floor impact
- cord/plug/WALL-socket connection
- chair pushed/occupied state
- candle/holder/flame
- cabinet/stockpot/lid/towels/speaker
- device text/effect
- power/light
- canonical geometry

Strip boundary is not time cut unless script explicitly defines one.

## Prop Provenance Seam Rule — Absolute

A story-critical object cannot materialize at N+1.

At seam ask:
- where was object at N end?
- is it at exact same place/hand at N+1 start?
- if different, is there explicit legal time cut or visible route?

Reject seam if packet, phone, pen, chopsticks, key, knife, notebook, lid, towel, plug, or other continuity prop changes source/location with no cause.

Chapter1 examples:
- Strip012 dead phone must be pocketed before Strip013
- Strip017 empty outer noodle packet must already exist before Strip019 step
- Strip028 lid/towel/speaker open topology carries to Strip029/030
- Strip029 empty outer packet only reaches table after visible pickup
- Strip031 pen must be resting on notebook before Strip032

## Prop Topology Seam Rule — Absolute

Seam preserves relative physical relationships, not just object list.

Across N→N+1 compare:
- pot same trivet/location
- cloth same hot-handle side
- candle same physical table position
- used/clean chopsticks same rest points
- packet/wrapper same floor/table positions
- pushed chair same angle/location
- knife same impact spot
- stockpot lid/towels/speaker/cord same arrangement

Reverse shot can flip screen-left/right but cannot swap story-world sides/order.

## Fixed Wall-Outlet Seam Rule — Absolute

If outlet has been canonically/finally established, N+1 inherits:
- same story-world wall
- same height
- same faceplate/socket orientation
- same nearby furniture/appliance relation
- same cord-route family

Do not invent new outlet for next shot.

If Strip N ends appliance wall-unplugged, N+1 also inherits:
- appliance-side cord attached
- same loose wall plug
- same fixed wall socket
- socket empty

No silent appliance-side disconnect or replug.

Chapter1:
- 006→007 TV remains wall-unplugged at same outlet landmark
- that TV remains physically wall-unplugged through powered aftermath/final 031→032
- stored speaker remains unplugged with attached cord/loose plug through storage/borrowed-current scenes

## Food / Small-Prop Seam Rule — Absolute

Food/small props do not disappear at seam.

Examples:
- Strip017 pot/noodles/chopsticks/packet/wrapper carry into 018
- empty outer packet persists 017→018→019
- knife floor spot 023 persists through 024–027 until 028 pickup
- Pair A/Pair B + packet/wrapper/pot topology from 029 carries 030→031→032
- notebook + pen 030→031→032 remain same objects

Occlusion is not disappearance.

## Hand-Occupancy Seam Rule — Absolute

End hand/body support must be physically compatible with next start.

Reject seam if:
- object vanishes from hand without placement/pocketing
- new object appears in hand with no pickup
- character suddenly holds more objects than hands/support permit
- bag/umbrella/phone/earbuds/key/binder hand roles silently swap

## Character ↔ Environment Seam Rule — Absolute

For A/E and continuous G seams preserve:
- camera axis/perspective when intended
- character scale/floor support
- actual chair/body relationship
- reachability/eyeline
- object scale
- wall/floor/background alignment
- door/cabinet hinge state
- power/light baseline

Do not mirror room/move fixed architecture to help next composition.

## No-Dead-Space Seam Rule — Absolute

Never create seam by huge empty lower area.

If pause needed, it must read through existing narration/SFX/reaction/environment/atmosphere/reveal timing. Otherwise continue artwork closer to edge with small buffer. Never invent text/SFX.

Reject double-gap join.

## Overlap Strategy

When practical, repeat small lower-edge continuity zone from N at top of N+1, crop duplicate during stitch. Roughly 10–20% transition area. Never reader-visible repeated panel.

No repeated dialogue/SFX. Repeated objects/body portions must match exactly; overlap is not second story-world object.

## Text Seam Rule — Absolute

Never split speech balloon, narration, handwriting, device text, critical SFX, or obvious face mismatch across seam.

Never introduce V/P/strip/beat/panel/scene production label at new file start.

## Seam QA — Third Hardened Checklist

Before approval compare bottom N to top N+1:
- width identical
- canonical environment landmarks correct
- fixed outlet landmark unchanged
- character identity/hair/wardrobe unchanged unless scripted
- exact position/feet/scale/pose handoff
- hand occupancy physically compatible
- prop provenance continuous
- prop topology/physical sides unchanged
- food/noodle/chopstick/pot/packet/wrapper consistent
- recurring object body/state canonical
- cord/plug/wall-socket identical unless explicit action changes
- key/manual/phone/notebook/pen/knife/candle/chair/cabinet small states persist
- storage lid/towel/speaker arrangement persists
- no accidental technical line
- no duplicated/missing text
- no missing floor/wall segment
- no changed appliance geometry
- no power/light jump unless scripted
- no pose/object teleport
- no narration-style reset resembling new-file header
- no `V-*`/production metadata
- no excessive dead bottom/top gap

If join obvious at phone-scroll speed, violates state/provenance/topology/outlet handoff, or conflicts canonical reference, reject/regenerate newer strip.
