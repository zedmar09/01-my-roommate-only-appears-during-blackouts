# Manga Page Production

`04-production/` contains generation-ready packages and approved rendered manga pages. It mirrors the story's arc/chapter organization and has **no volume layer**.

```text
04-production/
└── arc-01/
    └── chapter-001/
        ├── chapter-production.md
        ├── chapter-reference-manifest.md
        └── pages/
```

The normal generation unit is **one complete manga page**, containing however many panels the approved page map requires. Do not force a fixed panel count.

Every page is blocked until its exact reference manifest is complete. See `generation-standard.md` and `page-package-standard.md`.
