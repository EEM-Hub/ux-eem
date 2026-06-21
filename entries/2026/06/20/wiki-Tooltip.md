---
source: sources/wiki-Tooltip.md
source_url: https://en.wikipedia.org/wiki/Tooltip
---

## Tooltips: GUI Hover Information Elements

This page covers tooltips — a fundamental GUI element that displays contextual information when a user hovers over or long-presses a screen element. The article traces the origin, platform variations, implementation methods, and related UI patterns.

## Key Concepts

- A **tooltip** (also called infotip, hint, mouseover, or hover text) is a text box that appears on hover to describe a UI element's function, expand an abbreviation, or show metadata like timestamps.
- Tooltips display **continuously** as long as the user hovers over the triggering element.
- Tooltips can **nest**: hovering within a tooltip's text box can trigger another tooltip, to arbitrary depth.
- On **desktop**, tooltips activate on pointer hover without clicking.
- On **touch devices**, tooltips activate on **long-press** (tap and hold); stylus-equipped devices can also trigger tooltips on hover.
- A common older variant displayed tooltip-like descriptions in the **status bar** instead of a floating box.
- Platform-specific naming: Microsoft calls them **ScreenTips**, Apple calls them **help tags**, Classic Mac OS used **balloon help**.
- Some applications (e.g., GIMP) allow users to **toggle tooltips off**, but this is developer-discretionary and often unimplemented.

## Commands and Syntax

- In HTML, the `title` attribute on elements generates browser-native tooltips on hover.
- Custom tooltips can be built with **CSS**, **HTML**, and **JavaScript**.
- The **ARIA `tooltip` role** (`role="tooltip"`) provides accessible tooltip semantics for screen readers and assistive technology.
- WCAG 2.2 Success Criterion **1.4.13** ("Content on Hover or Focus") governs tooltip accessibility requirements.

## Relationships

- **Mouseover / Hoverbox**: The interaction pattern that triggers tooltips on desktop.
- **Dialog box / Popover**: Heavier UI elements that serve a similar contextual-information purpose but typically require explicit dismissal.
- **Status bar**: An alternative location for displaying the same kind of contextual help text.
- **Balloon help**: Apple's Classic Mac OS predecessor to modern tooltips.
- **Toolbar**: The original context where tooltips appeared (describing toolbar icon functions in early Microsoft apps like Word 95).
- Tooltips are classified as **informational** GUI elements, alongside progress bars, toasts, labels, icons, and loading screens.

## Exam-Relevant Points

- Tooltips are triggered by **hover** on desktop, **long-press** on touch devices.
- The HTML `title` attribute is the native mechanism for browser tooltips.
- WCAG 2.2 criterion **1.4.13** specifically addresses content that appears on hover or focus — critical for accessibility compliance.
- The ARIA role for tooltips is `role="tooltip"` (MDN documentation).
- Microsoft's term is **ScreenTips**; Apple's is **help tags**; Classic Mac OS used **balloon help**.
- Tooltips originated from **toolbar icon descriptions** in early 1990s Microsoft applications.
- Tooltips are **non-modal** — they don't block interaction with other UI elements, unlike dialog boxes.
- Nested tooltips are possible but uncommon in practice.
