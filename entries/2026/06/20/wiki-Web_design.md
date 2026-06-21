---
source: sources/wiki-Web_design.md
source_url: https://en.wikipedia.org/wiki/Web_design
---

## Web Design: Disciplines, History, and Core Techniques

Web design encompasses the skills and disciplines involved in producing and maintaining websites, spanning graphic design, UI design, UX design, markup authoring, and SEO. It focuses on the front-end (client-side) design process and overlaps with web engineering and web development. The field has evolved from simple table-based layouts in the early 1990s through the browser wars, Flash era, and CSS revolution to today's responsive, mobile-first paradigm.

## Key Concepts

- **Web design is multidisciplinary** — combines graphic design, UI design, UX design, authoring (code), and SEO into a single practice
- **Progressive enhancement** — strategy that delivers core content via HTML first, then layers CSS styling and JavaScript interactivity; ensures accessibility and backwards compatibility
- **Responsive web design** — CSS3-based approach using `@media` rules to adapt layouts per device; became critical after Google's 2018 mobile-first indexing rollout
- **Fluid layouts** — browser-adjustable layouts that replaced rigid table-based and grid-based designs around 2000; content blocks reflow based on window size rather than fixed pixel widths
- **Static vs. dynamic websites** — static sites serve pre-built files (simpler hosting, better security, faster); dynamic sites generate pages server-side from databases (more flexible, require broader skillset)
- **Homepage importance is debated** — traditional view (Nielsen, Soucy) emphasized homepage as most important page; Spool (2007) argued it's actually the least important as search engines and RSS drive users directly to internal pages
- **Carousels/sliders** — popular homepage element from 2012-2013; widely criticized as hurting both usability and SEO
- **Motion graphics** — must include user controls to disable animations per W3C accessibility standards
- **Code quality** — conforming to W3C standards via validation; requires correct DOCTYPE declaration; non-conformance doesn't break sites but affects readability, accessibility, and maintainability
- **Typography** — designers limit typeface variety for consistency; CSS3 font downloading (supported in Safari 3.1, Opera 10, Firefox 3.5) expanded web typography options

## Commands and Syntax

- **W3C Markup Validation**: Use the W3C validator to check HTML conformance; requires correct `<!DOCTYPE>` declaration
- **CSS `@media` rule**: Core mechanism for responsive web design — enables per-device styling within a single stylesheet
- **Progressive enhancement stack**: HTML (content) → CSS (presentation/layout) → JavaScript (interactivity/enhancement)
- **Static site generators**: Jekyll, Adobe Muse — automated static site creation that gained popularity around 2015
- **Dynamic page technologies**: Perl, PHP, ASP for server-side generation; template approach (PHP/ASP) where server-side pages mirror client-side structure with data insertion tags
- **Content management systems**: Higher-level tools (blogs, wikis, forums) that abstract away coding, building on general-purpose platforms

## Relationships

- **User Interface Design** — web design's visual and interactive layer; page layout, typography, and interactive design all feed into UI
- **User Experience Design** — closely intertwined; UX governs how users understand and interact with the site; drives the trend toward universal accessibility
- **Web Accessibility** — cross-cutting concern; W3C guidelines mandate animation controls, semantic HTML, and standards compliance
- **Search Engine Optimization** — design decisions (responsive design, carousel avoidance, code quality) directly impact SEO; Google's mobile-first indexing made responsive design essential
- **Web Development / Web Engineering** — web design overlaps with but is distinct from these broader technical disciplines
- **Content Management Systems** — abstraction layer that separates design from content authoring; shifted web creation from coding to organizational/design tasks
- **Progressive Enhancement** — architectural strategy connecting HTML semantics, CSS presentation, and JavaScript behavior in a layered dependency

## Exam-Relevant Points

- **Progressive enhancement order**: HTML (content) → CSS (styling) → JavaScript (interactivity) — content must be accessible without JS or CSS
- **Responsive design uses CSS3 `@media` rules**, not JavaScript, as its core mechanism
- **Mobile-first indexing**: Google announced rollout in March 2018 — responsive sites are advantaged
- **Fluid layouts vs. responsive design**: fluid layouts adjust to window/font size; responsive design uses CSS3 media queries for device-specific rules — responsive is the newer, more granular approach
- **Static sites**: simpler hosting, less server administration, fewer security holes, faster page serving; dynamic sites require server-side + database + client-side skills
- **W3C role**: Founded October 1994 to develop common protocols, prevent browser monopolization, and set interoperability standards (HTML, CSS, JavaScript)
- **CSS introduced December 1996** by W3C — separated presentation from semantics, improved accessibility, enabled tableless design
- **Two primary web design roles**: web designer (visual: layout, color, typography) and web developer (technical implementation) — often overlap in smaller organizations
- **W3C accessibility requirement**: site visitors must be able to disable motion graphics/animations
- **Carousels are widely considered harmful** to both usability and SEO despite their popularity
- **Homepage traffic patterns shifted** in the 2000s — users increasingly bypass homepages via search engines, newsletters, and RSS, arriving directly at internal content pages
