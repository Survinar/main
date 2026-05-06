---
name: Technical Refinement
colors:
  surface: '#10141a'
  surface-dim: '#10141a'
  surface-bright: '#353940'
  surface-container-lowest: '#0a0e14'
  surface-container-low: '#181c22'
  surface-container: '#1c2026'
  surface-container-high: '#262a31'
  surface-container-highest: '#31353c'
  on-surface: '#dfe2eb'
  on-surface-variant: '#c1c6d6'
  inverse-surface: '#dfe2eb'
  inverse-on-surface: '#2d3137'
  outline: '#8b909f'
  outline-variant: '#414754'
  surface-tint: '#acc7ff'
  primary: '#acc7ff'
  on-primary: '#002f68'
  primary-container: '#498fff'
  on-primary-container: '#00285b'
  inverse-primary: '#005bbf'
  secondary: '#bfc7d3'
  on-secondary: '#29313a'
  secondary-container: '#424a54'
  on-secondary-container: '#b1b9c5'
  tertiary: '#c1c7d0'
  on-tertiary: '#2b3138'
  tertiary-container: '#8b9199'
  on-tertiary-container: '#242a31'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#d7e2ff'
  primary-fixed-dim: '#acc7ff'
  on-primary-fixed: '#001a40'
  on-primary-fixed-variant: '#004492'
  secondary-fixed: '#dbe3ef'
  secondary-fixed-dim: '#bfc7d3'
  on-secondary-fixed: '#141c25'
  on-secondary-fixed-variant: '#404751'
  tertiary-fixed: '#dde3ec'
  tertiary-fixed-dim: '#c1c7d0'
  on-tertiary-fixed: '#161c23'
  on-tertiary-fixed-variant: '#41474f'
  background: '#10141a'
  on-background: '#dfe2eb'
  surface-variant: '#31353c'
typography:
  headline-xl:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.25'
    letterSpacing: -0.01em
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: '0'
  code-sm:
    fontFamily: Space Grotesk
    fontSize: 14px
    fontWeight: '400'
    lineHeight: '1.5'
    letterSpacing: '0'
  label-caps:
    fontFamily: Space Grotesk
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.05em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 8px
  container-max: 1200px
  gutter: 24px
  section-gap: 80px
  element-gap: 16px
---

## Brand & Style

The brand personality is authoritative yet understated, designed to signal technical competence and attention to detail. It targets a developer-centric audience that values performance, clarity, and the "raw" beauty of well-structured code. 

The design style is **Modern Minimalist with a Technical Edge**. It draws from the utility of GitHub’s interface but elevates it through increased whitespace, more sophisticated typographic hierarchies, and a restrained use of depth. The UI should evoke a sense of a high-end IDE—organized, responsive, and distraction-free—where the content (the code and the projects) is the hero.

## Colors

The palette is rooted in a deep, nocturnal spectrum to minimize eye strain and mirror the developer's natural environment. 

- **Primary (Link Blue):** A vibrant, high-contrast blue reserved for interactive elements, call-to-actions, and git-style contributions.
- **Secondary (Muted Slate):** Used for metadata, secondary labels, and supporting text to create a clear hierarchy.
- **Tertiary (Border & Surface):** A mid-tone gray for subtle UI boundaries and container backgrounds.
- **Neutral (Deep Slate/Black):** The canvas color, providing a solid, professional foundation.
- **Accents:** Success (Green: #238636) and Warning (Orange: #D29922) should be used sparingly for status indicators.

## Typography

Typography is used to distinguish between "human" narrative and "machine" data. 

**Inter** handles all primary interface text, ensuring maximum readability across varying screen densities. Use tighter letter-spacing for large headlines to maintain a modern, "tucked" look.

**Space Grotesk** is utilized for technical details, labels, and code snippets. While a geometric sans-serif, its technical construction provides the "mono" aesthetic required for developer tools while maintaining better legibility for prose-heavy technical descriptions than a standard monospaced font.

## Layout & Spacing

This design system utilizes a **Fixed Grid** model for desktop to ensure the portfolio feels like a curated document rather than a sprawling dashboard. 

- **Grid:** 12-column system with a 24px gutter.
- **Rhythm:** An 8px linear scale guides all spatial decisions. 
- **Margins:** Large vertical gaps (80px+) between sections (e.g., Intro, Projects, Contributions) are essential to provide visual breathing room and emphasize the quality of each individual entry. 
- **Alignment:** All technical labels and code blocks should align strictly to the left edge of their respective columns to reinforce a structured, "indented" code feel.

## Elevation & Depth

Depth is achieved through **Low-contrast outlines** and **Tonal layers** rather than heavy shadows. This maintains the clean, flat aesthetic preferred by technical audiences.

- **Level 0 (Background):** #0D1117.
- **Level 1 (Cards/Containers):** #161B22 with a 1px border (#30363D).
- **Level 2 (Hover states/Modals):** Slight elevation change using a subtle ambient shadow (0px 8px 24px rgba(0,0,0,0.4)) and a brighter border (#484F58).
- **Inlays:** Code blocks should appear "recessed" using a darker background (#010409) and a 1px solid border.

## Shapes

The shape language is **Soft (0.25rem)**. This slight rounding takes the edge off the "brutalist" nature of code while maintaining a professional, rigid structure. 

- **Primary Elements:** Buttons and Input fields use a 6px (0.375rem) radius.
- **Containers:** Project cards and code blocks use an 8px (0.5rem) radius.
- **Badges:** Language tags and status chips use a fully rounded (pill) shape to provide a visual contrast against the rectangular grid of the rest of the UI.

## Components

### Buttons
- **Primary:** Solid Blue background (#2F81F7), white text, 6px radius. Subtle scale-down effect on click.
- **Secondary:** Ghost style with a #30363D border and #C9D1D9 text. On hover, the background shifts to #21262D.

### Cards (Projects)
- Feature a 1px border and a subtle internal padding (24px).
- Include a "Header" area for the repo name (Bold Inter) and a "Footer" area for language stats and star counts.

### Chips (Language Tags)
- Small, pill-shaped elements with a subtle background tint related to the language (e.g., yellow for JS, blue for TS) at 15% opacity with a matching 1px border.

### Code Blocks
- Syntax highlighting should follow the GitHub Dark Dimmed theme.
- Must include a "Copy" button in the top-right corner that only appears on hover.
- Use Space Grotesk for the content.

### Inputs
- Background: #0D1117; Border: #30363D. Focus state should trigger a 1px Blue border and a soft blue outer glow (0px 0px 0px 3px rgba(47, 129, 247, 0.3)).

### Timeline / Contribution Graph
- A vertical "Git-log" style line for experience sections, using #30363D for the line and Primary Blue for the nodes.