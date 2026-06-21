---
source: sources/wiki-Web_accessibility.md
source_url: https://en.wikipedia.org/wiki/Web_accessibility
---

## Web Accessibility Standards, Legislation, and Assistive Technologies

Web accessibility (eAccessibility) is the inclusive practice of removing barriers that prevent people with disabilities from interacting with websites. This page covers the definition of web accessibility, the disability categories it addresses, assistive technologies used for web browsing, the W3C guidelines ecosystem (WCAG, ATAG, UAAG), and country-by-country legislation mandating accessible web content. Through the curb cut effect, accessibility improvements also benefit users with situational disabilities and bandwidth constraints.

## Key Concepts

- **Web accessibility** ensures equal access to web content for people with physical, sensory, cognitive, and situational disabilities
- **Curb cut effect**: accessibility features designed for disabled users benefit everyone (e.g., captions help in noisy environments)
- **Five disability categories addressed**: Visual, Motor/Mobility, Auditory, Seizure, Cognitive/Intellectual
- **Situational disability**: temporary context-based limitations (e.g., carrying a baby makes you effectively one-handed)
- **Semantic HTML** with text equivalents for images and meaningful link names enables assistive technology compatibility
- **WCAG 2.0 four principles**: Perceivable, Operable, Understandable, Robust (POUR)
- **WCAG 2.0 structure**: 4 principles → 12 guidelines (untestable goals) → 65 testable success criteria
- **ISO/IEC 40500:2012** is the ISO standard equivalent of WCAG 2.0
- **Three W3C guideline sets**: WCAG (content), ATAG (authoring tools), UAAG (user agents/browsers)
- **ATAG** has 28 checkpoints covering accessible output, author prompting, checking/correcting content, and tool accessibility
- **UAAG** covers content access, rendering control, UI control, and standard programming interfaces
- Close to **93% of web accessibility practitioners** received no formal schooling on accessibility (2018 WebAIM survey)

## Assistive Technologies

- **Screen readers**: synthesized speech output of screen content (used by blind/vision-impaired users)
- **Braille terminals**: refreshable braille displays with raised pegs; paired with standard or braille keyboards
- **Screen magnification software**: enlarges display content for low-vision users
- **Speech recognition software**: accepts spoken commands or dictation for users who cannot use mouse/keyboard
- **Keyboard overlays**: assist users with motor control difficulties
- **Captioned/sign language video**: enables deaf and hard-of-hearing access

## Commands and Syntax

No CLI commands per se, but key technical practices:

- Code with **semantically meaningful HTML**
- Provide **text equivalents** (alt text) for all images
- Use **meaningful link text** (not "click here")
- Ensure links are **differentiated by more than color alone** (underline or other visual cue)
- Make **clickable areas large enough** for imprecise pointer control
- Ensure full **keyboard-only navigation** support
- Provide **closed captions, chapters, and sign language versions** for video
- Avoid or make optional **flashing/strobe effects**
- Write in **plain language** with instructional diagrams

## Relationships

- **WCAG ↔ ATAG ↔ UAAG**: Three complementary W3C guideline sets covering content, authoring tools, and browsers respectively
- **WCAG → National legislation**: Most countries reference WCAG 2.0/2.1 in their accessibility laws rather than creating independent standards
- **Web accessibility ↔ Universal design**: Web accessibility is a specific application of universal/inclusive design principles
- **Accessibility ↔ Usability**: Properly implemented accessibility does not decrease usability for non-disabled users
- **EN 301 549**: European standard that operationalizes WCAG for EU Web Accessibility Directive compliance
- **European Accessibility Act (2025)** extends requirements from public sector to private sector products and services

## Exam-Relevant Points

- **WCAG 2.0 was published December 11, 2008**; WCAG 2.1 extended it in 2018
- **WCAG 2.0 has 4 principles, 12 guidelines, 65 success criteria** — principles/guidelines are stable; techniques are updated periodically
- **WCAG 2.0 = ISO/IEC 40500:2012** — know this equivalence
- **POUR mnemonic**: Perceivable, Operable, Understandable, Robust
- **First successful web accessibility lawsuit**: 2000, blind Australian man vs. Sydney Olympic Games committee (Disability Discrimination Act 1992), $20,000 award
- **EU Web Accessibility Directive (2016)**: public sector websites by Sept 2018, mobile apps by June 2021
- **European Accessibility Act**: enters force June 28, 2025, extends to private sector
- **Accessible Canada Act**: passed 2019, builds on provincial laws (AODA, Manitoba, Nova Scotia)
- **Color differentiation alone is insufficient** — links must be underlined or otherwise visually distinguished beyond color
- **ATAG has 28 checkpoints**; WCAG 1.0 has 14 guidelines; WCAG 2.0 restructured to principles/guidelines/success criteria
- **Keyboard-only navigation** and **single switch access** must be supported — never code pages that hinder non-mouse navigation
- **93% of practitioners lack formal accessibility training** — this statistic underscores the gap in professional education
