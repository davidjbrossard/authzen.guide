# authzen.guide

Source for [authzen.guide](https://authzen.guide/), a practical guide to the OpenID AuthZEN Authorization API.

Static site in `www/`, deployed with Cloudflare Pages (build output directory: `www`, no build command).

| File | Purpose |
|---|---|
| `www/index.html` | Overview, status, how it works, talks, FAQ |
| `www/api.html` | API reference with JSON examples (served at `/api`) |
| `www/implementations.html` | Directory of AuthZEN implementations |
| `www/compare.html` | AuthZEN vs XACML, OPA, Cedar, OpenFGA |
| `www/manifesto.html` | The Authorization Manifesto |
| `www/404.html` | Real 404 page (stops Pages from serving index.html for unknown URLs) |
| `www/robots.txt`, `www/sitemap.xml`, `www/llms.txt` | Crawler and AI-assistant discovery |
| `www/_headers` | `noindex` on `*.pages.dev`, long cache for `/assets/*` |

When editing content, bump the "Last updated" date, `dateModified` in the JSON-LD, and `lastmod` in `sitemap.xml`.
