# Chapter 1 Continuous Manhwa Generation Checklist

Status: **PILOT / ONE-CONTINUOUS-SCROLL FORMAT**

## Absolute Format Gate

- Chapter 1 is one continuous vertical scroll.
- Working width is 1080 px.
- Final publishing width is 800 px.
- Technical strips are not separate pages or scroll episodes.
- No circled panel numbers.
- No page numbers.
- No repeated chapter title inside the body.
- No visible strip seam.
- No fixed comic-page grid.

Automatic reject if a generated strip looks like a self-contained printed page with a top/bottom page composition.

## Technical Strip Gate

Every `strip-###`:
- same exact 1080 px width
- height may vary
- may use a small continuity overlap at top
- overlap is cropped during stitch
- ends only in a safe gutter or completed low-information beat
- never cuts a balloon, face, important hand action, SFX, or screen text
- contains no strip label in artwork

## Character References

Attach only visible canonical characters:
- Nari: `Character-References/nari-canonical-flat2d.png`
- Mrs. Na: `Character-References/mrs-na-canonical-flat2d.png`
- Seungjae: `Character-References/seungjae-canonical-flat2d.png`
- Hyun-woo: `Character-References/hyunwoo-canonical-flat2d.png` only when physically visible

Do not attach Hyun-woo during voice-only/powered states unless a specific prompt explicitly requires it.

## Story Continuity Gate

Use the approved Chapter 1 source story as authority for:
- event order
- dialogue meaning/text
- time/location
- power state
- who is physically present
- apartment geography
- prop inventory and movement
- helpful vs hostile device signatures

The manhwa adaptation may recompose panel count/camera/gutters but may not create teleportation or change lore.

## One-Scroll Composition Gate

Require:
- varied panel widths
- full-width establishing/reveal art where earned
- centered medium dialogue panels
- narrow clue inserts used sparingly
- vertical negative space used intentionally
- no mechanical equal spacing
- no multi-column newspaper layout

## Lettering Gate

- mobile readable after 1080 → 800 uniform scale
- correct speaker tails
- narration visually distinct
- device text on the actual device
- no fake UI filler
- no brands/logos
- SFX at exact source

## SFX Gate

Quiet local SFX stay restrained.
Medium action/electrical SFX integrate into the art.
Major impact SFX may cross panel edges when readable.

Do not invent filler sounds.

## Visual Style Gate

Require:
- polished original 2D Korean-webtoon rendering
- canonical identities
- controlled cel/soft-cel shadows
- detailed establishing environments
- matte surfaces
- readable lighting

Reject:
- photoreal
- 3D/CG
- glossy plastic hair/skin
- mirror-like surfaces
- bloom-heavy cinematic rendering
- excessive blur
- copied compositions from the reference title

## Chapter-Specific Reveal Gate

Give extra vertical breathing room before:
- `YOU COULD SAY PLEASE.`
- unplugged TV still active
- handwritten reply
- blackout
- `SLURP`
- physical Hyun-woo reveal
- `YOON NARI`
- `IDENTITY LOCKING`
- Hyun-woo absence after power return
- unplugged speaker talking again
- `NEW TENANT CONFIRMED`

## Blackout Background Gate

Before actual outage: keep reader background light/neutral.
During actual outage: transition into charcoal/black continuous background.
Do not switch to black merely for random drama.
Return toward light background only after power/reality stabilizes.

## Assembly Gate

After stitching approved strips:
- exactly one continuous 1080 px master
- no doubled overlap
- no accidental missing pixels/gutter jump
- no seam color mismatch
- no duplicated dialogue/SFX
- no width mismatch
- no artificial blank band at strip boundaries

Then uniformly resize the complete master to 800 px width.

If platform upload requires multiple files, cut the finished 800 px master into same-width blocks with no added space. These are delivery files only.

## Pilot Approval

First assemble technical strips 001–003 into one continuous top-of-chapter sample.

Approve based on the **stitched result**:
- does it read as one webtoon chapter?
- are gutters natural?
- does text read on mobile?
- do panel widths vary naturally?
- does the apartment remain continuous?
- are strip seams invisible?

Only after this passes should the rest of Chapter 1 be generated.
