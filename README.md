# My Roommate Only Appears During Blackouts

Genre: Supernatural Romantic Comedy / Modern Mystery / Urban Fantasy / Korean Manhwa

## Premise

Yoon Nari, an exhausted game designer, rents an unusually cheap smart apartment in a Seoul high-rise. The landlord gives her one unnerving rule: keep a mains-powered apartment light on after midnight, and if the power goes out, keep the screens dark.

During a citywide blackout Nari discovers a tall masked man eating her emergency noodles at the dining table. He calls himself Hyun-woo. No lease, camera record, or building log can prove he exists, and he becomes physically present only while Unit 2407 itself has lost ordinary supplied power.

The story mixes smart-home comedy, adult romance, electrical horror, missing records, and an urban-fantasy mystery about why the city seems to be forgetting someone on purpose.

## Production Format — Manhwa Only

The active visual-production pipeline is now `Manhwa/` only.

The former top-level `Comics/` manga/page-production directory has been retired and removed from active production.

Current Chapter 1:
- one continuous vertical chapter
- 146 internal read beats
- 32 technical production strips
- no reader-visible page/strip numbering
- full story from move-in through `NEW TENANT CONFIRMED`
- deterministic script/prompt audit passes, but visual production is not complete until current character-card canonicals, environment/object canonicals, rendered strips, and the stitched chapter are approved

Chapter 2's old script package is preserved only as non-generatable source material under `Manhwa/Source-Archives/` until it is converted into the same vertical format.

## Canonical Production Stack

For a Manhwa strip, authority is:
1. current user instruction
2. current strip/chapter script
3. current approved character canonical PNG(s)
4. approved environment canonical PNG(s)
5. approved core-object canonical PNG(s)
6. immediately previous approved strip for temporary pose/prop/power/seam continuity

Environment canonicals prevent apartment/lobby geometry drift. Core-object canonicals prevent the smart speaker, TV, refrigerator, electrical-operation guide, and brass backup key from redesigning themselves between strips.

Missing, stale, provisional, or unapproved required canonicals are blocking. Never substitute a Markdown reference prompt or a previous rejected/obsolete image for an approved canonical PNG.

## Visual Direction — Absolute

**STRICT FLAT 2D HUMAN-DRAWN KOREAN MANHWA/WEBTOON ILLUSTRATION.**

Use clean intentional linework, flat colors, restrained simple hard-edged cel shading only, matte materials, stable adult proportions/anatomy, natural hands, readable mobile lettering, and consistent canonical environments/objects.

Reject photorealism or semi-photorealism, 3D/CGI/game-render appearance, soft-cel/airbrushed rendering, painterly realism, glossy/plastic/wet skin or hair, beauty-ad shine, mirror-like surfaces, excessive specular reflections, bloom-heavy or cinematic treatment, depth-of-field blur, gratuitous rim light/lens flare, cinematic color grading, and over-rendered AI-polished output.

Helpful/Hyun-woo communication uses clean stable cyan-white accents. Hostile communication uses broken stark-white text with black-pixel corruption. TV and refrigerator keep different hostile manifestation languages as defined in their object canonical sheets.

`Manhwa/style-guide.md` is the absolute visual-style authority; prompt wording alone does not pass visual QA.

## Character Canonical Status

`Character-References/` contains reusable canonical prompts and PNG filenames. Under the September 1, 2026 full character-card standard, PNGs created before that standard are legacy/provisional until regenerated and approved from the upgraded prompts.

For Chapter 1, Nari, Hyun-woo, Mrs. Na, and Seungjae current PNGs predate the full-card standard and must be regenerated/approved before sequential strip production. Nari's prior short-hair PNG is explicitly obsolete; the current design uses long dark-plum hair and must replace the canonical PNG at the same filename.

## Creator-Only Blackout Continuity

1. After midnight, Hyun-woo becomes physical when Unit 2407 loses ordinary supplied power.
2. Switching off a room light is not the same as losing Unit 2407 power.
3. City power may return before Unit 2407; Hyun-woo remains physical until the unit itself powers on.
4. When Unit 2407 power returns, Hyun-woo is simply absent; do not show a visible dissolution process.
5. A mains-powered light is Mrs. Na's powered-night protective anchor. Phone/tablet screens do not replace it.
6. During an actual outage, open flame/screens can help the hostile system locate Nari; darkness can deny it a visual target.
7. Hyun-woo can communicate through devices and, with effort, briefly energize a disconnected speaker while remaining nonphysical.
8. Helpful and hostile device signatures never merge.
9. Hyun-woo's circuit-sigil tattoos are matte-black ink with only faint current accents under pressure.
10. The reason for Hyun-woo's mask remains a later mystery.

Full long-range spoilers remain in `series-plan.md`.

## Current Project Structure

- `Manhwa/` — sole active vertical-manhwa production pipeline
- `Manhwa/01-Arc-The-Tenant-In-The-Grid/` — active Arc 1 production
- `Manhwa/Environment-References/` — reusable canonical environment prompts/bibles and approved PNG packs when generated
- `Manhwa/Object-References/` — reusable canonical recurring-object prompts/bibles and approved PNG packs when generated
- `Manhwa/Source-Archives/` — non-generatable legacy story/script source waiting for conversion
- `Character-References/` — reusable character-card prompts and canonical PNG filenames; current Chapter 1 PNGs require regeneration/approval under the full-card standard
- `characters.md` — character and supernatural continuity
- `series-plan.md` — long-running roadmap and creator-only mystery spine
- `Covers/` — story/promotional cover material

## Arc 1 Release Plan

1. The Man Eating My Emergency Noodles
2. Do Not Turn Off All The Lights

Future chapter titles remain in `series-plan.md` until production begins.
