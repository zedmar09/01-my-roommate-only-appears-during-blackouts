# Tenth Hardening — Pose / Performance / Relative-Scale Continuity Addendum

This is the FINAL preproduction hardening addendum for Chapter 1 Strip 001–032 under `manhwa-2d-production-auditor`.

It does not change story canon. It closes the remaining loophole where the generator can preserve the correct character identity, anatomy, objects, references, location, camera axis and action mechanics while still resetting the character's pose, relative scale, emotional performance, body facing, gesture, clothing-layer state, or hair/garment motion between adjacent slices.

## Authority

1. current user instruction
2. current chapter/current strip script
3. approved character WebPs
4. approved environment WebPs
5. approved object WebPs
6. current hardened strip prompt
7. previous APPROVED strip temporary state only
8. canon-compatible derived micro-detail only

Previous generated artwork never creates new permanent emotion, height, costume or pose canon.

## Pose-State Conservation — Absolute

A camera cut is not a pose reset.

Track the actual body state across adjacent slices:
- standing / seated / crouched / kneeling / walking / leaning / shielding
- weight-bearing leg(s)
- shoulder and hip orientation
- torso facing
- head turn relative to torso
- elbow/arm gesture
- hand height and hand purpose
- spine bend / lean direction
- feet placement and body center of mass

Rules:
- if only the head/eyes turn, shoulders/hips/feet remain where they were
- if the torso turns, show or clearly stage that torso rotation
- if an arm lowers/raises/crosses/uncrosses, that gesture change must be visible or occur at a legal cut
- reverse camera may flip screen direction but cannot silently rotate the body to a different story-world facing
- a close-up cannot imply a shoulder/torso orientation incompatible with the adjacent wider pose
- the same stationary conversation pose cannot randomly alternate between hands-at-sides, arms-crossed, hand-on-hip, hands-up, etc. unless the gesture change is shown

## Body-Facing / Shoulder-Hip Axis — Absolute

Eyeline continuity alone is not enough.

For stationary dialogue/action:
- preserve the story-world direction of shoulders, sternum, hips and feet
- head rotation may differ from torso facing only within believable neck range
- a reverse shot must not make a character's chest/hips face the opposite physical direction while feet remain unchanged
- if a character turns toward a new source/person/device, specify whether the change is head-only, upper-torso, or full-body; do not let the generator choose a larger movement than scripted

If a pose would require re-planting feet or changing chair support, that movement must be visible.

## Relative Height / Build / Body-Scale Continuity — Absolute

Canonical height/build relationships must remain physically stable.

- Nari = medium-height slim adult build
- Hyun-woo = clearly taller and broader/powerful than Nari when both are upright on the same floor plane
- Seungjae = lean-to-average youthful adult build, clearly less broad/intimidating than Hyun-woo and same-generation peer to Nari
- Mrs. Na = realistic older-adult proportions; do not enlarge/shrink her between counter/door views

Rules:
- camera perspective may change screen size but not world-space height/build
- characters standing on the same floor plane may not gain/lose head-height/body-width relationships between reverse shots
- seated/crouched poses must explain temporary apparent height difference through the pose, not character resizing
- do not make Hyun-woo the same height/build as Nari for a close two-shot
- do not make Seungjae suddenly tall/broad/ominous to resemble Hyun-woo
- do not shrink Nari in final TV shots merely to make the TV dramatic

When a canonical card does not provide an exact numeric height, preserve its build/proportion identity and the first canon-compatible shared-scene relative scale as temporary scene continuity; this never overrides the canonical character WebPs.

## Expression / Emotion Continuity — Absolute

Emotion changes only because the story gives the character a reason to change.

A new camera angle, close-up, gutter or strip boundary cannot randomly reset emotional intensity.

Rules:
- carry the prior emotional state into the next slice unless dialogue/action/environment provides a visible cause for escalation/de-escalation
- do not alternate smile → panic → neutral → anger between adjacent dialogue views without scripted stimulus
- do not add tears, blushing, screaming, rage, villain smirks, horror faces or romantic glamour unless the event supports that intensity
- subtle adult reactions are preferred over exaggerated anime/chibi/emote acting
- the same emotional beat may use different camera angles but must still look like the same continuing performance

Chapter 1 baseline progression:
- move-in/automation = dry, tired, practical, mildly amused
- early impossible evidence = skeptical, analytical, increasingly uneasy; not immediate hysteria
- Seungjae sequence = ordinary social warmth/awkwardness with device confusion; no sinister villain performance
- blackout preparation/onset = controlled alertness escalating to tension
- first `SLURP` / knife approach = guarded fear + practical caution, not screaming panic
- Hyun-woo interrogation = wary, skeptical, defensive; Hyun-woo guarded/calm/dry rather than villainous rage
- hostile refrigerator escalation = focused danger/protective urgency
- knife drop/wrist catch = acute shock localized to the event
- powered aftermath = shaken but investigative/functional
- final TV message = controlled dread/shock; no melodramatic scream/cry unless script explicitly says so

## Gesture Continuity — Absolute

A gesture is temporary state.

Track:
- pointing/indicating hand
- phone-holding hand
- arms shielding eyes
- hand toward ear
- knife-low posture
- hand on cabinet/door/object
- hand resting on table/notebook
- chair-supported arm/body posture

A gesture persists until visibly released/changed or a legal cut explicitly allows a new pose.
Do not invent expressive gestures that interfere with held-object/hand-occupancy continuity.

## Clothing-Layer / Closure-State Continuity — Absolute

Within one continuous scene, preserve not only wardrobe identity but how it is currently worn:
- jacket/coat present or absent
- open/closed/fastened state where visibly established
- hood up/down
- sleeve length/rolled state
- shirt/top tucked/untucked if visible
- bag worn/removed
- headphones neck position
- mask seated/lowered state

A reverse shot may not zip/unzip a jacket, raise/drop a hood, roll sleeves, remove a bag, change coat opening, or alter mask state without action/legal cut.

A legal time/location cut may establish a new clothing-layer state, but the new state must then remain stable through that continuous scene.

## Hair / Garment Motion Continuity — Absolute

Motion may affect flexible shapes naturally, but it cannot redesign them.

- Nari's long loose hair may sway with walking/turning but retains same length/part/fringe/volume family
- Hyun-woo's low-tied hair tail may shift with movement but remains tied low and one continuous tail/mass
- Mrs. Na's tight silver twist remains fixed/practical, not loose because the camera changed
- Seungjae's medium-brown styled hair may respond minimally to rain/entry but retains the same part/silhouette
- coat/hoodie/trouser folds may move with pose but do not become a new garment construction

Do not let hair/coat/hoodie motion hide a body move that was never actually performed.

## Emotional / Pose Seam Rule — Absolute

At every strip boundary, carry forward:
- last body support/pose
- shoulder/hip facing
- head orientation where relevant
- held gesture
- relative distance/height relationship
- emotional intensity/performance
- clothing-layer state

The next strip may change these only by its scripted first action or a legal time/location cut.

## Tenth-Pass Automatic Reject Additions

Reject if:
- stationary character silently rotates torso/hips/feet between adjacent views
- a head-only turn becomes an unscripted full-body turn
- gesture changes without visible release/change
- relative character height/build changes on the same floor plane
- Hyun-woo loses tall/broad relation to Nari or Seungjae becomes Hyun-woo-like in scale
- character emotional intensity resets or jumps without story cause
- an ordinary scene becomes exaggerated horror/romance/villain acting without script support
- Nari screams/cries/panics in a beat that only scripts controlled reaction
- Hyun-woo becomes enraged/villainous when the script calls for guarded/protective calm
- Seungjae becomes sinister/dominating rather than ordinary confident coworker
- clothing layer/hood/sleeve/coat/bag/mask wear state changes without action/legal cut
- hair flexible motion becomes a different hairstyle/length/volume construction
- strip boundary resets pose/facing/emotion instead of inheriting it

These are prompt/preproduction gates. Actual rendered compliance remains PENDING until image pixels are inspected.