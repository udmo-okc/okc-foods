# OKC Guide

A local's guide to Oklahoma City, organized by neighborhood. Built for visitors and residents who want to know where to actually go.

**Live:** [udmo-okc.github.io/okc-guide](https://udmo-okc.github.io/okc-guide)

---

158 spots across 15 districts — restaurants, bars, coffee, shops, and activities. Includes a Must Visit designation, directions to every spot via Apple Maps, and live search.

The Mexican and Latin section covers authentic spots citywide, separate from the neighborhood districts.

---

## Editing spots

Open `data.json` and find the district. Each spot follows this format:

```json
{ "name": "Spot Name", "category": "restaurant", "status": "open", "hours": "9AM–9PM", "must": true, "note": "Your note here." }
```

Categories: `mexican` · `restaurant` · `bar_drinks` · `coffee` · `shop` · `seafood` · `bakery` · `activity`

Statuses: `open` · `closed-today` · `temp-closed` · `opening-soon` · `perm-closed`

Set `"must": true` to mark a spot with the Must Visit indicator. Save the file and the site updates within 60 seconds on GitHub Pages.

---

## License

The code in this repository is released under the MIT License — copy it, fork it, build your own city guide.

The guide content (spot selections, district curation, and written notes) is original work by the author and is not covered by the MIT License. If you use the content as a reference, credit the source.

© 2025 udmo-okc
