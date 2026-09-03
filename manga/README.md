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
    └── arc-01/
        └── chapter-001/
            ├── chapter-001-production.md
            └── pages/                 # approved final WebPs only
```

There is **no volume layer**. Arcs are story units; chapters are installments inside those arcs.

## Format Lock

- black-and-white manga
- hand-drawn pencil/ink impression
- line-weight variation
- screentones, hatching, and solid blacks
- expressive manga simplification when appropriate
- conventional manga pages rather than vertical webtoon strips
- variable panel count, size, shape, and density according to scene rhythm
- one approved page-canvas specification; dramatic variation comes from panel composition
- no color pipeline
- no glossy, cinematic, CGI, 3D-rendered, photoreal, painterly, or webtoon-strip look

## Reference Model

Reusable visual continuity is controlled by approved packages under `02-references/`.

A production-safe recurring subject normally has both:

- semantic authority: `.md`
- visual authority: approved `.webp`

Do not duplicate canonical WebPs inside chapters.

## Production Model

Each chapter has exactly **one production Markdown file**:

`manga/04-production/arc-##/chapter-###/chapter-###-production.md`

That one file compiles all generation requirements for the entire chapter: story/script, page map, panel instructions, exact reference paths, per-page attach sets, image-generation prompts, continuity, QA, and approval state.

Do not create separate page Markdown packages. Approved page images are stored under the chapter's `pages/` directory as `page-###.webp` only.

## Authority Order

1. current user instruction
2. `00-series/` canon and continuity
3. current approved arc/chapter story files under `03-story/`
4. `01-style/` visual rules and approved style-reference WebP(s)
5. approved canonical reference packages under `02-references/`
6. the current chapter's single master production Markdown under `04-production/`
7. immediately previous approved page WebP only for local pose/prop/environment seam continuity

A required visual reference missing from the approved reference register blocks generation. Never improvise a replacement merely to continue.
