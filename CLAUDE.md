# CLAUDE.md

This file orients Claude at the start of every session in this repo. It is not for humans — see `README.md`.

## What this repo is

The Nivoda Brand System: the single source of truth for how Nivoda looks, sounds, and presents itself across all touchpoints. This is not a design system (that's Clarity V2) — it's the brand identity layer that the design system and everything else derives from.

## Relationship to other repos

- `../clarity-v2/` — the design system. Consumes brand primitives (colours, fonts) and implements them as design tokens and UI components.
- `../experience-framework/` — governance, principles, personas, surface rules. The "constitution" to Clarity V2's "law" and this repo's "identity".
- `../minivoda/clarity-digital-twin/` — the living digital twin. Consumes Clarity V2 components and by extension these brand values.

**Dependency flow:** brand-system → clarity-v2 (tokens) → clarity-v2 (components) → minivoda / platform

## Repo structure

```
brand-system/
├── CLAUDE.md                          ← you are here
├── README.md                          ← human-facing overview
├── docs/
│   ├── design.md                      ← THE FILE. All brand rules in one place.
│   ├── agent-instructions.md          ← entry point: gap protocol, mode identification
│   └── _archive/                      ← previous split-file versions (reference only)
│       ├── visual-identity.md
│       ├── brand-application-rules.md
│       ├── voice-and-tone.md
│       └── writing-style-guide.md
├── guidelines/
│   ├── editorial-guidelines.html      ← living visual source of truth (HTML)
│   └── font-specimen.html
├── handoffs/
│   └── JCK-brand-handoff.html
└── assets/
    ├── fonts/                         ← canonical .ttf files (Inter, JetBrains Mono, Nanum Myeongjo)
    ├── logos/                         ← canonical logo SVGs (wordmark-white/black, icon-white/black)
    └── images/
```

## Current status (2026-05-07)

**Complete:**
- Colour system (full scales, two-violet rule, dark/light context interactions, accessibility ratios)
- Typography (all three typefaces, full specs including letter-spacing and lede component)
- Buttons and interactive elements (all states, focus rings, inputs, links)
- Layout & spacing (4px base, page layout, grid system, negative space principle)
- Shadows, border radius
- Photography (editorial mode + banner/procession mode, AI prompts)
- Logos (4 SVG variants, inline in design.md)
- Iconography (Lucide outlined, approved 30-icon set)
- Brand modes (editorial vs UI, email, documentation, internal)
- Writing style (full-stop rule, capitalisation, grammar)

**Still open (BRAND GAPs — do not fill in):**
- Company tagline
- Three named voice principles
- Canonical terminology table
- UI copy patterns
- Date and currency format
- Co-branding / third-party rules

## Key files

- `docs/design.md` — **the single source of truth.** Everything an agent needs is in this one file. Read it in full before producing any brand output.
- `docs/agent-instructions.md` — entry point for agents. Gap protocol and mode identification.
- `guidelines/editorial-guidelines.html` — the living visual reference. When design.md and the HTML disagree, design.md holds the resolved canonical value.

## How to work in this repo

- **Values come from Clarity V2.** If a colour or font value changes, it changes in Clarity V2 first, then gets synced here. Don't originate values in this repo.
- **Rules originate here.** Application rules (when to use violet, how to write a CTA) are authored here and referenced by other repos.
- **BRAND GAP protocol.** If a section is marked BRAND GAP, don't fill it in. Flag it and wait for Chris (design lead) to make the decision.
- **design.md stays in sync.** After any Clarity V2 token change, update the values in design.md to match.

## Things to avoid

- Do not originate colour or typography values here — they come from Clarity V2.
- Do not improvise voice, tone, or terminology decisions — flag gaps for Chris.
- Do not add dependencies or build tools. This repo is markdown + assets. No npm, no build step.
- Do not create files outside the documented structure without discussing first.

## When in doubt

Ask Chris. He owns all brand decisions.
