# Arc 01 Production

Story authority remains under `manga/03-story/arc-01/`.

Production files under this folder translate approved story material into page-specific visual generation.

## Chapter Production Structure

A page may have separate layout-reference pre-production plus final page production:

```text
chapter-001/
├── page-001-layout-production.md
├── page-001-layout-reference.webp
├── page-001-production.md
├── page-001.webp
├── page-002-production.md
├── page-002.webp
└── ...
```

`page-###-layout-production.md` is optional pre-production used only when composition needs a visual lock.

`page-###-production.md` remains the final story-page generation authority.

Final pages use finished 2D black-and-white manga quality, not rough sketch quality.

Follow:

- `manga/04-production/layout-reference-workflow.md`
- `manga/04-production/page-production-standard.md`
