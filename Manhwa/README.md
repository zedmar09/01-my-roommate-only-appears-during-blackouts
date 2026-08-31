# Manhwa Vertical-Scroll Workspace

`Manhwa/` is the experimental continuous vertical-scroll production pipeline for `My Roommate Only Appears During Blackouts`.

## Isolation Rule — Absolute

The existing `Comics/` directory remains untouched and remains the source story/continuity authority during this test. Nothing in `Manhwa/` automatically replaces, renames, deletes, or weakens the existing comic production package.

Only after the manhwa version is proven effective and the user explicitly approves promotion may we plan replacement/migration of the older comic presentation.

## Current Chapter 1 Lock

Manhwa Chapter 1 adapts the FULL source Comic Chapter 1, Pages **001–018**.

Production target:
- one reader-visible continuous vertical chapter
- exactly **146 internal vertical read beats** (`V01`–`V146`) for planning/QA only
- exactly **32 tall technical production strips** (`strip-001`–`strip-032`)
- Strips `001–015` cover source Pages 001–009
- Strips `016–032` cover source Pages 010–018
- all strips use one fixed width and stitch into one seamless scroll
- beat IDs and strip IDs are production-only and never appear in reader-facing artwork
- no circled panel numbers or page numbers

The final chapter ends on the source Page 18 hostile-TV beat: `NEW TENANT CONFIRMED` while Unit 2407 remains powered.

## Canonical Continuity Stack — Absolute

Every strip must use the smallest relevant set of approved references in this order:

1. current strip prompt / source story authority
2. canonical character PNGs for physically visible characters
3. approved canonical environment reference(s) for the current location/angle
4. approved canonical core-object reference(s) when a plot-critical recurring object is visible or changing state
5. immediately previous APPROVED strip for temporary pose, wardrobe, lighting, prop state, and seam continuity

Environment canonicals control architecture, room relationships, furniture/appliance placement, camera-axis logic, and recurring background identity. Object canonicals control the object's body/design and approved supernatural state vocabulary. A previous strip must never be allowed to propagate a geometry/object-design mistake that conflicts with an approved canonical reference; reject/regenerate the drift instead.

## New Chapter / New Environment Rule — Absolute

Before production of every new manhwa chapter:
- inventory every environment used in the chapter
- create or reuse an approved environment canonical pack for each environment
- create a new pack for any location not already canonically defined
- identify plot-critical recurring objects and create/reuse object canonicals before their first important appearance

Every new environment gets at least a geometry/orientation reference and a canonical establishing view. Recurring environments require a multi-angle pack, key-zone details, and relevant lighting states.

See:
- `Environment-References/`
- `Object-References/`

## No-Dead-Space Rule — Absolute

Vertical space is part of the storytelling, but unused canvas is not.

A large gap is allowed only when it clearly performs a story function such as:
- an existing narration/time caption
- hesitation or silence
- suspense/reveal delay
- a sound-first beat using an already scripted SFX
- atmosphere/environment continuation
- reaction hold
- transition between scenes or power states

Never invent filler narration, dialogue, or SFX just to occupy space. If a strip would otherwise end with a huge blank tail, expand the existing composition, canonical environment, reaction, darkness/rain/effect field, or use only a compact seam buffer. Reject any strip that feels empty, cut off, broken, or unfinished.

## Reference Goal

The supplied Asura-style reader example is used only to study professional continuous-reader behavior: one long chapter, sequential same-width image delivery, variable vertical pacing, large reveals, mobile lettering, integrated SFX, and invisible technical image boundaries.

Do not copy another title's exact artwork, characters, poses, panel compositions, backgrounds, dialogue, or proprietary assets.

## Core Files

- `reference-vibe-profile.md` — target reading behavior and visual density
- `style-guide.md` — rendering rules
- `vertical-scroll-layout-guide.md` — continuous layout, pacing, and no-dead-space rules
- `seam-continuity-protocol.md` — cross-strip continuation rules
- `lettering-sfx-guide.md` — dialogue, narration, device text, and SFX
- `generation-workflow.md` — sequential production/approval workflow
- `prompt-template.md` — technical-strip prompt template
- `Environment-References/` — canonical architecture/location system
- `Object-References/` — recurring plot-object identity/state system
- `pilot-promotion-gate.md` — requirements before replacing the existing comic pipeline
