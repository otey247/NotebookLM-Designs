# Design 42: Terminal & Command Line

**Category:** Tech & Digital  
**Style Tags:** terminal, CLI, command-line, hacker, phosphor, ASCII  
**Difficulty:** Intermediate  
**Best For:** DevOps presentations, infrastructure and security talks, sysadmin training, command-line tool documentation, and any deep technical presentation where the CLI is the primary working environment. Ideal for infrastructure engineers, security professionals, and Unix-culture audiences.

---

## Visual Direction

Pure terminal/CLI aesthetic — the green or amber phosphor text of a CRT terminal display on black, cursor blinking, command prompt formatting, ASCII art headers, man-page style documentation layout, and the deep technical culture of Unix and hacker communities. This aesthetic communicates: we work at the deepest level of the system.

## Background & Texture

Pure black (#000000) or near-black (#0A0A0A) — the terminal screen. Subtle CRT scanline texture at very low opacity for authentic period feel (optional, for maximum effect). Phosphor glow effect on green or amber text — the slight halo of a cathode ray tube display.

## Typography

Monospace exclusively: Courier New, Terminus, or a terminal-specific bitmap font like Perfect DOS VGA. Text rendered in the phosphor color (green #00FF00 or amber #FFB300) on pure black. No size variation — all text at one terminal font size, with structural differentiation through indentation, bold weight, and color only. ASCII box-drawing characters (┌─┐│└─┘) for framing.

## Color Palette

- **Primary:** Pure black (#000000) — terminal screen background
- **Secondary:** Phosphor green (#00FF00) — classic terminal text color (or amber variant)
- **Accent 1:** Bright white (#FFFFFF) — active prompt, selected text, critical output
- **Accent 2:** Cyan (#00FFFF) — man page formatting, hyperlinks, secondary emphasis
- **Neutral:** Dark green (#003300) — dim/inactive terminal text

## Layout & Composition

Terminal screen composition: every element is text within an 80-column (or 132-column wide mode) fixed-width grid. ASCII art banner at the top for the title. Command prompt lines ($ or #) for input elements. Output blocks for content information. Man page format for documentation sections (.TH, .SH, .PP formatting). ASCII table structures for data. Progress bar text animations for process flows.

## Graphic Elements & Decorations

ASCII art headers and dividers (═══════════════════════════). Command prompt symbols ($ for user, # for root, > for interactive prompts). Blinking cursor block (_) at end of active prompts. Scrollback history effect (ghost text above active content). ASCII box-drawing characters for framing content zones. Progress bar animations in ASCII (████████░░ 80%). Man-page header format.

## Slide Types & Templates

- **Title Slide:** ASCII art banner spelling the presentation title in box-drawing characters, system information block (OS, kernel version, user) styled as login greeting, $ prompt with title command beneath.
- **Content Slide:** Man page format — .TH header, .SH SYNOPSIS, .PP paragraphs, .B bold emphasis, indented .IP list items. All in terminal font on black.
- **Process/Flow Slide:** Pipeline commands showing data flow ($ cat data.txt | grep pattern | sort | uniq -c | sort -rn), each pipe stage as a step.
- **Data/Chart Slide:** ASCII bar chart (built from = or █ characters), numerical output in terminal table format with box-drawing borders.
- **Closing Slide:** $ exit command → "logout" response → "Connection to [host] closed" → cursor blink.

## Tone & Mood

Deeply technical, authentically Unix-culture, and unpretentiously expert. The tone communicates that the presenter works at the command line, understands what's happening beneath abstraction layers, and respects the audience enough to speak their language. Audiences from technical communities feel genuine kinship.

## Avoid

- Any graphical elements beyond ASCII
- Color beyond the defined phosphor + accent palette
- Typography other than monospace
- Variable-width layout
- Non-technical aesthetic references
- Anything that couldn't appear on an actual terminal display

## Example Prompt

> Design a presentation slide in pure terminal and command line aesthetic. Use a pure black background, phosphor green (#00FF00) monospace text (Courier New or terminal bitmap font), an ASCII art banner at the top using box-drawing characters, command prompt lines ($ and #) for interactive elements, man page style content formatting (.TH, .SH, .PP), ASCII box-drawing borders around content sections, a blinking cursor at the end of the active prompt, and ASCII progress bar characters (████████░░) for a process visualization. Subtle CRT scanline texture at very low opacity. The feel should be deeply technical, authentically Unix-culture, and purely textual — terminal aesthetics as presentation design.
