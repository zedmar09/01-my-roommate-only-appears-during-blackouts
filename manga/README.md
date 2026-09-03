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

## Authority Order

1. current user instruction
2. `00-series/` canon and continuity
3. current approved arc/chapter story files under `03-story/`
4. `01-style/` visual rules and approved style-reference WebP(s)
5. approved canonical reference packages under `02-references/`
6. current chapter/page production package under `04-production/`
7. immediately previous approved page WebP only for local pose/prop/environment seam continuity

A page must not be generated until its required text authorities and exact approved WebP references are identified in its reference manifest.
