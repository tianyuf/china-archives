# china-archives

Open archive catalogs published by Chinese municipal archives, packaged as offline-searchable single-page apps with the raw CSV alongside.

## Catalogs

| Archive | Catalog | Records | Link |
|---|---|---|---|
| Nanchang City Archives (南昌市档案馆) | Open archive catalog · through 2000 | 89,879 | [`nanchang/`](nanchang/) |

## About

- Each catalog is a self-contained HTML file with the data embedded — **search, filter, and sort with no network connection**.
  - Keyword search across title / creator / archive number / fond (space-separated terms are OR-matched).
  - Filter by fond and by year range.
  - Click a column header to sort (click again to reverse).
- Each catalog also ships its raw CSV (e.g. `nanchang/nanchang_archives_full.csv`) for further analysis.

## Local usage

The pages are plain static files. Serve them with any static file server:

```bash
python3 -m http.server 8000
# then open http://localhost:8000/nanchang/
```

Or just open the HTML file directly in a browser.

## Sources & license

- Data: publicly published open archive catalogs.
- The catalogs are hosted on GitHub Pages at <https://tianyuf.github.io/china-archives/>.
