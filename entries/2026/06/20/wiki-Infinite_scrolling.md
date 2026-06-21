---
source: sources/wiki-Infinite_scrolling.md
source_url: https://en.wikipedia.org/wiki/Infinite_scrolling
---

## Infinite Scrolling: Pattern, Variations, and UX Concerns

Infinite scrolling (also called endless scrolling) is a web design pattern where new content is dynamically appended to the bottom of a page as the user scrolls, creating the appearance of a never-ending page. It stands in contrast to pagination, which divides content into discrete, numbered pages. The pattern is widely used in social media feeds and search results, but raises significant usability and ethical concerns.

## Key Concepts

- **Core mechanic**: Content loads dynamically as the user approaches the bottom of the viewport, eliminating the need to click "next page."
- **Contrast with pagination**: Pagination divides content into discrete pages with explicit navigation; infinite scroll removes those boundaries.
- **Originated at Microsoft**: Filed as a US patent (US7664739B2) on 14 February 2006 by the Windows Live Image Search team (now Bing). First shipped 8 March 2006.
- **Inventors**: Julie Farago, Nick Craswell, and Hugh Williams (Microsoft).
- **Accessibility concern**: Usability research indicates infinite scrolling can present accessibility issues — users may struggle to reach footer content, lose their place, or have difficulty with assistive technologies.
- **Addiction pathway**: The lack of natural stopping cues has been identified as contributing to smartphone addiction and social media addiction (sometimes called "doomscrolling").

## Commands and Syntax

No specific commands or configuration syntax — this is a design pattern, not a tooling topic. Implementation typically involves:

- **Scroll event listeners** or **Intersection Observer API** to detect when the user nears the bottom of content.
- **Dynamic content fetching** (AJAX/fetch calls) to load the next batch of items.
- **DOM appending** to insert new content below existing items.

## Relationships

- **Pagination** — the primary alternative pattern; trades discoverability of all content for user control and predictability.
- **"Load more" button** — a hybrid variation that gives users explicit control over when new content appears (used by Google Search).
- **Pagination indicators within infinite scroll** — another hybrid showing scroll progress (used by Google Shopping mobile).
- **Doomscrolling** — the behavioral consequence of infinite scroll's removal of stopping cues.
- **Problematic smartphone/social media use** — broader behavioral research context linking infinite scroll to compulsive usage patterns.
- **Social media feed design** — Instagram, TikTok, YouTube Shorts, and Meta Reels all employ infinite scroll as a core interaction pattern.

## Exam-Relevant Points

- Infinite scroll removes natural stopping cues, which is a known contributor to compulsive usage — a key ethical consideration in UX design.
- The pattern creates accessibility barriers: users cannot easily reach page footers, bookmark positions, or navigate with keyboards/screen readers.
- Two main hybrid variations mitigate pure infinite scroll's drawbacks: (1) "load more" buttons for user control, and (2) integrated pagination indicators for orientation.
- When choosing between infinite scroll and pagination, the decision should weigh content type, user task (browsing vs. goal-directed search), and accessibility requirements.
- Infinite scroll is best suited for discovery/browsing tasks; pagination is preferred for goal-directed tasks where users need to locate specific items or return to a known position.
