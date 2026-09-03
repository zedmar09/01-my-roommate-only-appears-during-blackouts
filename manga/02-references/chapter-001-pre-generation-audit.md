# Chapter 001 — Pre-Generation Reference Audit

## Current Audit Result

**PASS — STYLE A + STYLE B + NARI ARE APPROVED. ENVIRONMENT GENERATION MAY PROCEED.**

The Chapter 001 story direction, Nari baseline, apartment spatial baseline, neighbor relationship, workplace identity, paired style system, and Nari canonical are approved.

## Current Approved WebP Authorities

All reusable final WebPs are centralized in:

`manga/02-references/approved-webp/`

Currently approved:

1. `series-manga-style-reference-a.webp`
2. `series-manga-style-reference-b.webp`
3. `nari-canonical.webp`

Full paths:

- `manga/02-references/approved-webp/series-manga-style-reference-a.webp`
- `manga/02-references/approved-webp/series-manga-style-reference-b.webp`
- `manga/02-references/approved-webp/nari-canonical.webp`

## Attachment Rule

Before every generation, check:

`manga/02-references/generation-attachment-map.md`

Generation prompts must explicitly name the exact WebPs to attach.

## Story / Reveal Audit

**PASS.** Chapter 001 remains locked to:

- Nari is verifiably at her publishing-company workplace while activity is heard from her apartment.
- The complaint comes from the resident directly below Nari.
- Ordinary access/security logic does not resolve it.
- The second dining chair becomes the physical continuity marker.
- The reader alone receives the final chair movement.
- Hyun-woo is not shown, heard, named, silhouetted, or attached as a Chapter 001 reference.
- No reader-facing blackout explanation appears.

## Approved Nari Visual

Nari's semantic authority:

`manga/02-references/characters/nari/canon.md`

Approved visual authority:

`manga/02-references/approved-webp/nari-canonical.webp`

Nari is now safe for later page generation. Style A/B control rendering language only and do not replace her identity.

## Paired Style System — Approved

Both style references must normally be attached together:

- `manga/02-references/approved-webp/series-manga-style-reference-a.webp`
- `manga/02-references/approved-webp/series-manga-style-reference-b.webp`

Style A is strongest for character/anatomy/ink/hatching treatment. Style B complements it with adult-female, ordinary-life, domestic, quiet-suspense and environment treatment.

The generic people and environments inside the style sheets are not story canon.

## Next Generation — Nari Apartment Master Atlas

**READY NOW.**

Prompt:

`manga/02-references/environments/nari-apartment/nari-apartment-reference-generation-prompt.md`

Attach exactly:

1. `manga/02-references/approved-webp/series-manga-style-reference-a.webp`
2. `manga/02-references/approved-webp/series-manga-style-reference-b.webp`

Do not attach Nari canonical to the environment atlas.

Generate:

`nari-apartment-master-atlas.png`

After review/approval, manually convert to:

`manga/02-references/approved-webp/nari-apartment-master-atlas.webp`

## Apartment Floor Plan

**WAIT UNTIL MASTER ATLAS APPROVAL.**

Only generate a separate floor-plan PNG if the master atlas itself cannot provide a reliable legible spatial plan.

If needed, attach:

1. Style A WebP
2. Style B WebP
3. approved `nari-apartment-master-atlas.webp`

Then generate `nari-apartment-floor-plan.png` and convert the approved result to the centralized WebP path.

## Nari Workplace Atlas

**TEXT READY.**

Prompt:

`manga/02-references/environments/nari-workplace/nari-workplace-reference-generation-prompt.md`

Attach exactly:

1. `manga/02-references/approved-webp/series-manga-style-reference-a.webp`
2. `manga/02-references/approved-webp/series-manga-style-reference-b.webp`

Do not attach Nari canonical to the environment atlas unless a later revised prompt explicitly requires visible Nari.

## Conditional Reference

Koo Hyejin remains conditional. Do not generate her until her rebuilt role/design is separately approved and Chapter 001 confirms she is visibly needed.

## Explicitly Deferred For Chapter 001

Do not generate solely for Chapter 001:

- Hyun-woo canonical
- building service/electrical-area atlas
- blackout visual-language atlas
- separate dining-chair object canonical
- separate smartphone canonical
- separate smart-lock canonical
- full neighbor character atlas unless the neighbor becomes recurring

## PNG → WebP Rule

All new visual generations still follow:

1. generate PNG
2. visual audit
3. user manually converts exact approved PNG to WebP
4. commit WebP under `manga/02-references/approved-webp/`
5. mark reference `APPROVED`

## Current Generation Order

1. **Nari apartment master atlas — NOW**
2. apartment floor plan — only if needed after atlas approval
3. Nari workplace master atlas
4. Hyejin only if separately approved/required
5. reference audit again before page-production files begin
