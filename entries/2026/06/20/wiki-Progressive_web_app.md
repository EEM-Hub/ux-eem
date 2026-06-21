---
source: sources/wiki-Progressive_web_app.md
source_url: https://en.wikipedia.org/wiki/Progressive_web_app
---

## Progressive Web Applications (PWAs)

Progressive web applications are a type of web application that can be installed on a device as a standalone app, using the device's browser offline cache. Introduced from 2016 as an alternative to native platform-specific apps, PWAs are built with standard web technologies (HTML, CSS, JavaScript, WebAssembly) and work across platforms without requiring separate bundling or distribution. They can optionally be published to app stores but are primarily distributed via the web.

## Key Concepts

- **PWA definition**: A web app that meets installability criteria — served over HTTPS, registers a service worker with fetch handler, and includes a valid web app manifest
- **Progressive enhancement**: PWAs employ progressive enhancement, working on any standards-compliant browser with increasing capability on more capable browsers
- **App Shell Model**: Architectural pattern where the service worker caches the basic UI "shell" in the browser's offline cache, allowing the app to load a static frame first, then progressively load content — enables native-like use with or without connectivity
- **Cross-platform by default**: Single codebase works on desktop and mobile; no separate bundling per platform needed
- **Not dependent on app stores**: Can be distributed directly via the web, though Google Play, Microsoft Store, and Samsung Galaxy Store support PWA publication (Apple App Store does not)
- **Size advantage over native apps**: Twitter Lite consumed 1–3% of native app size; Starbucks PWA was 99.84% smaller than its iOS equivalent

## Commands and Syntax

**Web App Manifest (manifest.json)** — W3C-specified JSON file with required properties:
```json
{
  "name": "App Name",
  "short_name": "App",
  "start_url": "/",
  "display": "standalone",
  "icons": [
    { "src": "icon-192.png", "sizes": "192x192" },
    { "src": "icon-512.png", "sizes": "512x512" }
  ]
}
```
- `display` must be one of: `standalone`, `fullscreen`, or `minimal-ui`
- Icons must include both 192px and 512px versions

**Service Worker Registration**:
```javascript
navigator.serviceWorker.register('/sw.js');
```

**Service Worker Lifecycle**: Registration → Installation → Activation
- Installation occurs when no service worker exists or an update is available
- Activation occurs when all PWA pages are closed (prevents version conflicts)
- Only one service worker can be active per domain

**iOS-specific metadata** (Apple meta tags for Safari):
```html
<meta name="apple-mobile-web-app-capable" content="yes">
<meta name="apple-mobile-web-app-title" content="App Name">
<link rel="apple-touch-icon" href="icon.png">
```

## Relationships

- **Service Workers** are the core enabling technology — they are a type of **Web Worker** that acts as a programmable network proxy, enabling offline support, push notifications, and background sync
- **Web App Manifest** is a W3C specification that provides metadata for installability — connects to home screen integration, splash screens, and app discovery
- **WebAssembly** enables near-native performance within PWAs, allowing libraries written in C/C++ to run in the browser
- **Data Storage APIs**: PWAs use **Web Storage** (sessionStorage/localStorage for key-value data) and **IndexedDB** (for structured/JSON data) since execution contexts are unloaded when idle
- **HTTPS/TLS** is a hard requirement — PWAs must be served over secure origins with no mixed content
- **Responsive Web Design** is foundational — screen-size flexibility made PWA development practical
- **Google Lighthouse** is the standard open-source audit tool for evaluating PWA compliance
- **Progressive Enhancement** is the core development strategy — baseline functionality works everywhere, enhanced features layer on top

## Exam-Relevant Points

- **Three technical criteria for installability**: (1) served over HTTPS with no mixed content, (2) service worker with fetch handler registered, (3) valid web app manifest with `name`/`short_name`, `start_url`, `display`, and `icons`
- **Service worker lifecycle has exactly three steps**: Registration, Installation, Activation
- **Only one service worker can be active per domain** at a time
- **Manifest `display` values** that qualify: `standalone`, `fullscreen`, `minimal-ui`
- **Manifest icon sizes required**: 192px and 512px
- **Apple App Store does not support PWA publication**; Google Play, Microsoft Store, and Samsung Galaxy Store do
- **Microsoft Store auto-publishes** qualifying PWAs discovered via Bing indexing, even without developer request
- **Firefox desktop abandoned PWA support** in December 2020, then added Windows-only PWA support in Firefox 143 (September 2025)
- **Term coined in 2015** by Frances Berriman and Alex Russell (Google Chrome engineer)
- **Service worker caches differ from HTTP caches**: they can explicitly prefetch content before first use and explicitly discard when no longer needed
- **iOS Safari only partially implements manifests** — developers must use Apple-specific meta tags for full PWA metadata
- **Data storage**: `sessionStorage` is wiped on session end; `localStorage` persists across sessions; IndexedDB handles structured/JSON data
