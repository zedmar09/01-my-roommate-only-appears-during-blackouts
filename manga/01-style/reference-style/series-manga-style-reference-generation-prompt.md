# Series Manga Style Reference — Generation Record

## Status

**COMPLETED — APPROVED PAIRED STYLE AUTHORITIES EXIST.**

Chapter 001 does not need another style-reference generation.

Approved final WebPs are centralized at:

- `manga/02-references/approved-webp/series-manga-style-reference-a.webp`
- `manga/02-references/approved-webp/series-manga-style-reference-b.webp`

These two images are used **together** as the series manga rendering authority.

## Authority Roles

### Style Reference A

Primary strengths:

- finished manga character rendering
- adult anatomy
- face construction
- hand rendering
- stronger black placement
- hatching/cross-hatching
- clothing and movement treatment

It controls rendering language only. Its generic male subject is not Hyun-woo or any story character.

### Style Reference B

Primary strengths:

- adult female rendering
- ordinary adult-life expressions
- domestic/interior rendering
- quiet suspense
- environment line density
- everyday object interaction
- simplified comedy/reaction language

It controls rendering language only. Its generic female subject is not Nari, and its generic apartment is not Nari's apartment.

## Required Use Rule

When a generation prompt needs the series style authority, attach **both**:

1. `manga/02-references/approved-webp/series-manga-style-reference-a.webp`
2. `manga/02-references/approved-webp/series-manga-style-reference-b.webp`

Do not attach only one unless a future prompt explicitly explains why.

See:

`manga/02-references/generation-attachment-map.md`

## Identity / Geometry Firewall

Style references may control:

- line quality
- screentone density
- hatching/cross-hatching
- solid-black usage
- anatomy treatment
- hair/fabric rendering language
- background detail balance
- simplified reaction rendering
- finished printed-manga feeling

They must **not** control:

- Nari's exact face/hair/body identity
- Hyun-woo's future identity
- any supporting character identity
- Nari apartment geometry
- Nari workplace geometry
- story props
- dialogue
- page-specific composition

Character/environment canon MDs and their approved canonical WebPs override any subject identity or geometry visible inside the style sheets.

## PNG → WebP Workflow

The approved A and B PNG review candidates were manually converted to WebP. The centralized WebPs above are now final repository authorities.

Do not create Style C/D or another Chapter 001 style image merely to add variety. The approved A+B pair is intentionally the fixed baseline until deliberately revised.
