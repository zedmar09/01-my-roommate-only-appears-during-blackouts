# Chapter 1 — 32 Technical Strip Manifest

Strip IDs are production-only. The final reader sees one continuous chapter.

## Audit Status

**Fresh `manhwa-2d-production-auditor` re-audit confirms the 32-strip story/script/dialogue/SFX/movement/object/power/seam design remains coherent. Approved Chapter 1 character, environment, and object WebP authorities are present. The active pre-strip blocker is exact Markdown reference migration: every strip must point to the real current `.webp` path/basename instead of obsolete PNG or shorthand-only names. Rendered Strip 001–032 artwork remains ungenerated, so final visual/stitch gates are still pending.**

## Strip Map

| Strip | Read beats | Historical map | Main purpose | Seam OUT |
|---:|---|---|---|---|
| 001 | V01–V07 | P1 | move-in / smart-home / speaker welcome | G |
| 002 | V08–V11 | P2 | Mrs. Na arrival / binder-key setup | G |
| 003 | V12–V15 | P2 | hallway-light / phone-tablet rule | A/G |
| 004 | V16–V20 | P2–P3 | outage warning → one-week automation | G |
| 005 | V21–V25 | P3 | first natural male voice | G |
| 006 | V26–V30 | P3–P4 | speaker unplug → unplugged TV proof | A |
| 007 | V31–V35 | P4–P5 | TV warning → hostile fridge → key route | G |
| 008 | V36–V40 | P5 | speaker hidden / paper test / pen movement | G |
| 009 | V41–V45 | P5–P6 | reply / photo failures / tablet freeze | A/E |
| 010 | V46–V50 | P6 | digital warning / binder clue / Mrs. Na texts | G |
| 011 | V51–V54 | P7 | blackout kit / apartment prep | G |
| 012 | V55–V59 | P8 | Seungjae invitation / phone dies | A |
| 013 | V60–V64 | P8 | devices fail / tablet warning / elevator split | G |
| 014 | V65–V67 | P9 | 12:43 outage / citywide confirmation | E |
| 015 | V68–V70 | P9 | no-screen choice / failed tools / listen | E/G |
| 016 | V71–V75 | P10 | first SLURP / knife draw / approach / teaser | A/E |
| 017 | V76–V80 | P10–P11 | hidden eater / first exchange | A/G |
| 018 | V81–V84 | P11 | screen admission / mask / name reveal | G |
| 019 | V85–V89 | P12 | entry interrogation / one step / pantry | A/G |
| 020 | V90–V93 | P12–P13 | Mrs. Na admission / hostile start / rise | A |
| 021 | V94–V97 | P13 | protective crossing / `YOON NARI` | E |
| 022 | V98–V102 | P14 | candle order / `IDENTITY LOCKING` / blue center | A/E |
| 023 | V103–V107 | P14 | candle out / shriek / knife drop / wrist catch | G |
| 024 | V108–V112 | P15 | separate hostile actor | G/E |
| 025 | V113–V118 | P15 | city return / unit power / Hyun-woo absent | G |
| 026 | V119–V123 | P16 | door/history/camera/security evidence | G |
| 027 | V124–V127 | P16 | voicemail / cabinet chimes | A/G |
| 028 | V128–V132 | P17 | speaker reveal / borrowed power / knife retrieval | A |
| 029 | V133–V137 | P17 | sheath knife / food / paper warning | G |
| 030 | V138–V142 | P18 | missing-section silence / danger / notebook route | G |
| 031 | V143–V145 | P18 | bug report / TV activation | A/E |
| 032 | V146 | P18 | `NEW TENANT CONFIRMED` final reveal | END |

## Reference Authority

For every strip: current user instruction > script/current strip > approved current character WebP > approved environment WebP > approved object WebP > previous approved rendered strip temporary state.

The binding global visual/lettering/seam rules under `Manhwa/` always apply. A strip may be stricter but may never loosen them.

## Repository Image Format Rule

Reference prompts may generate PNG first locally. After approval, manually convert to WebP. Production Markdown uses the committed WebP only.

## Chapter 1 Character WebPs

- `C-NARI` = `Character-References/nari-canonical-flat2d.webp`
- `C-HYUNWOO` = `Character-References/hyunwoo-canonical-flat2d.webp`
- `C-MRSNA` = `Character-References/mrs-na-canonical-flat2d.webp`
- `C-SEUNGJAE` = `Character-References/seungjae-canonical-flat2d.webp`

Nari's current authority is the long dark-plum-haired adult design. Seungjae is exactly 30, same age as Nari.

## Reuse Rule — Absolute

References belong to physical people/locations/objects, not chapters. Reuse Unit 2407, Building Shared Areas, smart speaker, TV, refrigerator, electrical-operation guide, and brass backup key WebPs in future chapters whenever they return.

## Reusable Reference Shorthand — Exact Current Files

Unit 2407:
- `U-FP` = `Manhwa/Environment-References/Unit-2407/unit-2407-floor-plan-reference.webp`
- `U-ATLAS` = `Manhwa/Environment-References/Unit-2407/unit-2407-room-angle-atlas-reference.webp`
- `U-ENTRY` = `Manhwa/Environment-References/Unit-2407/unit-2407-entry-living-wide-reference.webp`
- `U-L2K` = `Manhwa/Environment-References/Unit-2407/unit-2407-living-to-kitchen-wide-reference.webp`
- `U-K2L` = `Manhwa/Environment-References/Unit-2407/unit-2407-kitchen-to-living-wide-reference.webp`
- `U-HALL` = `Manhwa/Environment-References/Unit-2407/unit-2407-hallway-reference.webp`
- `U-DESK` = `Manhwa/Environment-References/Unit-2407/unit-2407-desk-zone-detail-reference.webp`
- `U-FRIDGE` = `Manhwa/Environment-References/Unit-2407/unit-2407-fridge-cabinet-zone-detail-reference.webp`
- `U-LIGHT` = `Manhwa/Environment-References/Unit-2407/unit-2407-lighting-state-sheet-reference.webp`

Building:
- `B-ENTRY` = `Manhwa/Environment-References/Building-Shared-Areas/rainy-building-entrance-reference.webp`
- `B-LOBBY` = `Manhwa/Environment-References/Building-Shared-Areas/building-lobby-elevator-reference.webp`

Objects:
- `O-SPK` = `Manhwa/Object-References/smart-speaker-canonical-reference.webp`
- `O-TV` = `Manhwa/Object-References/tv-canonical-reference.webp`
- `O-FRIDGE` = `Manhwa/Object-References/refrigerator-canonical-reference.webp`
- `O-MANUAL` = `Manhwa/Object-References/electrical-operation-guide-canonical-reference.webp`
- `O-KEY` = `Manhwa/Object-References/brass-backup-key-canonical-reference.webp`

## Required-Asset Gate — Absolute

The shorthand above maps to **current approved WebP authorities**. Individual strip prompts must still repeat the exact full WebP paths rather than relying on shorthand alone.

If any required WebP is missing, stale, wrong-path, or later rejected, stop before strip generation. Do not substitute its Markdown prompt or improvise a replacement.

## Strip Attachment Audit Map

| Strip | Character | Environment | Object |
|---:|---|---|---|
| 001 | C-NARI | U-FP,U-ENTRY,U-L2K | O-SPK |
| 002 | C-NARI,C-MRSNA | U-FP,U-ENTRY,U-L2K,U-HALL | O-MANUAL,O-KEY |
| 003 | C-NARI,C-MRSNA | U-FP,U-L2K,U-HALL | O-MANUAL,O-KEY |
| 004 | C-NARI,C-MRSNA | U-FP,U-ENTRY,U-L2K,U-HALL | O-MANUAL,O-KEY |
| 005 | C-NARI | U-FP,U-L2K,U-K2L | O-SPK |
| 006 | C-NARI | U-FP,U-L2K,U-K2L | O-SPK,O-TV |
| 007 | C-NARI | U-FP,U-L2K,U-K2L,U-FRIDGE | O-TV,O-FRIDGE,O-KEY |
| 008 | C-NARI | U-FP,U-FRIDGE,U-L2K | O-SPK |
| 009 | C-NARI | U-FP,U-FRIDGE,U-DESK | — |
| 010 | C-NARI | U-FP,U-L2K,U-DESK,U-HALL | O-MANUAL |
| 011 | C-NARI | U-FP,U-FRIDGE,U-DESK | — |
| 012 | C-NARI,C-SEUNGJAE | B-ENTRY,B-LOBBY | — |
| 013 | C-NARI,C-SEUNGJAE | B-LOBBY | — |
| 014 | C-NARI | U-FP,U-DESK,U-HALL,U-LIGHT | — |
| 015 | C-NARI | U-FP,U-DESK,U-LIGHT | — |
| 016 | C-NARI,C-HYUNWOO | U-FP,U-DESK,U-HALL,U-L2K,U-LIGHT | — |
| 017–019 | C-NARI,C-HYUNWOO | U-FP,U-L2K,U-K2L,U-FRIDGE,U-LIGHT | — |
| 020–025 | C-NARI,C-HYUNWOO | U-FP,U-L2K,U-K2L,U-FRIDGE,U-LIGHT | O-FRIDGE |
| 026 | C-NARI | U-FP,U-DESK,U-ENTRY,U-LIGHT | O-KEY |
| 027 | C-NARI | U-FP,U-ENTRY,U-FRIDGE,U-LIGHT | — |
| 028 | C-NARI | U-FP,U-FRIDGE,U-DESK,U-K2L,U-LIGHT | O-SPK |
| 029 | C-NARI | U-FP,U-FRIDGE,U-DESK,U-L2K,U-LIGHT | O-SPK |
| 030 | C-NARI | U-FP,U-DESK,U-L2K,U-LIGHT | O-SPK |
| 031 | C-NARI | U-FP,U-L2K,U-K2L,U-DESK,U-LIGHT | O-TV |
| 032 | C-NARI | U-FP,U-L2K,U-K2L,U-LIGHT | O-TV |

Every individual strip file repeats its exact visual attachment list. `U-ATLAS` is additionally required only when an intended camera angle is not sufficiently covered by the listed primary environment views.

## Black Read-Slice Rule

Every distinct vertical slice: small black gutter.
Two distinct shots sharing a row: diagonal/slanted black divider.
Time/location cut: stronger but compact black separator.
A/E technical file seam with continuing art/effect: NO visible black technical bar.
Never use black spacing as purposeless filler.

## Critical Continuity Seams

- 012→013 same lobby route; no external black seam
- 014→015→016 continuous blackout field
- 016→017 exact teaser→hidden-eater geometry
- 017→018 same cautious distance
- 019→020→021 Nari closer position + chair state + fridge geometry
- 020→021 chair rise→walk, no teleport
- 021→022→023 hostile fridge/candle/action chain
- 023→024 preserve post-candle-reach geometry and wrist/knife state
- 024→025 city returns before Unit 2407
- 025→026 powered baseline begins
- 027→028 cabinet source/approach
- 028→029 knife route to desk sheath
- 031→032 same unplugged TV activation

## Strict Flat 2D Human-Drawn Rule — Absolute

All rendered strip pixels must comply with `Manhwa/style-guide.md`. Flat human-drawn appearance outranks prior-strip style drift. Prompt wording alone does not pass this visual gate.

## No-Dead-Space Rule

Small black gutters are deliberate slice grammar. Huge unused black/white/neutral areas are failures. Never invent filler text/SFX.

## Completion Rule

This manifest validates planned coverage and dependencies. It cannot by itself prove visual production complete. Final approval requires every current strip prompt to resolve to the exact approved WebPs, rendered Strip 001–032 artwork, sequential visual QA, stitch/seam QA, and a fresh clean-room final audit.

Current pre-strip blocker: **exact WebP path migration in active Markdown**. After that passes, Chapter 1 is ready for sequential Strip 001 generation, but not `PRODUCTION COMPLETE`.
