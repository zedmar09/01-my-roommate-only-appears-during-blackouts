# Manga Production Root

`manga/` is the only active production root for **My Roommate Only Appears During Blackouts**.

## Directory Model

```text
manga/
├── 00-series/
├── 01-style/
├── 02-references/
│   ├── approved-webp/              # centralized approved reusable visual authorities
│   ├── characters/
│   ├── environments/
│   ├── objects/
│   ├── effects/
│   ├── generation-attachment-map.md
│   └── reference-register.md
├── 03-story/
│   └── arc-01/
│       └── chapter-001/
└── 04-production/
    ├── page-production-standard.md
    └── arc-01/
        └── chapter-001/
            ├── page-001-production.md
            ├── page-001.webp
            └── ...
```

There is **no volume layer**. Arcs are story units; chapters are installments inside those arcs.

## Format Lock

- black-and-white manga
- finished hand-drawn ink impression
- line-weight variation
- screentones, hatching, and solid blacks
- expressive manga simplification when appropriate
- conventional manga pages rather than vertical webtoon strips
- variable panel count, size, shape, density, and hierarchy according to scene rhythm
- one approved page-canvas specification; dramatic variation comes from panel composition
- no color pipeline
- no glossy, cinematic, CGI, 3D-rendered, photoreal, painterly, or webtoon-strip look

## PNG → WebP Workflow

All image generation is PNG first:

- ChatGPT/image generation returns a `.png` review candidate.
- The PNG is visually reviewed.
- If approved, the user manually converts that exact PNG to `.webp`.

Reusable approved reference WebPs go to:

`manga/02-references/approved-webp/`

Approved final manga page WebPs stay beside their page-production MDs because they are sequential page outputs.

## Paired Series Style Authority

Use both approved style WebPs together when a prompt calls for the series rendering authority:

- `manga/02-references/approved-webp/series-manga-style-reference-a.webp`
- `manga/02-references/approved-webp/series-manga-style-reference-b.webp`

They control rendering language only, not character identity or environment geometry.

## Reference Model

Semantic authorities remain in subject folders as Markdown.

Approved reusable visual authorities are centralized under `approved-webp/`.

Before every reference generation, consult:

`manga/02-references/generation-attachment-map.md`

That file lists the exact WebPs to attach for each generation prompt.

Do not attach every available reference automatically.

## Production Model — One Page, One MD

Every manga page receives one self-contained production Markdown file:

`manga/04-production/arc-##/chapter-###/page-###-production.md`

That page file must list exact approved centralized reference WebPs needed by the page, plus the previous approved page WebP only when local seam continuity requires it.

Image generation first creates `page-###.png`; after approval the user manually converts it to `page-###.webp`.

See `manga/04-production/page-production-standard.md`.

## Authority Order

1. current user instruction
2. `00-series/` canon and continuity
3. current approved arc/chapter story files under `03-story/`
4. `01-style/` visual text rules
5. approved reusable WebPs under `02-references/approved-webp/`
6. relevant semantic canon MDs under `02-references/`
7. current `page-###-production.md`
8. immediately previous approved page WebP only for local seam continuity

A required visual reference missing from the register blocks generation. Never improvise a replacement merely to continue.
