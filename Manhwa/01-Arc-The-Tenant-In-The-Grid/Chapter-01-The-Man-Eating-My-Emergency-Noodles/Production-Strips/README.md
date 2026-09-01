# Chapter 1 Production Strips

This folder contains **32 technical image-generation prompts** for one continuous Manhwa Chapter 1. Historical P001–P018 and V01–V146 labels are production-only mapping shorthand.

Current status: **FULL HARDENED PREPRODUCTION GATE PASS — READY TO RETEST FROM STRIP 001 — NOT PRODUCTION COMPLETE.**

The full Strip 001→032 prompt package has been rewritten and clean-room re-audited under the current `manhwa-2d-production-auditor` standard.

## Prior Render Rejection — Absolute

Previously generated / pre-hardening strip attempts are **NOT APPROVED continuity authority** for this retest.

Do not attach an older rejected render as `APPROVED Strip N` merely because it already exists. The new production test restarts from:

`Strip 001 → audit / fix / re-audit → approve → Strip 002 → ... → Strip 032`

Only a newly generated strip that passes the current hardened visual QA may become temporary continuity authority for the next strip.

## Binding Global Rules — Absolute

Every strip inherits:
- `../../../style-guide.md`
- `../../../lettering-sfx-guide.md`
- `../../../seam-continuity-protocol.md`
- `../../../vertical-scroll-layout-guide.md`
- `../../../generation-workflow.md`
- `../../../production-readiness-gate.md`

The current strip prompt may be stricter but may never loosen them.

## Attached References Are Binding — Absolute

Every attached approved WebP is **identity / geometry / object-design authority**, not inspiration or a moodboard.

Production must not redesign or relocate a reference-controlled character, room, wall socket, furniture item, appliance, cord, plug, key, binder, mask, chair, pot, knife, sheath, bag, phone, or other recurring object to make a composition easier.

If an intended camera/action conflicts with canon, **recompose the camera/action**. Never modify canon to make generation easier.

## Real-Scenario State Rule — Absolute

Every meaningful change must follow:

`START STATE → PHYSICAL CAUSE → VISIBLE ACTION → RESULT → PERSISTENT END STATE`

Each hardened strip now includes or explicitly enforces a START / ALLOWED CHANGES / END state ledger.

A camera cut, close-up, black gutter, reverse angle, or file boundary does not reset the story world.

## Micro-Continuity — Absolute

Between adjacent vertical slices and strips, preserve every state not visibly changed:
- hands and held items
- character feet / body support / facing / distance / seated-standing state
- food / noodle amount and physical path
- bowls / pots / chopsticks / packets / wrappers
- cords / plugs / WALL sockets
- key / manual / note / phone / tablet / bag
- knife / sheath / fixed impact locations
- candle / holder / flame / wick state
- chair position / occupancy
- cabinet / stockpot / lid / EXACTLY two towels / speaker
- notebook / pen / prior handwriting
- device display and power state

Occlusion is not disappearance. A dialogue close-up does not delete props.

If food/noodles are visible in one slice, they may change only through a visible or physically unmistakable bite, slurp, lowering, spill, placement, or legal time cut. They may not simply vanish in the next slice.

## Wall-Socket / Unplugging Rule — Absolute

Unless the script explicitly says otherwise, `UNPLUGGED` means:
- the electrical **plug is removed from the WALL-MOUNTED socket/outlet**
- the appliance-side cord remains attached to the appliance body
- the same cord still ends in the loose electrical plug
- the wall socket is empty
- that disconnected wall-end state persists until an explicit re-plug action

It does **NOT** mean pulling a cable out of the TV / speaker / appliance body.

Chapter 1 critical continuity:
- Strip 006: speaker unplugged FROM WALL
- Strip 006: TV unplugged FROM WALL
- Strip 007: same TV loose plug + empty wall socket persist
- Strips 031–032: that same TV is still unplugged FROM WALL while it activates
- stored speaker keeps its attached cord + loose wall plug physically accounted for inside the stockpot / towels state

Any appliance-side disconnect masquerading as `unplugged` = **AUTOMATIC REJECT**.

## Character ↔ Environment Reality — Absolute

Audit every small interaction:
- feet/body must have real support
- sitting must align with the actual chair
- hands must be able to reach the actual target
- eyelines must point to the target's canonical location
- doors/cabinets respect their hinges and nearby walls
- walking routes must fit the canonical floor plan
- bodies cannot pass through tables, chairs, counters, appliances, or walls
- reverse angles must remain physically truthful, never mirrored for convenience

## Narration Design By Scenario — Absolute

Narration wording remains exact, but its visual design must follow the current event and situation. Do **not** force one identical narration-box design across the whole chapter.

Use one coherent publication family with functional variants such as:
- time / location transition → compact editorial caption
- ordinary observation / dry comedy → restrained unobtrusive caption
- rule / procedural warning → firmer utilitarian treatment
- investigation / evidence context → compact report-like treatment
- ominous realization → sparse higher-contrast treatment
- suspense / listening / reveal delay → minimal footprint

Narration must never imitate speech bubbles, device UI, physical handwriting, or production labels, and must not cover continuity-critical hands, food paths, wall plugs/sockets, clues, or environment anchors.

## NO Reader-Visible Production Metadata — Automatic Reject

Never render, especially at the top-left of a vertical slice:
- `V01`, `V-01`, `V##`
- `P1`, `P001`, `P##`
- `Strip 001`, `strip-001`
- `BEAT`, `PANEL`, `SCENE`, `SHOT`
- reference / draft / layout / QA labels
- circled production numbers, crop marks, technical headers/footers

V/P/strip identifiers written inside Markdown are instructions for production only. They must never appear in reader-facing art.

## Every Strip Is Self-Contained For Attachments — Absolute

Every current `strip-001` through `strip-032` explicitly lists its exact required visual WebPs plus the immediately previous newly APPROVED strip for 002–032.

Use exact repository filenames. Do not substitute obsolete PNG names, vague shorthand, a Markdown reference prompt, or a rejected old render.

## Current Approved Chapter 1 Character WebPs

- `Character-References/nari-canonical-flat2d.webp`
- `Character-References/hyunwoo-canonical-flat2d.webp`
- `Character-References/mrs-na-canonical-flat2d.webp`
- `Character-References/seungjae-canonical-flat2d.webp`

Nari's current identity uses long dark-plum hair approximately mid-back length, loose by default. Retired short-hair Nari is invalid.

## Reference-Image Generation Format

Character / environment / object image prompts may continue to generate PNG first as a **local intermediate**. After visual approval, manually convert the accepted PNG to WebP. The committed WebP is the production attachment authority.

## Strict Flat 2D Human-Drawn Style — Absolute

All generated pixels must satisfy `../../../style-guide.md`: strict flat 2D human-drawn Korean manhwa/webtoon illustration, clean intentional line art, flat colors, restrained hard-edged cel shading only, matte materials, stable anatomy/proportions, natural hands, and mobile readability.

Reject photoreal/semi-photoreal, 3D/CGI, glossy, cinematic, painterly, airbrushed, bloom-heavy, mirror-like, depth-of-field, or AI-polished over-rendering.

## Black Read-Slice / No-Dead-Space Rules

Use small black gutters between distinct vertical reading slices and diagonal/slanted black dividers between separate shots sharing one row.

A gutter is reading grammar, not permission to reset state or fill canvas. Do not create huge black/white dead bands. A technical A/E seam remains invisible when art/effect continues.

## Current Production Order

1. Generate **new Strip 001** using its exact hardened prompt + exact approved WebPs.
2. Deep-audit the actual rendered pixels against the current hardening gates.
3. Fix/regenerate until Strip 001 passes.
4. Only then treat that Strip 001 as APPROVED and attach it to Strip 002.
5. Repeat sequentially through Strip 032.
6. Stitch all approved strips.
7. Run a fresh final clean-room visual audit.

`PRODUCTION COMPLETE` is forbidden until that final rendered/stitch audit reaches zero unresolved mandatory findings.
