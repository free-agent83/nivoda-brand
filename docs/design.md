# Nivoda Design Language

The single source of truth for how Nivoda looks, sounds, and presents itself. One file. Read it once and you have everything.

*Last updated: 2026-05-07. Values sourced from Clarity V2 design tokens. Owner: Chris Learey.*

---

## 01 — How to use this file

**For AI agents:** Read this file in full before producing any visual or written output. Every decision you need is here. Values are exact — do not interpolate or approximate. If something is marked BRAND GAP, do not fill it in; flag it and wait.

**For humans:** This is the reference. Use it to review brand application across surfaces.

**BRAND GAP protocol:** Any section marked `<!-- BRAND GAP -->` is unresolved. Do not improvise. Flag it to Chris (Design Lead) before proceeding.

**Reading order if cross-referencing the HTML:** `guidelines/editorial-guidelines.html` is the visual source of truth. This file is the prose encoding of everything that HTML renders. When they conflict, this file reflects the resolved canonical value.

---

## 02 — Brand direction

### The three pillars

Nivoda's brand sits at the intersection of three identities:

1. **Human, local, relational.** Century-old tradition of real people doing business with real people. Independent jewellers, family businesses, trusted suppliers. Manifests in: warm photography of real people, friendly human imagery, approachable tone.

2. **Luxury marketplace.** High-end products deserve high-end presentation. Diamonds, fine jewellery, certified stones. Manifests in: serif display typography, restrained use of colour, generous whitespace, warm neutral palette.

3. **Fintech backbone.** A serious credit business underpins the platform. Trust, reliability, financial infrastructure. Manifests in: clean data presentation, confidence in tone, dual-context palette that works across light and dark surfaces.

The brand expression is **warm and restrained**. A dual-context palette — warm light surfaces (`#f5f0ec`) with white cards, dark surfaces (`#0c0a09`) for immersive moments. Violet is precious and reserved. Photography and serif typography carry the warmth.

### Identity

| | |
|---|---|
| Company name | **Nivoda** |
| Description | The global B2B marketplace for diamonds and jewellery |
| Tagline | <!-- BRAND GAP: needs definition --> |
| Brand colour | **violet** (not purple) |
| Neutral colour | **stone** (warm grey, not cool grey) |
| Black | Soft black `#0c0a09` — warmth, not harshness. Never true black `#000000`. |
| Theme | **Dual-context** — warm light (`#f5f0ec`) with white cards, dark (`#0c0a09`) for immersive moments |

---

## 03 — Colour

### Colour tokens

All values sourced from Clarity V2. Do not originate values here.

**Violet scale**

| Token | Hex | OKLCH |
|-------|-----|-------|
| violet-50 | `#f4f2ff` | oklch(96% 0.022 282) |
| violet-100 | `#e9e8ff` | oklch(92% 0.042 282) |
| violet-200 | `#d7d4ff` | oklch(86% 0.075 282) |
| violet-300 | `#bab2ff` | oklch(77% 0.115 282) |
| violet-400 | `#9886ff` | oklch(67% 0.155 282) |
| violet-500 | `#7655fd` | oklch(56% 0.195 282) |
| violet-600 | `#6330f5` | oklch(48% 0.225 282) |
| violet-700 | `#5620e1` | oklch(42% 0.220 282) |
| violet-800 | `#481abd` | oklch(36% 0.200 282) |
| violet-900 | `#3d189a` | oklch(30% 0.175 282) |
| violet-950 | `#230c69` | oklch(20% 0.130 282) |

**Stone scale**

| Token | Hex |
|-------|-----|
| stone-50 | `#fafaf9` |
| stone-100 | `#f5f5f4` |
| stone-200 | `#e7e5e4` |
| stone-300 | `#d6d3d1` |
| stone-400 | `#a8a29e` |
| stone-500 | `#78716c` |
| stone-600 | `#57534e` |
| stone-700 | `#44403c` |
| stone-800 | `#292524` |
| stone-900 | `#1c1917` |
| stone-950 | `#0c0a09` |

**Status colours** (mid-tone reference only — no full scales used)

| Role | Hex |
|------|-----|
| Green · Success | `#59b186` |
| Red · Error | `#ef4444` |
| Amber · Warning | `#f59e0b` |
| Blue · Info | `#326cff` |

### Colour roles — canonical table

The definitive mapping of semantic role to token in each context.

| Role | Dark context | Light context |
|------|-------------|---------------|
| Background | stone-950 `#0c0a09` | warm `#f5f0ec` |
| Surface / card | stone-900 `#1c1917` | white `#ffffff` |
| Border | stone-700 `#44403c` | stone-200 `#e7e5e4` |
| Text — primary | stone-50 `#fafaf9` | stone-950 `#0c0a09` |
| Text — body / muted | stone-400 `#a8a29e` | stone-600 `#57534e` |
| Text — strong (`<strong>`) | stone-50 `#fafaf9` | stone-950 `#0c0a09` — weight 500 |
| Accent — display / fill | violet-500 `#7655fd` | violet-600 `#6330f5` |
| Accent — text / thin border | violet-400 `#9886ff` | violet-600 `#6330f5` |
| Hover fill | violet-500 `#7655fd` | violet-600 `#6330f5` |
| Eyebrow text | stone-400 `#a8a29e` | stone-500 `#78716c` |
| Eyebrow hairline | violet-400 `#9886ff` | violet-600 `#6330f5` |
| Inline link — rest | stone-300 `#d6d3d1` | stone-600 `#57534e` |
| Inline link — hover | violet-400 `#9886ff` | violet-600 `#6330f5` |

**Note on "Eyebrow text" vs "Eyebrow hairline":** These are separate roles. The eyebrow text is always grey (stone-400 dark / stone-500 light). The violet lives only in the 96px hairline beneath it. Never set eyebrow text to violet.

### The two-violet rule on dark

Saturated violet against near-black causes chromatic vibration in thin or small elements.

**Rule:**
- **Violet-500** (`#7655fd`) — only where violet has mass: Nanum Myeongjo display type, button hover fills, large accent blocks.
- **Violet-400** (`#9886ff`) — everywhere else on dark: small text, links, eyebrow hairlines, 1px borders and dividers, dots, any decorative line under 2px.

The lift from 500 to 400 pushes contrast against stone-950 from approximately 4.7:1 to 7.2:1, and desaturates the chromatic fringe in thin elements.

**Light context does not need this split.** Violet-600 holds at every size on warm surfaces.

**Hard rules:**
- Never use violet-600 on dark backgrounds
- Never use violet-500 for text or thin borders on dark
- Never use violet-400 for fills or display type on dark
- On light, violet-600 only — no split needed

### Call and response

Italic violet at the final beat of a Nanum Myeongjo headline. One gesture per composition. The brand's single typographic accent.

**Rules:**
- Nanum Myeongjo titles only. Never in Inter, never in JetBrains Mono.
- Final beat of the headline only. Never mid-phrase. Never the opening word.
- Always italic (`font-style: italic`).
- Colour: violet-600 `#6330f5` on light; violet-500 `#7655fd` on dark.
- One per composition. The response is rare because it is earned.

**Correct:**
> Design becomes *a systems function.* ✓
> A market built on *trust.* ✓

**Wrong:**
> The platform is built for *scale* in every market. ✗ (mid-phrase, not final beat)
> A subtitle with a *violet* beat ✗ (Inter, not Nanum)
> *Brilliance* at every price point. ✗ (opening word, not final)

### Composition budget

Maximum **2–3 violet roles per composition**. Example:
- Headline call-and-response em = 1
- Eyebrow hairline = 2
- Button hover = 3 (interaction state, so it counts separately)

Violet placed more than three times in a single composition is scattered, not intentional.

### Accessibility

| Pairing | Contrast | Result |
|---------|----------|--------|
| stone-50 on stone-950 | 19.2:1 | AAA |
| stone-950 on white | 19.2:1 | AAA |
| violet-400 on stone-950 | 6.77:1 | AA (all sizes) |
| violet-600 on white | 3.97:1 | AA (large text ≥18px only) |
| stone-400 on stone-950 | 4.55:1 | AA (body text) |

**Rules:**
- Meet WCAG AA minimum: 4.5:1 for body text, 3:1 for large text (≥18px or ≥14px bold).
- Never rely on colour alone to convey meaning — always pair with a shape, label, or pattern.
- Violet-600 on white fails AA for small text. Use violet-700+ for small violet text on white.
- Violet-400 on stone-950 passes AA at all sizes — safe for dark surface links and labels.

---

## 04 — Typography

### Typefaces and stacks

| Role | Family | CSS stack |
|------|--------|-----------|
| Headlines / display | Nanum Myeongjo | `'Nanum Myeongjo', 'Times New Roman', serif` |
| Body / UI | Inter | `'Inter', system-ui, -apple-system, sans-serif` |
| Labels / structure | JetBrains Mono | `'JetBrains Mono', ui-monospace, monospace` |

Font files live in `assets/fonts/`. Google Fonts CDN is the fallback source.

**Font smoothing (required for web rendering):**
```css
-webkit-font-smoothing: antialiased;
-moz-osx-font-smoothing: grayscale;
```
Without these, Inter and Nanum Myeongjo render with subpixel aliasing that conflicts with the brand's warm precision.

### Approved weights

Four weights only. No 300, no 800+.

| Weight | Name | Use |
|--------|------|-----|
| 400 | Regular | Nanum Myeongjo (all uses), Inter body, JetBrains Mono labels |
| 500 | Medium | Inter labels, buttons, strong emphasis |
| 600 | Semibold | Inter UI labels, navigation emphasis |
| 700 | Bold | Inter data, financial figures, critical callouts |

### UI type scale

| Token | Size | Line height | Use |
|-------|------|-------------|-----|
| xs | 12px | 1.4 | Captions, legal, footnotes |
| sm | 14px | 1.5 | Labels, metadata, table data |
| base | 16px | 1.6 | Body text (canonical body size) |
| lg | 18px | 1.5 | Large body, introductory paragraphs |
| xl | 20px | 1.4 | Sub-headings, callouts |
| 2xl | 24px | 1.3 | Section labels, card headings |
| 3xl | 30px | 1.2 | Small display |
| 4xl | 36px | 1.1 | Medium display, h3 |
| 5xl | 48px | 1.0 | Large display |

### Presentation type scale

| Token | Size | Use |
|-------|------|-----|
| pres-hero | 180px | Cover slides, single word statements |
| pres-display | 96px | Opening statements, hero text |
| pres-h1 | 72px | Primary slide headings |
| pres-h2 | 48px | Section headings, key statements |
| pres-h3 | 36px | Supporting headings |
| pres-body | 24px | Slide body text |
| pres-caption | 18px | Captions, annotations |
| pres-meta | 13–14px | Metadata, footnotes, source labels |

### Letter-spacing

**Nanum Myeongjo — always negative tracking:**

| Size | Letter-spacing |
|------|---------------|
| Hero (~96px) | -0.03em |
| Section heading (~56px) | -0.02em |
| Sub-heading (~36px) | -0.01em |
| Under 24px | 0 (default) |

Negative tracking tightens at larger sizes for optical correctness. Never apply positive letter-spacing to Nanum Myeongjo.

**JetBrains Mono:**

| Use | Letter-spacing |
|-----|---------------|
| Standard labels, eyebrows | 0.12em |
| Compact labels (tight spaces) | 0.08em minimum |
| Swatch / specimen labels | 0.04em |

### Line heights

| Context | Value |
|---------|-------|
| Tight (display, hero) | 0.95–1.1 |
| Heading (h2, h3) | 1.1–1.2 |
| Lede / intro | 1.5 |
| Body | 1.6 |
| Mono labels | 1.4 |

### The lede text component

The large introductory paragraph beneath a section heading. Not a heading; not body text.

- **Font:** Inter, 22px, weight 400
- **Line height:** 1.5
- **Colour:** stone-600 `#57534e` on light; stone-400 `#a8a29e` on dark
- **Max-width:** 800px (prevents line lengths that become hard to scan)
- **Margin below:** 64px before first body paragraph
- **Never override font-size inline.** The 22px class value is correct at all uses.

### Eyebrow composition — full spec

An eyebrow is a JetBrains Mono uppercase label that opens a section or card. It always has a violet hairline beneath it.

**Section eyebrow (used before h2 section headings):**
```
EYEBROW TEXT          ← JetBrains Mono, 14px, weight 400, 0.12em tracking, uppercase, stone-500 (light) / stone-400 (dark)
                      ← 20px gap
─────────────         ← 96px × 1px hairline, violet-600 (light) / violet-400 (dark)
                      ← 32px gap
Section heading       ← h2
```

**Card eyebrow (used inside .card elements before h4):**
```
CARD LABEL            ← JetBrains Mono, 14px, weight 400, 0.12em tracking, uppercase, stone-500 (light) / stone-400 (dark)
                      ← 14px gap
──────                ← 32px × 1px hairline, violet-600 (light) / violet-400 (dark)
```

The section hairline (96px) and the card hairline (32px) are distinct. Using the wrong width breaks the visual hierarchy.

### Typography hard rules

1. **Nanum Myeongjo is never uppercase.** Sentence case only. Text-transform: none.
2. **JetBrains Mono is uppercase labels and headings only.** Never sentences. Never body text. Never all-lowercase.
3. **No weights outside the approved four** (400, 500, 600, 700).
4. **Body text uses the UI scale** in product and documentation. Presentation contexts use the presentation scale. Do not mix.
5. **Call-and-response (italic violet `<em>`) is Nanum Myeongjo only.** Never Inter. Never JetBrains Mono. Never mid-phrase.
6. **Negative tracking on all Nanum Myeongjo display text.** The exact values are above.
7. **Never resize body text below 14px** (sm token). Anything smaller is a caption and must use 12px (xs) or a mono label.
8. **JetBrains Mono labels use weight 400**, not 500. The uppercase + tracking provides sufficient visual differentiation without extra weight.

---

## 05 — Buttons and interactive elements

### The violet reveal principle

Shape signals interactivity. Colour rewards engagement.

Buttons, links, and inputs carry no violet at rest — the chrome stays neutral. Violet appears only when the user reaches for the element: on hover, focus, or active. The pill shape, underline, or border already tells the user "this is touchable." Violet is not a badge — it is the reward of touching.

This principle applies across all Nivoda surfaces, editorial and product alike.

### Buttons

All buttons are pill-shaped (`border-radius: 999px`). Sentence case. One primary button per viewport.

**Shared properties (all buttons):**
- Font: Inter, weight 500, letter-spacing 0.03em
- Transition: `all 0.2s ease`
- Cursor: pointer
- No icons in primary buttons unless functionally necessary

**Default size:**
- Font size: 14px
- Padding: 14px 32px

**Small size:**
- Font size: 13px
- Padding: 8px 20px

**Disabled state (all buttons):**
- Opacity: 50%
- Cursor: not-allowed
- Never hide — always show the disabled state. The user needs to know the action exists but is unavailable.

#### Dark background buttons

| Variant | Rest | Hover | Focus ring |
|---------|------|-------|------------|
| Primary | stone-200 fill `#e7e5e4`, stone-950 text, stone-200 border | violet-500 fill, white text, violet-500 border | 2.5px solid violet-400, 2px offset |
| Secondary | transparent, stone-700 border `#44403c`, stone-400 text | violet-400 border, violet-400 text | 2.5px solid violet-400, 2px offset |
| Small | Same as primary at smaller size | Same hover | Same focus ring |

#### Light background buttons

| Variant | Rest | Hover | Focus ring |
|---------|------|-------|------------|
| Primary | stone-950 fill `#0c0a09`, white text, stone-950 border | violet-600 fill, white text, violet-600 border | 2.5px solid violet-600, 2px offset |
| Secondary | transparent, stone-200 border `#e7e5e4`, stone-950 text | violet-600 border, violet-600 text | 2.5px solid violet-600, 2px offset |
| Small | Same as primary at smaller size | Same hover | Same focus ring |

### Form inputs

Inputs are rectangular (`border-radius: 2px`), not pill-shaped. The pill is exclusive to buttons.

**Shared properties:**
- Font: Inter, 15px
- Padding: 12px 16px
- Transition: `border-color 0.2s`

| Property | Light context | Dark context |
|----------|--------------|--------------|
| Border (rest) | stone-200 `#e7e5e4` | stone-700 `#44403c` |
| Fill | white `#ffffff` | stone-900 `#1c1917` |
| Text | stone-950 `#0c0a09` | stone-50 `#fafaf9` |
| Placeholder | stone-400 `#a8a29e` | stone-500 `#78716c` |
| Border (focus) | violet-600 `#6330f5` | violet-400 `#9886ff` |
| Focus ring | 2.5px solid violet-600, 2px offset | 2.5px solid violet-400, 2px offset |

### Inline links

Underlines always persist — in both rest and hover states. The underline is a structural signal, not a hover effect.

| Property | Light context | Dark context |
|----------|--------------|--------------|
| Colour (rest) | stone-600 `#57534e` | stone-300 `#d6d3d1` |
| Colour (hover) | violet-600 `#6330f5` | violet-400 `#9886ff` |
| Underline | Always present | Always present |
| text-underline-offset | 3px | 3px |
| text-decoration-thickness | 1px | 1px |
| Transition | `color 0.2s` | `color 0.2s` |

### Focus rings — universal spec

Every interactive element — buttons, inputs, links — uses the same focus ring system for keyboard accessibility.

- **Width:** 2.5px solid outline
- **Offset:** 2px (gap between element edge and ring)
- **Colour on light:** violet-600 `#6330f5`
- **Colour on dark:** violet-400 `#9886ff`
- **Applied via:** `:focus-visible` (not `:focus` — avoids showing ring on mouse click)

---

## 06 — Logo

### Approved variants

Four SVG variants. All live in `assets/logos/`. Use canonical SVG files — never recreate from vectors.

| Filename | Use |
|----------|-----|
| `wordmark-white.svg` | Dark backgrounds, dark photography |
| `wordmark-black.svg` | Light backgrounds, white cards, warm surfaces |
| `icon-white.svg` | Icon-only contexts on dark backgrounds |
| `icon-black.svg` | Icon-only contexts on light backgrounds |

### Inline SVG — canonical artwork

**icon-white.svg** (dark backgrounds):
```svg
<svg width="345" height="169" viewBox="0 0 345 169" fill="none" xmlns="http://www.w3.org/2000/svg">
<path d="M0 6.60425L88.8292 164.575L177.4 6.60425H0Z" fill="white"/>
<path d="M260.61 0C214.048 0 176.298 37.7459 176.298 84.3126C176.298 130.875 214.048 168.625 260.61 168.625C307.173 168.625 344.923 130.875 344.923 84.3126C344.923 37.7459 307.173 0 260.61 0Z" fill="white"/>
</svg>
```

**icon-black.svg** (light backgrounds):
```svg
<svg width="345" height="169" viewBox="0 0 345 169" fill="none" xmlns="http://www.w3.org/2000/svg">
<path d="M260.61 0C214.048 0 176.298 37.7459 176.298 84.3126C176.298 130.875 214.048 168.625 260.61 168.625C307.173 168.625 344.923 130.875 344.923 84.3126C344.923 37.7459 307.173 0 260.61 0Z" fill="black"/>
<path d="M0 6.60425L88.8293 164.575L177.4 6.60425H0Z" fill="black"/>
</svg>
```

**wordmark-white.svg** (dark backgrounds):
```svg
<svg width="945" height="156" viewBox="0 0 945 156" fill="none" xmlns="http://www.w3.org/2000/svg">
<g clip-path="url(#clip0_2590_42)">
<path d="M119.712 2.14577V101.088L0.215668 -0.27002V153.71H27.6703V55.8183L147.166 156.021V2.14577H119.712Z" fill="white"/>
<path d="M215.856 2.14578H187.034V153.71H215.856V2.14578Z" fill="white"/>
<path d="M380.373 2.14578L324.517 105.815L269.503 2.98606L269.082 2.14578H238.366L324.622 155.916L410.668 2.14578H380.373Z" fill="white"/>
<path d="M502.604 0.0450842C481.341 -0.242499 460.811 7.79903 445.414 22.446C430.018 37.093 420.981 57.1797 420.24 78.4006C421.538 99.3189 430.775 118.956 446.069 133.31C461.362 147.665 481.562 155.656 502.552 155.656C523.541 155.656 543.741 147.665 559.035 133.31C574.328 118.956 583.565 99.3189 584.863 78.4006C584.122 57.1981 575.1 37.1272 559.726 22.4831C544.353 7.83904 523.85 -0.214816 502.604 0.0450842ZM502.604 131.758C495.59 131.76 488.646 130.361 482.181 127.643C475.716 124.926 469.861 120.944 464.96 115.933C460.06 110.922 456.212 104.983 453.644 98.4652C451.077 91.9473 449.841 84.9825 450.009 77.9805C450.009 64.0521 455.55 50.6942 465.414 40.8453C475.277 30.9964 488.655 25.4634 502.604 25.4634C516.553 25.4634 529.931 30.9964 539.795 40.8453C549.658 50.6942 555.199 64.0521 555.199 77.9805C555.368 84.9825 554.132 91.9473 551.564 98.4652C548.996 104.983 545.149 110.922 540.248 115.933C535.347 120.944 529.492 124.926 523.027 127.643C516.563 130.361 509.619 131.76 502.604 131.758Z" fill="white"/>
<path d="M671.329 2.14578H618.734V153.71H671.329C733.076 153.71 767.052 126.821 767.052 77.8755C767.052 28.9295 733.076 2.14578 671.329 2.14578ZM671.329 130.288H646.925V25.8835H671.014C714.563 25.8835 738.441 44.4746 738.441 78.4007C738.441 112.327 714.563 130.288 671.014 130.288H671.329Z" fill="white"/>
<path d="M859.515 -0.0599365L774.837 151.294L773.469 153.71H803.764L825.643 113.062H893.281L914.319 152.87V153.71H944.929L859.515 -0.0599365ZM838.477 89.8494L859.515 50.0414L880.553 89.8494H838.477Z" fill="white"/>
</g>
<defs><clipPath id="clip0_2590_42"><rect width="945" height="155.856" fill="white"/></clipPath></defs>
</svg>
```

**wordmark-black.svg** (light backgrounds):
```svg
<svg width="945" height="156" viewBox="0 0 945 156" fill="none" xmlns="http://www.w3.org/2000/svg">
<g clip-path="url(#clip0_2590_41)">
<path d="M119.712 2.14577V101.088L0.215668 -0.27002V153.71H27.6703V55.8183L147.166 156.021V2.14577H119.712Z" fill="black"/>
<path d="M215.856 2.14578H187.034V153.71H215.856V2.14578Z" fill="black"/>
<path d="M380.373 2.14578L324.517 105.815L269.503 2.98606L269.082 2.14578H238.366L324.622 155.916L410.668 2.14578H380.373Z" fill="black"/>
<path d="M502.604 0.0450842C481.341 -0.242499 460.811 7.79903 445.414 22.446C430.018 37.093 420.981 57.1797 420.24 78.4006C421.538 99.3189 430.775 118.956 446.069 133.31C461.362 147.665 481.562 155.656 502.552 155.656C523.541 155.656 543.741 147.665 559.035 133.31C574.328 118.956 583.565 99.3189 584.863 78.4006C584.122 57.1981 575.1 37.1272 559.726 22.4831C544.353 7.83904 523.85 -0.214816 502.604 0.0450842ZM502.604 131.758C495.59 131.76 488.646 130.361 482.181 127.643C475.716 124.926 469.861 120.944 464.96 115.933C460.06 110.922 456.212 104.983 453.644 98.4652C451.077 91.9473 449.841 84.9825 450.009 77.9805C450.009 64.0521 455.55 50.6942 465.414 40.8453C475.277 30.9964 488.655 25.4634 502.604 25.4634C516.553 25.4634 529.931 30.9964 539.795 40.8453C549.658 50.6942 555.199 64.0521 555.199 77.9805C555.368 84.9825 554.132 91.9473 551.564 98.4652C548.996 104.983 545.149 110.922 540.248 115.933C535.347 120.944 529.492 124.926 523.027 127.643C516.563 130.361 509.619 131.76 502.604 131.758Z" fill="black"/>
<path d="M671.329 2.14578H618.734V153.71H671.329C733.076 153.71 767.052 126.821 767.052 77.8755C767.052 28.9295 733.076 2.14578 671.329 2.14578ZM671.329 130.288H646.925V25.8835H671.014C714.563 25.8835 738.441 44.4746 738.441 78.4007C738.441 112.327 714.563 130.288 671.014 130.288H671.329Z" fill="black"/>
<path d="M859.515 -0.0599365L774.837 151.294L773.469 153.71H803.764L825.643 113.062H893.281L914.319 152.87V153.71H944.929L859.515 -0.0599365ZM838.477 89.8494L859.515 50.0414L880.553 89.8494H838.477Z" fill="black"/>
</g>
<defs><clipPath id="clip0_2590_41"><rect width="945" height="155.856" fill="white"/></clipPath></defs>
</svg>
```

### Usage rules

| Rule | Spec |
|------|------|
| Safe backgrounds | Warm light `#f5f0ec`, white `#ffffff` (cards only), dark `#0c0a09`, dark photography |
| Minimum clear space | 16px on all sides, or 1/4 of logo height — whichever is larger |
| Minimum size (digital) | 40px width (wordmark), 24px width (icon) |
| Minimum size (print) | 1 inch / 25mm (wordmark), 0.5 inch / 12mm (icon) |
| Maximum scale | No upper limit. Always maintain aspect ratio. Use SVG for infinite scalability. |
| Co-branding | Equal or greater visual weight. 16px minimum clear space between logos. |
| Variant pairing | White variant on dark backgrounds. Black variant on light backgrounds. Always. |
| Placement in product | Navigation bar only. Never repeated within page content. |

### Never
Stretch, rotate, or distort. Change logo colours. Place on backgrounds that reduce legibility. Recreate or approximate from scratch. Add effects (shadows, gradients, outlines). Use on backgrounds not in the safe list. Use white variant on light or black variant on dark.

### Always
Use canonical SVG assets from `assets/logos/`. Maintain aspect ratio. Respect minimum clear space. Use white variant on dark, black variant on light.

---

## 07 — Tables and data display

Tables are used for token references, colour roles, type scales, and structured data. They are always clean and minimal — no heavy header fills, no decorative chrome.

### Table spec

| Property | Value |
|----------|-------|
| Background | White `#ffffff` |
| Border | 1px solid stone-200 `#e7e5e4` |
| Border radius | 4px |
| Font size | 15px body |

**Header row (`th`):**
- Font: JetBrains Mono, 12px, weight 400
- Letter-spacing: 0.12em
- Text: uppercase
- Colour: stone-500 `#78716c`
- Background: semi-transparent white (`rgba(255,255,255,0.5)`)
- Border-bottom: 1px `rgba(0,0,0,0.06)`
- Padding: 12px 16px

**Data rows (`td`):**
- Font: Inter, 15px, weight 400
- Colour: stone-600 `#57534e`
- First column colour: stone-700 `#44403c`
- Padding: 14px 16px
- Border-bottom: 1px `rgba(0,0,0,0.06)` (none on last row)

**Dark context:**
- Table background: `rgba(255,255,255,0.06)`
- Border: stone-800
- `th` background: `rgba(255,255,255,0.04)`
- `td` colour: stone-400 `#a8a29e`
- First column colour: stone-300 `#d6d3d1`

### Hard rules

- Never use a solid dark fill on table headers. The header is distinguished by font treatment (mono uppercase), not background colour.
- Never bold table header text — JetBrains Mono uppercase with letter-spacing provides sufficient differentiation at weight 400.
- Numbers and financial figures in tables use Inter weight 700. All other data uses weight 400.

---

## 07 — Spacing and layout

### Spacing scale

Base unit: 4px. All spacing is a multiple of 4.

| Token | px | Common use |
|-------|----|------------|
| sp-1 | 4px | Icon padding, tight gaps |
| sp-2 | 8px | Input padding (vertical), small gaps |
| sp-3 | 12px | Button gap, inline gaps |
| sp-4 | 16px | Small card padding, nav gaps |
| sp-5 | 20px | Button padding (small, horizontal) |
| sp-6 | 24px | Paragraph margin, small grid gaps |
| sp-8 | 32px | Card gaps, section eyebrow-to-heading |
| sp-10 | 40px | Card padding |
| sp-12 | 48px | Sub-section padding, demo block padding |
| sp-16 | 64px | Heading margins, horizontal page padding |
| sp-20 | 80px | Before h3 headings |
| sp-24 | 96px | Minimum section padding |
| sp-32 | 128px | Section vertical padding (canonical) |

### Contextual spacing

| Context | Value |
|---------|-------|
| Between major sections | 128px (sp-32) |
| Before h3 sub-headings | 80–96px (sp-20 to sp-24) |
| After section eyebrow, before h2 | 32px gap (sp-8) — this follows the 20px eyebrow hairline gap |
| Between cards in a grid | 32px (sp-8) |
| Inside card padding | 40px (sp-10) |
| Between paragraphs | 24px (sp-6) |

### Page layout

| Property | Value |
|----------|-------|
| Max-width | 1200px, horizontally centered |
| Horizontal padding | 64px (reduces to 32px below 900px breakpoint) |
| Section padding | 128px top and bottom |
| Background | `#f5f0ec` (warm light) |

**Dark full-bleed sections:**
Dark background sections extend edge-to-edge using the `-9999px` margin technique:
```css
.dark {
  margin: 0 -9999px;
  padding: 128px 9999px;
}
```
This extends the background colour to the viewport edge while keeping content within the page max-width.

### Grid system

| Class | Columns | Gap | Use |
|-------|---------|-----|-----|
| grid-2 | 1fr 1fr | 32px | Two-column content, do/dont pairs |
| grid-3 | 1fr 1fr 1fr | 32px | Principle cards, three-column features |
| grid-4 | repeat(4, 1fr) | 24px | Colour swatches, icon grids |

All grids collapse to single column at the 900px breakpoint.

### Responsive breakpoint

Single breakpoint at **900px**:
- Page padding: 64px → 32px
- Hero title: 96px → 56px
- Section heading (h2): 56px → 36px
- All multi-column grids: collapse to 1 column

### Border radius

Two values only. No intermediates, no bespoke values.

| Value | Use |
|-------|-----|
| `999px` | All buttons, pill shapes |
| `2px` | All cards, inputs, containers, border-radius on structural elements |

The contrast between the fully-round button and the minimal 2px card is intentional — it distinguishes interactive elements from content surfaces at a glance.

### Shadows

| Token | CSS value | Use |
|-------|-----------|-----|
| shadow-sm | `0 1px 2px rgba(12,10,9,0.05)` | Subtle card lift |
| shadow-md | `0 4px 6px rgba(12,10,9,0.07), 0 2px 4px rgba(12,10,9,0.06)` | Cards, dropdowns |
| shadow-lg | `0 10px 15px rgba(12,10,9,0.1), 0 4px 6px rgba(12,10,9,0.05)` | Modals, elevated panels |
| shadow-xl | `0 20px 25px rgba(12,10,9,0.1), 0 10px 10px rgba(12,10,9,0.04)` | Full-screen overlays |

Shadows use the brand's soft black (`#0c0a09`) as their base, not pure black. This keeps shadows warm.

### Negative space

Luxury is not packed. Breathing room is not wasted space — it is an active design decision that communicates authority, restraint, and confidence in the content.

**Rules:**
- If it feels cramped, it is cramped.
- Never reduce section padding below 96px to fit more content — cut the content instead.
- Cards breathe at 40px padding. Going below 32px makes a card feel compressed.
- The 32px gap between cards is a non-negotiable minimum.
- White space between major sections signals transition. When it disappears, sections blend and hierarchy collapses.

---

## 08 — Imagery

### Mode 1 — Editorial photography

For marketing pages, hero moments, sales materials, campaign assets. Human presence, warmth, jeweller's perspective.

**Three principles:**

**01 — Perspective: through the jeweller's eyes**
Shot from inside the partner's world looking out — not from a customer's perspective, not from a brand's elevated view. The camera is where a skilled craftsperson would stand: close to the work, at the bench, inside the conversation. Subject matter can be product, people, or both.

**02 — Light: luxury studio, cinematic depth**
Soft directional studio light. Cinematic depth of field at f/1.4–f/2.8. Bokeh that separates subject from environment without erasing context. The light quality references high-end fashion and jewellery advertising. Saul Leiter is the visual touchstone — intimate, layered, light-struck. Never hard flash. Never even, flat lighting.

**03 — Palette: moody and golden, with measured colour**
Warm golden tonal base. Deep shadows. Photography is not pure monochrome — selective colour is welcome and earns its place: a flash of red on a velvet tray, the green of an emerald, the cobalt of a sapphire box, the warmth of skin. The rule: warm and golden as the base, with colour as the accent that proves the photograph is alive. Never desaturated. Never grayscale.

**AI generation prompt (editorial):**
```
[subject/scene], shot from the jeweller's perspective looking out, soft directional studio light, cinematic depth of field at f/1.4–f/2.8, reflection or refraction in frame, warm golden tonal palette with selective colour accents, high-end fashion-advertising aesthetic, Saul Leiter inspiration, never sterile or retail
```

### Mode 2 — Promotional banners (the procession)

For category banners in the marketplace. No human presence. Product only. Three ideas in one frame.

**Three principles:**

**Scale:** The procession communicates infinite supply. A line of identical pieces receding from foreground to background, the end always out of frame. The viewer never reaches the last one. This is abundance without counting.

**Consistency:** Identical items, uniformly arranged. The repetition signals that Nivoda's supply is reliable and deep — not a curated selection of one-offs but a category that flows.

**Cadence:** The even spacing between pieces creates rhythm. Rhythm implies repeat business. Every banner is a visual argument for the return purchase.

**Spec:**

| Property | Value |
|----------|-------|
| Aspect ratio | Approximately 5:1 (wide banner format) |
| Background | Near-black studio surface |
| Subject | Product only — no hands, no context, no props |
| Minimum items | Five visible in frame; line extends to blur |
| Depth | Sharp foreground softening to blur |
| Colour | Warm product tones (gold, silver, diamond) against cool dark. No artificial colour overlays. |

**AI generation prompt (banners):**
```
[product category], arranged in a receding procession on a dark studio surface, cinematic depth of field, sharp foreground softening to blur, warm metallic product tones against near-black background, infinite-supply framing, no human presence, no context, product-only, professional product photography
```

---

## 09 — Iconography

### Usage rules

| Property | Value |
|----------|-------|
| Library | Lucide (outlined only — no filled variants) |
| Stroke | 1.5px |
| Sizes | 16px / 20px / 24px |
| Colour | Inherits text colour. On dark contexts, use stone-200 for icons. |
| Behaviour | Used sparingly, with intent. Never as decoration. |

**Approved concepts:** Gems, marketplace, partnership, craft, certification, provenance. Never generic UI plumbing (settings cog, hamburger, chevrons, ellipsis) unless functionally required.

Introducing additional Lucide glyphs beyond the approved set requires sign-off from Chris.

### Approved 30-icon set

**Jewellery & gems:**
gem, crown, sparkles, heart, flame, award

**Marketplace & commerce:**
store, globe, handshake, shopping-bag, package, truck

**Partnership & value:**
users, user-check, coins, badge-check, shield-check, lock

**Craft & precision:**
key, microscope, scale, compass, pen-tool, stamp

**Documentation & origin:**
file-check, clipboard-check, book-open, map-pin, mountain, history

---

## 10 — Brand modes

### The first question

Before producing anything: **is this editorial or UI?** These two modes have different vocabularies. Applying the wrong mode breaks the brand.

### Editorial mode

Anywhere the brand is performing — expressing identity, telling a story, persuading, presenting.

**Applies to:** marketing pages (nivoda.com, blog, campaign landing pages), sales and investor decks, pitch materials, conference handoffs (JCK, partner collateral, event signage), longform documents (whitepapers, reports, brand books), hero moments (splash screens, marketing emails, brand films, social hero assets), internal brand onboarding and all-hands presentations.

**Full vocabulary available in editorial mode:**
- Decorative violet eyebrows (section eyebrows with the violet hairline beneath)
- Italic call-and-response (italic violet `<em>` at final beat of Nanum Myeongjo headlines)
- Dual-context palette — warm light (`#f5f0ec`) with white cards, or dark (`#0c0a09`) for immersive moments
- The two-violet rule on dark (violet-500 for mass, violet-400 for thin)
- Promotional banner photography (procession mode)
- Editorial photography (perspective, light, palette)
- Nanum Myeongjo at display scale for headlines
- JetBrains Mono for structural labels and eyebrows

**Restraint still applies.** The full vocabulary is permitted, not mandatory. Violet is precious — maximum 2–3 violet roles per composition. Dual-context palette means choose one context per composition; do not mix dark and warm-light surfaces in the same layout.

**Tone in editorial mode:** Warm and persuasive. Confident without being boastful. Human without being casual. The brand is speaking at full volume.

### UI mode

Anywhere the brand is serving a task — the Nivoda app, dashboards, transactional flows, marketplace, forms, data tables. The brand recedes; the work comes forward.

**Applies to:** the Nivoda platform (buyer and supplier facing), internal tooling, dashboards, checkout flows, form pages, data tables, transactional email (order confirmation, shipping updates, invoices).

**Rules for UI mode:**
- **Monochrome chrome at rest.** Buttons, navigation, and interactive elements are stone-coloured at rest. Violet is hidden.
- **Violet revealed only on hover/focus.** Buttons hover to violet-500 (dark) or violet-600 (light). Links hover to violet-600. Inputs get a violet-600 focus ring. Violet signals interaction, not decoration.
- **No decorative violet eyebrows.** Section labels in UI are Inter or JetBrains Mono in stone — never with the decorative violet hairline. That is an editorial gesture.
- **No call-and-response in UI.** No italic violet type. The gesture belongs to display moments, not task surfaces.
- **Photography carries colour.** Where imagery appears in UI, it uses editorial photography principles (warm, human, jeweller's perspective). The image provides colour; the chrome stays neutral.
- **Logo in nav only.** Never repeated within page content.
- **Typography follows the design system scale.** No bespoke sizing; use Clarity V2 tokens.
- **No marketing language in product UI.** Copy follows the writing style guide.

**The line:** Product UI is a tool, not a billboard. Users are here to transact. Brand builds trust and clarity — it never competes with the task.

### Email

- **Promotional / marketing emails:** follow editorial mode. The inbox is personal space — slightly reduced intensity but the full vocabulary is permitted. One primary CTA per email.
- **Transactional emails** (order confirmation, shipping updates, invoices): follow UI mode. Clear, concise, action-oriented. No decorative violet. No call-and-response. The task is the focus.
- Subject lines: sentence case. No ALL CAPS. No clickbait.
- Every email must be scannable in under 10 seconds.

### Documentation and help

- Voice register: precise, patient, structured. Never casual, never promotional.
- Step-by-step instructions use numbered lists.
- Screenshots must use current UI — never outdated.
- Technical terms defined on first use.
- Write for the least experienced user — never assume expertise.

### Internal communications

- Voice register: casual, direct, no jargon inflation.
- Slack, Notion, internal docs — the brand still applies at lowest formality.
- Never use internal shorthand in any context that might be forwarded externally.

### Third-party and co-branding contexts

<!-- BRAND GAP: Co-branding rules not yet defined. Flag to Chris before proceeding. -->
- Logo usage in partner contexts: see Logo section above
- Minimum brand requirements when appearing on third-party sites: [BRAND GAP]
- Approval process for co-branded materials: [BRAND GAP]

---

## 11 — Voice and tone

### Voice is constant; tone shifts by context

Voice is who Nivoda is. Tone is how Nivoda adapts to the situation. The voice never changes; the register does.

### Tone register by context

| Context | Register | Do | Don't |
|---------|----------|----|-------|
| Product UI | Clear, concise, action-oriented | "Place order", "View invoice" | "Explore your amazing order journey" |
| Error messages | Calm, helpful, never blaming | "We couldn't process that — please try again" | "You made an error" |
| Marketing | Confident, professional, warm | "The global diamond marketplace, built for the trade" | "Disruptive. Revolutionary. Game-changing." |
| Email | Personal, direct, value-focused | "Your order is on its way" | "Dear valued customer" |
| Documentation | Precise, patient, structured | Numbered steps, defined terms | Assumed knowledge, skipped steps |
| Internal comms | Casual, direct, no jargon inflation | Plain language, short sentences | Inflated corporate speak |

### Voice principles

<!-- BRAND GAP: Three named voice principles not yet defined. Flag to Chris. -->
The three core voice principles that define how Nivoda sounds across all surfaces are being developed. Do not invent them. Flag this to Chris.

---

## 12 — Writing style

### The full-stop rule

**Never use a full stop at the end of a heading, title, or label** — in any context, on any surface. This includes h1–h6, page titles, section headings, card headings, navigation labels, eyebrows, captions, and button text.

Full stops are for prose: body copy, multi-sentence descriptions, legal text. A heading is a signal, not a sentence. A full stop after a heading reads as an error, not as confidence.

No exceptions.

### Capitalisation

| Element | Style | Example |
|---------|-------|---------|
| Page titles | Sentence case | "Order history" |
| Section headings | Sentence case | "Shipping details" |
| Eyebrows / labels | UPPERCASE (JetBrains Mono only) | "03 — COLOUR" |
| Buttons | Sentence case | "Place order" |
| Tab labels | Sentence case | "All diamonds" |
| Table headers | Sentence case | "Date created" |
| Navigation items | Sentence case | "My orders" |
| Product names | Title Case | "Nivoda Express" |

### Grammar rules

- Sentence case for all headings and button labels — never Title Case for body elements
- Use the Oxford comma
- Use contractions in product UI (it's, you'll, don't) but not in legal or formal documentation
- Numbers: spell out one through nine; use numerals for 10+. Always use numerals for prices, quantities, and measurements.
- Date format: [BRAND GAP — define format]
- Currency format: [BRAND GAP — define format]

### Punctuation in UI

- No full stops on single-sentence UI labels, buttons, or tooltips
- Full stops on multi-sentence body text
- No exclamation marks in product UI (reserve for marketing if at all)
- Question marks only in confirmation dialogs: "Are you sure you want to cancel?"

### Canonical terminology

<!-- BRAND GAP: The definitive list of Nivoda terms has not been established. Do not substitute synonyms for any product term until this table is filled. Flag to Chris. -->

| Canonical term | Never say | Context |
|----------------|-----------|---------|
| [BRAND GAP] | | |

### UI copy patterns

<!-- BRAND GAP: Standard patterns for common UI elements have not been defined. Flag to Chris. -->

| Element | Pattern | Example |
|---------|---------|---------|
| Button (primary action) | [BRAND GAP] | |
| Empty state headline | [BRAND GAP] | |
| Empty state body | [BRAND GAP] | |
| Error message | [BRAND GAP] | |
| Success message | [BRAND GAP] | |
| Placeholder text | [BRAND GAP] | |

---

*This file is the canonical source of truth for the Nivoda brand. It is maintained by Chris Learey (Design Lead). All brand decisions flow through Chris. If something is not in this file, it is either a BRAND GAP or it belongs in Clarity V2 (the design system for UI implementation).*

*Archived source files: `docs/_archive/` contains the previous split-file versions for reference.*
