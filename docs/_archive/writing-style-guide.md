# Writing Style Guide

## Purpose
Governs grammar, terminology, naming, and UI copy conventions across all Nivoda surfaces. This is the reference agents and engineers check before writing any user-facing text.

---

## Terminology

### Canonical Terms
<!-- TODO: Build the definitive list of Nivoda terminology -->

Use these terms exactly as written. Do not substitute synonyms.

| Canonical term | Never say | Context |
|---------------|-----------|---------|
| <!-- e.g. "memo" --> | <!-- e.g. "consignment", "loan" --> | <!-- e.g. Nivoda's memo programme for try-before-you-buy --> |
| <!-- e.g. "supplier" --> | <!-- e.g. "vendor", "seller" --> | <!-- --> |
| <!-- e.g. "buyer" --> | <!-- e.g. "customer", "client" --> | <!-- in product UI context --> |
| <!-- e.g. "order" --> | <!-- e.g. "purchase", "transaction" --> | <!-- --> |

### Product & Feature Names
<!-- TODO: List official names for Nivoda products and features -->
- Always capitalise product names: [e.g. "Nivoda Express", not "nivoda express"]
- Never abbreviate product names in user-facing copy unless documented here
- Internal codenames must never appear in user-facing copy

---

## Grammar & Style

### General Rules
<!-- TODO: Confirm these match Nivoda's actual style preferences -->
- Use sentence case for headings and button labels (not Title Case)
- Use the Oxford comma
- Use contractions in product UI (it's, you'll, don't) but not in legal or formal documentation
- Numbers: spell out one through nine, use numerals for 10+. Always use numerals for prices, quantities, and measurements.
- Dates: [define format — e.g. "14 Apr 2026" or "April 14, 2026"]
- Currency: [define format — e.g. "US$1,200" or "$1,200 USD"]

### UI Copy Patterns
<!-- TODO: Define standard patterns for common UI elements -->

| Element | Pattern | Example |
|---------|---------|---------|
| Button (primary action) | <!-- e.g. Verb + object, imperative --> | <!-- e.g. "Place order" --> |
| Button (secondary) | <!-- --> | <!-- e.g. "Cancel" --> |
| Empty state headline | <!-- --> | <!-- e.g. "No orders yet" --> |
| Empty state body | <!-- --> | <!-- e.g. "Your orders will appear here once you've placed one." --> |
| Error message | <!-- --> | <!-- e.g. "Something went wrong. Please try again." --> |
| Success message | <!-- --> | <!-- e.g. "Order placed successfully" --> |
| Placeholder text | <!-- --> | <!-- e.g. "Search by stone ID or certificate..." --> |
| Tooltip | <!-- --> | <!-- --> |

---

## Punctuation

### The full-stop rule
**Never use a full stop at the end of a heading, title, or label** — in any context, on any surface. This includes h1–h6, page titles, section headings, card headings, navigation labels, eyebrows, captions, and button text.

Full stops are for prose: body copy, multi-sentence descriptions, legal text. A heading is a signal, not a sentence. A full stop after a heading reads as an error, not as confidence.

This rule applies equally to editorial and UI contexts. No exceptions.

### Punctuation in UI

- No full stops on single-sentence UI labels, buttons, or tooltips
- Full stops on multi-sentence body text
- No exclamation marks in product UI (reserve for marketing if at all)
- Question marks only in confirmation dialogs ("Are you sure you want to cancel?")

---

## Capitalisation

| Element | Style | Example |
|---------|-------|---------|
| Page titles | Sentence case | "Order history" |
| Section headings | Sentence case | "Shipping details" |
| Buttons | Sentence case | "Place order" |
| Tab labels | Sentence case | "All diamonds" |
| Table headers | Sentence case | "Date created" |
| Product names | Title Case | "Nivoda Express" |
| Navigation items | Sentence case | "My orders" |

---

## How to Use This File

**Agents:** Before writing any user-facing text, check the terminology table and UI copy patterns. Use canonical terms exactly. Follow the grammar rules. If a term or pattern isn't documented, flag a BRAND GAP.

**Humans:** This is the reference for copy reviews. Add new canonical terms here as they're established.

---

*This file is scaffolded and awaiting content from the design function. Each section marked with TODO or <!-- --> needs real Nivoda conventions.*
