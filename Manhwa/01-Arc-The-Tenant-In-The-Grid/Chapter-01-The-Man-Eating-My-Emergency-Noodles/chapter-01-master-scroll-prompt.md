# Chapter 1 Master Continuous-Scroll Prompt

This document is the presentation authority for the full Chapter 1 Manhwa production.

```text
Create Chapter 1 of "My Roommate Only Appears During Blackouts" as ONE CONTINUOUS full-color vertical Korean-webtoon/manhwa chapter.

PRODUCTION SOURCE
Use the locked Chapter 1 Manhwa beat plan, strip manifest, current strip prompts, and approved reusable canonicals. Historical P001–P018 labels are mapping shorthand only.

GLOBAL PRODUCTION RULES — ABSOLUTE
`Manhwa/style-guide.md`, `Manhwa/lettering-sfx-guide.md`, `Manhwa/seam-continuity-protocol.md`, `Manhwa/vertical-scroll-layout-guide.md`, and `Manhwa/generation-workflow.md` apply to every technical strip even when they are not repeated in an individual strip attachment list. A strip prompt may make these rules stricter but may never loosen them.

INTERNAL PLAN
146 internal read beats V01–V146 and 32 technical strips strip-001–strip-032. Never render those IDs.

FINAL READER EXPERIENCE
No traditional pages, page numbers, circled panel numbers, reader-visible strip divisions, or repeated headers/footers.

CANONICAL CONTINUITY STACK
1. current user instruction
2. current chapter story/strip script
3. current approved character canonical WebP(s)
4. approved reusable environment WebP(s)
5. approved reusable object WebP(s)
6. previous approved rendered strip temporary state

REUSABLE REFERENCES
Environment: `Manhwa/Environment-References/Unit-2407/`, `Manhwa/Environment-References/Building-Shared-Areas/`.
Objects: current approved WebPs under `Manhwa/Object-References/` for smart speaker / TV / refrigerator / electrical-operation guide / brass backup key.
Reuse these in later chapters whenever the same physical place/object returns.

REFERENCE IMAGE FORMAT
Reference prompts may generate PNG first locally. After visual approval, manually convert to WebP. The exact committed WebP is the production attachment authority.

REFERENCE AVAILABILITY — BLOCKING
If any required canonical WebP listed by a strip is missing, stale, wrong-path, or unapproved, STOP before strip generation. Do not improvise a substitute and do not promote draft/reference-prompt text into visual approval.

Every strip attachment block must use the exact current repository `.webp` filename, not an obsolete PNG or vague shorthand.

BLACK READ-SLICE GRAMMAR — ABSOLUTE
Every DISTINCT vertical reading slice/composition uses a small black gutter before the next distinct slice.
When two distinct camera slices share one horizontal row, separate them with a diagonal/slanted black divider. No face/text/balloon/prop/background crosses that divider.
Black gutters are compact reading grammar, not giant dead bands.
Do not insert a visible black bar at an A/E technical file seam when artwork/effect must stitch continuously.

STYLE — ABSOLUTE
STRICT FLAT 2D HUMAN-DRAWN KOREAN MANHWA/WEBTOON ILLUSTRATION.
Clean intentional line art, stable line weight, flat colors, restrained simple hard-edged cel shading only, matte skin, matte hair, matte fabrics, matte walls/floors/furniture/appliances/screens, believable adult proportions, natural hands, stable canonical anatomy, and mobile-readable silhouettes/composition.
DO NOT render as photorealistic, semi-photorealistic, 3D, CGI, game art, cinematic film still, painterly realism, glossy/plastic/wet skin or hair, beauty-ad shine, heavy airbrush, heavy gradients, excessive bloom, rim light, lens flare, mirror-like reflections, excessive specular highlights, cinematic depth of field, cinematic color grading, hyper-detailed skin texture, or over-rendered AI-polished artwork.
Blackout, candle, rain, and device effects remain controlled flat shapes/contained accents. No room-flooding cinematic glow.
A previous strip may control temporary continuity but may NEVER propagate style drift against `Manhwa/style-guide.md`.

REAL-SCENARIO CONTINUITY
All movement, carried-object routes, prop counts, room axes, device states, power states, and dialogue/SFX ownership must remain physically coherent across all 32 strips. Follow `chapter-01-real-scenario-continuity-audit.md` and generation checklist.

SFX / LETTERING
For every sound verify PHYSICAL SOURCE → ACTION → SOUND → TIMING → PLACEMENT and any state change/consequence. Preserve exact scripted wording/source/type. Never invent filler SFX and never print production metadata.

NO DEAD BOTTOM — ABSOLUTE
Negative space must communicate something. Never leave a giant unused bottom tail and never invent filler text/SFX. Use existing action/reaction, canonical environment, atmosphere, reveal timing, or compact seam buffer.

POWER ARC
Strips 014–025 contain real Unit 2407 outage. Hyun-woo remains physical until Unit 2407 itself powers on. Strips 026–032 are normally powered.

CHAPTER END
End on visibly unplugged TV displaying `NEW TENANT CONFIRMED`; apartment lights flicker once `FZZT` but remain powered. End immediately on Nari reaction + hostile message.

FINAL APPROVAL RULE
Do not declare Chapter 1 production-complete from prompts/reference availability alone. Final approval requires all 32 rendered strips, sequential visual QA, seam/stitch QA, and a fresh clean-room visual audit proving strict flat 2D human-drawn compliance with zero unresolved mandatory defects.
```

## Deep-Hardening Binding Note — Absolute

The current Strip 001–032 prompts have been rewritten under the full `manhwa-2d-production-auditor` hardening pass. Their stricter per-strip rules are binding and override any looser generic wording above.

In particular, production must obey all of the following:
- attached approved WebPs are binding identity / geometry / object authorities, never loose inspiration
- every strip's `START / ALLOWED CHANGE / END` state ledger is mandatory
- adjacent vertical slices preserve hands, held objects, food/noodles, chopsticks, props, chair state, power state, and other micro-continuity unless a visible action changes them
- `unplugged` means the electrical plug is removed from the **wall-mounted socket/outlet** while the appliance-side cord stays attached; the loose plug and empty wall socket remain physically consistent until an explicit re-plug action
- narration treatment must follow the current scenario/event function rather than reuse one identical box design everywhere
- `V01`, `V-01`, P numbers, strip/beat/panel/scene/shot labels, and all other production metadata are forbidden in reader-facing art, especially at the top-left of a vertical slice
- if a desired camera/action conflicts with an attached reference, recompose the camera/action; never modify canon to make generation easier

Previously rejected or unhardened rendered attempts are not approved previous-strip continuity authorities. Retesting begins from Strip 001 under the current hardened prompt package.
