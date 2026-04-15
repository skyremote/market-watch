# Watchlist — URLs and keywords tracked weekly

## Competitor pages
Edit this table to match your market. Keep `slug` short — it's the filename in `snapshots/`.

| Slug | URL | What to watch |
|---|---|---|
| competitor-a-home | https://example-a.com/ | positioning, hero headline, CTA |
| competitor-a-pricing | https://example-a.com/pricing | tier changes, new add-ons |
| competitor-b-home | https://example-b.com/ | positioning, product lineup |
| competitor-b-blog | https://example-b.com/blog | launch posts, thought-leadership tempo |

## SERP keywords
Queries re-run weekly via the Google SERP API. Record the top-10 results.

| Keyword | Market | Notes |
|---|---|---|
| ai automation agency | US | broad market signal |
| claude code agent | global | our space |
| ai workflow automation | US | intent match with buyers |
| ai consultant for startups | US | ICP search term |

## Notes

- Add or remove rows here without touching `ROUTINE.md`.
- For pages behind a login, use a separate credentialed fetcher; don't paste tokens into this file.
- Slug convention: `{brand}-{page}`. Keep it stable — if you rename it, you break the diff chain.
