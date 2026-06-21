---
source: sources/wiki-Web_performance.md
source_url: https://en.wikipedia.org/wiki/Web_performance
---

## Web Performance Optimization (WPO)

Web performance refers to the speed at which web pages are downloaded and displayed in a user's browser. Web performance optimization (WPO) is the discipline of improving this speed through front-end and back-end techniques. Faster sites increase visitor retention, user satisfaction (especially on mobile/slow connections), and reduce energy consumption. Steve Souders coined the term "WPO" in 2004 and established that at least 80% of page load time is controlled by front-end structure.

## Key Concepts

- **Front-end optimization (FEO) / content optimization**: The primary focus of WPO — reducing file sizes and minimizing the number of HTTP requests needed to load a page
- **Resource consolidation**: Bundling smaller files (e.g., images) into a single file to reduce HTTP round trips, since browsers limit simultaneous TCP connections per host
- **File compression**: Reduces code file sizes by approximately 40%, improving responsiveness
- **Code minification**: Removes comments, whitespace, and shortens variable names — can reduce file sizes by up to 60%
- **Lossy image compression**: Removes non-essential header information and reduces image quality in ways imperceptible to users
- **Vector graphics substitution**: Replacing raster graphics with resolution-independent vector graphics for simple geometric images
- **Lazy loading**: Defers loading of images/video until they are needed (e.g., when scrolled into view), reducing initial page load time, weight, and resource usage
- **Web caching**: Stores copies of resources to reduce server load, bandwidth, and latency; can be client-side (forward) or server-side (reverse)
- **Content Delivery Network (CDN)**: Proxy servers distributed globally that serve content from the server closest to (or fastest for) the user
- **80/20 rule (Souders)**: At least 80% of load time is front-end controlled, not server-side

## Commands and Syntax

No CLI commands per se, but key tools and measurement approaches:

- **Google Lighthouse**: Chrome DevTools component for measuring web performance
- **PageSpeed Insights**: Google's web tool for measuring and comparing site performance against recommended thresholds
- **Core Web Vitals library**: Google's JS library for measuring performance metrics in frontend applications
- **Network Monitor (Firefox)**: Provides insight into network-level transmission slowdowns
- **Framework integration**: React (`create-react-app` measuring), NuxtJS (`@nuxtjs/web-vitals`), Vue (`vue-web-vitals`) all provide modules for measuring performance metrics

## Relationships

- **HTTP/2 vs HTTP/1.x**: HTTP/2 improves performance through binary framing, full multiplexing (single connection for parallelism), header compression, and server push — directly reduces the overhead that HTTP/1 imposed on optimization strategies
- **User Experience (UX)**: WPO is a core component of UX; page speed directly affects perceived quality and user satisfaction
- **CDNs**: Work in tandem with HTTP/2 and caching strategies; serve as the delivery backbone for optimized assets
- **Web caching and HTTP cache**: Configured via request/response headers; operates at both browser and CDN levels
- **Mobile performance**: Mobile users on slower connections benefit disproportionately from WPO techniques
- **Environmental impact**: Reduced data transfer lowers power consumption and carbon footprint of web infrastructure
- **SEO**: Google uses site speed as a search ranking factor, directly linking WPO to discoverability

## Exam-Relevant Points

- **80% rule**: At least 80% of page load time is front-end, not server (Souders, 2007)
- **Compression reduces code files by ~40%**; **minification reduces by up to ~60%**
- **HTTP/2 advantages over HTTP/1**: binary (not textual), fully multiplexed (not ordered/blocked), single connection for parallelism, header compression, server push
- **Lazy loading** defers resource loading until needed — reduces initial page weight and system resource usage
- **Core Web Vitals metrics**: TTFB (Time to First Byte), FCP (First Contentful Paint), FID (First Input Delay), CLS (Cumulative Layout Shift), LCP (Largest Contentful Paint)
- **Additional metrics**: Request Count, DOMContentLoaded, Above The Fold Time, Round Trip Time, Render Blocking Resources count, Onload Time, Connection Time, Total Page Size
- **CDN selection logic**: Chooses the server with the quickest response time based on network proximity
- **Web caching positions**: Forward (client-side) and reverse (server-side)
- **Resource consolidation** reduces HTTP requests by bundling files, addressing browser connection limits per host
- **Steve Souders** coined "WPO" in 2004; authored *High Performance Websites* (2007)
