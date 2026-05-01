# Design 85: Scientific Data Visualization

**Category:** Data & Visualization  
**Style Tags:** scientific, matplotlib, R-ggplot2, academic-charts, peer-review, Nature  
**Difficulty:** Advanced  
**Best For:** Scientific paper figure preparation, lab meeting presentations, conference scientific talks, academic peer review materials, and any data visualization where publication-quality standards and analytical precision are required. Ideal for researchers, data scientists, and academic presenters.

---

## Visual Direction

Nature, Science, and Cell journal figure aesthetics — the publication-quality standard for scientific data visualization. Clean axes, consistent font sizes (8–10pt for labels, 12pt for panel labels), appropriate statistical annotations (significance brackets, error bars, effect sizes), multi-panel figures with panel labels (A, B, C, D), and the conservative elegance of peer-reviewed science communication.

## Background & Texture

Pure white (#FFFFFF) — scientific publication figures use white backgrounds universally. No decorative elements. Every pixel serves the data.

## Typography

Clean, light-weight sans-serif at small sizes — Helvetica, Arial, or Myriad Pro at 8–12pt. Panel labels (A, B, C, D) in bold 12pt. Axis labels in 10pt. Tick labels in 8pt. Statistical significance notation in standard format (*, **, ***, ns, exact p-value). Figure caption in 8pt serif below the figure.

## Color Palette

- **Primary:** Pure white (#FFFFFF) — figure background
- **Secondary:** Black (#000000) — axes, borders, primary text
- **Accent 1:** Nature blue (#4472C4) — primary data series color
- **Accent 2:** Nature orange (#ED7D31) — secondary data series
- **Neutral:** Nature gray (#7F7F7F) — tertiary series, reference data, error bars

## Layout & Composition

Multi-panel figure layout: four panels (A, B, C, D) or six panels in a 2×3 grid. Each panel labeled in bold in the upper-left corner. Panels aligned on a shared baseline grid. Consistent axis scale ranges for comparable panels. Statistical significance brackets with notation above relevant bar pairs. Error bars (SEM, SD, or 95% CI — labeled in the figure legend).

## Graphic Elements & Decorations

Significance brackets with standard annotation (* p<0.05, ** p<0.01, *** p<0.001, ns p>0.05). Error bars on bar charts and scatter plots. Trend lines with equation and R² value. Box plots with median line, IQR box, whiskers, and outlier points. Heatmap with color bar legend. Survival curves with event table. Statistical test label (Two-tailed t-test, ANOVA, Wilcoxon, etc.).

## Slide Types & Templates

- **Title Slide:** Paper title, authors, affiliations, journal name, date — academic paper title page format.
- **Content Slide:** Main multi-panel figure with panel labels, all axes labeled, statistical annotations, figure caption below.
- **Process/Flow Slide:** Experimental design schematic — treatment conditions, controls, randomization, measurement timepoints as a scientific workflow diagram.
- **Data/Chart Slide:** Single panel at large scale — scatter plot, survival curve, or box plot — with full statistical annotation, n sizes, p-values.
- **Closing Slide:** Summary figure — the key finding from each paper section in one condensed multi-panel figure.

## Tone & Mood

Statistically honest, methodologically transparent, and analytically precise. The tone communicates: every data point is real, every statistic is correctly calculated, every uncertainty is represented. Scientific integrity is the highest value. Audiences of scientific peers feel they can trust the analysis.

## Avoid

- 3D chart effects that distort data perception
- Pie charts (scientific visualization rarely uses them)
- Color choices that create perceptual bias (avoid rainbow scales, use perceptually uniform palettes)
- Missing error bars or uncertainty representation
- Imprecise or missing statistical annotations
- Font sizes too small to read when projected

## Example Prompt

> Design a presentation slide as a scientific data visualization in publication-quality style. Use a pure white background, a four-panel figure layout with panels labeled A, B, C, D in bold 12pt in the upper-left of each panel, panel A showing a scatter plot with trend line (R²=0.82, p<0.001 annotated), panel B showing a grouped bar chart with SEM error bars and significance brackets (* p<0.05, ns), panel C showing a violin plot with individual data points overlaid, panel D showing a heatmap with color bar legend. All axis labels in 10pt Helvetica, tick labels in 8pt, a detailed figure caption below in 8pt. The feel should be publication-grade, statistically honest, and peer-review ready.
