# Chapter 001 Reference Needs

## Status

**AUDIT PASSED — CORE TEXT AUTHORITIES READY.**

Generate only reusable visual authorities that Chapter 001 actually shows.

## Image Format Workflow

Every first-generation visual is PNG. After visual approval, the user manually converts that exact accepted PNG to WebP. Only the WebP becomes repository authority.

See `manga/02-references/image-format-workflow.md`.

The series manga style PNG must be generated, approved, manually converted to its final WebP, and marked `APPROVED` **before** generating Nari or environment PNG candidates.

## Style

### Required first

- `manga/01-style/manga-style-lock.md`
- `manga/01-style/reference-style/series-manga-style-reference-generation-prompt.md`
- first generated candidate: `series-manga-style-reference.png`
- final approved authority after manual conversion: `manga/01-style/reference-style/series-manga-style-reference.webp`

The style image is an original black-and-white manga visual-language calibration sheet. It must not copy any specific reference manga character, dialogue, logo, panel, or exact composition.

---

## Characters

### 1. Yoon Nari — REQUIRED / REUSABLE / TEXT APPROVED

Package:

```text
manga/02-references/characters/nari/
├── canon.md
├── nari-reference-generation-prompt.md
├── nari-canonical.webp             # final authority after PNG approval + manual conversion
└── variants/                        # only when a later scripted state truly needs one
```

First generated candidate: `nari-canonical.png`.

Locked Chapter 001 baseline:

- Korean woman, age 30
- editor at a mid-sized publishing company
- approximately 165 cm
- natural slim-average adult build
- mature but approachable face, expressive eyes, slightly tired resting expression
- dark mid-back hair with restrained natural wave; normally loose, simple low tie acceptable when concentrating
- no permanent glasses
- practical work wardrobe: blouse/knit top, cardigan/simple jacket, straight slacks, simple shoes
- home wardrobe: loose T-shirt or long-sleeve top + comfortable lounge pants
- grounded, observant, dry humor, low-glamour everyday presentation
- natural hands for manuscripts/proofs, phone, lock, chair, household actions, and ordinary office work

Do not inherit the retired Manhwa design automatically.

### 2. Neighbor Below — CHAPTER-LOCAL OR REUSABLE LATER

The complaining neighbor lives **directly below Nari**.

Do **not** create a full canonical character atlas unless later Arc 01 planning makes this neighbor recurring. For Chapter 001, preserve short-scene identity through page-local description and adjacent-page continuity.

### 3. Koo Hyejin — CONDITIONAL REUSABLE SUPPORT

Hyejin remains a proposed trusted friend/coworker anchor, but her old QA/technical role is retired.

Do not generate a Hyejin canonical until her exact rebuilt role and manga design are separately approved. If retained in Chapter 001, her reference must be approved before pages that visibly show her are produced.

### Joo Hyun-woo — NOT REQUIRED FOR CHAPTER 001

Chapter 001 does not show Hyun-woo, a silhouette, body fragment, shadow, or voice source.

Therefore **do not generate or attach Hyun-woo solely for Chapter 001**. Create his canonical package later, before the first page that genuinely needs his visual identity.

---

## Environments

### 1. Nari's Apartment — REQUIRED / HIGHLY REUSABLE / TEXT APPROVED

Package:

```text
manga/02-references/environments/nari-apartment/
├── canon.md
├── nari-apartment-reference-generation-prompt.md
├── nari-apartment-master-atlas.webp     # final authority after PNG approval + manual conversion
├── nari-apartment-floor-plan.webp       # optional separate final authority if needed
└── details/                              # only if later needed
```

First generated candidate: `nari-apartment-master-atlas.png`.

If a separate floor plan is needed: `nari-apartment-floor-plan.png`.

Locked baseline:

- modest modern Seoul one-bedroom apartment
- approximately 40–45 m²
- ordinary working-adult rental; not luxury, not horror-run-down, not a studio
- front door → short entry hall → readable sightline toward living/dining
- compact kitchen connected to dining zone
- compact bathroom near entry side
- separate bedroom/private room off the inner living/hall route
- main living area at the exterior-window side
- home work/activity zone inside the living area
- one small rectangular dining table
- exactly two matching dining chairs
- one habitual Nari chair + one **second continuity chair**
- the second chair's known position must be visually reproducible: fully tucked at its designated side, back parallel to table edge, leg/floor geometry providing a clear alignment reference
- immediate exterior front-door view, short corridor, and elevator/common route should be covered in the same reusable atlas if clarity remains strong
- the complaining neighbor lives directly below Nari

The chair remains part of the environment package. Do not create a separate chair canonical for Chapter 001.

### 2. Nari's Workplace — REQUIRED / REUSABLE / TEXT APPROVED

Package:

```text
manga/02-references/environments/nari-workplace/
├── canon.md
├── nari-workplace-reference-generation-prompt.md
└── nari-workplace-master-atlas.webp      # final authority after PNG approval + manual conversion
```

First generated candidate: `nari-workplace-master-atlas.png`.

Locked baseline:

- mid-sized publishing-company office
- normal professional/editorial environment rather than technical startup or game studio
- recurring open editorial work area
- Nari desk
- nearby coworker desks
- books/reference shelves
- manuscripts / printed proofs / ordinary editorial materials
- small review/meeting area
- same geometry must work for daytime scenes and quiet reduced-staff late-night scenes
- Chapter 001 cold open uses this office to prove Nari is away when the apartment noise occurs

### 3. Apartment Corridor / Elevator / Common Route — MERGE FIRST

The morning complaint needs the immediate route outside Nari's front door and the elevator/common circulation point.

Preferred solution: include these views in the `nari-apartment` master atlas. Create a separate common-area environment package only if the master atlas becomes too crowded or spatially ambiguous.

### 4. Neighbor Interior — NO FULL CANON YET

Because the neighbor is directly below Nari, the previous-night sound scene may use a small page-local interior crop oriented toward the ceiling. Do not build a full neighbor-apartment atlas unless the location later recurs.

### Building Service / Electrical Area — NOT REQUIRED FOR CHAPTER 001

The revised Chapter 001 does not use a maintenance/electrical intercut. Do not generate this environment yet.

---

## Objects

### Second Dining Chair — ENVIRONMENT-LEVEL CONTINUITY OBJECT

Its exact design, count, designated side of table, and known reference position are controlled by the apartment canon/atlas. It is the most important physical continuity marker in Chapter 001.

### Smart Lock / Access Interface — GENERIC / ENVIRONMENT DETAIL

Chapter 001 needs believable access-history checking, but no separate object canonical is required yet. The exact UI may remain generic unless future plot mechanics require exact hardware behavior.

### Smartphone — GENERIC

Keep visually consistent within the chapter, but do not create a standalone canonical unless later mechanics make it story-critical.

---

## Effects

### Blackout Visual-Language Atlas — NOT REQUIRED FOR CHAPTER 001

Chapter 001 does not show a major reader-visible blackout. Do not generate a blackout-effect atlas solely for this chapter.

Create it later before the first substantial blackout chapter if the approved series manga style image is insufficient.

---

## Chapter 001 Minimal Reference Generation Order

### First visual generation

1. Generate `series-manga-style-reference.png`.
2. Review it.
3. If approved, manually convert that exact PNG to `series-manga-style-reference.webp`, commit it, and mark it `APPROVED`.

### Only after the style WebP is approved

4. Generate `nari-canonical.png`.
5. Generate `nari-apartment-master-atlas.png`.
6. Generate `nari-apartment-floor-plan.png` only if the master atlas cannot contain a legible floor plan.
7. Generate `nari-workplace-master-atlas.png`.

For every accepted PNG above, manually convert the exact approved PNG to its final WebP before marking the package `APPROVED`.

### Conditional later addition

8. Hyejin canonical only after her rebuilt story role/design is approved and only if Chapter 001 visibly uses her.

Do not generate Hyun-woo, service-area, blackout-effect, separate chair, phone, lock, or other speculative references before the story actually needs them.
