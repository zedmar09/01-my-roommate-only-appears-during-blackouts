# Manhwa Generation Workflow

## Pilot Isolation

`Comics/` remains untouched and authoritative during this test.

Manhwa Chapter 1 adapts source Comic Chapter 1 Pages **001–018** as one continuous vertical chapter.

## Fixed Chapter Plan

- 1 continuous reader-visible chapter
- 146 internal read beats (`V01`–`V146`), never printed
- 32 technical strips (`strip-001`–`strip-032`), never printed
- one fixed width across all generated strips
- Strips 001–015 = source Pages 001–009
- Strips 016–032 = source Pages 010–018

## Sequential Production

1. Read the current strip prompt.
2. Attach only canonical PNGs for characters physically visible in that strip.
3. For Strip 002 onward, attach the immediately previous APPROVED manhwa strip.
4. Generate one tall vertical technical strip using the available canvas efficiently.
5. QA exact script, identity, environment, vertical pacing, seam type, lettering, SFX, power state, and style.
6. QA the bottom 20–25% specifically for dead/unused canvas.
7. Reject/regenerate before proceeding if any mandatory item fails.
8. Only an APPROVED Strip N becomes continuity authority for Strip N+1.
9. After Strip 032 passes, stitch all approved strips in order.
10. Crop intentional overlap regions only during final assembly.
11. Run one seam-by-seam full-chapter QA.
12. Uniformly resize the completed master for publishing.

## Character Reference Map

- Nari: `Character-References/nari-canonical-flat2d.png`
- Mrs. Na: `Character-References/mrs-na-canonical-flat2d.png`
- Seungjae: `Character-References/seungjae-canonical-flat2d.png`
- Hyun-woo: `Character-References/hyunwoo-canonical-flat2d.png`

Attachment rule by strip:
- 001: Nari
- 002–004: Nari + Mrs. Na
- 005–011: Nari
- 012–013: Nari + Seungjae
- 014–016: Nari
- 017–025: Nari + Hyun-woo because he is physically visible during the blackout sequence
- 026–032: Nari only

For Strips 028–030, Hyun-woo is voice-only through the unplugged speaker. Do NOT attach his canonical PNG there; this reduces the risk of an accidental physical appearance while Unit 2407 is powered.

## Power-State Production Lock

- Strips 014–025 include the citywide/Unit 2407 outage sequence.
- Hyun-woo is physical only while Unit 2407 itself lacks ordinary supplied power.
- Strip 025 restores Unit 2407 power and then shows Hyun-woo simply absent; never show a visible dissolution process.
- Strips 026–032 are normally powered present-time scenes. Do not carry blackout lighting forward.

## Source Comic Usage

Use source Comic Pages 001–018 as exact story/script/prop-rule authority, not as page-layout templates.

Do not recreate the old page grids. Recompose the approved events into continuous scroll pacing while preserving exact reader-facing wording, speaker/source ownership, event order, character knowledge, object state, and supernatural rules.

## No-Dead-Bottom Rule — Absolute

Reject any strip with a huge unused white/neutral/black tail that has no narrative function.

Allowed vertical space must clearly function as one of:
- existing narration/time transition
- meaningful silence/hesitation
- reveal delay
- existing scripted SFX beat
- reaction hold
- environmental/atmospheric continuation
- controlled seam transition

Do NOT invent filler captions, dialogue, or sounds to fill space. If the scripted story ends early in the canvas, enlarge/recompose existing art, reaction, room geography, darkness/rain/effect field, or use only a compact seam buffer.

Also reject a double-gap seam where Strip N ends with excessive emptiness and Strip N+1 starts with another excessive empty area.

## Automatic Reject Rules

Reject for:
- wrong/missing source text
- invented dialogue/SFX/narration
- wrong speaker/source
- canonical identity drift
- physical Hyun-woo while Unit 2407 is powered
- missing Hyun-woo when the blackout script physically shows him
- apartment geography reset
- missing/moved continuity prop without scripted action
- visible strip label/beat/page number
- uniform printed-page grid
- obvious seam or double blank seam
- text split at seam
- helpful/hostile device signature swapped
- wrong current power/lighting state
- huge purposeless bottom whitespace
- glossy/photoreal/3D rendering
