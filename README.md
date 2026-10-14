# FIT3179 DV2 — Dog Breeds

Working first-pass build for **What Makes Australia’s Top Dog?**

## Run locally
Do not open `index.html` directly with `file://`. Use a local web server, e.g. VS Code Live Server, or run:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Visualisations
1. Proportional-symbol world map — breed origins
2. Radial chord-style connection diagram — origin regions ↔ FCI groups
3. Australia choropleth — Dogs Australia members per 100,000 residents
4. Pictorial unit grid — Australian household pet penetration
5. Dorling-style state cartogram — membership size + change
6. Treemap — 2025 registrations by Dogs Australia breed group
7. Bump chart — rank among 10 selected breeds, 2000–2025
8. Slopegraph — selected breed registrations, 2000 vs 2025
9. Heatmap — temperament/behaviour traits
10. Parallel coordinates — breed physical/health profiles
11. Lollipop — exercise-need score
12. Scatterplot — weight vs lifespan

## Important before submission
- Replace the prototype Australian state boundary file with the preferred ABS boundary source if your tutor requires official spatial geometry.
- Review wording/annotations after inspecting final rendered charts.
- Add the exact AI acknowledgement wording required by the unit.
- Confirm source URLs/attribution in the final page.
