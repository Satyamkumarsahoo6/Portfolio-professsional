---
name: Technical Precision
colors:
  surface: '#0f131c'
  surface-dim: '#0f131c'
  surface-bright: '#353942'
  surface-container-lowest: '#0a0e16'
  surface-container-low: '#181c24'
  surface-container: '#1c2028'
  surface-container-high: '#262a33'
  surface-container-highest: '#31353e'
  on-surface: '#dfe2ee'
  on-surface-variant: '#c2c6d7'
  inverse-surface: '#dfe2ee'
  inverse-on-surface: '#2c3039'
  outline: '#8c90a0'
  outline-variant: '#424654'
  surface-tint: '#b0c6ff'
  primary: '#b0c6ff'
  on-primary: '#002c6f'
  primary-container: '#256fee'
  on-primary-container: '#fffeff'
  inverse-primary: '#0058cc'
  secondary: '#a4c9ff'
  on-secondary: '#00315d'
  secondary-container: '#0267b8'
  on-secondary-container: '#d6e5ff'
  tertiary: '#adc6ff'
  on-tertiary: '#002e6a'
  tertiary-container: '#2372e5'
  on-tertiary-container: '#fffeff'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#d9e2ff'
  primary-fixed-dim: '#b0c6ff'
  on-primary-fixed: '#001945'
  on-primary-fixed-variant: '#00419c'
  secondary-fixed: '#d4e3ff'
  secondary-fixed-dim: '#a4c9ff'
  on-secondary-fixed: '#001c39'
  on-secondary-fixed-variant: '#004883'
  tertiary-fixed: '#d8e2ff'
  tertiary-fixed-dim: '#adc6ff'
  on-tertiary-fixed: '#001a42'
  on-tertiary-fixed-variant: '#004395'
  background: '#0f131c'
  on-background: '#dfe2ee'
  surface-variant: '#31353e'
typography:
  headline-hero:
    fontFamily: Plus Jakarta Sans
    fontSize: 56px
    fontWeight: '800'
    lineHeight: 64px
    letterSpacing: -0.03em
  headline-hero-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '800'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.025em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
    letterSpacing: -0.015em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
    letterSpacing: -0.005em
  body-md:
    fontFamily: Inter
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
  code-base:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
  label-code:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.04em
  label-ui:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.01em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  space-2xs: 0.25rem
  space-xs: 0.5rem
  space-sm: 0.75rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
  space-2xl: 3rem
  space-3xl: 4.5rem
  space-4xl: 6rem
  container-max: 72rem
  gutter-mobile: 1rem
  gutter-desktop: 1.5rem
---

## Brand & Style

This design system establishes a high-performance, developer-centric digital portfolio aesthetic. It bridges software engineering discipline with academic depth across artificial intelligence, machine learning, and data science. The visual architecture is deliberate, analytical, and uncluttered.

### Personality & Tone
- **Analytical & Precise:** Content relies on structured hierarchy, accurate spacing, and monospaced indicators to signal rigour and algorithmic focus.
- **Modern Technical Minimalist:** Blends deep terminal-inspired canvas tones with razor-thin structural borders and luminous electric blue accents. Avoids gratuitous ornamental flourishes in favor of high-legibility telemetry and card-driven data architecture.
- **Credible & Forward-Looking:** Designed to convey technical authority to engineering hiring managers, technical leads, and academic researchers.

### Visual Expression
The interface implements a refined hybrid of **technical minimalism** and **dark-mode glass structuralism**. Depth is defined by layered charcoal surfaces, ultra-subtle borders, and controlled blue emissive highlights, retaining the immediacy of code editors and analytical dashboards.

## Colors

The palette uses a calibrated dark-mode hierarchy designed to optimize contrast, minimize visual fatigue, and direct focus through calibrated luminance steps.

### Palette Roles
- **Base Canvas (`#0B0F17`):** The foundational substrate for all viewport backgrounds.
- **Surface Elevation (`#111827`, `#1E293B`):** Container surfaces and structural panels that step upward in brightness to establish spatial depth.
- **Electric Accents (`#256FEE`, `#3B82F6`, `#60A5FA`):** Used strictly for interactive states, key focal points, live code badges, and metric callouts.
- **Content Hierarchy:**
  - **High-Emphasis Text (`#F8FAFC`):** Display titles, primary metrics, active labels.
  - **Medium-Emphasis Text (`#94A3B8`):** Body paragraphs, system descriptions, technical specifications.
  - **Subtle / Muted Text (`#64748B`):** Metadata, line counts, auxiliary timestamps.
- **Structural Outlines (`rgba(51, 65, 85, 0.4)` to `rgba(51, 65, 85, 0.7)`):** Ultra-refined borders that outline cards and modules without heavy visual weight.

## Typography

The typographic hierarchy implements three distinct typefaces serving dedicated functional roles:

1. **Display & Structural Headings (Plus Jakarta Sans):** Modern geometric grotesk with humanist details that softens technical hardness while maintaining clean, authoritative weight.
2. **Reading & Interface Copy (Inter):** Highly legible, neutral workhorse engine optimized for multi-screen readability, documentation, and technical descriptions.
3. **Code, Telemetry, and Badges (JetBrains Mono):** Monospaced type providing structural rhythm for code snippets, tech stack indicators, parameters, and metadata tags.

## Layout & Spacing

The layout is built on a mobile-first, 12-column responsive fluid grid capped at a maximum width of `72rem` (1152px) to guarantee optimal line length and visual density.

### Breakpoint Strategy
- **Mobile (`< 640px`):** 4 columns, `1rem` outer margins, `1rem` gutters. Elements stack vertically; secondary stats and metadata wrap or reflow below headings.
- **Tablet (`640px - 1023px`):** 8 columns, `1.5rem` outer margins, `1.25rem` gutters. Cards switch to two-column distribution.
- **Desktop (`>= 1024px`):** 12 columns, `1.5rem` margins auto-centered, `1.5rem` gutters. Complex layouts (e.g., project previews, dual-column code/architecture breakdowns) take full shape.

### Spacing Cadence
Spacing follows a strict base-4 / base-8 rhythmic progression. Structural layout vertical gaps utilize `space-3xl` and `space-4xl`, while intra-card component rhythm defaults strictly to `space-xs` through `space-lg`.

## Elevation & Depth

This design system eschews heavy drop shadows in favor of a layered **tonal elevation and luminous border** paradigm suited for dark-mode technical interfaces.

### Surface Tiers
- **Surface 0 (Base):** `#0B0F17` (Deep solid canvas).
- **Surface 1 (Panels & Structural Groups):** `#111827` overlaid with a 1px continuous border of `rgba(51, 65, 85, 0.4)`.
- **Surface 2 (Interactive Cards & Drawers):** `rgba(30, 41, 59, 0.7)` with `backdrop-filter: blur(12px)` and a 1px border of `rgba(51, 65, 85, 0.6)`.
- **Surface 3 (Popovers, Tooltips & Floating Nav):** `rgba(17, 24, 39, 0.9)` with `backdrop-filter: blur(16px)` and a perimeter border of `rgba(96, 165, 250, 0.3)`.

### Accent Lighting & Glows
Depth accents utilize subtle radial glow projections rather than standard cast shadows:
- **Interactive Card Hover:** 1px border transition to `rgba(59, 130, 246, 0.6)` paired with an ambient soft blue backlight (`box-shadow: 0 0 24px -4px rgba(37, 111, 238, 0.15)`).
- **Active Focus Ring:** A clean, unblurred `0 0 0 2px #256FEE` ring offset from the element by `2px` of canvas color.

## Shapes

The design system adopts a **soft structural** shape language (`roundedness: 1`). This approach strikes a balance between sharp engineering precision and modern ergonomics.

### Corner Radii Guidelines
- **Micro UI & Indicators (Badges, Buttons, Inputs):** `0.375rem` (6px) to `0.5rem` (8px) for crisp control definitions.
- **Tech Stack Badges:** Pill-shaped (`rounded-full` / `9999px`) to create clear visual differentiation between content containers and categoric labels.
- **Structural Cards & Panels:** `0.75rem` (12px) to maintain a contained silhouette that mirrors code editor tab frames.
- **Inner Nested Media / Previews:** `0.375rem` (6px) ensuring inner items respect the outer card geometry proportionally.

## Components

### Buttons
- **Primary Action:** Solid `#256FEE` fill, `#F8FAFC` label (`label-ui`), `0.375rem` radius. On hover: shifts to `#3B82F6` with an inner subtle top edge highlight (`inset 0 1px 0 rgba(255, 255, 255, 0.15)`).
- **Secondary / Outline Action:** Transparent background, 1px border of `rgba(51, 65, 85, 0.7)`, `#94A3B8` label. On hover: border promotes to `#60A5FA`, label turns `#F8FAFC`, background tints to `rgba(37, 111, 238, 0.08)`.
- **Icon Utility Button:** Square aspect ratio (36x36px or 40x40px), Surface 1 fill with subtle border, centering monochromatic SVG icons.

### Tech Stack Chips & Pill Badges
- **Display:** Pill shape (`9999px` radius), inline-flex alignment, horizontal padding `0.625rem`, vertical padding `0.25rem`.
- **Visuals:** Background `rgba(30, 41, 59, 0.5)`, border 1px solid `rgba(51, 65, 85, 0.4)`. Text in `JetBrains Mono` (`label-code`) rendered at `#60A5FA` or `#94A3B8`. Optional 6px pulsing dot indicator for live/production models.

### Project & Technical Cards
- **Architecture:** Surface 1 or Surface 2 background with 1px `rgba(51, 65, 85, 0.4)` border and `0.75rem` radius.
- **Header:** Project title (`headline-sm`) accompanied by live deployment and source repository action icons.
- **Body:** Brief problem-solution breakdown (`body-md`), followed by a nested tech stack pill matrix.
- **Hover Micro-Interaction:** Subtle upward translate (-2px), outline shifts to `rgba(59, 130, 246, 0.5)`, and faint blue ambient bloom activates.

### Inputs & Terminal Search
- **Form Controls:** Surface 1 fill, 1px border `rgba(51, 65, 85, 0.6)`, text `#F8FAFC`, placeholder `#64748B`. Font set to `Inter` for standard inputs, or `JetBrains Mono` for command/search fields. Focus triggers `#256FEE` ring without default browser outline.

### Code Snippets & Architecture Blocks
- **Block Container:** Monospaced viewport utilizing `#080C14` background, 1px border `rgba(51, 65, 85, 0.3)`, header bar indicating file name and execution timing, accompanied by syntax highlighting calibrated to dark navy surfaces.