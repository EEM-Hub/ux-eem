---
source: sources/wiki-Above_the_fold.md
source_url: https://en.wikipedia.org/wiki/Above_the_fold
---

## Above the Fold: Content Prioritization by Viewport Position

This page covers the concept of "above the fold" — originally a newspaper term for the upper half of the front page visible when folded for display, now widely adopted in web design to describe the portion of a webpage visible without scrolling. The concept is foundational to content hierarchy, advertising placement, and layout strategy.

## Key Concepts

- **Above the fold** (web): the portion of a webpage visible in the browser viewport without scrolling; also called "above the scroll"
- **No fixed pixel definition**: because screen resolutions and browser window sizes vary, there is no universal pixel boundary for "the fold" — responsive layouts further complicate this
- **77% non-scroll stat (Nielsen, 2006)**: Jakob Nielsen found 77% of visitors do not scroll, seeing only above-the-fold content — though this figure is dated and likely shifted with mobile-first browsing
- **84% attention differential (Schade/NNgroup)**: users treat above-fold content dramatically differently from below-fold content, with a large attention drop-off after the fold
- **Below the fold**: content not visible without scrolling; receives significantly less attention and engagement
- **"After the jump"**: synonym for content accessible only via clickthrough or scrolling
- The fold concept extends beyond web pages to search result rankings (first-page placement as "above the fold") and even resume layout (top-third "hot zone")

## Commands and Syntax

Not applicable — this is a conceptual/design topic, not a technical implementation topic. However, relevant implementation considerations include:

- **Responsive design**: layouts that reflow based on viewport size mean the fold is dynamic, not a fixed pixel line
- **JavaScript visibility tricks**: Apple once used JS to push legally required content below the fold on its UK site (Samsung acknowledgement case, 2012) — an example of fold manipulation with legal consequences
- Ad networks define their own fold thresholds: BlogHer used 768px, FoodieBlogRoll used 1000px

## Relationships

- **Visual hierarchy and content prioritization**: above the fold is one application of the broader principle that spatial position signals importance
- **Responsive/adaptive design**: directly complicates fold-based design since viewport dimensions are not fixed
- **F-pattern and scanning behavior**: Nielsen's broader eye-tracking research connects to why above-fold content gets disproportionate attention
- **Advertising and monetization**: ad placement above vs. below the fold has measurable viewability impact (Google research)
- **Information architecture**: decisions about what content appears first are fundamentally IA decisions
- **Progressive disclosure**: the fold acts as a natural disclosure boundary — what to show immediately vs. on demand

## Exam-Relevant Points

- The fold has no universal pixel definition in web design — it depends on screen resolution, browser size, and responsive layout behavior
- Nielsen's 2006 finding (77% don't scroll) is frequently cited but should be understood as dated; NNgroup's later research confirms the attention differential (84%) persists even as scrolling behavior has increased
- Best practice: place the most important content above the fold, but do not sacrifice usability or design quality to cram everything above it
- The fold concept originated in print newspaper layout (upper half of front page visible on newsstands)
- Ad networks define fold thresholds differently (no industry standard pixel value)
- The fold is a design consideration, not an absolute rule — modern guidance balances fold placement with overall page usability
