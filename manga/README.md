# Manga Production Root

`manga/` is the only active production root for **My Roommate Only Appears During Blackouts**.

## Directory Model

```text
manga/
├── 00-series/
├── 01-style/
├── 02-references/
├── 03-story/
│   └── arc-01/
│       ├── arc-bible.md
│       ├── arc-outline.md
│       ├── event-thread-map.md
│       ├── mystery-progression.md
│       └── chapter-001/
└── 04-production/
    ├── page-production-standard.md
    └── arc-01/
        └── chapter-001/
            ├── page-001-production.md
            ├── page-001.webp
            ├── page-002-production.md
            ├── page-002.webp
            └── ...
```

There is **no volume layer**. Arcs are story units; chapters are installments inside those arcs.

## Format Lock

- black-and-white manga
- hand-drawn pencil/ink impression
- line-weight variation
- screentones, hatching, and solid blacks
- expressive manga simplification when appropriate
- conventional manga pages rather than vertical webtoon strips
- variable panel count, size, shape, density, and hierarchy according to scene rhythm
- one approved page-canvas specification; dramatic variation comes from panel composition
- no color pipeline
- no glossy, cinematic, CGI, 3D-rendered, photoreal, painterly, or webtoon-strip look

## Reference Model

Reusable visual continuity is controlled by approved packages under `02-references/`.

A production-safe recurring subject normally has both:

- semantic authority: `.md`
- visual authority: approved `.webp`

Do not duplicate canonical WebPs inside chapter production folders.

## Production Model — One Page, One MD

Every manga page receives one self-contained production Markdown file:

`manga/04-production/arc-##/chapter-###/page-###-production.md`

That one page file contains everything required for that specific page, including:

- exact page/output size and aspect ratio
- scenario, chronology, event thread, location, and page purpose
- exact `.md` + `.webp` attachment/reference paths
- continuity input/output
- panel count, sizes, hierarchy, gutters, and reading order
- complete panel-by-panel actions, camera, blocking, reactions, objects, and effects
- exact dialogue, narration, SFX, and silence
- complete page-generation instruction
- automatic rejection rules
- page-specific QA and approval status

Do **not** split one page into separate blueprint, prompt, manifest, script, or QA Markdown files.

Once the page is visually approved, its matching `page-###.webp` is stored beside the MD and becomes the local visual continuity authority for the next page.

See `manga/04-production/page-production-standard.md` for the complete required internal structure.

## Authority Order

1. current user instruction
2. `00-series/` canon and continuity
3. current approved arc/chapter story files under `03-story/`
4. `01-style/` visual rules and approved style-reference WebP(s)
5. approved canonical reference packages under `02-references/`
6. the current page's `page-###-production.md`
7. immediately previous approved page WebP only for local pose/prop/environment seam continuity

A required visual reference missing from the approved reference register blocks generation. Never improvise a replacement merely to continue.
