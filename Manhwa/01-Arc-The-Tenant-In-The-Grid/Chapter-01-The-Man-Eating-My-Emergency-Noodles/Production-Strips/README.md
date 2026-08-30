# Chapter 1 Production Strips

This folder contains **32 technical image-generation prompts** for one continuous Manhwa Chapter 1 adapting source Comic Pages 001–018.

They are not reader-visible pages or episodes.

Generate strictly in order:

`001 → 002 → 003 → ... → 032`

Scope:
- `001–015` = source Pages 001–009
- `016–032` = source Pages 010–018

Rules:
- approve each strip before generating the next
- attach the immediately previous approved strip for 002–032
- attach canonical PNGs only for characters physically visible in the current strip
- use one fixed width throughout
- preserve seam type in `../chapter-01-strip-manifest.md`
- never render strip IDs, V-beat IDs, page numbers, or circled numbers
- never leave a huge purposeless bottom blank tail
- never invent filler text/SFX to occupy extra canvas
- stitch all approved strips into one continuous chapter after 032

If a strip needs extra vertical room, use existing story composition, reaction, atmosphere, narration, or scripted SFX intentionally. The technical canvas must not feel empty or broken.
