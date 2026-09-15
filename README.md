# jpdferreira.com v3

## Structure

- `/index.html` — homepage
- `/thinking/index.html` — article index
- `/thinking/valley-of-death/index.html` — revisited 2014 article
- `/thinking/entrepreneurial-culture/index.html` — revisited 2015 article
- `/assets/images/profile.jpg` — add your portrait here
- `/assets/images/articles/` — optional future article images
- `/robots.txt`
- `/sitemap.xml`

## Photo

Add a portrait named exactly:

`assets/images/profile.jpg`

Recommended:
- portrait orientation, 4:5
- at least 1000 × 1250 px
- simple background
- visually consistent with your LinkedIn profile photo

Until that file exists, the site shows a clean JP fallback.

## Thinking

The homepage now shows three featured pieces:
1. The Valley of Death: From Technology to Operating Reality
2. Why Entrepreneurial Cultures Die as Companies Scale
3. AI Won't Fix a Broken Operating Model (currently links to LinkedIn)

The first two are local article pages. The third can later be migrated to the website.

## Future article pattern

For clean URLs, use:

`thinking/article-slug/index.html`

Then add the URL to:
- `thinking/index.html`
- the homepage if it is featured
- `sitemap.xml`

## Before publishing

1. Confirm public email: `j.p.d.ferreira@gmail.com`
2. Add `assets/images/profile.jpg`
3. Replace current GitHub site files with this structure
4. Test all navigation after deployment
