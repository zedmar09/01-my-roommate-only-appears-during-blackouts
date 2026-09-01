# Canonical Character Card Standard — Flat 2D Manhwa

This is the reusable visual-reference standard for every recurring human character in `My Roommate Only Appears During Blackouts`.

## Purpose

A canonical character reference is a **multi-view character card / model sheet** detailed enough to preserve identity across different camera angles, emotions, poses, and full-body compositions throughout the Manhwa.

Once a card is generated, visually approved, manually converted, and committed, reuse that SAME canonical WebP across every later chapter in which the same character appears. Do not make chapter-specific character references.

## Generation / Repository Format Rule

The image-generation prompt may request PNG as the first local output because that is the normal generation workflow. PNG is an intermediate generation/QA artifact.

After approval:
- manually convert the approved PNG to WebP
- commit/store only the canonical `.webp` file in GitHub
- production Markdown and strip attachment lists must reference the exact stored `.webp` filename

A deleted/intermediate PNG must never be treated as the repository's active production authority.

## Absolute Visual Style

- 100% flat 2D human-drawn full-color manhwa
- clean visible ink/linework
- matte cel colors
- solid color blocking
- one restrained hard-edged cel-shadow tone where needed
- natural adult anatomy and readable hands
- simple plain light-neutral background
- consistent proportions across every repeated view of the character

ABSOLUTELY NO glossy webtoon shine, shiny skin/hair, cinematic lighting, bloom, rim light, lens flare, volumetric light, photorealism, semi-photorealism, 3D/CG, painterly rendering, airbrushed gradients, mirror-like reflections, depth-of-field blur, or over-rendering.

## Required Card Layout

Each card must show the SAME person repeatedly with no identity drift.

### 1. Full-Body Turnaround
Show the entire body including shoes/feet in consistent scale:
- front
- 3/4 left
- left profile
- back
- 3/4 right

A right profile may be added when useful. Do not crop heads, hands, or feet.

### 2. Face / Hair Angle Row
Show larger head-and-shoulder references:
- front
- 3/4
- side profile
- rear/back-of-hair view when hairstyle geometry matters

### 3. Expression Set
Include at least 6–8 expressions appropriate to the character. Expressions may change, but face shape, eye shape, nose, lips, age, beauty marks, hairstyle, glasses/mask, and other identity features must not.

### 4. Signature Prop / Detail Area
Include only story-relevant recurring details such as glasses, mask, tattoos, phone, tablet, bag, watch, or other signature objects. Plot-critical reusable objects that have their own canonical under `Manhwa/Object-References/` should remain separate unless a character prompt explicitly needs a scale/detail coordination inset.

### 5. Primary Outfit Authority
The card must show the full primary outfit clearly enough to reproduce garment lengths, layering, footwear, accessories, and silhouette. Later story outfits may change when scripted, but body/face/hair identity remains canonical.

## Card Composition Rules

- one clean unified reference sheet, not a story scene or comic sequence
- repeated views may be arranged in rows/columns with clean whitespace
- no dramatic environment or story lighting
- no reader-facing labels are required; prefer ZERO text inside the generated artwork
- no speech balloons, SFX, captions, watermarks, signatures, measurements, or fake UI
- plain uniform light-neutral background so silhouettes are easy to compare

## Production Authority

Character cards control:
- face identity
- age presentation
- body proportions and height/build
- hair shape/length/color
- permanent marks/accessories
- primary outfit silhouette
- signature prop design shown on the card

The current strip controls temporary pose, expression, action, wardrobe changes, injuries, wet/dry state, and story-specific prop state.

## Regeneration Rule

If a character design changes or an older card no longer satisfies this standard, regenerate it from the current prompt, visually approve it, manually convert the accepted PNG to WebP, and replace the repository WebP authority deliberately.

Nari's previous short-hair design is specifically obsolete. Her active card uses the current long dark-plum-haired design.

## Acceptance Gate

Reject a card if:
- face/hair/body changes between angles
- front/back views imply different clothing construction
- character becomes younger/older between expressions
- hands/feet are missing from full-body turnaround
- signature marks/accessories disappear inconsistently
- duplicated props appear
- hairstyle changes length between views
- the sheet becomes glossy, cinematic, 3D, painterly, or photoreal
- different views look like different people
