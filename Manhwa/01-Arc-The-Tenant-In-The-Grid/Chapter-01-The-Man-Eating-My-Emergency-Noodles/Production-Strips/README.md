# Chapter 1 Production Strips

This folder contains **32 technical image-generation prompts** for one continuous Manhwa Chapter 1. Historical P001–P018 labels are story-mapping shorthand only.

Current status: **prompt package audited; visual production is not complete. Required environment/object canonical PNGs must be generated and approved before sequential strip generation begins.**

Generate strictly in order: `001 → 002 → 003 → ... → 032`.

## Binding Global Rules — Absolute

Every strip inherits the current repository production rules even when they are not repeated in the strip attachment list:
- `../../../style-guide.md`
- `../../../lettering-sfx-guide.md`
- `../../../seam-continuity-protocol.md`
- `../../../vertical-scroll-layout-guide.md`
- `../../../generation-workflow.md`
- `../../../production-readiness-gate.md`

A strip may make these stricter but never looser.

## Every Strip Prompt Is Self-Contained For Visual Attachments — Absolute

Every `strip-###-...md` must explicitly list inside the file itself:
1. current strip prompt
2. required visible-character canonical PNG(s)
3. every required reusable environment canonical PNG
4. every required reusable object canonical PNG
5. immediately previous APPROVED strip for 002–032

Do not rely on the manifest alone when working in the production chat. The manifest is the audit map; the current strip file must repeat the exact visual attachments needed for that generation.

If a listed canonical PNG has not yet been generated/approved, **STOP**. Do not substitute a random reference, an old rejected image, or the Markdown reference prompt itself. Generate/approve the canonical first.

Reuse Unit 2407, Building Shared Areas, smart-speaker, TV, refrigerator, electrical-operation-guide, and brass-key canonicals in later chapters whenever the same place/object returns. Never create chapter-numbered duplicates.

## Strict Flat 2D Human-Drawn Style — Absolute

Actual strip pixels must satisfy `../../../style-guide.md`:
- strict flat 2D human-drawn Korean manhwa/webtoon illustration
- clean intentional line art
- flat colors
- restrained simple hard-edged cel shading only
- matte characters, materials, rooms, furniture, appliances, screens, glass, floors, and props
- stable canonical anatomy/proportions and natural hands

Reject photoreal/semi-photoreal, 3D/CGI/game-render, glossy/plastic/wet, painterly, airbrushed, cinematic grading, depth-of-field blur, bloom, lens flare, excessive rim light, mirror-like reflections, excessive specular highlights, or over-rendered AI-polished output.

Previous-strip continuity never overrides the permanent flat style gate.

## Black Read-Slice Grammar — Absolute

Every distinct vertical reading slice/composition inside a technical strip receives a **small black gutter** before the next distinct slice.

Rules:
- gutter is narrow and deliberate, never a huge dead black band
- use black, not random white spacing, as the normal visual slice separator
- meaningful longer pauses may be slightly larger but still purposeful
- time/location cuts may use a somewhat stronger compact black divider
- if TWO different camera slices share one horizontal row, separate them with a **diagonal/slanted black divider**
- faces, text, balloons, props, and backgrounds must not cross the diagonal divider
- side-by-side slices must read as separate shots, never one merged impossible environment

Technical file seams are different. For A/E continuation seams, do **not** add a visible black bar merely because one generated file ends; the final stitched chapter must remain seamless.

## Production Rules

- approve each required canonical before it is used
- approve each strip before generating the next
- re-audit every corrected strip and adjacent seams before approval
- use one fixed width throughout
- preserve seam type in `../chapter-01-strip-manifest.md`
- preserve canonical room geometry and recurring object identity/state
- preserve exact movement/object routes and dialogue ownership
- verify every SFX as physical source → action → sound → timing → placement → consequence
- never render production IDs/page numbers/circled panel numbers
- never leave huge purposeless bottom blank space
- never invent filler narration/dialogue/SFX
- stitch all approved strips into one continuous chapter after 032
- run a fresh clean-room visual audit after stitching; do not inherit earlier PASS labels

See `../chapter-01-real-scenario-continuity-audit.md` for the current audit result.