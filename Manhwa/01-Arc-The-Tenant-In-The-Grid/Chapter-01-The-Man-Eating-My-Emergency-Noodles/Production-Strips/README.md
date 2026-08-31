# Chapter 1 Production Strips

This folder contains **32 technical image-generation prompts** for one continuous Manhwa Chapter 1 adapting source Comic Pages 001–018.

Generate strictly in order: `001 → 002 → 003 → ... → 032`.

Scope:
- `001–015` = source Pages 001–009
- `016–032` = source Pages 010–018

## Production Attachment Stack

For every strip, follow `../chapter-01-strip-manifest.md` and attach:
1. current strip prompt
2. required visible-character canonical PNG(s)
3. relevant approved environment canonical PNG(s)
4. relevant approved core-object canonical PNG(s)
5. immediately previous approved strip for 002–032

Environment/object canonicals become mandatory after their packs are generated and approved. Do not attach rejected reference images or unrelated canonical sheets.

## Rules

- approve each strip before generating the next
- use one fixed width throughout
- preserve seam type in the manifest
- preserve canonical room geometry and recurring object design/state
- never render strip IDs, V-beat IDs, page numbers, or circled numbers
- never leave a huge purposeless bottom blank tail
- never invent filler text/SFX to occupy extra canvas
- stitch all approved strips into one continuous chapter after 032

If a strip needs extra vertical room, use existing story composition, canonical environment, reaction, atmosphere, narration, or scripted SFX intentionally. The technical canvas must not feel empty or broken.
