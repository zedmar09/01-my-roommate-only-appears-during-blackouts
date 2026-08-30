# Continuous Manhwa Technical-Strip Prompt Template

Use this template only when the entire chapter cannot be generated as one enormous image.

```text
Create exactly ONE technical image strip that belongs inside a SINGLE CONTINUOUS vertical manhwa chapter for "My Roommate Only Appears During Blackouts".

IMPORTANT FORMAT
This is NOT a page, NOT a separate scroll episode, and NOT a mini-chapter.
It is one same-width segment of a longer stitched Chapter 1 reader.
No strip title, no page number, no circled panel numbers, no ending card.

CANVAS
Working width: 1080 px.
Use the full fixed width consistently with the previous approved strip.
Height may be as tall as the generation tool safely permits.
The final stitched chapter will be uniformly reduced to 800 px width.

CONTINUITY REFERENCES
Attach only visible-character canonical PNGs.
Attach the immediately previous APPROVED technical strip when this scene directly continues.
The previous strip controls environment/object/wardrobe/power state, but not camera angle.

STYLE
Original polished full-color Korean webtoon/manhwa rendering:
- clean 2D linework
- controlled cel/soft-cel shadows
- detailed establishing backgrounds
- mobile-readable faces/hands
- matte materials
- no photorealism, 3D/CG, glossy plastic skin/hair, bloom-heavy cinematic treatment, or mirror-like surfaces

ONE-SCROLL COMPOSITION
Compose naturally top-to-bottom.
Mix full-width art, centered dialogue panels, narrow clue inserts, and vertical negative space.
Do not arrange the strip like a printed comic page.
Do not make gutters mechanically equal.

TOP HANDOFF
If continuing from an approved strip, preserve a small continuity overlap/background handoff at the very top so stitching can be checked. This duplicate area will be cropped during final assembly.

STORY BEATS
[INSERT ONLY THE STORY BEATS COVERED BY THIS TECHNICAL STRIP]

READER-FACING TEXT LOCK
[INSERT EXACT DIALOGUE / NARRATION / DEVICE TEXT / SFX]

LETTERING
White clean speech balloons with correct tails.
Simple high-contrast narration boxes.
SFX integrated beside exact source.
Helpful device text clean cyan-white.
Hostile device text broken stark-white + black pixel corruption.

BOTTOM HANDOFF
End in a natural low-information gutter or stable completed beat that can continue immediately into the next strip.
Do not add a reader-visible ending.
Do not repeat chapter title.
Do not create a large artificial blank gap solely because the technical strip ends.

REJECTION
Reject if it looks like a standalone comic page, contains panel numbers, changes width, resets the environment, shrinks text, duplicates dialogue, adds fake branding, or creates a visible technical boundary.
```

## Naming

Use:
`strip-001-...-chatgpt-image-prompt.md`
`strip-002-...-chatgpt-image-prompt.md`

The `strip-###` label is production-only and must never appear inside final artwork.
