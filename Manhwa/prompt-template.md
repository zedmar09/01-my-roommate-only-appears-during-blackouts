# Manhwa Scroll Prompt Template

Copy this structure for each future vertical-scroll slice.

```text
Create exactly ONE vertical full-color 2D manhwa scroll slice for "My Roommate Only Appears During Blackouts".

OUTPUT INTENT
This is one slice of a longer stitched vertical-scroll chapter, not a printed comic page. Compose top-to-bottom for phone reading. No circled panel numbers. No fixed page-grid layout.

EXECUTION LOCK
Follow the scripted actions/text literally. Do not invent dialogue, narration, SFX, props, supernatural events, wardrobe changes, time jumps, or location resets.

REFERENCES
- canonical character PNGs for visible characters only
- immediately previous APPROVED manhwa slice when continuity is direct
- `Manhwa/style-guide.md`
- `Manhwa/vertical-scroll-layout-guide.md`
- `Manhwa/lettering-sfx-guide.md`
- source comic chapter only for story/lore/object continuity, never as a fixed layout template

VISUAL STYLE
Polished modern full-color Korean-manwha presentation. Detailed clean 2D line art, controlled character rendering, atmospheric but readable backgrounds, strong value separation, expressive faces/hands, varied panel scale. No photorealism, 3D/CG, plastic gloss, excessive bloom, mirror reflections, or generic AI cinematic effects.

VERTICAL PACING
Use variable gutters. Ordinary dialogue stays relatively tight. Suspense and reveal moments receive larger vertical gaps. Important reveal panels receive more height than routine dialogue panels.

LETTERING
Use exact reader-facing text. White dialogue balloons with clean dark outlines. Narration boxes separate from speech. Device text stays on actual device displays. SFX visually originates from its source.

DEVICE SIGNATURES
Helpful/Hyun-woo: clean stable cyan-white.
Hostile system: broken/doubled stark white + black crawling pixel corruption.
Never swap.

CONTINUITY
State exact incoming positions/objects/lighting from the previous approved slice. Every movement must be readable. No object teleportation.

SLICE BEATS
[Define 5–8 top-to-bottom beats.]

READER-FACING TEXT LOCK
[List exact dialogue/narration/SFX/device text in reading order.]

END-OF-SLICE HANDOFF
[Describe the final character/object/lighting state that the next approved slice must inherit.]

AVOID
No panel numbers, extra UI, brands/logos, filler text, incorrect speaker tails, extra SFX, character identity drift, environment reset, or effects that obscure story clues.
```

## Recommended Beat Count

Prefer 5–8 visually meaningful beats per generated slice.

If a scene needs more than 8 beats, split it into `A/B` slices rather than shrinking panels and lettering.

## Recommended Reveal Pattern

For horror reveal:

`clue/sound → reaction → vertical gap → partial reveal → vertical gap → full reveal → aftershock`

## End Handoff

Every prompt must document the exact ending state so the next slice can continue without guessing.
