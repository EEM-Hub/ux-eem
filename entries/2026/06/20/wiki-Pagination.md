---
source: sources/wiki-Pagination.md
source_url: https://en.wikipedia.org/wiki/Pagination
---

## Pagination: Dividing Content Across Pages in Web and Print

Pagination is the process of dividing content into discrete pages, whether electronic or printed. In web software, pagination is a foundational UX pattern used to break large data sets into manageable chunks, displayed across multiple navigable pages within a single view. The concept spans from historical print page-numbering (common since ~1550) through modern dynamic web pagination, and involves both technical implementation choices and significant usability considerations.

## Key Concepts

- **Pagination** divides a document or data set into discrete pages; **paging** is a synonym.
- **Electronic pages** can be fixed-size (word processor, PDF) or dynamic (HTML/web pages).
- **Client-side pagination**: all records are pre-loaded in the HTML source; JavaScript or CSS handles page display. Best for very small data sets.
- **Server-side pagination**: each page is requested individually from the server on navigation. More common; appropriate for large data sets. Provides faster initial page load and works without JavaScript (accessibility benefit).
- **Hybrid (AJAX) pagination**: JavaScript requests subsequent pages from the server and inserts them into the DOM without a full page reload.
- **Infinite scrolling** is an alternative to pagination — content loads continuously. Pagination allows skipping pages and supports permanent links (e.g., `offset` URL parameter); infinite scrolling does not.
- **Widows and orphans** — typographic rule about avoiding stranded lines at page boundaries; relevant to print pagination algorithms.
- **Separation of presentation and content** — semantic markup (XML, HTML) allows the same content to be paginated differently for different output media (print, screen, mobile).

## Commands and Syntax

- **MediaWiki-style permanent pagination links**: use an `offset` URL parameter (e.g., `?offset=20`) to create deep-linkable paginated views.
- **SQL pagination** (database layer): `SELECT ... LIMIT n OFFSET m` pattern retrieves one "page" of rows at a time.
- **Page break controls in markup**:
  - CSS: `page-break-before`, `page-break-after`, `break-before`, `break-after`
  - Word processors: manual page break insertion overrides automatic pagination algorithms
- **Soft hyphens** (`&shy;` in HTML): inserted to control word-wrap behavior without forcing a visible hyphen.

## Relationships

- **Search engine results pages (SERPs)**: pagination is the standard pattern for displaying limited results per page.
- **Forum threads / feed views**: pagination or infinite scroll are the two primary patterns for long content lists.
- **Accessibility**: server-side pagination works without JavaScript, making it more accessible; client-side pagination requires JavaScript and may fail for assistive technology users.
- **SEO and deep linking**: paginated pages with URL parameters (e.g., `?page=3`) are individually addressable and indexable, unlike infinite scroll.
- **Database queries**: pagination at the UI layer maps directly to `LIMIT`/`OFFSET` (or cursor-based) queries at the data layer.
- **Responsive design**: pagination UI components (page number links, previous/next controls) must adapt to different viewport sizes.

## Exam-Relevant Points

- **Server-side pagination is preferred for large data sets** — faster initial load, better accessibility, supports complex business logic.
- **Client-side pagination is only appropriate for very small record sets** where all data can be returned at once.
- **AJAX hybrid approach** combines benefits: no full page reload (client-side feel) with on-demand data loading (server-side efficiency).
- **Pagination vs. infinite scrolling trade-off**: pagination supports skip-navigation and permanent links; infinite scrolling provides seamless browsing but loses addressability.
- **Key usability decisions** when implementing pagination: whether to include previous/next links, how many page links to display, whether to link to first/last pages, and whether users can control records-per-page.
- **Pagination is described as "difficult to implement correctly"** — the usability questions around navigation controls are non-trivial design decisions.
- **Separation of content and presentation** means pagination decisions can be deferred to the rendering layer — the same content can be paginated differently for print vs. screen.
