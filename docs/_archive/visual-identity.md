# Visual Identity

The single source of truth for Nivoda's visual identity. All values here are sourced from Clarity V2 design tokens (last synced 2026-04-15). If a value changes, it changes in Clarity V2 first, then gets updated here.

---

## Brand direction

Nivoda's brand sits at the intersection of three identities:

1. **Human, local, relational.** Century-old tradition of real people doing business with real people. Independent jewellers, family businesses, trusted suppliers. Manifests in: warm photography of real people, friendly human imagery, approachable tone.

2. **Luxury marketplace.** High-end products deserve high-end presentation. Diamonds, fine jewellery, certified stones. Manifests in: serif display typography, restrained use of colour, generous whitespace, warm neutral palette.

3. **Fintech backbone.** A serious credit business underpins the platform. Trust, reliability, financial infrastructure. Manifests in: clean data presentation, confidence in tone, dual-context palette that works across light and dark surfaces.

The brand expression is **warm and restrained**. A dual-context palette — warm light surfaces (`#f5f0ec`) with white cards, dark surfaces (`#0c0a09`) for immersive moments. Violet is precious and reserved. Photography and serif typography carry the warmth.

---

## Identity

- Company name: **Nivoda**
- Description: The global B2B marketplace for diamonds and jewellery
- Tagline: <!-- BRAND GAP: needs definition -->
- Brand colour name: **violet** (not purple)
- Neutral colour name: **stone** (warm grey, not cool grey)
- Black philosophy: soft black (`#0c0a09`) not true black (`#000000`) — warmth, not harshness
- Theme: **dual-context** — warm light (`#f5f0ec`) with white cards, dark (`#0c0a09`) for immersive moments

---

## Logo

### Approved variants

All logos live in `assets/logos/` as canonical SVG assets. Use these, never recreate or approximate.

- **wordmark-white.svg** — Full wordmark in white. Use on dark backgrounds or dark photography.
- **wordmark-black.svg** — Full wordmark in black. Use on light backgrounds, white surfaces, or light photography.
- **icon-white.svg** — Icon only, white. Use when wordmark is unavailable (small spaces, favicons, app icons).
- **icon-black.svg** — Icon only, black. Use when wordmark is unavailable on light backgrounds.

### Usage rules

**Safe backgrounds:** white (`#ffffff`), off-white (`#fafaf9`), dark (`#0c0a09`), dark photography/imagery

**Minimum clear space:** 16px on all sides (or 1/4 of logo height, whichever is larger). Nothing else should appear in this space — no text, icons, borders, or other elements.

**Minimum size:**
- **Web/digital:** 40px width (wordmark), 24px width (icon)
- **Print:** 1 inch / 25mm width (wordmark), 0.5 inch / 12mm width (icon)
- Below these sizes, logos become illegible. Do not render smaller.

**Maximum scale:** No limits. Scale up as needed, but always maintain aspect ratio. Use SVG for infinite scalability.

**Co-branding:** When Nivoda logo appears alongside partner or partner logos, maintain equal or greater visual weight. Minimum 16px clear space between logos.

### Never
- Stretch, rotate, or distort the logo
- Change the logo colours
- Place on backgrounds that reduce legibility
- Recreate or approximate — always use the canonical asset from `/logos`
- Add effects (shadows, gradients, outlines)

---

## Colour

### Quick reference

The six values someone building a slide deck, doc, or email needs immediately:

| Use for | Hex | Token |
|---------|-----|-------|
| Brand accent (dark surfaces) | `#9886ff` | violet-400 |
| Brand accent (light surfaces) | `#6330f5` | violet-600 |
| Brand light (tinted backgrounds) | `#f4f2ff` | violet-50 |
| Text (primary) | `#0c0a09` | stone-950 |
| Text (secondary) | `#57534e` | stone-600 |
| Background (white) | `#ffffff` | — |
| Background (off-white) | `#fafaf9` | stone-50 |

### Brand (Violet) — full scale

The signature Nivoda colour.

| Tier | Hex | OKLCH |
|------|-----|-------|
| 50 | `#f4f2ff` | `oklch(0.966 0.0174 293.1)` |
| 100 | `#e9e8ff` | `oklch(0.939 0.0309 287.8)` |
| 200 | `#d7d4ff` | `oklch(0.886 0.0589 288.3)` |
| 300 | `#bab2ff` | `oklch(0.798 0.1082 288.5)` |
| 400 | `#9886ff` | `oklch(0.69 0.1729 287.8)` |
| 500 | `#7655fd` | `oklch(0.582 0.2362 285.4)` |
| 600 | `#6330f5` | `oklch(0.515 0.2644 284)` |
| 700 | `#5620e1` | `oklch(0.47 0.2559 283.2)` |
| 800 | `#481abd` | `oklch(0.414 0.2239 283.6)` |
| 900 | `#3d189a` | `oklch(0.364 0.1886 285.1)` |
| 950 | `#230c69` | `oklch(0.271 0.1444 282.3)` |

### Neutral (Stone) — full scale

Warm greys for text, backgrounds, and borders.

| Tier | Hex | OKLCH |
|------|-----|-------|
| 50 | `#fafaf9` | `oklch(0.985 0.0013 106.4)` |
| 100 | `#f5f5f4` | `oklch(0.97 0.0013 106.4)` |
| 200 | `#e7e5e4` | `oklch(0.923 0.0026 48.7)` |
| 300 | `#d6d3d1` | `oklch(0.869 0.0043 56.4)` |
| 400 | `#a8a29e` | `oklch(0.716 0.0091 56.3)` |
| 500 | `#78716c` | `oklch(0.553 0.0116 58.1)` |
| 600 | `#57534e` | `oklch(0.444 0.0096 73.6)` |
| 700 | `#44403c` | `oklch(0.374 0.0087 67.6)` |
| 800 | `#292524` | `oklch(0.268 0.0063 34.3)` |
| 900 | `#1c1917` | `oklch(0.216 0.0061 56)` |
| 950 | `#0c0a09` | `oklch(0.147 0.0041 49.2)` |

### Status colours

**Green (success)** — confirmations, positive states, completed actions

| Tier | Hex |
|------|-----|
| 50 | `#f3faf6` |
| 100 | `#d6f2e3` |
| 200 | `#b4e4cb` |
| 300 | `#93d5b3` |
| 400 | `#74c49c` |
| 500 | `#59b186` |
| 600 | `#479570` |
| 700 | `#3d745c` |
| 800 | `#315345` |
| 900 | `#25362f` |
| 950 | `#1e2724` |

**Red (error)** — errors, destructive actions, critical alerts

| Tier | Hex |
|------|-----|
| 50 | `#fef2f2` |
| 100 | `#fee2e2` |
| 200 | `#fecaca` |
| 300 | `#fca5a5` |
| 400 | `#f87171` |
| 500 | `#ef4444` |
| 600 | `#dc2626` |
| 700 | `#b91c1c` |
| 800 | `#991b1b` |
| 900 | `#7f1d1d` |
| 950 | `#450a0a` |

**Amber (warning)** — caution, attention needed, pending states

| Tier | Hex |
|------|-----|
| 50 | `#fffbeb` |
| 100 | `#fef3c7` |
| 200 | `#fde68a` |
| 300 | `#fcd34d` |
| 400 | `#fbbf24` |
| 500 | `#f59e0b` |
| 600 | `#d97706` |
| 700 | `#b45309` |
| 800 | `#92400e` |
| 900 | `#78350f` |
| 950 | `#451a03` |

**Blue (info)** — informational states, links, neutral highlights

| Tier | Hex |
|------|-----|
| 50 | `#eef4ff` |
| 100 | `#d9e6ff` |
| 200 | `#bcd4ff` |
| 300 | `#8ebaff` |
| 400 | `#5893ff` |
| 500 | `#326cff` |
| 600 | `#1e4cf5` |
| 700 | `#1436e1` |
| 800 | `#172cb6` |
| 900 | `#192b8f` |
| 950 | `#141c57` |

### The violet rule

Violet is precious. It is never scattered — it is placed deliberately as a finishing accent. Two distinct uses govern it.

#### 1. Call and response (Nanum Myeongjo display headlines only)

Italic violet text (`<em>` coloured violet) appears **only at the final beat of a Nanum Myeongjo headline**. Neutral text sets up the phrase; violet resolves it at the very end — italic, final word or short phrase only.

**Hard rules:**
- Nanum Myeongjo headlines only — never in Inter body text, never in subtitles, never in JetBrains Mono
- Final beat only — never mid-phrase, never interrupting
- Always italic — the italic is part of the gesture, not optional
- Light context: violet-600 (`#6330f5`) for the response em
- Dark context: violet-500 (`#7655fd`) for the response em (more visual mass at display size)

**Correct:**
- "Design becomes a *systems function.*" — violet italic at the final beat, Nanum Myeongjo headline ✓
- "A market built on *trust.*" — single word, final beat ✓

**Wrong:**
- "The platform is built for *scale.*" in Inter body text ✗ — wrong typeface
- "A *great* platform." ✗ — mid-phrase, not a final beat
- "03 — CATEGORY" eyebrow in violet ✗ — mono labels are grey (see section 2 below)

#### 2. Mono labels: grey by default

JetBrains Mono labels — eyebrows, card labels, captions, metadata, specimen headings, pagination — are **grey by default**.

- Light context: stone-500 (`#78716c`)
- Dark context: stone-400 (`#a8a29e`)

The violet in an eyebrow composition is the **hairline** (96px wide, 1px) that sits beneath the eyebrow text — not the eyebrow text itself. The text is always neutral. The hairline carries the brand accent.

Violet mono text is a rare exception used only in deliberate editorial compositions where the label itself is a designed moment — never in card labels, captions, or structural eyebrows.

#### The two-violet rule on dark surfaces

Saturated violet against near-black causes chromatic vibration in thin or small elements. Use two different tokens based on visual weight:

- **violet-500** (`#7655fd`) — elements with mass: Nanum display em, button hover fills, large accent blocks
- **violet-400** (`#9886ff`) — thin or small elements: 1px hairlines, decorative rules, thin borders

Light context does not require this split — **violet-600** (`#6330f5`) holds at every size on warm surfaces.

#### Composition budget

Maximum **2–3 violet roles per composition**. Count before adding. A violet headline em + a violet eyebrow hairline = 2. A violet button hover makes 3. Stop there. Violet scattered beyond 3 roles loses its precision and reads as decoration.

### Dark context (default brand expression)

For immersive sections, hero moments, and presentations. Violet-400 (`#9886ff`) for text accents. Button hover: violet-400 fill, white text.

| Element | Rest state | Hover state |
|---------|-----------|-------------|
| Button (primary) | stone-200 fill (`#e7e5e4`), dark text, 999px radius | violet-400 fill (`#9886ff`), white text |
| Button (secondary) | transparent, stone-700 border (`#44403c`), muted text, 999px radius | violet-400 text, violet-400 border |
| Card border | subtle (stone-700 `#44403c`) | lighter (stone-400 `#a8a29e`) |
| Card link | muted text (stone-500 `#78716c`) | white text — triggers on card hover, not link hover |
| Text link (inline) | secondary text (stone-400 `#a8a29e`), underline | violet-400 text, underline |
| Labels/eyebrows | stone-400 text (`#a8a29e`); violet-400 (`#9886ff`) hairline beneath eyebrow only | — |
| Numbered indices | stone-400 (`#a8a29e`) | — |

Dark context palette: stone-950 `#0c0a09` (deep bg), stone-900 `#1c1917` (surface), stone-800 `#292524` (elevated), stone-700 `#44403c` (borders), stone-200 `#e7e5e4` (light fills), stone-50 `#fafaf9` (text), violet-400 `#9886ff` (hairlines and thin borders only).

### Light context (warm light surface `#f5f0ec`, white cards, modals, marketing sections)

Violet-600 (`#6330f5`) for text accents, labels, and interactive fills on light surfaces.

| Element | Rest state | Hover state |
|---------|-----------|-------------|
| Button (filled) | dark fill (stone-950 `#0c0a09`), white text | violet fill (`#6330f5`), white text |
| Button (outline) | transparent, light border (stone-200 `#e7e5e4`), dark text, 999px radius | violet text (`#6330f5`), violet border |
| Card border | light grey (stone-200 `#e7e5e4`) | violet (`#6330f5`) — border and link change together on card hover |
| Card link | muted text (stone-500 `#78716c`) | violet (`#6330f5`) — triggers on card hover, not link hover |
| Text link (inline) | muted text (stone-500 `#78716c`) | violet (`#6330f5`) |

### Context separation

Keep each context internally consistent. White cards belong on the warm light surface (`#f5f0ec`), not floating on dark backgrounds. Dark sections should stay dark throughout — use stone-900 for elevated surfaces within dark contexts, not white cards.

### Colour application rules

| Role | When to use | When NOT to use |
|------|------------|-----------------|
| Brand violet (text) | Italic em at final beat of Nanum Myeongjo headline only (call-and-response). Violet-500 (`#7655fd`) on dark, violet-600 (`#6330f5`) on light. Rare deliberate label accent in editorial compositions only. | Body text. Inter text. Subtitles. Mid-phrase. JetBrains Mono labels (those are grey by default). |
| Brand violet (fills) | Button hover fills on both contexts. Violet-500 on dark, violet-600 on light. | Resting-state fills. Large background areas. |
| Neutral (stone) | Body text, headings, backgrounds, borders, cards, buttons | Never use pure black (`#000`) — always use stone scale |
| White | Card surfaces on warm light background. Text on dark surfaces. | As page-level background — use warm light `#f5f0ec` instead |
| Success (green) | Confirmation messages, positive metrics, completed states | Decorative use, brand expression |
| Error (red) | Error messages, destructive action warnings, validation failures | General emphasis (use amber instead) |
| Warning (amber) | Caution states, pending actions, non-critical alerts | Errors (use red) or positive states (use green) |
| Info (blue) | Informational banners, neutral highlights | Primary CTAs (use violet on light) or links on dark (use white) |

### Accessibility

- All text/background combinations must meet WCAG AA (4.5:1 body, 3:1 large text)
- Never rely on colour alone to convey meaning — pair with text or iconography
- Stone-50 on stone-950: high contrast, passes AAA
- Violet-600 on white: 3.97:1 — passes AA for large text only. Use violet-700+ for small text on white
- On dark backgrounds, ensure sufficient contrast between stone tiers (e.g. stone-400 text on stone-950 bg)

---

## Typography

### Font families

**Nanum Myeongjo** — headlines only. Display serif for hero headings, page titles, section headers. Korean typeface with formal elegance; carries warmth and reinforces "high-end marketplace" pillar.
- Source: https://fonts.google.com/specimen/Nanum+Myeongjo
- Stack: `Nanum Myeongjo, serif`
- Usage: display text (48px), page titles (36px), section headers (24px). Headlines and display only. Do not use for body or UI.

**Inter** — body copy and everything else. Primary typeface for paragraphs, UI, labels, supporting text, navigation, UI copy.
- Source: https://fonts.google.com/specimen/Inter
- Stack: `Inter, system-ui, sans-serif`
- Usage: body paragraphs, buttons, form labels, captions, navigation, all UI elements.

**JetBrains Mono** — monospaced, for technical and structural content. Code, data tables, metadata labels, eyebrows, pagination, system-level text, and any content that signals "structure" or "precision." Works especially well for uppercase labels with wide letter-spacing (0.08–0.16em) — it carries a systems-thinking tone that reinforces the brand's fintech backbone.
- Source: https://fonts.google.com/specimen/JetBrains+Mono
- Stack: `JetBrains Mono, monospace`
- Usage: code and data (always), but also: eyebrow labels, slide/page pagination, category tags, role labels, numbered indices, metadata lines. Anywhere the content is structural rather than narrative.

### Approved weights

Only these four. Do not use light (300) or extra-bold (800+).

| Weight | Value | Usage |
|--------|-------|-------|
| Normal | 400 | Body text, descriptions, supporting content. **Also all Nanum Myeongjo display and headline text** — the serif carries its own weight through size, not boldness. |
| Medium | 500 | Subsection headings (Inter), labels, emphasis within body, JetBrains Mono labels |
| Semibold | 600 | Section headings (Inter), page titles (Inter), navigation |
| Bold | 700 | Strong emphasis (use sparingly). Not for Nanum Myeongjo — serif display is always 400. |

### Size scale

#### UI scale (product, web, documentation)

| Token | Size | Usage |
|-------|------|-------|
| xs | 12px | Labels, metadata, helper text |
| sm | 14px | Supporting text, captions, table cells |
| base | 16px | Default body text |
| lg | 18px | Emphasised body, lead paragraphs |
| xl | 20px | Subsection headings |
| 2xl | 24px | Section headings |
| 3xl | 30px | Page titles |
| 4xl | 36px | Marketing headings |
| 5xl | 48px | Hero/display text |

#### Presentation scale (1920×1080 projected decks)

Presentation contexts require a larger scale. These sizes are calibrated for readability at projection distance on a 1920×1080 canvas.

| Token | Size | Usage |
|-------|------|-------|
| pres-meta | 13–14px | Pagination, chrome labels, footer text (JetBrains Mono) |
| pres-label | 14–18px | Eyebrows, category labels, role labels (JetBrains Mono, uppercase) |
| pres-body-sm | 18–20px | Footnotes, supporting text, italic closers |
| pres-body | 22–26px | Card body text, list items, descriptions |
| pres-lede | 28–36px | Lead paragraphs, subheadings, card titles (Nanum Myeongjo) |
| pres-title | 88px | Slide titles (Nanum Myeongjo, 400 weight) |
| pres-quote | 96px | Pull quotes, section cover statements (Nanum Myeongjo) |
| pres-hero | 180px | Title slide hero text (Nanum Myeongjo, 400 weight) |

### Line heights

| Token | Value | Usage |
|-------|-------|-------|
| tight | 1.25 | Headings, display text |
| normal | 1.5 | Body text, default |
| relaxed | 1.625 | Long-form reading |

### Typographic hierarchy for non-UI contexts

#### Documents and marketing

| Level | Size | Weight | Line height | Use |
|-------|------|--------|-------------|-----|
| Display | 48px | Normal (400) | 1.25 | Title slides, hero headlines (Nanum Myeongjo) |
| Heading 1 | 36px | Normal (400) | 1.25 | Page/slide titles (Nanum Myeongjo) |
| Heading 2 | 24px | Normal (400) | 1.25 | Section headers (Nanum Myeongjo) |
| Heading 3 | 20px | Medium (500) | 1.5 | Subsection headers (Inter) |
| Body | 16px | Normal (400) | 1.5 | Default text (Inter) |
| Body small | 14px | Normal (400) | 1.5 | Supporting text, footnotes (Inter) |
| Caption | 12px | Medium (500) | 1.5 | Labels, metadata (JetBrains Mono) |

#### Presentations (1920×1080)

| Level | Size | Weight | Line height | Use |
|-------|------|--------|-------------|-----|
| Hero | 180px | Normal (400) | 0.95 | Title/bookend slides (Nanum Myeongjo) |
| Pull quote | 96px | Normal (400) | 1.05 | Section cover statements (Nanum Myeongjo) |
| Title | 88px | Normal (400) | 1.05 | Slide titles (Nanum Myeongjo) |
| Card heading | 36–42px | Normal (400) | 1.2 | Card and pillar headings (Nanum Myeongjo) |
| Lede | 28–36px | Normal (400) | 1.4 | Lead paragraphs (Inter or Nanum Myeongjo italic) |
| Body | 22–26px | Normal (400) | 1.55 | Card body, list items (Inter) |
| Eyebrow | 14–18px | Medium (500) | — | Category/section labels (JetBrains Mono, uppercase, 0.14em tracking) |
| Chrome | 13px | Normal (400) | — | Pagination, footer (JetBrains Mono) |

### Typography rules

**Hard rules — no exceptions:**

- **Nanum Myeongjo is always weight 400.** The serif carries authority through size, not boldness. Never bold.
- **Nanum Myeongjo is never uppercase.** Sentence case only. The typeface's elegance depends on mixed case. Uppercase belongs to JetBrains Mono exclusively.
- **JetBrains Mono is uppercase labels and headings only.** Never sentences. Never body text. Never all-lowercase. If you are writing a sentence (subject + verb + object), use Inter. JetBrains Mono is for structural tokens: eyebrow labels, card labels, captions, metadata, pagination, table headers, specimen headings — short, uppercase, functional.
- **Call-and-response is Nanum Myeongjo display headlines only.** Italic violet `<em>` at the final beat belongs to Nanum Myeongjo headlines. It does not apply to Inter text, JetBrains Mono labels, subtitles, or any other context. Mono labels have nothing to do with call-and-response.
- **Never use weights outside the four approved.** No 300 (light), no 800+ (extra bold).
- **UI contexts use the UI scale. Presentation contexts use the presentation scale.** Do not mix.
- **Letter-spacing for JetBrains Mono labels:** 0.12em standard, 0.08em minimum. Wide tracking is intentional — it carries the precision signal.

---

## Spacing

4px base unit. Use for consistent padding, margins, and gaps.

| Token | Value |
|-------|-------|
| 0 | 0px |
| 1 | 4px |
| 2 | 8px |
| 3 | 12px |
| 4 | 16px |
| 5 | 20px |
| 6 | 24px |
| 8 | 32px |
| 10 | 40px |
| 12 | 48px |
| 16 | 64px |
| 20 | 80px |
| 24 | 96px |
| 32 | 128px |

### Negative space

Luxury is not packed. Breathing room is an active design decision — it communicates authority, restraint, and confidence. The brand should never feel hurried. When in doubt, give it more room. A cramped layout signals anxiety; a generous layout signals that Nivoda knows its worth.

**The rule: if it feels cramped, it is cramped.**

| Context | Spacing intent |
|---------|---------------|
| Between major sections | 128px — a full breath between subjects |
| Before a subsection heading (h3) | 80–96px — clear separation from what came before |
| After eyebrow, before h2 | 32px for hairline, then 64px to first body content |
| Between cards in a grid | 32px — enough to read as distinct objects |
| Inside a card | 40px padding — content should not touch the edge |
| Between body paragraphs | 24px — measured but unhurried |
| h2 margin-bottom | 64px |
| h3 margin-top | 80px base, 96px for major conceptual breaks |

This applies at every scale — between major sections, between subsections within a section, between cards, between a heading and its body text. Self-contained objects (cards side by side) can be adjacent; everything else needs room.

---

## Border radius

Two distinct values create visual hierarchy and distinguish component types.

| Token | Value | Usage |
|-------|-------|-------|
| full | 999px (or 50%) | Buttons and inputs only. Pill-shaped buttons create approachable, action-oriented feel. |
| sm | 2px | Cards only. Minimal softness; maintains formal, structured appearance of content containers. |

**Buttons:** Fully rounded (999px) — soft, inviting, action-focused.
**Cards:** Near-square (2px) — formal, structured, content-focused.

Same hover interaction patterns, different visual language.

---

## Shadows

| Token | Value |
|-------|-------|
| sm | `0 1px 2px 0 rgba(0,0,0,0.05)` |
| md | `0 4px 6px -1px rgba(0,0,0,0.1)` |
| lg | `0 10px 15px -3px rgba(0,0,0,0.1)` |
| xl | `0 20px 25px -5px rgba(0,0,0,0.1)` |

---

## Imagery & photography

Two photography modes. Each has different rules and serves a different context.

---

### Mode 1 — Editorial photography

For marketing pages, decks, hero moments, longform content, and anywhere the brand tells a story. Human presence. Three governing principles.

#### 01 — Perspective: through the jeweller's eyes

Every photograph is shot from **inside the partner's world, looking out**. Never outside, looking in. The jeweller is not a subject we observe from a distance — we sit beside them, behind their counter, in their consultation. Same posture Shopify takes with merchants.

**Practically:** Position the camera where the jeweller would stand. Subjects face the camera as if greeting the jeweller. Settings are jewellery-trade environments — workbenches, vault rooms, showroom floors, supplier offices. Avoid corporate-Nivoda settings; the empathy is always with the retailer.

#### 02 — Light: luxury studio, cinematic depth

Soft directional studio lighting — boutique invite, not retail flood. High-end fashion-advertising aesthetic. Cinematic depth of field: subject sharp, foreground and background falling soft. Reflection and refraction welcomed — through glass, vitrines, polished surfaces, diamonds — adding sophistication and tactile richness. Saul Leiter is the touchstone for the layered, semi-obscured quality.

**Practically:** Shoot wide aperture (f/1.4–f/2.8). Diffuse the key light. Allow secondary planes to blur. Look for reflections in vitrines, refractions through diamonds, light catching on glass.

#### 03 — Palette: moody and golden, with measured colour

The dominant tonal vocabulary is black, white, and golden warmth. Tungsten skin tones, amber highlights, deep charcoal shadows. Cool whites, fluorescent blues, and clinical lighting are out — they read as retail, not boutique.

Photography is **not pure monochrome**. Selective colour — a flash of red velvet, the green of an emerald, the cobalt of a sapphire box, the warmth of skin — is welcome and earns its place. Warm and golden as the base; colour as the accent that proves the photograph is alive. Never desaturated, never grayscale.

#### AI generation prompt (editorial)

```
[subject/scene], shot from the jeweller's perspective looking out, soft directional studio light, cinematic depth of field at f/1.4–f/2.8, reflection or refraction in frame, warm golden tonal palette with selective colour accents, high-end fashion-advertising aesthetic, Saul Leiter inspiration, never sterile or retail
```

---

### Mode 2 — Promotional banners (the procession)

For category banners inside the marketplace. No human presence — the product is the subject. Three ideas in every frame.

#### 01 — Scale
Products arranged in a receding line, one behind the other, extending infinitely into depth. The end is always out of frame. This is a big operation — an infinite handoff, always running.

#### 02 — Consistency
Every item in the line is identical. Same bracelet. Same ring setting. Same proportions. Whatever the order number, the quality doesn't vary. Reliability is built into the composition.

#### 03 — Cadence
The spacing between items is the rhythm of repeat business. First order. Second. Third. Fourth. The sequence is already drawn for the customer. The visual rhythm and the business relationship are the same thing.

#### Spec

| | |
|---|---|
| Aspect ratio | Approximately 5:1 — wide, shallow banner format. Never square, never portrait. |
| Background | Near-black studio surface. No editorial warmth. The dark field makes products luminous. |
| Subject | Product only. No human presence, no jewellery-trade setting, no context. |
| Arrangement | Products in a receding sequence. Minimum five items visible; the line must extend to blur. No scattered placement. |
| Depth of field | Sharp foreground, softening to blur as the line recedes. |
| Colour | Warm product tones (gold, silver, diamond) against cool dark background. No artificial colour overlays. |

#### AI generation prompt (banners)

```
[product category], arranged in a receding procession on a dark studio surface, cinematic depth of field, sharp foreground softening to blur, warm metallic product tones against near-black background, infinite-supply framing, no human presence, no context, product-only, professional product photography
```

---

## Iconography

**Icon set:** Lucide outlined only. No filled/solid variants.

| | |
|---|---|
| Stroke | 1.5px |
| Sizes | 16px (small), 20px (standard), 24px (large) |
| Colour | Inherits from surrounding text colour |
| Style | Outlined only — never filled, never custom |

**Curated for brand-relevant concepts** — gems, marketplace, partnership, craft, certification, origin, provenance. Never generic UI plumbing (settings cog, hamburger, chevrons, ellipsis) unless functionally required. Icons are not decoration.

**Approved 30-icon set** (pick from these first; introducing additional Lucide glyphs requires sign-off from Chris):

- Jewellery & gems: `gem`, `crown`, `sparkles`, `heart`, `flame`, `award`
- Marketplace & commerce: `store`, `globe`, `handshake`, `shopping-bag`, `package`, `truck`
- Partnership & value: `users`, `user-check`, `coins`, `badge-check`, `shield-check`, `lock`
- Craft & precision: `key`, `microscope`, `scale`, `compass`, `pen-tool`, `stamp`
- Documentation & origin: `file-check`, `clipboard-check`, `book-open`, `map-pin`, `mountain`, `history`

---

*Last updated: 2026-05-07. Sections marked BRAND GAP need input from the design lead (Chris Learey). Major update: violet rule refined (call-and-response is Nanum-only; mono labels are grey by default), two-violet dark rule formalised, typography hard rules added (JetBrains Mono uppercase labels only; Nanum never uppercase), negative space principle added, photography section rewritten with three editorial principles + promotional banner mode, iconography curated set documented.*
