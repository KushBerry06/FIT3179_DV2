# FIT3179 DV2 | What Makes Australia’s Top Dog?

Final cleaned project package for the FIT3179 Data Visualisation 2 submission.

Created by **Kush Berry**, Monash University, Semester 2 2026. Published 22 October 2026.

## Run locally
Do not open `index.html` directly with `file://`. Start a local web server from this folder:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Final visualisation order
1. Pet ownership waffle chart
2. State pedigree-membership choropleth
3. State pedigree-membership change chart
4. World breed-origin proportional-symbol map
5. Selected-breed origin flow map
6. Region to FCI breed-group chord diagram
7. National pedigree-registration trend
8. 2025 breed-group treemap
9. Selected-breed popularity bump chart
10. Selected-breed registration slopegraph
11. Breed temperament heatmap
12. Breed-profile parallel coordinates
13. Weight versus lifespan scatterplot

## Folder structure
- `index.html` | page content and Vega embeds
- `css/main.css` | page styling
- `js/` | the 13 Vega / Vega-Lite specifications in story order
- `data/` | only datasets used by the final visualisations, plus `sources.csv`

## External dependencies
The page loads Vega, Vega-Lite and Vega-Embed from jsDelivr. Map geometry is loaded from stable external sources referenced in the relevant specifications. An internet connection is therefore required when viewing the page.

## Source documentation
See `data/sources.csv` and the Sources & Notes section at the bottom of `index.html`. The metadata includes URLs, access dates, licence/use notes and the charts supplied by each source.
