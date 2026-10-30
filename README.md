# Digital Skills DV2 — Version 21 (HD-focused repair)

Replace **index.html**, the complete **charts/** folder and **data/** folder in GitHub Pages. Keep directory names unchanged.

## Changes
- Chart 7: selected state's 2011 and 2021 figures and change shown beneath the chart.
- Chart 9: less crowded Australian symbol map, clear dual legends and tooltips.
- Chart 10: repaired failure behaviour: attempt state-boundary choropleth; if external GeoJSON fails, show a local position-based state map instead of a broken graphic. The actual choropleth source still requires network access.
- Chart 6: improved high-score cell text contrast.
- Charts 2–5: refined chart titles to distinguish progress, gaps and other social factors.
- Charts 8 and 11: clear signed gap and exclusion descriptions.

## Verification and limitations
- JSON syntax and local paths checked. Do an actual browser visual test of all charts and legends before submission.
- The fallback map keeps a visual and data display, but **is not a state choropleth**. A complete offline GeoJSON boundary file is needed to guarantee the third requested map idiom without network access.
- These charts draw on existing supplied data files and do not invent additional survey years.
- No grade can be guaranteed.
