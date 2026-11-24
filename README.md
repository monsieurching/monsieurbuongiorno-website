# Monsieur Buongiorno website

A static editorial home for Albert Ching. Netlify publishes the repository root automatically when `main` changes.

## Add a new article

Copy an existing article folder under `perfumes/` or `drinks/`, update its copy and metadata, link it from the relevant index and homepage, then add the URL to `sitemap.xml`. Netlify publishes pushes to `main` automatically.

## Add a seasonal perfume edit

1. Copy `perfumes/cold-season/index.html` to a new folder such as `perfumes/spring/index.html`.
2. Replace the title, meta description, canonical URL, article text, image, and BlogPosting structured data.
3. Link the new page from `perfumes/index.html` and the homepage `index.html`.
4. Add its URL to `sitemap.xml`, then commit and push to `main`.
5. If you use a ShopMy link, keep an affiliate disclosure near the recommendations and `rel="sponsored nofollow noopener"` on the link.

The newsletter currently links to the existing Substack.

Site analytics use the existing Maison Buongiorno PostHog project. Filter events by `site = monsieurbuongiorno.com` or host. Pageviews and ShopMy outbound clicks are recorded; local preview visits are excluded.
