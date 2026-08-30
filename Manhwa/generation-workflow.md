# Manhwa Generation Workflow — One Continuous Chapter

## Separation From Comics

`Comics/` and `Manhwa/` are separate presentation pipelines.

Do not overwrite approved comic prompts/art while testing the manhwa conversion. Story/lore canon may be read from `Comics/`; manhwa layout/pacing comes from this directory.

## Final Product

The final product is **one continuous Chapter 1 vertical scroll**.

Technical strips exist only because image-generation tools and websites cannot always handle one enormous canvas.

## Generation Loop

For each technical strip:
1. read the chapter continuous-scroll plan
2. read the current strip prompt
3. attach only canonical PNGs for characters visible in that strip
4. attach the immediately previous APPROVED technical strip when continuity is direct
5. generate at the fixed 1080 px working width
6. preserve a small top continuity overlap when needed
7. QA script, identity, environment, lighting, SFX, lettering, and one-scroll rhythm
8. approve or regenerate
9. crop duplicated overlap during assembly
10. append approved strip directly beneath the previous strip with no inserted border/gap beyond the story's intended gutter

## Technical Strips Are Not Story Units

Never describe the final chapter to the reader as 12 scrolls or 20 pages.

`strip-001`, `strip-002`, etc. are internal production assets only.

A strip may contain several panels and may end anywhere that a natural empty gutter allows. If a story beat needs more space, extend the strip or move the technical cut; never compress the art just to hit a predetermined strip count.

## Fixed Geometry

- generation/compositing width: 1080 px
- final publishing width: 800 px
- all strips identical width
- strip heights may vary
- final chapter is uniformly downscaled after stitching

Never resize individual strips independently.

## Character Attachments — Chapter 1

- Nari: `Character-References/nari-canonical-flat2d.png`
- Mrs. Na: `Character-References/mrs-na-canonical-flat2d.png`
- Seungjae: `Character-References/seungjae-canonical-flat2d.png`
- Hyun-woo: `Character-References/hyunwoo-canonical-flat2d.png` only when physically visible

When Hyun-woo is voice-only, default to not attaching his PNG to reduce accidental manifestation.

## Previous-Strip Continuity

The previous approved strip controls:
- current wardrobe
- hairstyle state
- prop positions
- open/closed doors/cabinets
- appliance locations
- lighting/power state
- character position at handoff
- damage/mess/evidence

It does not force the same camera angle or panel proportions.

## Source Comic Usage

Source comic pages are story/object continuity authority, not manhwa layout templates.

Do not paste or imitate the old page grid. Recompose each scene for continuous vertical pacing.

## Assembly Workflow

After all strips pass QA:
1. stitch at 1080 px width
2. remove duplicated continuity overlaps
3. inspect every seam at 100% zoom
4. verify continuous background/gutter color
5. verify no dialogue/SFX duplicated or lost
6. export one long master image if tooling permits
7. uniformly downscale master to 800 px width
8. if the reader/platform requires multiple upload images, cut the finished master into same-width sequential WebP/PNG blocks
9. add **zero extra spacing** between delivery blocks

The reader must perceive one continuous chapter.

## Pilot Test

Generate only the top three technical strips first. Stitch them together immediately and evaluate the **assembled continuous section**, not each strip as if it were a separate page.

Lock after pilot approval:
- line weight
- rendering density
- shadow treatment
- fixed width
- gutter rhythm
- balloon design
- narration design
- SFX treatment
- device-text treatment
- strip seam behavior

Then continue the same chapter downward.
