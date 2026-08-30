# Seam Continuity Protocol

## Purpose

Technical image boundaries must disappear after stitching. The reader should never be able to identify where `strip-###` ends.

## Seam Types

### G — Gutter Seam
Preferred when a natural blank/quiet vertical gap exists. End one strip inside the gap and begin the next as a continuation of that same reader-space background.

### A — Artwork-Continuation Seam
Used when a tall composition intentionally crosses files. The lower portion of Strip N and upper portion of Strip N+1 depict the same continuous environment/composition.

### E — Effect/Atmosphere Seam
Used for rain, darkness, glitch fragments, light falloff, city background, or other continuous atmospheric fields.

## Previous-Strip Attachment Rule

For every strip after 001, attach the immediately previous APPROVED manhwa strip as mandatory continuity reference.

For A/E seams, the previous strip is especially critical. The next strip must continue:
- same camera axis/perspective
- same object scale
- same wall/floor/background alignment
- same character wardrobe/identity
- same continuing pose when the body crosses the seam
- same lighting/background tone

## Overlap Strategy

When practical, intentionally repeat a small lower-edge continuity zone from Strip N at the top of Strip N+1. The duplicate region is cropped during final stitching.

Recommended overlap concept: roughly 10–20% of the visible transition area, not a reader-visible repeated panel.

Do not repeat dialogue or SFX inside the overlap.

## Text Seam Rule — Absolute

Never split these across a seam:
- speech balloon
- narration box
- handwritten message
- device text
- critical SFX word
- a face if the seam would create a visibly mismatched reconstruction

A background, torso/legs, furniture, rain field, dark room, or tall effect may continue if continuity can be matched reliably.

## Seam QA

Before approval compare the bottom of Strip N to the top of Strip N+1:
- width identical
- no horizontal white/black accidental line
- no duplicated text
- no missing floor/wall segment
- no changed appliance geometry
- no color-temperature jump
- no changed character scale
- no pose teleport

If the join is obvious at normal phone-scroll speed, reject/regenerate the newer strip before continuing.
