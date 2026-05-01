# Design 84: Geographic & Cartographic Data

**Category:** Data & Visualization  
**Style Tags:** map, cartography, geographic, choropleth, spatial, GIS  
**Difficulty:** Intermediate  
**Best For:** Regional analysis, demographic data presentations, supply chain geography, market penetration mapping, environmental data presentations, and any content where the geographic distribution of data carries the primary analytical insight. Ideal for geographic analysts, business intelligence teams, and policy researchers.

---

## Visual Direction

Mapbox studio aesthetics, Census Bureau statistical map standards, ESRI ArcGIS cartographic conventions — choropleth maps, graduated symbol maps, flow maps with proportional arrows, and the specific visual vocabulary of professional cartographic data presentation. Geography IS the insight.

## Background & Texture

Map background in the style used: dark Mapbox-style (#1A1A2E with land in #252540) for modern data visualization, or neutral light (#F5F0E8 land with #C8D8E8 water) for traditional print cartography. The map projection and base layer are first-class design decisions.

## Typography

Clean geographic sans-serif following cartographic conventions: Helvetica, Gill Sans, or Noto Sans for label hierarchy. Country/state names in different weights than city names. Water body names in italic. The cartographic label hierarchy (continent > country > state > city > neighborhood) must be visible through type scale and weight.

## Color Palette

**For Choropleth (sequential):**
- Light to dark single hue: from very light tint (low value) to full saturation (high value)

**For Categorical:**
- Distinct hues that are perceptually separable: ColorBrewer qualitative palettes

**Standard accent:**
- **Highlight:** Vivid orange (#E87722) — selected region, focus area
- **Reference:** Dark navy (#1A2A4A) — borders, labels
- **Water:** Blue (#C8D8E8 light mode or #0A1A2E dark mode)

## Layout & Composition

Map occupying 60–70% of the slide. Legend positioned in the lower-left or lower-right corner with adequate explanation of color encoding. Inset map showing the full area context when a zoomed view is shown. Scale bar and north arrow when precision is needed. Title, subtitle, and data source below or alongside the map.

## Graphic Elements & Decorations

Choropleth color fills with appropriate classification (quantile, natural breaks, equal interval). Graduated circles scaled by data value for point data. Flow arrows with width proportional to flow volume. Cartographic border lines by administrative level weight (country heavier than state, state heavier than county). Inset map at smaller scale for context. Scale bar. North arrow. Legend with appropriate data range labels.

## Slide Types & Templates

- **Title Slide:** Full map view of the study area, presentation title as a cartouche overlay, data year in the corner.
- **Content Slide:** Choropleth map at 65%, supporting ranked bar chart at 35% listing the geographic entities by their values, linking to the visual.
- **Process/Flow Slide:** Sequential maps showing temporal change — same area at four time points as small multiples, showing the pattern's evolution.
- **Data/Chart Slide:** Bivariate choropleth showing two variables simultaneously, or a flow map with graduated arrows, detailed legend.
- **Closing Slide:** Full map view with selected geographic insights annotated with callout labels pointing to significant areas.

## Tone & Mood

Spatially analytical, evidence-grounded, and geographically precise. The tone communicates: where things happen matters. The geographic distribution of data reveals patterns that aggregate statistics cannot. Audiences understand the spatial dimension of a problem for the first time.

## Avoid

- Maps without legends or data sources
- Color scales that distort perception (never use rainbow/jet color scales)
- Removing geographic context that helps orientation
- Projection choices that distort the phenomenon being mapped
- Missing scale bars when geographic scale is analytically important
- Cartographic elements used decoratively without data encoding

## Example Prompt

> Design a presentation slide as a geographic and cartographic data visualization. Use a clean map of the continental United States in a light mode (tan land, blue-gray water, dark navy state borders), with a sequential choropleth color fill from pale to deep blue showing a data variable by state (darker = higher value), a legend in the lower-left with 5 value range labels, a graduated circle overlay showing a second variable as circles sized by value at state capitals, a scale bar in the lower-right, the map title above, data source in small type below the legend, and a highlight circle on three states of analytical significance with callout labels. The feel should be spatially analytical, cartographically precise, and geographically insightful.
