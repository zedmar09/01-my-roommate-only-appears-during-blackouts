# 01-style

Visual grammar for the black-and-white manga pipeline.

These files control:

- finished 2D manga line treatment
- screentone/hatching/solid-black use
- page composition and panel language
- speech balloons and SFX
- reader-visible language/lettering
- tone differences between ordinary, comedic, suspense, horror and action scenes

Final story pages target **finished professional 2D hand-drawn manga quality**, not rough sketch quality.

## Reader-Visible Language

Global rule:

`manga/01-style/reader-visible-language-lock.md`

All reader-visible text is **English only** unless the user explicitly approves a page-specific exception before generation.

Layout references use empty balloons and normally contain zero readable text. Final pages use only the exact approved English wording from their production Markdown.

The style system rejects cinematic/movie-still lighting, glossy digital illustration, painterly grayscale, photorealism and CGI/3D.
