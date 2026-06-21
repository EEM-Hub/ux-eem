---
source: https://en.wikipedia.org/wiki/Site_map
fetched: 2026-06-20
---

List of pages of a web site 

A **site map** or **sitemap** is a list of [pages](./Web_page) of a [web site](./Web_site) within a [domain](./Domain_name).

 

There are three primary kinds of sitemap:

 
- Sitemaps used during the planning of a website by its [designers](./Web_design)
- Human-visible listings, typically hierarchical, of the pages on a site
- Structured listings intended for [web crawlers](./Web_crawler) such as [search engines](./Web_search_engine)

 

## Types

 [![](//upload.wikimedia.org/wikipedia/commons/thumb/8/83/Main_Page_Usability.png/500px-Main_Page_Usability.png)](./File:Main_Page_Usability.png)A sitemap of what links from the [English Wikipedia](./English_Wikipedia)'s Main Page [![](//upload.wikimedia.org/wikipedia/commons/thumb/2/20/Sitemap_google.jpg/500px-Sitemap_google.jpg)](./File:Sitemap_google.jpg)Sitemap of Google in 2006 

Sitemaps may be addressed to users or to software.

 

Many sites have user-visible sitemaps which present a systematic view, typically hierarchical, of the site. These are intended to help visitors find specific pages, and can also be used by crawlers. They also act as a navigation aid[[1]](./Site_map#cite_note-1) by providing an overview of a site's content at a single glance.
Alphabetically organized sitemaps, sometimes called site indexes, are a different approach.

 

For use by search engines and other crawlers, there is a structured format, the [XML](./XML) Sitemap, which lists the pages in a site, their relative importance, and how often they are updated.[[2]](./Site_map#cite_note-2) This is pointed to from the [robots.txt file](./Robots_exclusion_standard) and is typically called **sitemap.xml**. The structured format is particularly important for websites which include pages that are not accessible through [links](./Hyperlink) from other pages, but only through the site's search tools or by dynamic construction of [URLs](./URL) in [JavaScript](./JavaScript).

 

## XML sitemaps

 Main article: [Sitemaps](./Sitemaps) 

[Google](./Google) introduced the [Sitemap protocol](./Sitemaps), so web developers can publish lists of links from across their sites. The basic premise is that some sites have a large number of dynamic pages that are only available through the use of forms and user entries. The Sitemap files contain URLs to these pages so that [web crawlers](./Web_crawlers) can find them. [Bing](./Bing.com), Google, [Yahoo](./Yahoo) and [Ask](./Ask.com) now jointly support the Sitemaps protocol.

 

Since the major [search engines](./Search_engine) use the same protocol,[[3]](./Site_map#cite_note-Oreilly-3) having a Sitemap lets them have the updated page information. Sitemaps do not guarantee all links will be crawled, and being crawled does not guarantee indexing.[[4]](./Site_map#cite_note-4) Google Webmaster Tools allow a website owner to upload a sitemap that Google will crawl, or they can accomplish the same thing with the robots.txt file.[[5]](./Site_map#cite_note-Google-5)

 

### Sample

 

Below is an example of a validated XML sitemap for a simple three-page website. Sitemaps are a useful tool for making sites searchable, particularly those written in non-HTML languages.

 
```
<?xml version="1.0" encoding="UTF-8"?>
<urlset xmlns="http://www.sitemaps.org/schemas/sitemap/0.9">
  <url>
    <loc>http://www.example.net/?id=who</loc>
    <lastmod>2009-09-22</lastmod>
  </url>
  <url>
    <loc>http://www.example.net/?id=what</loc>
    <lastmod>2009-09-22</lastmod>
  </url>
  <url>
    <loc>http://www.example.net/?id=how</loc>
    <lastmod>2009-09-22</lastmod>
  </url>
</urlset>

```
 

**Notes:**

 
- As with all XML files, all tag values must be entity escaped.
- Google ignores the `<priority>` and `<changefreq>` values.[[6]](./Site_map#cite_note-GoogleSitemaps-6)
- Google may use the `<lastmod>` value if it is consistently and verifiably accurate (for example, matching the actual last modification date of the page).[[6]](./Site_map#cite_note-GoogleSitemaps-6)

 

## See also

  
- [Biositemap](./Biositemap), a protocol for broadcasting and disseminating information about [computational biology](./Computational_biology) resources (data, software tools and web-services)
- [Contact page](./Contact_page)
- [Home page](./Home_page)
- [Search engine indexing](./Search_engine_indexing)
- [Link page](./Link_page)
- [Search engine optimization](./Search_engine_optimization)
- [Web indexing](./Web_indexing)

  

## References

  
1. [↑](./Site_map#cite_ref-1) [Sitemap Usability](http://www.nngroup.com/articles/site-map-usability/) Jakob Nielsen's Alertbox, August 12, 2008
2. [↑](./Site_map#cite_ref-2) Nadik, Tessa (2023-02-09). ["What Is A Sitemap? Do I Need One?"](https://www.searchenginejournal.com/what-is-a-sitemap/478071/). *Search Engine Journal*. Retrieved 2023-09-16.
3. [↑](./Site_map#cite_ref-Oreilly_3-0) ["Google, Yahoo!, Microsoft Standardize Against Google Sitemap Protocol"](http://www.oreillynet.com/xml/blog/2006/11/google_yahoo_microsoft_standar.html). [Oreilly](./Oreilly). Retrieved 2012-07-24.
4. [↑](./Site_map#cite_ref-4) [Joint announcement](http://www.google.com/press/pressrel/sitemapsorg.html) from Google, Yahoo, and Bing supporting Sitemaps
5. [↑](./Site_map#cite_ref-Google_5-0) ["Submitting Sitemaps"](https://support.google.com/webmasters/bin/answer.py?hl=en&answer=183669&topic=8476&ctx=topic). Google Inc. Retrieved 2012-07-06.
6. [1](./Site_map#cite_ref-GoogleSitemaps_6-0) [2](./Site_map#cite_ref-GoogleSitemaps_6-1) ["Build and submit a sitemap"](https://developers.google.com/search/docs/crawling-indexing/sitemaps/build-sitemap#xml). *Google Search Central*. Google. Retrieved 31 October 2025.

 

## External links

 
- [Common Official Website](http://www.sitemaps.org/) - Jointly maintained website by Google, Yahoo, MSN for an XML sitemap format.

 [Portal](./Wikipedia:Contents/Portals):
- [![icon](//upload.wikimedia.org/wikipedia/commons/thumb/f/f9/Crystal_Clear_app_linneighborhood.svg/20px-Crystal_Clear_app_linneighborhood.svg.png)](./File:Crystal_Clear_app_linneighborhood.svg) [Internet](./Portal:Internet)