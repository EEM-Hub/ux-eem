---
source: sources/wiki-Site_map.md
source_url: https://en.wikipedia.org/wiki/Site_map
---

## Sitemaps: Types, XML Protocol, and Search Engine Integration

A sitemap is a list of pages of a website within a domain. Sitemaps serve both human visitors (as navigational aids) and software (as structured data for web crawlers). This page covers the three primary kinds of sitemaps, the XML Sitemap protocol jointly supported by major search engines, and the syntax for creating valid XML sitemaps.

## Key Concepts

- **Three types of sitemaps**: (1) planning sitemaps used by web designers, (2) human-visible hierarchical page listings, and (3) structured listings for web crawlers/search engines
- **Human-visible sitemaps** present a systematic, typically hierarchical view of site content; they help visitors find pages and can double as crawler aids
- **Site indexes** are alphabetically organized sitemaps, a distinct approach from hierarchical ones
- **XML Sitemaps** are structured files (typically `sitemap.xml`) that list pages, their relative importance, and update frequency for search engine consumption
- **The Sitemaps protocol** was introduced by Google and is now jointly supported by Google, Bing, Yahoo, and Ask
- Sitemaps are referenced from the `robots.txt` file
- Sitemaps are especially important for pages not accessible via hyperlinks — those only reachable through search tools, forms, or dynamically constructed JavaScript URLs
- **Sitemaps do not guarantee crawling**, and being crawled does not guarantee indexing

## Commands and Syntax

**XML Sitemap structure:**
```xml
<?xml version="1.0" encoding="UTF-8"?>
<urlset xmlns="http://www.sitemaps.org/schemas/sitemap/0.9">
  <url>
    <loc>http://www.example.net/?id=who</loc>
    <lastmod>2009-09-22</lastmod>
  </url>
</urlset>
```

**Key syntax notes:**
- All tag values must be XML entity-escaped
- Google **ignores** `<priority>` and `<changefreq>` values
- Google **may use** `<lastmod>` only if it is consistently and verifiably accurate (matches actual last modification date)

## Relationships

- **robots.txt** — sitemaps are pointed to from this file; both mechanisms help control crawler behavior
- **Search engine indexing / SEO** — sitemaps support discoverability but are one part of a broader indexing and optimization strategy
- **Web crawlers** — sitemaps exist primarily to feed crawlers URLs they might not otherwise discover
- **Web design** — planning-phase sitemaps are a design tool distinct from the published sitemap
- **JavaScript / dynamic pages** — sitemaps solve the problem of content hidden behind dynamic URL construction or forms

## Exam-Relevant Points

- The XML Sitemap protocol is jointly supported by Google, Bing, Yahoo, and Ask
- The standard filename is `sitemap.xml` and it is referenced from `robots.txt`
- Google ignores `<priority>` and `<changefreq>` — do not rely on these for crawl behavior
- `<lastmod>` is only used by Google if verifiably accurate
- Sitemaps do **not** guarantee crawling or indexing
- Sitemaps are critical for pages only reachable via forms, site search, or JavaScript-generated URLs
- The XML namespace for sitemaps is `http://www.sitemaps.org/schemas/sitemap/0.9`
