# OKC Food & Culture Guide

A local's guide to Oklahoma City — every neighborhood, every vibe. Built for visitors and locals who want to know where to actually go.

**Live site:** [udmo-okc.github.io/okc-guide](https://udmo-okc.github.io/okc-guide)

---

## What's inside

16 districts covering 100+ spots across OKC — restaurants, bars, coffee, shops, and activities. Includes a curated Must Visit list, category filters, and live search.

Mexican and Latin spots are broken out into their own dedicated section.

---

## How to add, edit, or remove a spot

Open `data.json` and find the district you want. Each spot follows this format:

```json
{ "name": "Spot Name", "category": "mexican", "status": "open", "hours": "9AM–9PM", "must": true, "note": "Your note here." }
```

**Categories:** `mexican` · `restaurant` · `bar_drinks` · `coffee` · `shop` · `seafood` · `bakery` · `activity`

**Statuses:** `open` · `closed-today` · `temp-closed` · `opening-soon` · `perm-closed`

Set `"must": true` to feature a spot in the Must Visit section at the top.

Save the file and the site updates within 60 seconds.

---

## Stack

Plain HTML, CSS, and JavaScript — no frameworks, no build step. Data lives in a single `data.json` file. Hosted on GitHub Pages.
