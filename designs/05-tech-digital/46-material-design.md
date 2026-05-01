# Design 46: Material Design

**Category:** Tech & Digital  
**Style Tags:** Material, Google, systematic, accessible, elevation, Android  
**Difficulty:** Beginner  
**Best For:** Google Workspace presentations, Android developer talks, Material Design system showcases, UX/UI design process documentation, and any Google-ecosystem product presentation. Ideal for Google teams, Android developers, and Material Design practitioners.

---

## Visual Direction

Google Material Design system — bold headline colors on white surfaces, card-based components with subtle elevation shadows, floating action button aesthetics, motion-implied design elements, system iconography, and the structured clarity of Google's design language. The design communicates systematic accessibility and thoughtful interaction design.

## Background & Texture

Clean white (#FFFFFF) surface with very subtle elevation shadows distinguishing surface layers (1dp, 2dp, 4dp, 8dp equivalents). No decorative texture. The white surface represents the Material surface layer — content sits on paper, paper sits on backgrounds.

## Typography

Roboto exclusively (or Google Sans for newer Material You context). Type scales follow Material specification: Display Large (57sp), Headline Medium (28sp), Title Large (22sp), Body Large (16sp), Label Medium (12sp). Type in Material on-surface colors. No arbitrary type sizes — all from the defined scale.

## Color Palette

- **Primary:** Material Blue (#1565C0 or dynamic primary) — key elements, FABs, emphasis
- **Secondary:** Material background white (#FFFBFE — Material You white, slightly warm)
- **Accent 1:** Material secondary (#7B1FA2 or dynamic secondary) — secondary actions
- **Accent 2:** Material tertiary (#00695C or dynamic) — tertiary emphasis
- **Neutral:** On-surface (#1C1B1F) — body text in Material spec

## Layout & Composition

Material 8dp baseline grid — all spacing in multiples of 8 (8, 16, 24, 32, 48, 64dp). 12-column responsive grid with 16dp margins. Cards with 4dp corner radius and elevation shadows (4dp or 8dp). Navigation rail on the left for multi-section slides. FAB-style button element in lower right. Section dividers using surface variant color zones.

## Graphic Elements & Decorations

Material Design icon set (material-symbols or material-icons) — consistent 24dp with rounded style. Card components with appropriate elevation (1–6 elevation levels). Filled/tonal/outlined button styles. Chip components for labels and filters. Progress indicators (linear and circular). Navigation bar/rail element. Snackbar/toast notifications as content callouts.

## Slide Types & Templates

- **Title Slide:** Large Display scale headline in primary color on white, Material component showcase (cards, FAB, navigation rail) as a product hero illustration.
- **Content Slide:** Navigation rail left, three-card feature grid in center, each card with Material icon, bold label, and body description at correct type scale.
- **Process/Flow Slide:** Linear progress indicator at top, each stage as a Material step indicator component, connected by the progress line.
- **Data/Chart Slide:** Material-styled charts (clean lines, primary/secondary color series), card wrapper with 4dp elevation, data label chips in tonal style.
- **Closing Slide:** Dynamic color gradient background (Material You M3 style), white headline and CTA button in outlined style.

## Tone & Mood

Systematic, accessible, and Google-quality. The tone communicates that every decision here was made for a reason derivable from the design system specifications. There is functional trustworthiness in the consistent application of the system. Audiences that know Material feel at home; audiences that don't feel organized and cared for.

## Avoid

- Non-system fonts (Roboto or Google Sans only)
- Shadow elevations outside the Material specification
- Custom colors that don't follow Material color roles
- Non-standard spacing (must be multiples of 8dp)
- Decorative elements outside the Material component library
- Mixing Material versions (M2 and M3 have different visual languages)

## Example Prompt

> Design a presentation slide in Google Material Design 3 (Material You) style. Use a clean white surface background (#FFFBFE), Roboto typography at the correct Material type scale (Display for headline, Body for content), a three-card grid with 4dp corner radius and subtle 4dp elevation shadows, Material primary blue as the key accent color on card icons and the headline, Material Design icon set (rounded, 24dp) in each card, 8dp baseline grid spacing throughout, a floating action button element in the lower right, and a navigation rail on the left. The feel should be systematically clean, Google-native, and accessibly designed — Material Design applied rigorously to presentation format.
