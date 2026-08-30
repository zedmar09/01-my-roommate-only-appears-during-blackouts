# Manhwa Generation Workflow

## Separation From Comics Production

`Comics/` and `Manhwa/` are separate presentation pipelines.

Do not overwrite comic-page prompts, approved comic PNGs, or comic audits when testing the manhwa conversion.

Story/lore canon may be read from `Comics/`, but manhwa composition/pacing comes from this directory.

## Slice Workflow

1. Read the current manhwa slice prompt.
2. Attach only the canonical character PNGs required for visible characters.
3. Attach the immediately previous APPROVED manhwa slice when continuity is direct.
4. Generate one vertical-scroll slice.
5. QA the slice before using it downstream.
6. Reject and regenerate if continuity, script, lettering, SFX, character identity, or visual style is wrong.
7. Only approved slice N becomes visual continuity reference for slice N+1.
8. Stitch approved slices only after all slices in the chapter pass QA.

## Canonical Character Attachments — Chapter 1

Use only visible-character references.

- Nari: `Character-References/nari-canonical-flat2d.png`
- Mrs. Na: `Character-References/mrs-na-canonical-flat2d.png`
- Seungjae: `Character-References/seungjae-canonical-flat2d.png`
- Hyun-woo: `Character-References/hyunwoo-canonical-flat2d.png` only on slices where he is physically visible

When Hyun-woo is voice-only after power returns, do not attach his PNG unless a prompt specifically needs an off-panel identity continuity reminder; default is **do not attach** to reduce accidental physical manifestation.

## Previous-Slice Continuity Rule

The previous approved manhwa slice controls:
- current wardrobe
- current hairstyle state
- current prop positions
- open/closed doors/cabinets
- appliance locations
- lighting state
- character side of doorway/table
- damage/mess/evidence

It does **not** force:
- identical camera angle
- identical panel proportions
- identical crop
- identical pose when the script requires movement

## Source Comic Usage

The source comic chapter and prompts are story/continuity references, not layout templates.

Do not recreate the old printed-page grid inside the manhwa slice.

If a source comic image is attached for a difficult environment/object handoff, use it only to preserve the apartment/object reality. Recompose it for vertical scroll.

## QA Gates

### Script
- all dialogue/narration/device text exact
- no missing lines
- no invented lines
- correct source/speaker

### Character
- canonical identity preserved
- correct visible cast only
- no accidental physical Hyun-woo during powered states

### Environment
- Unit 2407 layout remains coherent
- props do not teleport
- door/cabinet/screen state follows previous approved slice

### Vertical pacing
- no fixed comic-page grid
- gutters vary intentionally
- major reveal has enough scroll space
- no panel numbers

### Lettering
- mobile-readable
- balloon tails correct
- device text on device
- SFX source aligned

### Visual style
- polished 2D manhwa
- not photoreal/3D/glossy
- characters not over-rendered into a different series

## Pilot Approval

Do not produce all Chapter 1 manhwa slices before the pilot is approved.

Pilot slices:
1. move-in / smart-home hook
2. Mrs. Na's warning
3. smart speaker answers back

After those three are visually approved, lock:
- character rendering density
- line weight
- shadow softness
- gutter scale
- bubble design
- narration-box design
- SFX font treatment
- device-text treatment

Then expand the remaining Chapter 1 prompts using the locked pilot as style authority.
