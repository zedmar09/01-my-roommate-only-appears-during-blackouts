# Chapter 1 Production Strips

This folder contains **32 technical image-generation prompts** for one continuous Manhwa Chapter 1. Historical P001–P018 labels are story-mapping shorthand only.

Current status: **FULL DEEP HARDENING IN PROGRESS — do not treat any Strip 001–032 prompt as final-production-safe until the current hardening pass and re-audit are complete.**

Generate strictly in order only after the hardening pass is complete: `001 → 002 → 003 → ... → 032`.

## Binding Global Rules — Absolute

Every strip inherits the current repository production rules even when they are not repeated in the strip attachment list:
- `../../../style-guide.md`
- `../../../lettering-sfx-guide.md`
- `../../../seam-continuity-protocol.md`
- `../../../vertical-scroll-layout-guide.md`
- `../../../generation-workflow.md`
- `../../../production-readiness-gate.md`

A strip may make these stricter but never looser.

## Attached References Are Binding Pixel Authority — Absolute

Every attached approved WebP is an **identity / geometry / object-design authority**, not inspiration, not a moodboard, and not an optional suggestion.

Production MUST NOT:
- redesign a character because another face/hairstyle/body is easier to draw
- move, mirror, resize, merge, delete, or invent fixed architecture/furniture/appliances against an environment reference
- redesign a recurring prop, cable, plug, socket, key, binder, appliance body, mask, chair, pot, bowl, knife, sheath, bag, phone, or other reference-controlled object
- replace an attached reference with a generic equivalent
- average conflicts by inventing a third design
- use a previous strip to override permanent canonical identity/geometry
- omit a reference-controlled detail merely because the shot is difficult

If the desired camera/action cannot be reconciled with the approved references, **STOP / RECOMPOSE THE CAMERA OR ACTION**. Do not modify canon to make the composition easier.

## Real-Scenario Cause → Action → Consequence — Absolute

For every meaningful state change, production must visibly respect:

`START STATE → PHYSICAL CAUSE → VISIBLE ACTION → RESULT → PERSISTENT END STATE`

Do not jump directly from intention to result when the physical transition matters.

Examples:
- character across room → visible walking route → reaches target
- object in hand → visible placement/drop/handoff → object on surface/floor/other hand
- seated → chair/body movement → standing
- candle lit → realistic reach/blow → extinguished wick/smoke
- knife in hand → fingers release → fall → impact → fixed floor location
- cabinet closed → character approaches → hand/hinge action → cabinet open

An action may be compressed only when the reader can still infer the complete real-world mechanics without contradiction. Never use an SFX or camera cut to hide an impossible teleport.

## Wall-Socket / Plug / Cord Physics — Absolute

When the story says an appliance is **unplugged**, the default meaning is **unplugged from the wall-mounted electrical socket/outlet**.

Required physical truth:
- the electrical socket/outlet is mounted on the wall at the canonical outlet location
- the appliance-side cable/cord remains attached to the SAME appliance body
- the same cord physically runs from the appliance to its plug
- the character grips/pulls the plug at the WALL SOCKET when the unplug action occurs
- after removal, the loose plug remains attached to that same cord
- the wall socket is empty / visibly no longer receiving the plug
- cord length, route, and appliance-side attachment do not arbitrarily change afterward

**DO NOT interpret `unplug` as disconnecting a detachable cable from the TV/speaker/appliance body.**

Automatic rejection:
- cable detached from appliance instead of wall
- loose cable end shown at appliance body
- plug disappears after removal
- socket is relocated to furniture/appliance
- cord changes sides, route, count, or attachment without cause
- unplugged appliance appears plugged again later without an explicit re-plug action

This rule is especially critical for the Strip 006→007 TV proof and the Strip 031→032 final TV state.

## Micro-Continuity / Object Persistence — Absolute

Every visible story-world state in vertical slice X persists into slice X+1 unless one of these is shown or explicitly authorized by a real time/location cut:
- pickup
- placement
- handoff
- drop/fall
- eating/drinking
- spill/breakage
- opening/closing
- plugging/unplugging
- clothing/pose change
- character movement
- deliberate offscreen continuation that is physically unambiguous

A camera cut does **not** erase objects. Occlusion does **not** mean disappearance.

Track small continuity details including:
- food/noodle amount and whether noodles are in bowl/pot/chopsticks/mouth
- chopstick pair identity and hand/table/floor position
- bowl/pot/trivet/cloth location
- hands and what each hand is holding
- cords/plugs/wall sockets
- manual open/closed page state
- brass-key location
- phone/tablet/bag location
- knife/sheath state
- candle/holder/flame/wick state
- chair push-back/occupied state
- cabinet/stockpot/lid/towel state
- packet counts
- pen/notebook/note state

If a detail cannot be shown because of framing, it must remain **logically unchanged**, not silently reset.

## Character ↔ Environment Interaction Reality — Absolute

Audit every contact and movement against the attached environment:
- feet must stand on believable floor support
- sitting body must align with the actual chair seat/back
- hands must reach objects from physically possible distance
- eyelines must point toward the real target location
- door/cabinet swing must respect hinges and nearby geometry
- walking routes must fit available circulation space
- a character cannot pass through table/counter/chair/appliance/wall
- scale between character, furniture, doors, appliances, props, and room must remain consistent
- reverse angles must be physically derivable from the canonical floor plan, never mirrored for convenience

## Start-State / Allowed-Change / End-State Ledger — Absolute

Every strip prompt must define or unmistakably enforce:
1. **START STATE:** exact character positions, held objects, object locations/states, power/lighting, room axis, open/closed states, food/device state inherited from the prior strip/time cut.
2. **ALLOWED CHANGES:** only the scripted movements/actions/state changes that may occur during this strip.
3. **END STATE:** exact state that must persist into the next strip.

Anything not listed as an allowed change remains unchanged.

## Narration Design Must Follow Scenario — Absolute

Narration wording stays exact, but its **visual treatment must be designed according to the function, event, situation, pacing, and emotional pressure of the specific beat**. Do not force one narration-box design across the whole chapter.

Possible treatments, always flat/matte/mobile-readable:
- neutral scene/time setup → clean compact editorial caption
- ordinary observational narration → restrained unobtrusive caption integrated with available negative space
- landlord/rule/procedural emphasis → firmer utilitarian caption treatment
- investigative/evidence narration → compact report-like treatment
- ominous realization → sparse higher-contrast treatment with controlled breathing room
- suspense/listening/reveal delay → minimal narration footprint; let silence/art carry the beat

Rules:
- narration must never imitate speech balloons, device UI, physical handwriting, or production labels
- do not use decorative cinematic/glitch boxes merely because the scene is supernatural
- do not cover faces, hands, plugs, sockets, food continuity, clues, or environment anchors
- narration treatment may vary between beats, but chapter typography must still feel like one coherent publication system
- the design follows the scene; the scene is never restaged merely to fit a favorite narration template

## NO Reader-Visible Production Metadata — Absolute

Production IDs are forbidden everywhere in generated art, **especially the top-left of a vertical slice**.

Never render:
- `V01`, `V-01`, `V1`, `V##`
- `P1`, `P001`, `P##`
- `Strip 001`, `strip-001`, strip numbers
- `BEAT`, `SCENE`, `PANEL`, `SHOT`, `REFERENCE`, `DRAFT`, `LAYOUT`, `SFX:` labels
- circled panel numbers
- headers/footers/crop marks/QA notes

The V/P/strip identifiers inside Markdown are production-only instructions and must **never** be copied into the artwork. Any accidental top-left `V-*` or similar technical label = **AUTOMATIC REJECT**.

## Every Strip Prompt Is Self-Contained For Visual Attachments — Absolute

Every `strip-###-...md` explicitly lists inside the file itself:
1. current strip prompt
2. required visible-character canonical WebP(s)
3. every required reusable environment WebP
4. every required reusable object WebP
5. immediately previous APPROVED rendered strip for 002–032

Do not rely on the manifest alone when working in the production chat. The manifest is the audit map; the current strip file repeats the exact visual attachments needed for that generation.

Use exact repository paths and exact filenames. Do not write only `Nari canonical`, `Unit 2407 floor plan`, or an obsolete `.png` path when the actual attachment is a `.webp` file.

If a listed canonical WebP is missing, stale, wrong-path, or unapproved, **STOP**. Do not substitute a random reference, an old rejected/obsolete image, or the Markdown reference prompt itself.

## Approved Chapter 1 Character WebPs

- `Character-References/nari-canonical-flat2d.webp`
- `Character-References/hyunwoo-canonical-flat2d.webp`
- `Character-References/mrs-na-canonical-flat2d.webp`
- `Character-References/seungjae-canonical-flat2d.webp`

Nari's current approved authority uses long dark-plum hair at approximately mid-back length. Her retired short-hair design must never be propagated.

## Reference-Image Generation Format

Reference prompt Markdown may continue to generate PNG first as a local intermediate. After visual approval, the accepted PNG is manually converted to WebP and the WebP becomes the GitHub/strip-attachment authority.

Do not change production-strip attachments back to the intermediate PNG name.

Reuse Unit 2407, Building Shared Areas, smart-speaker, TV, refrigerator, electrical-operation-guide, and brass-key WebPs in later chapters whenever the same place/object returns. Never create chapter-numbered duplicates.

## Strict Flat 2D Human-Drawn Style — Absolute

Actual strip pixels must satisfy `../../../style-guide.md`:
- strict flat 2D human-drawn Korean manhwa/webtoon illustration
- clean intentional line art
- flat colors
- restrained simple hard-edged cel shading only
- matte characters, materials, rooms, furniture, appliances, screens, glass, floors, and props
- stable canonical anatomy/proportions and natural hands

Reject photoreal/semi-photoreal, 3D/CGI/game-render, glossy/plastic/wet, painterly, airbrushed, cinematic grading, depth-of-field blur, bloom, lens flare, excessive rim light, mirror-like reflections, excessive specular highlights, or over-rendered AI-polished output.

Previous-strip continuity never overrides the permanent flat style gate.

## Black Read-Slice Grammar — Absolute

Every distinct vertical reading slice/composition inside a technical strip receives a **small black gutter** before the next distinct slice.

Rules:
- gutter is narrow and deliberate, never a huge dead black band
- use black, not random white spacing, as the normal visual slice separator
- meaningful longer pauses may be slightly larger but still purposeful
- time/location cuts may use a somewhat stronger compact black divider
- if TWO different camera slices share one horizontal row, separate them with a **diagonal/slanted black divider**
- faces, text, balloons, props, and backgrounds must not cross the diagonal divider
- side-by-side slices must read as separate shots, never one merged impossible environment

Technical file seams are different. For A/E continuation seams, do **not** add a visible black bar merely because one generated file ends; the final stitched chapter must remain seamless.

## Production Rules

- use only approved exact-path WebP canonicals
- approve each strip before generating the next
- re-audit every corrected strip and adjacent seams before approval
- use one fixed width throughout
- preserve seam type in `../chapter-01-strip-manifest.md`
- preserve canonical room geometry and recurring object identity/state
- preserve exact movement/object routes and dialogue ownership
- verify every SFX as physical source → action → sound → timing → placement → consequence
- audit hands, held objects, feet/support, eyelines, reachability, chair/body contact, plug/socket mechanics, and food continuity between every adjacent visual slice
- never render production IDs/page numbers/circled panel numbers
- never leave huge purposeless bottom blank space
- never invent filler narration/dialogue/SFX
- stitch all approved strips into one continuous chapter after 032
- run a fresh clean-room visual audit after stitching; do not inherit earlier PASS labels

See `../chapter-01-real-scenario-continuity-audit.md` for the current audit result.
