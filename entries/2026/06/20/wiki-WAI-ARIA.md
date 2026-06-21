---
source: sources/wiki-WAI-ARIA.md
source_url: https://en.wikipedia.org/wiki/WAI-ARIA
---

## WAI-ARIA: Accessible Rich Internet Applications Specification

WAI-ARIA (Web Accessibility Initiative – Accessible Rich Internet Applications) is a W3C technical specification that defines how to make dynamic web content and UI components accessible to users with disabilities. It addresses the gap left by standard HTML when developers build rich, interactive interfaces using Ajax, JavaScript, and client-side scripting — content patterns that screen readers and keyboard-only users otherwise cannot navigate.

## Key Concepts

- **Purpose**: Adds semantic role, property, and state information to dynamic web applications so assistive technologies can interpret them
- **Published by W3C**; current version is WAI-ARIA 1.2 (W3C Recommendation, June 2023)
- **Not limited to HTML** — can also be applied to SVG and other markup languages
- Allows pages or page regions to declare themselves as **applications** rather than static documents
- Targets four audiences: web app developers, browser implementers, assistive technology vendors, and accessibility evaluation tool creators

### The 5 Rules of ARIA (critical)

1. **Don't use ARIA** if native HTML achieves the same semantics — prefer semantic HTML first
2. **Don't change native HTML semantics** unless absolutely necessary
3. **All interactive ARIA controls must be keyboard-operable**
4. **Don't hide focusable elements** — never apply `role="presentation"` or `aria-hidden="true"` to elements that can receive focus
5. **All interactive elements must have an accessible name** via the Accessibility API

## Commands and Syntax

ARIA is applied via HTML attributes, not CLI commands. Core attribute categories:

- **Roles**: Define what an element *is* (e.g., `role="navigation"`, `role="menu"`, `role="alert"`)
- **Properties**: Describe characteristics (e.g., `aria-label="Close"`, `aria-required="true"`)
- **States**: Describe current conditions (e.g., `aria-expanded="false"`, `aria-checked="true"`, `aria-hidden="true"`)

Example — marking a collapsible navigation menu:
```html
<nav role="navigation">
  <button aria-expanded="false" aria-controls="menu1">Menu</button>
  <ul id="menu1" role="menu" aria-hidden="true">
    <li role="menuitem">Item 1</li>
  </ul>
</nav>
```

## Relationships

- **HTML / Semantic HTML**: ARIA supplements HTML semantics; native HTML elements should always be preferred over ARIA equivalents (Rule 1)
- **WCAG (Web Content Accessibility Guidelines)**: ARIA is an implementation mechanism for meeting WCAG success criteria; WCAG sets the *what*, ARIA provides part of the *how*
- **Screen readers and assistive technologies**: ARIA's primary consumers — it bridges the gap between visual UI and the accessibility tree
- **JavaScript / Ajax / Rich Internet Applications**: ARIA exists specifically because these technologies create dynamic UI patterns that native HTML cannot express
- **SVG**: SVG Tiny 1.2 added WAI-ARIA support (2008), extending accessibility semantics beyond HTML
- **Accessibility API (platform)**: ARIA attributes map to platform accessibility APIs (e.g., MSAA, UIA, ATK/AT-SPI, AX API on macOS) which assistive technologies query

## Exam-Relevant Points

- **The 5 Rules of ARIA are heavily tested** — especially Rule 1 ("first rule of ARIA: don't use ARIA") and Rule 3 (keyboard operability requirement)
- WAI-ARIA 1.0 became a W3C Recommendation on **March 20, 2014**; current version is **1.2 (June 2023)**
- ARIA provides three categories of attributes: **roles**, **properties**, and **states**
- `aria-hidden="true"` on a **focusable** element violates Rule 4 — this is a common exam trap
- Every interactive element **must** have an accessible name (Rule 5) — via `aria-label`, `aria-labelledby`, or visible label association
- ARIA does **not** change visual appearance or behavior — it only changes what the accessibility tree reports to assistive technologies
- The **WAI-ARIA Authoring Practices** document covers widget patterns, keyboard navigation, drag-and-drop, dialogs, and testing — a key companion resource
- Prefer native HTML over ARIA: a `<button>` is better than `<div role="button">` because it gets keyboard support and semantics for free
