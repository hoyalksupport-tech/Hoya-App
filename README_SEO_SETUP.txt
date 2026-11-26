HOYA SEO SETUP — GITHUB PAGES

UPLOAD THESE FILES TO THE ROOT OF YOUR Hoya-App REPOSITORY:
- index.html
- robots.txt
- sitemap.xml
- hoya-logo.png
- hoya-social-preview.png

The updated index.html includes:
- Sinhala/English-focused title and meta description
- Canonical URL and index/follow instructions
- Open Graph and Twitter sharing metadata
- WebSite structured data
- Crawlable business profile links using ?business=BUSINESS_ID
- Dynamic business title, description, canonical URL and LocalBusiness structured data

AFTER UPLOADING
1. Wait for GitHub Pages to publish.
2. Open the live website and check it.
3. Open Google Search Console: https://search.google.com/search-console/
4. Add a URL-prefix property:
   https://hoyalksupport-tech.github.io/Hoya-App/
5. Verify ownership using one of Google's offered methods.
6. In Search Console > Sitemaps, submit: sitemap.xml
7. Use URL Inspection on the homepage and request indexing.

SEO NOTES
- The sitemap initially lists the homepage only. A future automated sitemap should list every approved and active business.
- Business profile links now have their own query URLs. The page updates SEO metadata after Firebase data loads. This is still a JavaScript single-page app; server-rendered or pre-rendered business pages are more reliable for search indexing and social previews.
- The current site uses a GitHub Pages URL. A custom domain later improves branding and memorability but does not guarantee higher Google rankings.
- Publish only real, approved, active businesses. Do not present demo listings as genuine businesses.
- Each business should have a unique, accurate description, category, district, town, phone, address, opening hours and route/timetable details where relevant.
- Avoid keyword stuffing, fake reviews and copied descriptions.
- SEO indexing and rankings take time and are not guaranteed.
