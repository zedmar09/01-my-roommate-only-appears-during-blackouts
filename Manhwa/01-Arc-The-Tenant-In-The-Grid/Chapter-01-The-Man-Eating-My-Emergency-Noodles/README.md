# Manhwa Chapter 1 — Full Vertical Production

This is the active production package for Chapter 1.

## Chapter Shape

- one continuous reader-visible vertical chapter
- 146 internal read beats (`V01–V146`)
- 32 technical production strips (`001–032`)
- no reader-visible beat/strip/page numbering
- begins with Nari moving into Unit 2407
- ends with the visibly unplugged TV displaying `NEW TENANT CONFIRMED` while Unit 2407 remains powered

Historical P001–P018 mapping is retained only as story shorthand. There is no active page-grid production dependency.

## Reusable Canonical Reference Packs

Environment:
- `../../Environment-References/Unit-2407/`
- `../../Environment-References/Building-Shared-Areas/`

Objects:
- `../../Object-References/smart-speaker-canonical-reference-prompt.md`
- `../../Object-References/tv-canonical-reference-prompt.md`
- `../../Object-References/refrigerator-canonical-reference-prompt.md`
- `../../Object-References/electrical-operation-guide-canonical-reference-prompt.md`
- `../../Object-References/brass-backup-key-canonical-reference-prompt.md`

These references are reusable across later chapters whenever the same location/object returns. Do not create chapter-numbered duplicates.

## Production Authority

Story/current-strip authority for this chapter:
1. current user instruction
2. `chapter-01-continuous-scroll-plan.md`
3. `chapter-01-strip-manifest.md`
4. current `Production-Strips/strip-###-...md`
5. current approved character canonicals
6. approved reusable environment/object canonicals
7. previous approved strip for temporary state/seam continuity

The following global production rules are **always binding on every Chapter 1 strip**, even when an individual strip attachment list does not repeat them:
- `../../style-guide.md`
- `../../lettering-sfx-guide.md`
- `../../seam-continuity-protocol.md`
- `../../vertical-scroll-layout-guide.md`
- `../../generation-workflow.md`
- `../../production-readiness-gate.md`

A strip may make these rules stricter but may never loosen them.

The Chapter 1 Manhwa files are self-contained authority for dialogue, narration, SFX, device text, prop state, event order, movement, power logic, and supernatural rules.

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

If a strip lists a canonical PNG that is missing, stale, or unapproved, stop before generating the strip. Never improvise a replacement and never treat a reference-prompt Markdown file as an approved visual canonical.

Likewise, a prompt-only chapter package cannot be called `PRODUCTION COMPLETE`. Actual strip images and a stitched final chapter are required for visual style, character/object/environment consistency, lettering, dead-space, and seam approval.

## Existing Approved Strip Rule

Creating or improving reusable canonical environment/object packs does not automatically invalidate prior approved artwork. If a prior strip conflicts materially with an approved canonical, flag it for deliberate correction rather than propagating the drift.

## No-Dead-Space Rule

Large vertical spacing must perform a real story function. Do not leave giant empty tails and do not invent filler text/SFX. Expand existing art, canonical environment, action/reaction, or atmosphere instead.

## Audit Rule

After every correction, re-audit the corrected scope and adjacent dependencies. After all corrections, run a fresh clean-room audit from Strip 001 through Strip 032; do not inherit earlier PASS labels without rechecking the current state.