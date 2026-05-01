# Design 48: Neumorphism / Soft UI

**Category:** Tech & Digital  
**Style Tags:** neumorphism, soft-UI, extruded, monochromatic, tactile-digital, calm  
**Difficulty:** Advanced  
**Best For:** Product concept presentations, UX design process showcases, digital product design reviews, and presentations about interaction design philosophy. Ideal for UX designers, product teams, and design system presentations.

---

## Visual Direction

Soft UI / Neumorphism — the design trend of digitally extruded surfaces where elements appear to push out from or sink into the background through dual-shadow manipulation. A light source from the upper-left casts a bright shadow in the lower-right and a dark shadow in the upper-left, creating a three-dimensional illusion from a flat digital surface.

## Background & Texture

A single mid-tone background color — the key technical requirement of neumorphism. The background must be the precise mid-tone between the two shadow colors. Warm gray (#E0E5EC), dusty blue (#D6E0F0), or soft taupe (#E8E0D4) are the classic neumorphic base colors. Very subtle noise texture at the lowest opacity reinforces the soft material feel.

## Typography

Clean geometric or humanist sans-serif in medium weight. Typography remains modest and secondary — the design is about the surfaces, not the type. Colors derived from the neumorphic palette: slightly darker than the background for readable labels, slightly lighter for ghost/inactive states. No high-contrast black type on neumorphic backgrounds — that breaks the soft illusion.

## Color Palette

- **Primary:** Background base (#E0E5EC — soft blue-gray) — the defining surface
- **Secondary:** Light shadow (#FFFFFF or near-white — upper-left highlight shadow)
- **Accent 1:** Dark shadow (#A3B1C6 — lower-right depth shadow for pressed elements)
- **Accent 2:** Single color for CTAs only — vivid but used minimally (#0082C8 for blue accent)
- **Neutral:** Text gray (#6D7D8B) — readable on the neumorphic base without full contrast

## Layout & Composition

Clean, spacious layout with generous padding within all neumorphic components. Elements either extruded (raised from surface — convex) or inset (pressed into surface — concave). Extruded for informational elements (cards, panels). Concave for input states (active, pressed). The composition is monochromatic and calm — no competing color zones. Alignment is precise and generous.

## Graphic Elements & Decorations

Neumorphic card components (dual shadow: white upper-left, gray lower-right). Neumorphic button elements (same dual shadow, reduced on press state). Toggle switch components in neumorphic style. Circular progress indicators with soft shadow edges. Icon surfaces as raised circular or rectangular neumorphic pads. Input field inset elements. Slider thumb as raised circular element.

## Slide Types & Templates

- **Title Slide:** Large neumorphic panel centered on base background, presentation title in medium-weight sans-serif at readable contrast, small raised circular badge for category label.
- **Content Slide:** Three-column neumorphic card grid, each card raised from the surface, icon on raised circular pad, label and description below.
- **Process/Flow Slide:** Sequential neumorphic numbered circles along a subtle concave track, each circle raised with shadow, numbers in mid-contrast.
- **Data/Chart Slide:** Neumorphic bar chart — bars as raised rectangular extrusions from the base surface, data labels in base-tone text.
- **Closing Slide:** Single large raised neumorphic card with CTA button in pressed/inset state showing interaction.

## Tone & Mood

Calm, tactile, and contemplatively modern. The tone communicates thoughtful attention to the physical quality of digital interaction — an acknowledgment that humans respond to tactile metaphors even in purely digital contexts. Audiences feel a surprising physical quality in the digitally rendered surfaces.

## Avoid

- High-contrast backgrounds (neumorphism requires a specific mid-tone base)
- Multiple colors (neumorphism is almost always monochromatic)
- Hard shadows or drop shadows
- Textures that don't match the soft surface metaphor
- Bright colors on neumorphic surfaces (the soft palette is essential)
- Accessibility violations (neumorphism can have contrast issues — check WCAG compliance)

## Example Prompt

> Design a presentation slide in neumorphism / Soft UI style. Use a soft blue-gray base background (#E0E5EC) with very subtle noise texture, neumorphic card components using the dual-shadow system (white upper-left highlight shadow, dark blue-gray lower-right depth shadow), raised circular icon pads with the same dual shadow treatment, clean geometric sans-serif typography in mid-gray for readable labels, a three-card grid of raised neumorphic information panels, a concave inset track for a process sequence with raised numbered circle elements along it, and generous padding throughout. The feel should be calm, tactile, and softly three-dimensional — digitally extruded surfaces that invite touch.
