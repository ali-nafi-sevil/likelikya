# likelikya

A slow, hand-built guide to Lycia — the southwest coast of Turkey. The
ancient cities, the Lycian Way, the modern towns, and the ecology of the
coast and mountains.

**Live site:** https://ali-nafi-sevil.github.io/likelikya/

## What's here

- `index.html` — home
- `explore.html` — index of all ancient cities, with a schematic map
- `lycian-way.html` — the trail
- `ecology.html` — maquis, posidonia, monk seal, loggerheads
- `modern.html` — modern towns, food, activities, seasons
- `about.html` — about the project
- `cities/` — individual city pages. `antiphellos.html` is the showpiece
  (Kaş); the others are lighter scaffolds ready to expand.

## How it's built

Plain static HTML + CSS + a tiny bit of vanilla JavaScript. No build step,
no framework, no dependencies beyond Google Fonts (Cormorant Garamond + Inter).

## Run locally

```bash
python3 -m http.server 8765
# then open http://localhost:8765
```
