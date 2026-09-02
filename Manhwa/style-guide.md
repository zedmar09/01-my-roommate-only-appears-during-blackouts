# Manhwa Style Guide

## Core Target — ABSOLUTE

**STRICT FLAT 2D HUMAN-DRAWN KOREAN MANHWA/WEBTOON ILLUSTRATION.**

Every generated or edited story image must read unmistakably as a flat 2D illustration made with intentional human-drawn linework. This is a hard production gate, not a mood suggestion.

Required:
- clean intentional line art
- stable line weight and readable silhouettes
- flat colors
- restrained simple hard-edged cel shading only when needed
- matte skin, hair, fabrics, walls, floors, furniture, appliances, screens, glass, and props
- believable adult proportions according to canon
- natural hands and **one coherent human body per character**
- stable permanent facial/body landmarks
- stable character local colors/materials
- stable project palette
- mobile-first readability

Do **not** make the pipeline richer, more cinematic, more painterly, more glossy, or more realistic than the approved flat 2D canon.

Reject or repair:
- photorealism or semi-photorealism
- 3D, CGI, or game-render appearance
- plastic/glossy/wet-looking skin, hair, clothing, furniture, floors, counters, windows, TV, refrigerator, or appliances
- beauty-ad shine or excessive specular highlights
- soft airbrush rendering or heavy gradients that erase flat shape design
- painterly realism that weakens line definition
- cinematic color grading
- cinematic depth-of-field blur
- bloom, lens flare, excessive rim light, or gratuitous reflections
- dramatic film lighting not required by the script
- hyper-detailed pores/skin texture or over-rendered eyes/lips/hair
- AI-polished glossy finish

## Character Canonical Authority — Absolute

Approved canonical character-card WebPs under `Character-References/` are absolute identity authority. A locally generated PNG may be used during generation/QA, but after approval the exact repository WebP is the production attachment authority.

Character canon controls:
- face geometry and age presentation
- eye/nose/jaw relationships
- permanent facial marks and their anatomical side
- hair length/part/tie/fringe/silhouette/color
- height/build relationship
- tattoo coverage/pattern relationships
- mask construction/attachment
- wardrobe construction and signature local colors
- permanent accessories/wearables

A close-up, reverse shot, blackout rendering, expression, dramatic crop, or previous generated strip never outranks the character WebP.

## Whole-Body Anatomical Topology — Absolute

Every visible character must remain one physically coherent human body.

Reject:
- extra or missing arms, forearms, hands, legs, feet, ears, fingers, shoulders, or other body parts
- duplicated hands/feet/ears/limbs
- detached/floating hand, foot, ear, hair mass, shoulder, jaw, or limb
- fused limbs/fingers that make body topology impossible
- impossible elbow, knee, wrist, ankle, shoulder or hip articulation
- hand/arm emerging from the wrong side of the torso
- lower body/feet that cannot connect to the visible pelvis/legs
- close-up hand/foot/limb that cannot physically belong to the adjacent wider body pose

Partial occlusion is allowed only when the hidden connection remains anatomically possible and consistent.

## Limb Ownership / Reverse-Shot Identity — Absolute

When a close-up shows a continuity-critical hand, wrist, foot, arm, or leg:
- it belongs to the SAME character
- it belongs to the SAME anatomical side established by the current action/state
- sleeve, glove, tattoo, scrunchie, skin, clothing, and adjacent body cues remain compatible with that ownership
- reverse camera may flip screen-left/right, but anatomical ownership may not change
- a close-up is not permission to generate a generic disembodied hand/foot

Production-only identities such as `KNIFE HAND`, `PHONE HAND`, `WRITING HAND`, `STEP FOOT`, `CANDLE FOOT`, `SCRUNCHIE WRIST`, `BAG SHOULDER`, `UMBRELLA HAND`, and `PHONE POCKET` are never reader-facing text but remain physical continuity facts when established.

## Permanent Character Landmark Side — Absolute

### Yoon Nari
- exactly ONE tiny black beauty mark beside the **anatomical LEFT** corner of her mouth
- reverse camera may move the mark to the opposite screen side but may never move it to anatomical right
- never omit, duplicate, or relocate the mark when the face is readable
- long dark-plum hair remains clearly below shoulder to approximately mid-back with the same part/fringe/silhouette

### Joo Hyun-woo
- permanent tattoo coverage/pattern relationships remain on the same anatomical neck/collarbone/shoulder/arm regions
- reverse camera may not mirror the tattoo map between arms
- technical mask body/side hardware/straps remain the same construction
- long black hair remains tied LOW at the nape/back with the same gathered tail/mass

### Mrs. Na
- same pair of square jade earrings
- same analog-watch wrist
- same dark gloves unless the story explicitly removes them
- same silver practical twist construction

### Im Seungjae
- exactly age 30; same-generation peer to Nari
- same medium-brown hair part/silhouette/full youthful hairline
- same smartwatch wrist
- one earbud in each ear when worn

## Face / Hair / Age / Build Identity — Absolute

Expression changes happen on the SAME face.

Reject:
- Nari becoming teenage, doll-like, short-haired, wrong-hair-color, differently proportioned, or a different woman
- Hyun-woo becoming slim, short-haired, small-bun, unmasked/different-mask, differently tattooed, or a different man
- Mrs. Na becoming young, glamorous, frail caricature, witch-like, or losing her mature face/silver twist
- Seungjae appearing older than 30, middle-aged, paternal, executive/professor-like, gray/receding-haired, bearded/stubbled, or resembling Hyun-woo

Lighting, camera closeness, shock, fear, comedy, or romance does not authorize identity recasting.

## Wardrobe / Local-Color Continuity — Absolute

Within one continuous scene, clothing construction and signature local colors remain the same physical items/colors unless a legal cut or scripted wardrobe change explicitly establishes a new state.

Examples:
- Nari: long dark-plum hair, dark graphic hoodie/home wear where established, yellow scrunchie, headphones
- Hyun-woo: matte-black technical mask/top, dark utility trousers, matte-black tattoo map
- Mrs. Na: muted-mauve coat, dark gloves, jade earrings, analog watch
- Seungjae: medium-brown hair and one consistent youthful office-casual outfit for the scene

Lighting may change value/saturation naturally, but it may not change identity hue/material:
- Nari hair does not become pure black/brown/red/neon purple
- yellow scrunchie does not become another color
- Mrs. Na mauve coat/jade earrings do not shift palette between reverse shots
- Hyun-woo tattoos do not become neon/glowing circuitry
- Seungjae hair/outfit does not change construction/color between adjacent views

## Clothing / Body Occlusion Topology — Absolute

Clothing, hair, headphones, bags and straps must wrap/attach to one continuous body.

Reject:
- sleeves attached to the wrong arm
- hoodie/jacket/coat collar cutting through neck/jaw/headphones/hair
- trousers/coat/hoodie folds implying an extra hidden limb
- clothing occlusion used to hide a missing/extra arm or leg
- bag/headphone/mask strap intersecting body in impossible topology
- tattoos visible through opaque clothing
- a detached hand/foot appearing to emerge from clothing with no plausible limb connection

Flat graphic simplification is allowed; broken body topology is not.

## Speaking / Listening / Mouth-State Logic — Absolute

Dialogue ownership must agree with visible acting.

Reject:
- listener visibly mouthing another character's line
- two characters visibly speaking one non-overlapping line simultaneously
- narration/internal thought/device text/smart-speaker audio being acted as human spoken dialogue
- powered voice-only Hyun-woo producing a physical speaking body/mouth
- masked Hyun-woo exposing/redrawing his lower face merely to show speech

Mouth animation is optional. Source ownership must remain unambiguous.

## Character Material Continuity — Matte Only

Skin, hair, cloth, mask, tattoo, jewelry, watches and accessories retain the same flat matte material family across adjacent views.

Reject:
- glossy skin/lips/hair appearing only in close-up
- shiny plastic/metal Hyun-woo mask replacing the matte canonical mask
- luminous/neon tattoo circuitry
- glowing/mirror-chrome jade earrings or watch
- wet/glossy hair without a physical cause
- dramatic local material changes used only to beautify a reaction shot

## Environment Canonical Authority — Absolute

Recurring locations require approved environment canonicals. The exact committed WebP files are geometry/layout authorities, not decorative inspiration.

They control:
- room footprint and relationships
- doors/windows/hallway routes
- fixed furniture placement
- appliance/cabinet locations
- recurring material/color identity
- camera-axis logic and physically possible reverse angles
- relevant normal/blackout/restored lighting states

A strip may simplify background detail for close-ups, but it may not invent a different room layout. If a previous strip drifts from the approved environment canonical, regenerate/correct the drift rather than promoting it.

## Unit 2407 Known Locks

Keep stable:
- entry/foyer route
- TV/living relationship
- dining table/chairs
- kitchen/refrigerator
- lower speaker-storage cabinet
- hallway lamp
- work desk
- pantry
- two-bedroom/bathroom arrangement from approved floor-plan authority
- south-wall relationship where relevant

Establishing panels may be detailed. Dialogue close-ups may simplify backgrounds only after geography is clear.

## Core Object Canonical Authority — Absolute

Recurring plot-critical objects use approved canonical object WebPs. Preserve body proportions, cords/handles/displays, materials, and state vocabulary.

Chapter 1 core objects include:
- smart speaker
- TV
- refrigerator
- Unit 2407 electrical-operation guide
- Unit 2407 brass backup key

The same physical object must remain recognizable across every appearance. Do not promote a generated redesign into canon.

## Supernatural Device Language

Helpful/Hyun-woo communication:
- clean stable cyan-white accent
- no crawling black pixels
- restrained electrical accent
- speaker remains audio hardware; do not print spoken dialogue on its body

Hostile communication family:
- stark broken/doubled white glyphs
- restrained crawling black pixel fragments
- corrupted display edges
- never clean cyan styling

### TV hostile manifestation
TV hostility behaves like a **full-screen signal/broadcast hijack**: broad screen takeover, restrained horizontal sync-tear/scanline disruption, screen-edge digital tearing, broken/doubled white text, black-pixel interference. Effects stay inside/near the screen and do not flood the room with glow.

### Refrigerator hostile manifestation
Refrigerator hostility behaves like an **embedded diagnostic/identity-lock intrusion** in its narrow built-in display: segmented typing/locking progression, doubled broken white glyphs, black pixels crawling from display seams/edges, contained corruption. The whole refrigerator door must not become a giant TV screen.

Both belong to the same hostile family but must remain visually distinguishable.

## Materials — MATTE ONLY UNLESS CANON REQUIRES OTHERWISE

Prefer flat matte differentiated materials: painted wall, muted wood/laminate, brushed metal, cloth, ordinary glass.

Avoid mirror-like TV/fridge/counters/windows, wet-looking floors, excessive glass glare, specular sparkle, bloom, lens flare, gratuitous rim light, or cinematic depth-of-field blur.

## Lighting

Lighting serves story-state readability without cinematic rendering.

Powered apartment: medium-bright neutral practical flat-color baseline with readable walls/furniture.
Day: flat diffuse daylight with restrained practical fill.
Rain/lobby: grounded wet-weather atmosphere through flat value/color changes, not glossy film reflections.
Actual blackout: readable deep-charcoal and muted blue-gray flat shapes; candle is a small local flat amber source only.
After Unit 2407 power return: restore the same normal powered baseline; do not continue blackout rendering.

Light sources must physically exist. No unexplained lighting jump, room-flooding device glow, or decorative dramatic lighting.
Lighting may change values but must preserve character identity colors/materials.

## Composition

Use full-width establishing/reveal art, centered dialogue art, narrow inserts for plugs/notes/keys/watches/device clues, tall portrait/reveal compositions, and borderless art where useful.

Avoid a printed-page grid and equal-size boxes repeated down the strip.
A close-up must preserve enough character/object context to prove body/limb/object ownership when continuity depends on it.

## Final Rejection Gate

Reject a technical strip if:
- character identity drifts
- permanent facial/tattoo/accessory landmark changes anatomical side or disappears
- extra/missing/duplicated limb/body part appears
- close-up limb cannot belong to the same character/body/side
- face/age/build/hair changes between views
- wardrobe/local color/material changes without valid cause
- clothing/accessory occlusion hides impossible anatomy
- visible mouth/acting contradicts dialogue/thought/device/audio ownership
- canonical environment geometry resets
- recurring object design/state drifts
- text becomes unreadable at phone width
- every beat is boxed identically
- gutters become dead filler
- effects obscure story geography
- SFX source is unclear
- TV/refrigerator effect languages are swapped
- helpful/hostile signatures are swapped
- any character, object, or environment becomes photoreal, semi-photoreal, 3D, CGI, glossy, cinematic, painterly, airbrushed, heavily graded, or over-rendered

Style wording alone is never sufficient for approval. Every generated/repaired strip and the final stitched chapter must be visually inspected for actual compliance.
