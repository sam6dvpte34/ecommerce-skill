# Ecommerce Skill

150 Skills for ecommerce research, product data collection, price monitoring, and competitive intelligence.

Ecommerce platforms don't make data collection easy: product pages are JavaScript-rendered, prices hide behind login walls, and seller data spreads across dozens of marketplaces. These Skills give your agent a ready-made workflow for each platform and task — point it at a product URL, ASIN, or keyword and get structured results back.

These Skills use [BrowserAct](https://www.browseract.com/?co-from=ecommerce) as the browser runtime — so agents can log in, navigate, scroll, and capture network responses instead of getting blocked or rate-limited by plain HTTP requests.

## Popular workflows

| Workflow | Example outcome |
| --- | --- |
| Product research | Collect product details, specs, prices, review counts, and listing metadata from one or more marketplaces. |
| Price monitoring | Track prices, availability, discount history, and promotion activity across selected products or SKUs. |
| Competitor analysis | Compare assortment, pricing, seller ratings, review volume, and listing quality against competitors. |
| Supplier research | Find sellers, storefronts, suppliers, and brand pages with public contact and profile information. |
| Review analysis | Export reviews, ratings, reviewer details, timestamps, and helpful vote counts for sentiment or quality research. |
| Bestseller tracking | Collect ranking, category, and sales indicator data from bestseller, trending, and category pages. |

## Coverage

150 Skills across 20+ ecommerce platforms and marketplace types.

| Coverage group | Skills |
| --- | ---: |
| Cross-store ecommerce workflows | 20 |
| Amazon, eBay, Walmart, Etsy, Shopify, TikTok Shop | 46 |
| Google Shopping, Facebook Marketplace, Temu, Noon, AliExpress | 30 |
| Alibaba, 1688, Made-in-China, MercadoLibre, Lazada, Flipkart | 26 |
| Naver Shopping, Allegro, retail, reviews, food delivery, and digital marketplaces | 28 |

## Get started

1. Pick the Skill that matches your target platform and task.
2. Copy `skills/<skill-name>/` into your agent's Skill directory.
3. Ask your agent to run it, for example:

```text
Use the amazon-product-scraper Skill to collect product details and review counts for these ASINs and export a CSV.
```

## More example requests

```text
Use ebay-search-results-scraper to find listings matching these keywords and export price and seller data.

Use aliexpress-product-scraper to collect supplier product details, MOQ, and pricing for these URLs.

Use shopify-product-scraper to extract product listings, variants, and pricing from these store URLs.

Use temu-search-results-scraper to collect product listings and prices matching these search terms.
```

## Works with

Claude Code, OpenAI Codex, Cursor, Windsurf, OpenClaw, Hermes, and other local agents that support reusable Skill instructions.

## Notes

- Intended for public data or data you are authorized to access. Website availability, visible fields, login requirements, and result limits can change over time.
- Keep account details, cookies, browser IDs, proxies, keyword lists, and exported records outside shared Skill folders and public repositories.
