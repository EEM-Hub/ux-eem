---
source: sources/wiki-Web_Content_Accessibility_Guidelines.md
source_url: https://en.wikipedia.org/wiki/Web_Content_Accessibility_Guidelines
---

## WCAG: Web Content Accessibility Guidelines

The Web Content Accessibility Guidelines (WCAG) are the primary international standard for web accessibility, published by the Web Accessibility Initiative (WAI) of the W3C. They provide testable success criteria organized under four principles — Perceivable, Operable, Understandable, and Robust (POUR) — at three conformance levels (A, AA, AAA). WCAG 2.0 became ISO standard 40500:2012, and WCAG 2.2 became a W3C Recommendation on October 5, 2023. WCAG 3.0 is under active development with no release date defined.

## Key Concepts

- **Four Principles (POUR):** All WCAG 2.x criteria fall under Perceivable, Operable, Understandable, or Robust
- **Three Conformance Levels:**
  - **A** — minimum; content *must* meet these or some users cannot access it at all
  - **AA** — mid-range; content *should* meet these (this is the level most laws target)
  - **AAA** — highest; *may* address to improve access for additional groups
- **Success Criteria** are the testable requirements within each guideline; WCAG 2.0 has 61, WCAG 2.1 adds 17 more, WCAG 2.2 adds 9 more (and deprecates 4.1.1 Parsing)
- **Backwards compatibility:** Each 2.x version is a superset of the previous — meeting 2.2 means you also meet 2.1 and 2.0
- **Techniques vs. Success Criteria:** Techniques are periodically updated how-to guidance; principles, guidelines, and success criteria are stable and do not change
- **WCAG 1.0** used 14 guidelines with 65 checkpoints and three priority levels; this structure was replaced in 2.0
- **WCAG 3.0** is a working draft (last updated September 2025) — not yet an official recommendation and may change substantially

## Conformance Level Breakdown (WCAG 2.2)

- **Level A criteria** — baseline accessibility (e.g., non-text content alternatives, keyboard access, no keyboard traps, bypass blocks, page titles, focus order, seizure thresholds, error identification, labels)
- **Level AA criteria** — the legal/regulatory target (e.g., captions for prerecorded media, minimum contrast 4.5:1, resize text, reflow, non-text contrast, text spacing, focus visible, focus not obscured, consistent navigation, error suggestion, accessible authentication, target size minimum 24x24 CSS px, dragging alternatives)
- **Level AAA criteria** — enhanced accessibility (e.g., sign language, extended audio description, enhanced contrast 7:1, reading level, pronunciation, no timing, focus appearance)

## Key Success Criteria New in WCAG 2.1 and 2.2

- **2.1 additions:** Orientation (AA), Identify Input Purpose (AA), Reflow (AA), Non-Text Contrast (AA), Text Spacing (AA), Content on Hover or Focus (AA), Character Key Shortcuts (A), Pointer Gestures (A), Pointer Cancellation (A), Label in Name (A), Motion Actuation (A), Status Messages (AA)
- **2.2 additions:** Focus Not Obscured Minimum (AA), Focus Not Obscured Enhanced (AAA), Focus Appearance (AAA), Dragging Movements (AA), Target Size Minimum (AA), Consistent Help (A), Redundant Entry (A), Accessible Authentication Minimum (AA), Accessible Authentication Enhanced (AAA)
- **2.2 deprecation:** 4.1.1 Parsing was removed (modern browsers and assistive technologies no longer require it)

## Relationships

- **Web Accessibility Initiative (WAI):** Parent initiative within W3C that publishes WCAG
- **ISO/IEC 40500:2012:** The ISO codification of WCAG 2.0 — identical content, different standards body
- **EN 301 549:** European ICT accessibility standard that incorporates WCAG 2.1 AA by reference
- **Section 508 (US):** Updated in 2017 to adopt 17 WCAG 2.0 success criteria
- **ADA Title II (US):** 2024 DOJ final rule adopts WCAG 2.1 Level AA for state and local government web content and mobile apps
- **European Accessibility Act (EAA):** Became applicable June 28, 2025; requires WCAG 2.1 AA for websites, apps, ebooks, ecommerce, PDFs across the EU — extends requirements to private sector
- **Disability Discrimination Act 1992 (Australia):** Mandates WCAG 2.0 Level A for government websites
- **AODA (Ontario, Canada):** Requires WCAG 2.0 Level AA for public web content
- **Accessible Canada Act (2019):** Federal-level accessibility legislation

## Commands and Syntax

No CLI commands per se, but key technical references:

- **Contrast ratios:** AA minimum is 4.5:1 for normal text; AAA enhanced is 7:1
- **Target size:** AAA is the larger target (2.5.5), AA minimum is 24x24 CSS pixels (2.5.8, new in 2.2)
- **Reflow:** Content must reflow at 320 CSS px width without horizontal scrolling (1.4.10)
- **Text spacing:** Users must be able to override line height to 1.5x, paragraph spacing to 2x, letter spacing to 0.12x, word spacing to 0.16x without loss of content (1.4.12)

## Exam-Relevant Points

- **POUR** mnemonic: Perceivable, Operable, Understandable, Robust — the four principles organizing all WCAG 2.x criteria
- **AA is the regulatory standard worldwide** — almost every jurisdiction that references WCAG targets Level AA, not A or AAA
- WCAG 2.0 was published **December 2008** and became ISO 40500 in **October 2012**
- WCAG 2.2 was published **October 5, 2023** — nine new success criteria
- WCAG 2.2 **deprecated 4.1.1 Parsing** — the only criterion ever removed
- Each version is **backwards-compatible**: 2.2 ⊇ 2.1 ⊇ 2.0
- **Techniques are living documents** that update independently of the stable success criteria
- The **US DOJ 2024 ADA Title II rule** specifically adopts WCAG 2.1 AA (not 2.2)
- The **European Accessibility Act** (effective June 2025) extends WCAG requirements to private sector companies selling in the EU
- **WCAG 1.0** had 14 guidelines and 65 checkpoints using Priority 1/2/3; **WCAG 2.0** restructured to 4 principles, 12 guidelines, and 61 success criteria using A/AA/AAA
- **WCAG 3.0** is still a working draft with no defined release date — do not confuse it with a recommendation
- The first web accessibility guideline dates to **January 1995**, compiled by Gregg Vanderheiden
