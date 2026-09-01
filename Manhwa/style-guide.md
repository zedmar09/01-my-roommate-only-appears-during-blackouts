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
- natural hands and consistent anatomy
- stable project palette
- mobile-first readability

Do **not** make the pipeline richer, more cinematic, more painterly, or more realistic than the approved flat 2D canon.

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

## Characters

Approved canonical character-card WebPs under `Character-References/` are absolute identity authority. A locally generated PNG may be used during generation/QA, but after approval the exact repository WebP is the production attachment authority.

Require adult proportions, clean confident linework, expressive faces/hands, flat matte colors, restrained simple cel shading, readable fabric folds, and stable height/build relationships.

Reject beautification drift, age drift, glamour-model drift, photoreal faces, 3D/CG rendering, plastic/glossy skin or hair, beauty-ad shine, or airbrushed rendering that loses line definition.

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

For every new chapter and new environment, follow the repository environment-reference policy.

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
- two-bedroom/bathroom arrangement from the approved floor-plan authority
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

## Composition

Use full-width establishing/reveal art, centered dialogue art, narrow inserts for plugs/notes/keys/watches/device clues, tall portrait/reveal compositions, and borderless art where useful.

Avoid a printed-page grid and equal-size boxes repeated down the strip.

## Final Rejection Gate

Reject a technical strip if:
- character identity drifts
- canonical environment geometry resets
- recurring object design/state drifts
- text becomes unreadable at phone width
- every beat is boxed identically
- gutters are uniform or become dead filler
- effects obscure story geography
- SFX source is unclear
- TV/refrigerator effect languages are swapped
- helpful/hostile signatures are swapped
- any character, object, or environment becomes photoreal, semi-photoreal, 3D, CGI, glossy, cinematic, painterly, airbrushed, heavily graded, or over-rendered

Style wording alone is never sufficient for approval. Every generated/repaired strip and the final stitched chapter must be visually inspected for actual compliance.
