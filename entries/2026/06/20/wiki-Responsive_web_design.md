---
source: sources/wiki-Responsive_web_design.md
source_url: https://en.wikipedia.org/wiki/Responsive_web_design
---

## Responsive Web Design (RWD)

Responsive web design is an approach to web design that makes web pages render well across a variety of devices and screen sizes — from mobile phones to desktop monitors — ensuring usability and satisfaction. Coined by Ethan Marcotte in 2010, RWD relies on three core techniques: fluid grids, flexible images, and CSS3 media queries. It became critically important as mobile devices grew to account for the majority of web traffic, and was reinforced by Google's 2015 "Mobilegeddon" algorithm update that boosted mobile-friendly sites in search rankings.

## Key Concepts

- **Fluid grids**: Page elements are sized using relative units (percentages) rather than absolute units (pixels or points), allowing layouts to scale proportionally to the viewport.
- **Flexible images**: Images are also sized in relative units to prevent them from overflowing their containing elements.
- **CSS3 media queries**: An extension of the `@media` rule that applies different CSS styles based on device characteristics such as viewport width or physical display size.
- **Mobile-first design**: A related philosophy — build the baseline experience for the smallest screens first, then progressively enhance for larger devices (progressive enhancement), rather than relying on graceful degradation from a complex desktop design.
- **RESS (Responsive + Server-Side)**: A hybrid approach combining responsive front-end techniques with server-side components to deliver more optimized experiences per device category.
- **User interface plasticity**: The broader concept that a UI should withstand variations in device characteristics and environment while preserving usability. RWD is an instance of this principle.
- **"Content is like water"**: A metaphor illustrating that content should flow and adapt to fill whatever container (device/viewport) it is placed in.

## Commands and Syntax

- **Media query syntax**:
  ```css
  @media (max-width: 768px) {
    .container { width: 100%; }
  }
  ```
- **Fluid grid sizing**: Use percentage-based widths instead of fixed pixels.
  ```css
  .column { width: 48%; }   /* not width: 460px; */
  ```
- **Flexible images**:
  ```css
  img { max-width: 100%; height: auto; }
  ```
- **Viewport meta tag** (standard practice for mobile rendering):
  ```html
  <meta name="viewport" content="width=device-width, initial-scale=1">
  ```
- **Testing tools**: Browser developer tools in Chrome, Firefox, and Safari all include responsive design viewport resizers. Adobe Edge Inspect was historically used for simultaneous cross-device testing.

## Relationships

- **Progressive enhancement / Graceful degradation**: RWD aligns with progressive enhancement (build simple, enhance upward) rather than graceful degradation (build complex, degrade downward). Mobile-first design is a direct application of progressive enhancement.
- **CSS frameworks**: Bootstrap, Foundation, and Tailwind CSS all provide responsive grid systems and utility classes built on RWD principles.
- **Tableless web design**: RWD evolved from earlier tableless layout approaches; both reject HTML tables for layout in favor of CSS.
- **Adaptive web design**: A related but distinct approach that serves different fixed layouts for specific breakpoints, rather than a fully fluid layout.
- **CSS preprocessors (Sass, Less, Stylus)**: Often used in RESS approaches to generate device-specific stylesheets server-side.
- **SEO / Google ranking**: Google explicitly recommends responsive design and penalizes non-mobile-friendly sites in mobile search results.
- **Advertising**: Banner ads and video ads initially posed challenges for RWD because they were not fluid; the ad industry adapted with device-targeted ad formats.

## Exam-Relevant Points

- **Definition**: RWD uses three techniques — fluid grids, flexible images, and media queries — coined by Ethan Marcotte in a May 2010 *A List Apart* article.
- **Fluid grids use relative units (%, em, rem)**, not absolute units (px, pt).
- **Media queries** are an extension of the CSS `@media` rule and apply styles conditionally based on device/viewport characteristics.
- **Mobile-first** means designing for the smallest screen first and enhancing upward — this is progressive enhancement, not graceful degradation.
- **Google's Mobilegeddon (2015)** boosted mobile-friendly sites in mobile search rankings, making RWD an SEO concern, not just a UX concern.
- **RESS** combines client-side responsive CSS with server-side device detection for more tailored experiences.
- **First major responsive site**: Audi.com (late 2001), predating the term "responsive web design" by nearly a decade.
- **2013** was called "The Year of Responsive Web Design" by Mashable.
- **RWD is an example of user interface plasticity** — the ability of a UI to adapt to varying system and environmental conditions while maintaining usability.
- **Testing** should use browser developer tools with viewport resizing; dedicated mobile emulators and cross-device tools supplement this.
