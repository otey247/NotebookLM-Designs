# Design 89: Sankey & Flow Diagram

**Category:** Data & Visualization  
**Style Tags:** Sankey, flow, energy, financial-flow, conversion, system-dynamics  
**Difficulty:** Intermediate  
**Best For:** Energy flow analysis, financial resource allocation presentations, conversion funnel analysis, supply chain flow visualization, and any content where showing how a quantity flows and transforms through a system is the primary analytical task. Ideal for energy analysts, financial modelers, and systems analysts.

---

## Visual Direction

The Sankey diagram — named after Captain Matthew Henry Phineas Riall Sankey who used it for steam engine energy efficiency analysis — applied to any flow system. Flows represented as bands of width proportional to quantity, branching and merging, with losses and gains visible as narrowing and widening bands. The diagram shows not just where things go but how much is lost at each step.

## Background & Texture

Clean white (#FFFFFF) for most Sankey applications — the flow colors do the visual work. Occasionally deep charcoal for an energy system dark theme. No decorative background.

## Typography

Clean sans-serif at node label positions. Node labels in bold, positioned beside each source/sink node. Flow labels (quantities) positioned along the midpoint of bands for the largest flows. Small light type for minor flows. Unit notation clearly stated in the chart title.

## Color Palette

- **Primary:** Clean white (#FFFFFF) — background
- **Secondary:** Flow blue (#4472C4) — primary energy/resource flow
- **Accent 1:** Loss red (#CC2200) — waste, losses, inefficiency flows
- **Accent 2:** Useful green (#059669) — useful work, converted energy, productive flows
- **Neutral:** Neutral gray (#9CA3AF) — minor flows, classification flows

## Layout & Composition

Source nodes on the left, sink nodes on the right, intermediate transformation nodes in the middle. Vertical ordering of nodes reflects the quantity flowing through them (largest flows at the top or most prominent position). Bands connecting nodes are proportional in width to the quantity they represent. The total width of flows entering a node equals the total width leaving it (conservation). Labels clear and not overlapping the bands.

## Graphic Elements & Decorations

Rectangular node boxes with category labels. Proportional-width flow bands connecting nodes with smooth Bezier curves. Quantity labels on the largest bands. Percentage labels for conversion efficiency rates. Loss arrows dropping downward for dissipated energy/value. Total flow quantities at source and sink nodes. Category legend if color encoding carries information.

## Slide Types & Templates

- **Title Slide:** Simplified hero Sankey diagram showing the key system being analyzed, title above, unit definition below.
- **Content Slide:** Full Sankey diagram with all nodes and flows labeled, percentage efficiency at each conversion stage, total input at left, total useful output at right, losses highlighted.
- **Process/Flow Slide:** Funnel Sankey — starting population at left, sequential qualification stages in the middle, converted/lost populations at each node.
- **Data/Chart Slide:** Sankey with time comparison — current vs. projected state, showing how flows change with efficiency improvements.
- **Closing Slide:** Summary Sankey — simplified version showing only the key flows and the efficiency gap being targeted.

## Tone & Mood

Analytically transparent, system-aware, and efficiency-conscious. The tone communicates: we understand where everything goes, including the losses. The Sankey diagram is uniquely honest — it forces visibility of everything that's wasted or unaccounted for. Audiences see the full system at once.

## Avoid

- Non-proportional band widths (the proportionality IS the information)
- Too many small flows cluttering the main narrative
- Missing flow labels for the critical paths
- Color inconsistency between source and destination for the same material
- Breaking conservation (inputs must equal outputs at each node)
- Aesthetic flow shapes that distort the proportional relationships

## Example Prompt

> Design a presentation slide as a Sankey flow diagram for an energy efficiency system. Use a clean white background, five source nodes on the left (Primary Energy, Fuel, Electricity, Heat, Renewable), transformation nodes in the center representing conversion stages with smooth proportional-width Bezier flow bands connecting them, sink nodes on the right (Useful Work, Waste Heat, Transmission Loss, End Use), flow bands colored by flow type (green for useful flows, red for losses), quantity labels on the largest bands, percentage efficiency labels at each conversion node, node labels in clean bold sans-serif, and a total input/output balance label. The feel should be analytically transparent, system-complete, and loss-visible — Sankey diagram aesthetics making flow systems legible.
