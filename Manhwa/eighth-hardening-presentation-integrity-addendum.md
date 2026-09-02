# Eighth Hardening — Presentation Integrity Addendum

This addendum is binding on Chapter 1 Strip 001–032 and extends the existing `manhwa-2d-production-auditor` rules.

It does not change story canon. It closes presentation-level loopholes where the correct objects/actions technically exist but are warped, cropped, too small, poorly lit, or ordered so badly that the reader cannot verify the intended physical event.

## Authority

1. current user instruction
2. current chapter/current strip script
3. approved character WebPs
4. approved environment WebPs
5. approved object WebPs
6. current hardened strip prompt
7. previous APPROVED strip temporary state only
8. canon-compatible derived micro-detail only

No camera lens, crop, gutter, balloon layout, SFX placement, dramatic lighting, or mobile framing may override the physical truth above.

## Perspective / Lens Integrity — Absolute

Camera choice may change, but canonical geometry and human/object proportions may not bend to accommodate a shot.

Reject:
- fisheye or ultra-wide distortion that visibly curves straight walls, doors, cabinets, TV edges, refrigerator edges, table edges, or floor lines
- extreme perspective that enlarges a foreground hand/plug/knife/phone into a different world-space proportion while shrinking the connected body/object implausibly
- dutch-angle or perspective distortion that makes floor support, wall socket orientation, door threshold, chair seating, or walking route physically ambiguous
- forced perspective that makes two separate objects appear to touch/overlap when they do not in story space
- close-up perspective that reverses hinge, hand, object, screen, page, or body orientation

Use ordinary manhwa camera perspective. Dramatic composition must come from framing, scale of shot, pacing, and crop—not lens warping.

## Mobile-Scale Evidence Legibility — Absolute

A continuity-critical fact must be visually understandable at normal mobile reading scale.

The following cannot be technically present but microscopic/ambiguous:
- wall plug body, wall socket opening, loose plug and appliance-side attached cord
- key leaving/entering a hand/tray/ring
- binder page edge/rings and Section 16→18 proof
- tool leaving/returning to tray
- chopstick/food path
- foot→packet contact
- chair body/seat/leg clearance
- mask hardware movement
- knife leaving fingers, fall path and floor impact
- wrist grip/release
- phone/notebook pickup and placement
- cabinet handle/hinge/lid/towel/speaker reveal
- notebook handwriting and final TV message

If a wide shot makes the proof too small, add an immediately adjacent SAME-OBJECT detail view while preserving state and layout grammar. Never replace physical proof with SFX or text.

## Crop / Gutter / Divider Safe Margin — Absolute

Continuity-critical proof must not be amputated by the canvas edge, strip boundary, black gutter, diagonal divider, balloon, or crop.

For required mechanisms:
- keep the decisive contact and enough surrounding context fully inside the image area
- do not place plug/socket, hand/key, knife/fingers, foot/packet, chair legs, mask hardware, wrist grip, notebook edge, or cabinet hinge exactly on a crop line
- do not let a diagonal divider cut through a hand, foot, object, cord, text carrier, or evidence path
- external A/E seam cannot cut through a state-changing contact unless the seam is intentionally continuous and the full mechanism remains readable after stitching
- leave compact visual breathing room around required proof; do not use a single-pixel-edge inclusion as compliance

## Lighting Source / Shadow Direction Continuity — Absolute

Within the same lighting state, light direction and cast-shadow logic remain consistent with the actual sources.

Rules:
- powered Unit 2407 uses the attached normal-lighting baseline; adjacent shots cannot arbitrarily move the dominant light to the opposite side
- blackout scenes use only allowed sources: none, or the one small candle where present
- candle position determines local warm light/shadow direction until extinguished
- after candle is out, candle highlights/shadows disappear
- refrigerator/TV pixels never become room lights unless explicitly scripted; they do not create new face rim lights or cast shadows
- power restoration changes lighting exactly at the scripted event; before/after comparison must not retain impossible old shadows
- one `FZZT` flicker may briefly vary the real powered light but returns to the same powered baseline
- flat 2D readability separation is not a story-world second light source

Reject moving shadow directions, contradictory highlights, or invented cinematic light that changes perceived geometry/state.

## Top-to-Bottom Reader Order / Dialogue Sequencing — Absolute

Reader-facing text and action must read in the exact scripted causal order on a vertical mobile scroll.

For each strip:
- top-to-bottom reading order follows the written beat order
- within one composition, balloon order must not make later dialogue read before earlier dialogue
- tails must point to the correct speaker without crossing another speaker confusingly
- SFX must appear at the physical action moment, not visually before its cause or after the resulting state if that changes meaning
- device text must appear at the intended beat and not be visually read before the action that activates it
- narration must not be placed so it visually interrupts/reorders dialogue/action
- diagonal side-by-side views must still have one unambiguous reading sequence

If multiple lines cannot be read clearly in order, split into more vertical space or additional unlabeled sub-slices. Do not rewrite dialogue to solve layout.

## Critical Object / Limb Silhouette Completeness — Absolute

When continuity depends on a hand, foot, arm, leg, cord, utensil, knife, key, phone, or wearable:
- show enough of the connected body/object to prove ownership and orientation
- do not crop a hand so tightly that the reader cannot tell which arm it belongs to
- do not crop a foot so tightly that STEP FOOT/CANDLE FOOT identity becomes ambiguous
- do not show a loose plug without enough cord path to connect it to the same appliance
- do not show a knife impact without enough blade/handle contour to identify the same knife
- do not show a notebook page without enough notebook/spine context to prove it is the same physical notebook

A close-up is allowed, but adjacent context must preserve ownership.

## Readable In-World Text — Absolute

Exact scripted device/page/note/notebook text must be readable at intended mobile size.

- do not deliberately corrupt required exact words into illegible decorative glyphs
- hostile distortion may damage edges/spacing but the required message must remain readable when the story depends on the wording
- physical handwriting remains human-drawn in appearance but exact words must still be legible
- text cannot be so tiny that the reader must infer it from narration
- if the entire physical carrier cannot show readable text at normal shot size, use a SAME-OBJECT detail slice rather than enlarging the object in world space

## Eighth-Pass Automatic Reject Additions

Reject if:
- lens/perspective warps canonical geometry or body/object proportions
- continuity proof is present but too small to understand at mobile scale
- crop/gutter/divider cuts off decisive contact or evidence
- same lighting state changes source/shadow direction without physical cause
- powered/candle/blackout/flicker lighting contradicts the actual source state
- dialogue/SFX/device/narration reads in the wrong causal order
- close-up crops ownership so hand/foot/object identity becomes ambiguous
- required exact in-world text is unreadable, microscopic, or decorative gibberish

These are prompt/preproduction gates. Actual rendered compliance remains PENDING until image pixels are inspected.