# Chapter 1 Production Strips

This folder contains **15 technical image-generation prompts** for one continuous Manhwa Chapter 1.

They are not reader-visible pages or episodes.

Generate strictly in order:

`001 → 002 → 003 → ... → 015`

Rules:
- approve each strip before generating the next
- attach the immediately previous approved strip for 002–015
- use one fixed width throughout
- preserve seam type in `../chapter-01-strip-manifest.md`
- never render strip IDs or V-beat IDs
- stitch all approved strips into one continuous chapter after 015

The first test should stop after generating Strip 001 until its visual style/density is accepted. The remaining prompts exist so the roadmap is already stable.
