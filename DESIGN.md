---
name: Technical Precision Portfolio
colors:
  surface: '#0b1326'
  surface-dim: '#0b1326'
  surface-bright: '#31394d'
  surface-container-lowest: '#060e20'
  surface-container-low: '#131b2e'
  surface-container: '#171f33'
  surface-container-high: '#222a3d'
  surface-container-highest: '#2d3449'
  on-surface: '#dae2fd'
  on-surface-variant: '#c7c4d7'
  inverse-surface: '#dae2fd'
  inverse-on-surface: '#283044'
  outline: '#908fa0'
  outline-variant: '#464554'
  surface-tint: '#c0c1ff'
  primary: '#c0c1ff'
  on-primary: '#1000a9'
  primary-container: '#8083ff'
  on-primary-container: '#0d0096'
  inverse-primary: '#494bd6'
  secondary: '#4cd7f6'
  on-secondary: '#003640'
  secondary-container: '#03b5d3'
  on-secondary-container: '#00424e'
  tertiary: '#ddb7ff'
  on-tertiary: '#490080'
  tertiary-container: '#b76dff'
  on-tertiary-container: '#400071'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e1e0ff'
  primary-fixed-dim: '#c0c1ff'
  on-primary-fixed: '#07006c'
  on-primary-fixed-variant: '#2f2ebe'
  secondary-fixed: '#acedff'
  secondary-fixed-dim: '#4cd7f6'
  on-secondary-fixed: '#001f26'
  on-secondary-fixed-variant: '#004e5c'
  tertiary-fixed: '#f0dbff'
  tertiary-fixed-dim: '#ddb7ff'
  on-tertiary-fixed: '#2c0051'
  on-tertiary-fixed-variant: '#6900b3'
  background: '#0b1326'
  on-background: '#dae2fd'
  surface-variant: '#2d3449'
typography:
  display-hero:
    fontFamily: Space Grotesk
    fontSize: 56px
    fontWeight: '600'
    lineHeight: 64px
    letterSpacing: -0.03em
  display-hero-mobile:
    fontFamily: Space Grotesk
    fontSize: 36px
    fontWeight: '600'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Space Grotesk
    fontSize: 32px
    fontWeight: '500'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Space Grotesk
    fontSize: 26px
    fontWeight: '500'
    lineHeight: 34px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Space Grotesk
    fontSize: 22px
    fontWeight: '500'
    lineHeight: 28px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Space Grotesk
    fontSize: 18px
    fontWeight: '500'
    lineHeight: 24px
  body-lg:
    fontFamily: Geist
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
  body-md:
    fontFamily: Geist
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
  body-sm:
    fontFamily: Geist
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 18px
  code-md:
    fontFamily: JetBrains Mono
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
  label-mono:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.04em
  label-caps:
    fontFamily: JetBrains Mono
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.08em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 3rem
  margin-tablet: 2rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
  space-2xl: 4rem
  space-3xl: 6rem
---

## Brand & Style

This design system expresses a disciplined, highly technical student portfolio combining modern architectural minimalism with developer-grade utilitarianism. The aesthetic projects exceptional competence, forward-looking engineering rigor, and refined taste.

The interface prioritizes extreme clarity, balanced negative space, and typographic authority over gratuitous ornamentation. Drawing from modern technical minimalism, the visual tone balances quiet slate-gray surfaces, sharp mechanical text metrics, and calculated accents of electric indigo and cyan. The system communicates high intellectual horsepower, meticulous attention to detail, and a deliberate absence of visual clutter.

## Colors

The palette is engineered around deep slate neutrals that eliminate eye fatigue while framing technical artifacts with gallery-level contrast:

- **Primary (`#6366f1` - Indigo):** Reserved for focal points, interactive commits, primary CTAs, and active project states.
- **Secondary (`#06b6d4` - Cyan):** Used for technical metadata, live status indicators, system telemetries, and code highlights.
- **Tertiary (`#a855f7` - Violet):** Applied sparingly for specialized tags, academic distinctions, and research badges.
- **Neutral (`#0f172a` - Slate Canvas):** Root background surface, layered upwards through slate-900 (`#0f172a`), slate-850 (`#151f38`), and slate-800 (`#1e293b`) for surface separation.
- **Border & Dividers:** High-precision, low-opacity slate strokes (`rgba(148, 163, 184, 0.12)` to `rgba(148, 163, 184, 0.2)`).

## Typography

The type system blends structural geometric display forms with clinical monospaced data structures:

- **Space Grotesk (Headlines):** Delivers geometric confidence with subtle technical anomalies on key characters (`Q`, `g`, numerals), anchoring major section headers and hero statements.
- **Geist (Body & Documentation):** Provides high-density legibility, razor-sharp rendering on retina displays, and clean neutral tone for biographical text, project briefs, and case study documentation.
- **JetBrains Mono (Metadata, Badges & Labels):** Deployed for all operational data, date ranges, tech stacks, repository stats, file sizes, and status tags to anchor the design system in developer culture.

## Layout & Spacing

The layout is built upon a 12-column responsive fluid grid pinned within a strict max-width container of `1200px` to maintain optimal viewing geometry on widescreen monitors.

- **Desktop (1024px+):** 12 columns, 24px gutters, generous 48px canvas margins. Project grids default to 2 or 3 asymmetric columns.
- **Tablet (768px - 1023px):** 8 columns, 24px gutters, 32px canvas margins.
- **Mobile (<768px):** 4 columns, 16px gutters, 20px canvas margins. Technical cards collapse to a single column flow.

Vertical cadence relies on deliberate rhythm: components group tightly with `space-sm` and `space-md`, while thematic sections deploy dramatic `space-2xl` and `space-3xl` gaps to instill modern architectural breathing room.

## Elevation & Depth

Depth is established strictly through tonal surface layering and razor-thin borders, rather than heavy, muddy drop shadows:

- **Base Layer:** `#0a0f1d` (Root document background).
- **Surface Level 1:** `#0f172a` (Primary containers, sidebar, global navigation).
- **Surface Level 2:** `#1e293b` (Nested cards, code blocks, terminal wrappers).
- **Surface Level 3:** `#334155` (Hover states, active selections, dropdown overlays).

**Borders & Outlines:**
Surfaces use a consistent 1px hairline border rendered in `rgba(148, 163, 184, 0.12)`. When hovered, interactive card borders transition smoothly to `rgba(99, 102, 241, 0.4)`.

**Understated Elevation:**
When an elevated state is necessary (e.g., command palettes, preview modals), use a restrained ambient glow:
`box-shadow: 0 0 0 1px rgba(148, 163, 184, 0.1), 0 20px 40px -15px rgba(0, 0, 0, 0.6)`.

## Shapes

The shape system adopts a soft, restrained corner radius (`0.25rem` / `4px` base) to evoke physical computer hardware, terminal windows, and integrated circuit layouts:

- **Base Radius (4px):** Standard inputs, small tags, tooltips, and action buttons.
- **Large Radius (8px / `rounded-lg`):** Project showcase cards, modal shells, and interactive code sandboxes.
- **Extra Large Radius (12px / `rounded-xl`):** Primary viewport wrappers or segmented dashboard controls.

Avoid pill-shaped or bubble forms to preserve the technical, instrument-grade personality.

## Components

### Buttons
- **Primary:** Background in primary indigo (`#6366f1`) with high-contrast white text (`Geist`, medium weight). 1px border matching the background. Subtle glow on hover.
- **Secondary / Outline:** Background in transparent slate, 1px border `rgba(148, 163, 184, 0.2)`, text in slate-200. On hover, background shifts to `rgba(255, 255, 255, 0.04)` and border to cyan (`#06b6d4`).
- **Ghost:** Borderless, monospace label with icon prefix/suffix. Uses secondary cyan or muted slate text.

### Chips & Badges
- Rendered exclusively with `JetBrains Mono` using `label-mono` or `label-caps`.
- Visual structure: Background `rgba(148, 163, 184, 0.06)`, 1px border `rgba(148, 163, 184, 0.16)`, padding `2px 8px`.
- Status indicators feature a 6px pulsing dot (e.g., `#10b981` for active services, `#06b6d4` for ongoing projects).

### Project & Experience Cards
- Encapsulated in surface level 1 (`#0f172a`) with a 1px border.
- Headers integrate metadata bars featuring git branch names, commit hashes, or timeline markers set in monospaced typography.
- Interactive cards feature a 150ms ease-out translateY transition (-2px) on hover, accompanied by border illumination.

### Form Inputs & Code Blocks
- **Input Fields:** Inset surface (`#0a0f1d`), border `rgba(148, 163, 184, 0.16)`, text slate-100. Focused states activate a 1px indigo outline with zero offset.
- **Code Terminal:** Header bar with window control dots, file path title in `JetBrains Mono`, syntax-highlighted code container, and a 1-click copy action button.

### Checkboxes & Radio Buttons
- 16px square (checkbox) or circle (radio), 1px stroke `rgba(148, 163, 184, 0.3)`. Checked state fills with `#6366f1` featuring a crisp, high-contrast white glyph.