---
source: sources/wiki-Single-page_application.md
source_url: https://en.wikipedia.org/wiki/Single-page_application
---

## Single-Page Applications (SPAs): Architecture and UX Trade-offs

A single-page application (SPA) is a web application that dynamically rewrites the current page with new data from the server, rather than loading entire new pages. The goal is faster transitions that make the website feel more like a native app. All necessary HTML, JavaScript, and CSS is either retrieved with a single page load or dynamically loaded in response to user actions — a page refresh never occurs.

## Key Concepts

- **Core mechanism**: SPAs avoid full page reloads by dynamically updating the DOM with new data fetched from the server, creating a more fluid user experience
- **Thin server architecture**: SPAs shift logic from server to client, reducing the server's role to a pure data API/web service — this is sometimes called "Thin Server Architecture"
- **Thick stateful server**: Alternative where the server maintains client state in memory, simulates a web browser, and sends delta changes — simpler development model but more server resources required
- **Thick stateless server**: Client sends its current state with each Ajax request; server reconstructs state, generates updates, and returns them — more scalable since no per-client state is stored on server
- **Progressive downloading**: SPAs often lazily load features and screen modules as needed rather than downloading everything upfront
- **State-page analogy**: "States" in a SPA are analogous to "pages" in a traditional site — state navigation within a single page mirrors page navigation

## Commands and Syntax

- **Document hashes**: Use HTML element IDs with CSS `:target` pseudo-class to show/hide sections without JavaScript
- **History API**: `pushState` and `replaceState` provide programmatic access to the browser URL and history, replacing the older hash-fragment (`#`) approach
- **Hash-bang URLs** (`#!`): Deprecated Google convention (2009–2015) for making Ajax-driven state crawlable by search engines
- **Data transport patterns**:
  - Server returns raw data (XML/JSON) → client-side JavaScript translates to HTML via XSL or JSON templates → updates DOM
  - Server returns HTML fragments → JavaScript updates partial DOM area
- **Ajax**: Asynchronous requests via `XMLHttpRequest` or modern `fetch()` API for server communication without page reload
- **WebSockets**: Bidirectional real-time client-server communication; superior to Ajax for real-time use cases
- **Server-Sent Events (SSE)**: Server-initiated data push over standard HTTP; includes automatic reconnection, event IDs, and arbitrary event types

## Relationships

- **JavaScript frameworks**: Angular, React, Vue.js, Svelte, Ember.js, Knockout.js, Meteor.js all adopt SPA principles with different architectural patterns (MVC, MVVM, component-based)
- **WebAssembly SPAs**: Blazor, Flutter Web, Avalonia, Uno Platform, and OpenSilver extend the SPA model to non-JavaScript languages (C#, Dart) via WebAssembly
- **Meta-frameworks**: Astro, Fresh, enhance.dev represent a newer category emphasizing progressive enhancement, SSR, and minimal client-side JS — they shift work to build-time or server-side while hydrating only interactive parts
- **Progressive Web Applications (PWAs)**: Related concept; SPAs can be wrapped as PWAs for offline capability
- **Server-side rendering (SSR)**: Complementary technique where the first page load renders on the server, subsequent updates happen client-side — addresses SEO and initial load speed
- **Native app analogy**: SPA approach on the web parallels the single-document interface (SDI) pattern in desktop applications

## Exam-Relevant Points

- **SEO challenge**: SPAs historically struggled with SEO because search engine crawlers couldn't execute JavaScript; solutions evolved from hash-bang URLs (deprecated 2015) → dynamic rendering (deprecated by Google 2024) → SSR/static rendering/hydration (current recommendation)
- **Browser history problem**: SPAs break the back/forward button by default because there's only one page; solved via URL hash fragments or the History API (`pushState`/`replaceState`)
- **Analytics gap**: SPAs don't trigger new page loads, so analytics tools like Google Analytics require explicit function calls to track navigation — failing to do this means no tracking data
- **Security concerns**: SPAs face standard web vulnerabilities (XSS) plus unique risks: data exposure via APIs, client-side logic vulnerabilities, and client-side enforcement of server-side security; DAST tools struggle to scan JavaScript-rich SPAs
- **Performance trade-off**: "Pay me now or pay me later" — SPAs must download the framework and application code upfront; techniques like code splitting, lazy loading, and selective prerendering mitigate but don't eliminate this cost
- **Local execution**: SPAs can run from local file system using the `file://` URI scheme with browser Web Storage for persistence
- **Framework differentiators**: Svelte compiles away the framework (no virtual DOM shipped to client); React uses virtual DOM with JSX; Angular offers bidirectional data binding; Meteor provides full-stack reactivity with automatic client-server sync via DDP
- **Three server architectures** (thin, thick-stateful, thick-stateless) represent different trade-offs between scalability, development simplicity, and server resource usage
