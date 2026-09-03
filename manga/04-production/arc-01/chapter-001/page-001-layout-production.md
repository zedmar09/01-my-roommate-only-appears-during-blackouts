# Deprecated — Page 001 Layout Reference Production

## Status

**DEPRECATED FOR NORMAL PAGE 001 PRODUCTION.**

Page 001 now uses direct final-page generation from:

`manga/04-production/arc-01/chapter-001/page-001-production.md`

Do **not** generate `page-001-layout-reference.png` or `page-001-layout-reference.webp` as part of the normal workflow.

The normal Page 001 generation attachments are now exactly:

1. `manga/04-production/arc-01/chapter-001/page-001-production.md`
2. `manga/02-references/approved-webp/nari-canonical.webp`
3. `manga/02-references/approved-webp/nari-workplace-master-atlas.webp`

Do not attach Style A/B.

---

## Why This File Is Deprecated

The previous layout-reference step generated essentially the same manga page twice:

1. once with empty balloons,
2. again with final English lettering.

That duplicated work and introduced unnecessary opportunities for:

- face drift
- pose drift
- framing drift
- office-geometry drift
- panel-proportion drift
- inconsistent final rendering

Page 001's composition is now specified directly and completely inside `page-001-production.md`.

---

## Optional Troubleshooting Use Only

Keep this file only as a compatibility/troubleshooting pointer.

A separate layout reference may be reintroduced **only if** direct Page 001 generation repeatedly fails to follow the composition defined in `page-001-production.md`, and only after the user explicitly decides to use that fallback.

If such troubleshooting is ever used:

- it is not canonical by default
- it does not block final Page 001 generation
- the final `page-001-production.md` remains the story, composition, English-lettering and rendering authority
- layout output must contain zero readable text and empty balloons only
- Style A/B remain omitted

---

## Current Authority

For Page 001, use:

`manga/04-production/arc-01/chapter-001/page-001-production.md`

Global English-only lettering rule:

`manga/01-style/reader-visible-language-lock.md`

Global final-manga visual rule:

`manga/01-style/manga-style-lock.md`
