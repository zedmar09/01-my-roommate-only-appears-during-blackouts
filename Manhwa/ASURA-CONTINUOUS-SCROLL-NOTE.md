# Asura-Style Continuous Scroll Correction

The reader-facing manhwa format is **one continuous vertical chapter**.

The Asura reference chapter is delivered by the site as multiple sequential image assets, but those assets are stacked into one uninterrupted reader experience. They are technical delivery chunks, not separate story pages or separate scroll episodes.

For this repository:

- one chapter = one continuous vertical scroll
- working width = 1080 px for generation/compositing
- final publishing width = 800 px, uniformly downscaled as one chapter
- all technical image strips must use the same width
- no visible seam, border, page break, title repeat, or reset between strips
- strip boundaries must fall inside natural gutter space
- no circled panel numbers
- no printed-page grid
- internal story-run labels exist only in planning files and never appear in artwork

If a platform requires the final master to be uploaded as several images, cut the finished continuous master into same-width sequential WebP/PNG assets without adding space between them. The reader should perceive one uninterrupted chapter.
