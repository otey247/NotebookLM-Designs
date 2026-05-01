# Design 50: Data Dashboard UI

**Category:** Tech & Digital  
**Style Tags:** dashboard, data-visualization, KPI, analytics, operational, monitoring  
**Difficulty:** Intermediate  
**Best For:** Business performance reviews, analytics and BI presentations, operational briefings, product metrics showcases, and any context where a large volume of data needs to be communicated efficiently. Ideal for data analysts, product managers, and business intelligence teams.

---

## Visual Direction

Tableau, Looker, Grafana, and Datadog dashboard aesthetics brought into presentation format — KPI metric cards, sparklines showing trends, donut charts for proportion, heat maps for two-dimensional data, real-time indicator badges, and the operational visual language of data monitoring platforms.

## Background & Texture

Dark mode option: deep charcoal (#1A1A2E or #1E1E2E) for a Grafana/Datadog operational feel. Light mode option: clean white (#FFFFFF) for a Tableau/Looker business intelligence feel. No decorative texture — data dashboards are purely functional surfaces.

## Typography

Clean, highly legible sans-serif — Inter, Roboto, or DM Sans. Numbers in a monospace or tabular-numeral typeface for aligned metric readouts. Very clear scale hierarchy: large KPI numbers (40–60pt), medium chart labels (12pt), small metadata (10pt). Bold for key values, light for context labels.

## Color Palette

**Dark Mode:**
- **Primary:** Deep dark (#1A1A2E) — background
- **Secondary:** Surface dark (#252542) — card backgrounds
- **Accent 1:** Data blue (#4F9CF9) — primary data series
- **Accent 2:** Data green (#50FA7B) — positive/healthy metrics
- **Alert:** Data amber (#FFB86C) — warning states

**Light Mode:**
- **Primary:** Clean white (#FFFFFF) — primary surface
- **Secondary:** Light gray (#F8F9FA) — card backgrounds
- **Data Blue:** (#2563EB), **Data Green:** (#059669), **Data Amber:** (#D97706)

## Layout & Composition

Grid of metric tiles and visualization cards. Top row: 4–6 KPI metric cards (large number, trend sparkline, change percentage, status indicator). Middle zone: 2–3 primary visualization panels (larger charts). Bottom zone: data table or secondary metric grid. Cards have consistent padding and a subtle border or background differentiation.

## Graphic Elements & Decorations

KPI metric cards with: large bold number, small unit label, trend sparkline (tiny 24-point line chart), percentage change (green/red with arrow), period label. Chart types: line charts with area fills, bar charts with labeled axes, donut charts with center label, heat maps with color-encoded cells. Status badges (green dot, amber dot, red dot) for operational state. Time range selector labels.

## Slide Types & Templates

- **Title Slide:** Dashboard header bar with title, date range, refresh timestamp, filter chips (department, region, period) in pill style.
- **Content Slide:** 4-KPI tile row at top, two chart panels below (line chart left, donut right), time range and filter labels in header.
- **Process/Flow Slide:** Funnel chart or pipeline conversion visualization with stage labels and conversion rates, trend arrows on each stage.
- **Data/Chart Slide:** Single large primary chart taking 70% of slide, KPI summary cards in a column beside it, period selector at top.
- **Closing Slide:** Summary KPI dashboard — all key metrics for the period in a condensed grid, RAG status summary, period-over-period comparison.

## Tone & Mood

Operational, data-transparent, and accountability-supporting. The tone communicates: we have visibility into what's happening, we track what matters, and we make decisions based on evidence. There is a specific confidence that comes from data fluency — the organization can see and therefore can manage.

## Avoid

- Decorative elements without data function
- Non-standard chart types that obscure rather than reveal data
- Multiple font families
- Inconsistent color coding (green always means positive, red always means negative)
- Removing data labels or axes that provide necessary context
- Chartjunk (unnecessary visual elements inside chart areas)

## Example Prompt

> Design a presentation slide as a data dashboard. Use a dark mode deep charcoal background (#1A1A2E) with slightly lighter card surfaces (#252542), a top row of four KPI metric cards each showing a large bold number in data blue, a tiny sparkline trend, a percentage change with green/red color and arrow indicator, and a period label. Below: a primary line chart with area fill in data blue showing a trend over 12 months (full width), and a donut chart showing category breakdown with a central total metric. Include filter chips at the top (Department: All | Region: All | Period: Q4 2024). The feel should be operational, data-transparent, and monitoring-grade — Grafana/Tableau aesthetics in presentation format.
