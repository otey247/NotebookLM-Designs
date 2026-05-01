# Design 41: Dark Mode Developer

**Category:** Tech & Digital  
**Style Tags:** dark-mode, developer, VS-Code, GitHub, code-aesthetic, technical  
**Difficulty:** Beginner  
**Best For:** Engineering team presentations, API documentation showcases, technical architecture briefings, developer-facing product demos, and coding bootcamp curriculum. Ideal for software engineers, DevRel professionals, and technical educators.

---

## Visual Direction

VS Code dark theme, GitHub dark mode, and technical documentation aesthetics applied to presentation design. The design communicates to developers in their native visual language — the environment they spend most of their working hours in. Dark backgrounds, syntax-highlighted code blocks, monospace type, and file path typography signal authentic technical credibility.

## Background & Texture

Deep charcoal (#1E1E1E — VS Code default) or GitHub dark (#0D1117) as the primary background. Slightly lighter surface zones (#252526 equivalent) for content panels and code blocks. No decorative texture — the pure dark surface is the digital native environment.

## Typography

Primary: monospace for all code elements (Fira Code, JetBrains Mono, or Cascadia Code — with ligature support for operators). Secondary: Inter or Source Sans for non-code headings and body text. Fixed terminal-style prompt characters ($ / >) before command-line elements. File path typography (src/components/Button.tsx) as breadcrumb navigation.

## Color Palette

- **Primary:** VS Code background (#1E1E1E) — slide background
- **Secondary:** Syntax blue (#58A6FF) — keywords, links, important terms
- **Accent 1:** Syntax green (#3FB950) — strings, success states, positive metrics
- **Accent 2:** Syntax red (#F85149) — errors, warnings, negative states
- **Neutral:** Text white (#E6EDF3) — primary text on dark backgrounds

## Layout & Composition

Split-panel layout reflecting the IDE metaphor: file tree on left (narrow panel), main editor/content zone in the center (dominant), optional terminal panel at the bottom. Tab bar metaphor at the top — slide "files" as open tabs. Status bar element at the very bottom (language, line count, git branch). Code blocks are first-class content elements, not secondary.

## Graphic Elements & Decorations

Syntax-highlighted code blocks with line numbers in a slightly lighter background. Editor tab bar at the top with "open files" as slide titles. Status bar at the bottom with language identifier and line count. Minimap preview on the right edge. Git diff indicators (green + / red -) in code margins. Terminal panel with $ prompt and command output. Inline type annotations in a muted gray.

## Slide Types & Templates

- **Title Slide:** Dark background, "file" tab bar at top, presentation title as the currently-open file, subtitle as file path (/presentations/quarterly-review/index.md), language identifier in status bar.
- **Content Slide:** Primary content zone with key points, syntax-highlighted code block for any technical examples, terminal output panel at the bottom showing example command.
- **Process/Flow Slide:** Step sequence styled as a pipeline or CI/CD stages — each stage as a terminal command block with output, arrows connecting stages.
- **Data/Chart Slide:** Metrics displayed in the IDE aesthetic — light-on-dark charts, terminal-style table output (ascii table borders), log-format timestamps.
- **Closing Slide:** Terminal prompt closing sequence ("$ exit", "Connection closed."), git commit message style final thought, EOF marker.

## Tone & Mood

Developer-native, technically precise, and refreshingly unpretentious. The tone communicates: this presentation is for engineers, by engineers, and doesn't waste time on decorative formality. There is professional competence expressed through authentic technical aesthetic rather than corporate polish.

## Avoid

- Light or white backgrounds
- Corporate sans-serif typography without monospace
- Gradient backgrounds
- Stock photography
- Non-technical iconography
- Anything that resembles a standard business presentation

## Example Prompt

> Design a presentation slide in VS Code dark mode developer style. Use the VS Code dark background (#1E1E1E), a file tab bar at the top showing the slide title as an open file, a primary content zone with key technical information, a syntax-highlighted code block with line numbers (blue keywords, green strings, gray comments on a slightly darker background panel), a terminal panel at the bottom with $ prompt and sample command output, git diff indicators in the code margins, and a status bar at the bottom with language identifier. Use Fira Code for all code elements and Inter for headings. The feel should be developer-native, technically precise, and authentically IDE-aesthetic.
