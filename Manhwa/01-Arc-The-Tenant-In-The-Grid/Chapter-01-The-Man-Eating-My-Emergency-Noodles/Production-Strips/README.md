# Chapter 1 Production Strips

This folder contains **32 technical image-generation prompts** for one continuous Manhwa Chapter 1. Historical P001–P018 labels are story-mapping shorthand only.

Generate strictly in order: `001 → 002 → 003 → ... → 032`.

## Every Strip Prompt Is Self-Contained — Absolute

Every `strip-###-...md` must explicitly list inside the file itself:
1. current strip prompt
2. required visible-character canonical PNG(s)
3. every required reusable environment canonical PNG
4. every required reusable object canonical PNG
5. immediately previous APPROVED strip for 002–032

Do not rely on the manifest alone when working in the production chat. The manifest is the audit map; the current strip file must repeat the exact attachments needed for that generation.

If a listed canonical PNG has not yet been generated/approved, do not substitute a random reference. Generate/approve the canonical first.

Reuse `Unit-2407`, `Building-Shared-Areas`, smart-speaker, TV, and refrigerator canonicals in later chapters whenever the same place/object returns. Never create chapter-numbered duplicates.

## Black Read-Slice Grammar — Absolute

Every distinct vertical reading slice/composition inside a technical strip receives a **small black gutter** before the next distinct slice.

Rules:
- gutter is narrow and deliberate, never a huge dead black band
- use black, not random white spacing, as the normal visual slice separator
- meaningful longer pauses may be slightly larger but still purposeful
- time/location cuts may use a somewhat stronger compact black divider
- if TWO different camera slices share one horizontal row, separate them with a **diagonal/slanted black divider** (a black slash/wedge)
- faces, text, balloons, props, and backgrounds must not cross the diagonal divider
- side-by-side slices must read as separate shots, never one merged impossible environment

Technical file seams are different. For A/E continuation seams, do **not** add a visible black bar merely because one generated file ends; the final stitched chapter must remain seamless.

## Production Rules

- approve each strip before generating the next
- use one fixed width throughout
- preserve seam type in `../chapter-01-strip-manifest.md`
- preserve canonical room geometry and recurring object identity/state
- preserve exact movement/object routes and dialogue ownership
- never render production IDs/page numbers/circled panel numbers
- never leave huge purposeless bottom blank space
- never invent filler narration/dialogue/SFX
- stitch all approved strips into one continuous chapter after 032

See `../chapter-01-real-scenario-continuity-audit.md` for the complete renewed continuity audit.
