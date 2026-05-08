# Nivoda Brand System

The single source of truth for Nivoda's brand identity — colours, typography, voice, and application rules.

## Who this is for

Anyone producing something that represents Nivoda: slide decks, proposals, marketing pages, emails, documentation, social assets. Also consumed by AI agents that generate on-brand content.

## Quick start

**Need hex codes for a presentation?**

| Use for | Hex |
|---------|-----|
| Brand primary (violet) | `#6330f5` |
| Warm light background | `#f5f0ec` |
| Text | `#0c0a09` |
| Secondary text | `#57534e` |
| White | `#ffffff` |
| Off-white | `#fafaf9` |

**Need the fonts?**
- **Headlines:** Nanum Myeongjo — [Google Fonts](https://fonts.google.com/specimen/Nanum+Myeongjo). Display, page titles, section headers only.
- **Body & UI:** Inter — [Google Fonts](https://fonts.google.com/specimen/Inter). Weight 400 for body, 500 for labels and buttons.
- **Labels / structure:** JetBrains Mono — [Google Fonts](https://fonts.google.com/specimen/JetBrains+Mono). Uppercase labels, eyebrows, metadata.

**Need logos?** All approved variants live in `assets/logos/`. SVG source also embedded in `docs/design.md`.
- `wordmark-white.svg` — Use on dark backgrounds
- `wordmark-black.svg` — Use on light backgrounds
- `icon-white.svg` — Icon only, dark backgrounds
- `icon-black.svg` — Icon only, light backgrounds

**Want to see the brand in context?**
- `guidelines/editorial-guidelines.html` — the living brand vocabulary: colour, typography, buttons, spacing, photography, iconography. Includes live interactive demos of the violet reveal principle.

## The one file to read

**`docs/design.md`** — the consolidated single source of truth. All brand primitives, application rules, voice, and writing style in one document. This is what agents read, and what humans reference for brand decisions.

## For AI agents

Read `docs/design.md` in full. Then read `docs/agent-instructions.md` for the rules around gaps and mode identification.

## Relationship to Clarity V2

This repo defines the **what** and **why** of the Nivoda brand. Clarity V2 (`../clarity-v2/`) defines the **how** for UI specifically. Colour and typography values here are sourced from Clarity V2's design tokens — they're the same values, accessible for non-code contexts.

## Owner

Chris Learey — Design Lead. All brand decisions flow through Chris. If something is marked as a BRAND GAP, don't improvise — flag it.
