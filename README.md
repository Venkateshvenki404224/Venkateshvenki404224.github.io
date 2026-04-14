# Personal portfolio

Single-file static HTML site hosted on GitHub Pages at
[venkateshvenki404224.github.io](https://venkateshvenki404224.github.io).

## Stack

- Plain HTML + inline CSS + vanilla JS (no build step)
- Inter + JetBrains Mono via Google Fonts
- Live GitHub stats via public REST API
- Brand logos via Simple Icons CDN and Brandfetch

## Files

| File | Purpose |
|---|---|
| `index.html` | The entire site — markup, styles, scripts |
| `robots.txt` | Crawler rules + sitemap reference |
| `sitemap.xml` | Section anchors for search indexing |
| `og-image.html` | Template to screenshot into `og-image.png` |
| `.nojekyll` | Skip Jekyll processing on Pages |

## Local preview

Any static server works:

```bash
python3 -m http.server 8000
# or
npx serve .
```

Then open `http://localhost:8000`.

## Deploy

Every push to `main` is served automatically by GitHub Pages — no CI config.
