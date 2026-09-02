# Manhwa Chapter 1 — Full Vertical Production

This is the active production package for Chapter 1.

Current prompt/reference status: **FIFTH FULL HARDENED PREPRODUCTION GATE PASS — READY TO RETEST FROM STRIP 001 — NOT PRODUCTION COMPLETE.**

The current Strip 001–032 package has been clean-room re-audited five times under `manhwa-2d-production-auditor`. Earlier PASS labels and earlier problematic renders are not accepted as current proof.

## Chapter Shape

- one continuous reader-visible vertical chapter
- 146 internal read beats (`V01–V146`)
- 32 technical production strips (`001–032`)
- no reader-visible beat/strip/page numbering
- begins with Nari moving into Unit 2407
- ends with the visibly unplugged TV displaying `NEW TENANT CONFIRMED` while Unit 2407 remains powered

Historical P001–P018 mapping is retained only as story shorthand. There is no active page-grid production dependency.

## Approved Reusable Visual Authorities

### Character WebPs
- `Character-References/nari-canonical-flat2d.webp`
- `Character-References/hyunwoo-canonical-flat2d.webp`
- `Character-References/mrs-na-canonical-flat2d.webp`
- `Character-References/seungjae-canonical-flat2d.webp`

### Environment WebP packs
- `../../Environment-References/Unit-2407/`
- `../../Environment-References/Building-Shared-Areas/`

Every strip must attach the exact `.webp` filenames listed in its own prompt; directory names alone are not sufficient in a production thread.

### Object WebPs
- `../../Object-References/smart-speaker-canonical-reference.webp`
- `../../Object-References/tv-canonical-reference.webp`
- `../../Object-References/refrigerator-canonical-reference.webp`
- `../../Object-References/electrical-operation-guide-canonical-reference.webp`
- `../../Object-References/brass-backup-key-canonical-reference.webp`

These references are reusable across later chapters whenever the same location/object returns. Do not create chapter-numbered duplicates.

Image/reference prompts may still generate PNG first locally. The repository production authority after approval is the manually converted WebP.

## Production Authority

Story/current-strip authority for this chapter:
1. current user instruction
2. `chapter-01-continuous-scroll-plan.md`
3. `chapter-01-strip-manifest.md`
4. current `Production-Strips/strip-###-...md`
5. current approved character WebPs
6. approved reusable environment/object WebPs
7. previous approved rendered strip for temporary state/seam continuity only
8. canon-compatible derived micro-detail for chapter continuity only

Previous strip and derived micro-detail never override permanent canonical WebPs.

The following global production rules are **always binding on every Chapter 1 strip**, even when an individual strip attachment list does not repeat them:
- `../../style-guide.md`
- `../../lettering-sfx-guide.md`
- `../../seam-continuity-protocol.md`
- `../../vertical-scroll-layout-guide.md`
- `../../generation-workflow.md`
- `../../production-readiness-gate.md`

A strip may make these rules stricter but may never loosen them.

The Chapter 1 Manhwa files are self-contained authority for dialogue, narration, SFX, device text, prop state, event order, movement, power logic, and supernatural rules.

## Fifth-Pass Production Locks

The current package additionally blocks:
- close-up/inset views creating duplicate physical objects or incompatible same-moment states
- reader text/SFX hiding continuity-critical physical action proof
- legal time cuts erasing story-critical evidence
- contradictory physical alternatives for one action
- reverse-shot hand/foot/wrist/shoulder/pocket side swaps
- worn accessories disappearing or switching body location without visible action
- unexplained source/route for paper, pen, phone, packet, chopsticks, knife, notebook, or other recurring evidence
- floor routes disturbing persistent packet/knife evidence
- derived outlet/storage details overriding canonical environment geometry
- final table props overlapping/resetting when notebook/pen are introduced

Production-only temporary names such as `KNIFE HAND`, `PHONE HAND`, `SCRUNCHIE WRIST`, `STEP FOOT`, `CANDLE FOOT`, `BAG SHOULDER`, `PHONE POCKET`, and `NOTEBOOK ZONE` are audit instructions only and must never appear in reader-facing art.

## Strict Flat 2D Human-Drawn Style — Absolute

Every Chapter 1 canonical, strip, repair, and stitched output must visibly comply with `../../style-guide.md`:
- strict flat 2D human-drawn Korean manhwa/webtoon appearance
- clean intentional line art
- flat colors
- restrained simple hard-edged cel shading only
- matte characters, materials, architecture, appliances, screens, and props
- stable canonical anatomy/proportions and natural hands
- no photoreal/semi-photoreal, 3D/CGI/game-render, glossy/plastic/wet, painterly, airbrushed, cinematic, depth-of-field, bloom, lens-flare, excessive rim-light, mirror-reflection, or over-rendered AI-polished drift

Prompt wording alone does not pass this gate; rendered output must be visually inspected.

## Required-Asset Blocking Rule

If a strip lists a canonical WebP that is missing, stale, wrong-path, or unapproved, stop before generating the strip. Never improvise a replacement and never treat a reference-prompt Markdown file as an approved visual canonical.

The approved Chapter 1 character/environment/object WebPs are currently present. The next remaining production gate is sequential rendered Strip 001–032 generation and visual QA.

A prompt/reference-ready chapter cannot be called `PRODUCTION COMPLETE`. Actual strip images and a stitched final chapter are required for visual style, character/object/environment consistency, lettering, dead-space, and seam approval.

## Existing Approved Strip Rule

A previous strip becomes continuity authority only after it passes the **current fifth-pass visual QA**. Earlier rejected/pre-fifth renders must not be attached merely because they already exist.

Previous-strip temporary state can never override permanent canonical identity, architecture, or recurring object construction.

## No-Dead-Space Rule

Large vertical spacing must perform a real story function. Do not leave giant empty tails and do not invent filler text/SFX. Expand existing art, canonical environment, action/reaction, or atmosphere instead.

## Audit Rule

After every correction, re-audit the corrected scope and adjacent dependencies. After all corrections, run a fresh clean-room audit from Strip 001 through Strip 032; do not inherit earlier PASS labels without rechecking the current state.

## Current Next Action

1. generate a brand-new Strip 001 using its current fifth-pass prompt + exact approved WebPs
2. deep-audit the actual pixels against all current gates
3. reject/fix/regenerate until Strip 001 passes
4. only then attach that newly APPROVED Strip 001 to Strip 002
5. continue sequentially through Strip 032
6. stitch and run a fresh final visual clean-room audit
