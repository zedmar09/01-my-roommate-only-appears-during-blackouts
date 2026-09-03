# My Roommate Only Appears During Blackouts

This repository is the active **black-and-white manga** version of the project.

## Active Story Model

- **Series** — complete long-form story and canon
- **Arc** — major narrative problem/mystery/relationship movement
- **Chapter** — serialized installment inside an arc
- **Page** — visual storytelling and generation unit

The active project root is `manga/`.

## Production Stack

1. `manga/00-series/` — series canon, continuity and chronology
2. `manga/01-style/` — finished 2D manga visual grammar plus reader-visible language lock
3. `manga/02-references/` — canonical reusable character/environment/object/effect authorities
4. `manga/03-story/` — arcs and chapters
5. `manga/04-production/` — layout-reference and final page production

## Visual Lock

Final story pages are finished professional **2D black-and-white manga**:

- clean hand-drawn ink quality
- varied line weight
- screentone
- hatching
- flat graphic solid blacks
- conventional manga page composition

No glossy webtoon finish, cinematic/movie-still lighting, painterly grayscale, photorealism, CGI or 3D-render look.

## English-Only Reader-Visible Text

Global rule:

`manga/01-style/reader-visible-language-lock.md`

All reader-visible manga text is **English only** unless the user explicitly approves a page-specific exception before generation.

Final pages may contain only exact English wording approved in their `page-###-production.md`.

Never translate approved dialogue/SFX into Japanese, Korean, Chinese or another language. Never invent fake readable background text.

Layout references are composition authorities and are **text-free by default**:

- empty balloons
- no SFX lettering
- no readable signs/labels/documents/UI

## Page Production Model

When a separate layout reference is required:

```text
page-001-layout-production.md
page-001-layout-reference.webp
page-001-production.md
page-001.webp
```

The layout production file establishes composition only.

The final page-production file controls exact story content, final 2D manga rendering, and exact English lettering.

See:

- `manga/04-production/page-production-standard.md`
- `manga/04-production/layout-reference-workflow.md`
- `manga/02-references/generation-attachment-map.md`

## Image Format Workflow

1. generate PNG review candidate
2. visually review
3. if approved, manually convert the exact accepted PNG to WebP
4. commit approved WebP as the downstream visual authority

Do not treat rejected PNGs as canon.

## Canon Reset

The previous full-color vertical Manhwa production is retired and recoverable through Git history. The active project is rebuilt as conventional black-and-white manga.
