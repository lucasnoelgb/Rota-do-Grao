---
name: Espresso Reserve Analytics
colors:
  surface: '#17120f'
  surface-dim: '#17120f'
  surface-bright: '#3f3834'
  surface-container-lowest: '#120d0a'
  surface-container-low: '#201a17'
  surface-container: '#241e1b'
  surface-container-high: '#2f2925'
  surface-container-highest: '#3a3330'
  on-surface: '#ece0da'
  on-surface-variant: '#dbc1b4'
  inverse-surface: '#ece0da'
  inverse-on-surface: '#362f2b'
  outline: '#a38c80'
  outline-variant: '#554339'
  surface-tint: '#ffb689'
  primary: '#ffb689'
  on-primary: '#512300'
  primary-container: '#d67836'
  on-primary-container: '#471e00'
  inverse-primary: '#974802'
  secondary: '#e1c19f'
  on-secondary: '#402d15'
  secondary-container: '#594329'
  on-secondary-container: '#ceb08f'
  tertiary: '#dbc3a6'
  on-tertiary: '#3d2e19'
  tertiary-container: '#a38d73'
  on-tertiary-container: '#352713'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffdbc8'
  primary-fixed-dim: '#ffb689'
  on-primary-fixed: '#321300'
  on-primary-fixed-variant: '#743500'
  secondary-fixed: '#feddba'
  secondary-fixed-dim: '#e1c19f'
  on-secondary-fixed: '#291803'
  on-secondary-fixed-variant: '#594329'
  tertiary-fixed: '#f8dfc0'
  tertiary-fixed-dim: '#dbc3a6'
  on-tertiary-fixed: '#261907'
  on-tertiary-fixed-variant: '#55442e'
  background: '#17120f'
  on-background: '#ece0da'
  surface-variant: '#3a3330'
typography:
  display-lg:
    fontFamily: Oswald
    fontSize: 56px
    fontWeight: '600'
    lineHeight: 64px
    letterSpacing: 0.02em
  display-lg-mobile:
    fontFamily: Oswald
    fontSize: 36px
    fontWeight: '600'
    lineHeight: 44px
    letterSpacing: 0.02em
  display-md:
    fontFamily: Oswald
    fontSize: 40px
    fontWeight: '500'
    lineHeight: 48px
    letterSpacing: 0.02em
  display-md-mobile:
    fontFamily: Oswald
    fontSize: 28px
    fontWeight: '500'
    lineHeight: 36px
    letterSpacing: 0.01em
  headline-lg:
    fontFamily: Oswald
    fontSize: 28px
    fontWeight: '500'
    lineHeight: 36px
    letterSpacing: 0.03em
  headline-sm:
    fontFamily: Oswald
    fontSize: 20px
    fontWeight: '500'
    lineHeight: 28px
    letterSpacing: 0.03em
  metric-numeral-lg:
    fontFamily: Oswald
    fontSize: 48px
    fontWeight: '600'
    lineHeight: 52px
    letterSpacing: 0.01em
  metric-numeral-sm:
    fontFamily: Oswald
    fontSize: 24px
    fontWeight: '500'
    lineHeight: 30px
    letterSpacing: 0.02em
  body-lg:
    fontFamily: Open Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
  body-md:
    fontFamily: Open Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
  body-sm:
    fontFamily: Open Sans
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
  data-table-cell:
    fontFamily: Open Sans
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 20px
  label-caps:
    fontFamily: Open Sans
    fontSize: 11px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.08em
  badge-label:
    fontFamily: Open Sans
    fontSize: 11px
    fontWeight: '700'
    lineHeight: 14px
    letterSpacing: 0.04em
rounded:
  sm: 0.5rem
  DEFAULT: 1rem
  md: 1.5rem
  lg: 2rem
  xl: 3rem
  full: 9999px
spacing:
  gutter: 1.25rem
  gutter-mobile: 0.75rem
  margin: 2rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style
The design system manifests an editorial marriage between third-wave artisanal coffee culture and institutional financial intelligence: "Kinfolk meets Bloomberg Terminal." It balances the sensory warmth of roasted single-origin lots with the calculated precision of yield curves, commodity hedges, and batch profitability metrics.

The emotional signature is intimate, focused, and quietly prestigious. It trades sterile enterprise gray for obsidian espresso undertones, burnished copper, and warm cream typography.

The visual execution relies on moody, atmospheric dark surfaces, refined micro-borders, low-contrast structural containers, and translucent glass tiers floating above roasted botanical photography. High-density financial figures cut through the ambient gloom with vertical, condensed authority, while tabular copy remains grounded, balanced, and instantly legible.

## Colors
The palette is built directly upon the chemistry of coffee roasting—from green bean moisture evaporation to caramelized first crack and deep oily roast depth.

### Surface System
- **Canvas Base:** `#140F0C` (Darkest roasted grounds; the zero-ground substrate).
- **Surface Elevation 1 (Card/Panel fill):** `rgba(20, 15, 12, 0.82)` to `#1A130F`.
- **Surface Elevation 2 (Hover/Active states):** `#221812`.
- **Surface Elevation 3 (Floating popovers & modals):** `#2A1E17`.

### Core Typography & Foreground
- **Primary Text (Light Cream):** `#E6C6A4`. High-legibility warmth, avoiding cold digital white.
- **Secondary / Data Text (Muted Latte):** `#C4AD91`. Used for subtitles, data table records, secondary labels, and Period A comparisons.
- **Tertiary / Subdued Text:** `rgba(196, 173, 145, 0.6)`. Used for unit marks, metadata, and timestamps.

### Accent & Interaction Spectrum
- **Primary Accent (Caramel / Burnt Orange):** `#C86D2B`. Applied to primary calls to action, active indicators, high-yield metrics, and Period B data series.
- **Interactive Active / Pressed:** `#C46520`.
- **Deep Highlight / Focus Rim:** `#B45F24`.
- **Badge Fill:** `#E6C6A4` paired strictly with `#1B160B` ink for tactile physical tag emulation.

### Structural Delimiters
- **Borders & Ghost Outlines:** `#E0C1A0` rendered at variable opacities: `rgba(224, 193, 160, 0.12)` for baseline container bounds, climbing to `rgba(224, 193, 160, 0.25)` on interactive card hover states.

## Typography
The system enforces a dual-type architecture:

1. **Oswald (Condensed Display & Numerical Cadence):** Dedicated exclusively to display hierarchy, section anchors, and financial telemetry. Oswald’s vertical proportion evokes classic commodity exchange tally boards and artisanal roast batch labels. Numerical metrics must enable tabular figures (`font-variant-numeric: tabular-nums`) to prevent horizontal jitter during dynamic price/volume recalculations.
2. **Open Sans (Systemic Utility & Analytical Flow):** Governs running copy, tabular layouts, micro-copy, tooltips, and system form fields. Its open aperture and neutral footprint provide high legibility against tinted dark espresso backgrounds, preventing visual fatigue across prolonged analytical sessions.

All uppercase headers must use tracked letter spacing (`label-caps`) to maintain breathing room at small point sizes.

## Layout & Spacing
The layout architecture utilizes a structured 12-column fluid grid system on desktop, breaking into an 8-column layout on tablet (<=1024px) and a 4-column column flow on mobile (<=640px).

- **Desktop (1200px+):** Outer margins of `2rem` (`margin`) with `1.25rem` (`gutter`) column dividers. Financial ticker strips and summary KPI bands lock to top viewports while multi-pane financial charts span 8 columns paired with a 4-column contextual orderbook or bean cupping profile.
- **Tablet (641px - 1024px):** Outset margin adjusts to `1.5rem`; side-by-side comparative charts collapse to stacked tabbed panes.
- **Mobile (<=640px):** Canvas margin shrinks to `1rem` (`margin-mobile`), and gutters compact to `0.75rem` (`gutter-mobile`). Data tables enable horizontal kinetic scrolling with locked primary lot columns.

Vertical cadence follows strict increments derived from `0.25rem` (4px baseline). Cards use internal padding of `space-lg` (24px) for expansive analytics, stepping down to `space-md` (16px) on compact inventory tables.

## Elevation & Depth
Depth is constructed through atmospheric translucence and delicate hairline luminescence rather than heavy dropped drop-shadows.

### The Atmospheric Glassmorphic Stack
- **Base Canvas:** Deep obsidian `#140F0C` overlaid with a permanent, subtle roasted bean macro texture at 4%–7% opacity using CSS mix-blend-mode `luminosity`.
- **Level 1 (Card & Module Shells):** Backed with `rgba(20, 15, 12, 0.85)` and hardware-accelerated `backdrop-filter: blur(16px)`. Framed by a 1px border of `rgba(224, 193, 160, 0.15)`. No drop-shadow is applied here; containment is governed by internal contrast.
- **Level 2 (Hovered Panels & Filter Overlays):** Surface tint shifts to `rgba(34, 24, 18, 0.90)` with `backdrop-filter: blur(20px)`. The border transitions to `rgba(224, 193, 160, 0.3)`. An ambient, warm rim shadow manifests: `0 12px 32px -8px rgba(0, 0, 0, 0.65), 0 0 1px 0 rgba(200, 109, 43, 0.25)`.
- **Level 3 (Modals, Slide-overs & Drawers):** Grounded by `#1A130F` with 95% opacity, bounded by `rgba(224, 193, 160, 0.35)` and cast over a modal veil tinted to `rgba(10, 8, 6, 0.8)`. Shadow: `0 24px 48px -12px rgba(0, 0, 0, 0.85)`.

## Shapes
The design system adopts a deliberate contrast between structured, architectural card containers and pill-shaped interactive components.

- **Interactive Elements (Pill-shaped):** Action buttons, badge indicators, search pills, time-bracket selectors, and filter chips leverage complete pill geometry (`roundedness: 3`, using full-radius boundaries `9999px`). This mirrors coffee bean curves and softens analytical density.
- **Structural Containers:** Cards, analytical panels, and dropdown containers break from the full-pill treatment to preserve usable data real estate, utilizing an intermediate `rounded-lg` (0.75rem / 12px) curvature with 1px hairline outer strokes.
- **Form Controls:** Text and numeric inputs balance between cards and pills, carrying a `rounded-lg` radius to align with data grids.

## Components

### Buttons
- **Primary Pill:** Background `#C86D2B`, label `#140F0C` (or `#FFF` when paired with high-contrast rules; default is deep roasted ink `#140F0C` in bold Oswald). Hover state: `#C46520`. Active state: `#B45F24`. Shape: Full pill (`rounded-full`). Padding: `0.625rem 1.5rem`.
- **Secondary Outlined Pill:** Background transparent, border: 1px solid `rgba(224, 193, 160, 0.35)`, label `#E6C6A4`. Hover state: Border `#C86D2B`, label `#C86D2B`, background `rgba(200, 109, 43, 0.08)`.
- **Ghost Pill:** No border, label `#C4AD91`. Hover state: Background `rgba(230, 198, 164, 0.06)`, text `#E6C6A4`.

### Translucent Glass Cards
- Containers use `background: rgba(20, 15, 12, 0.85)`, `backdrop-filter: blur(16px)`, border: `1px solid rgba(224, 193, 160, 0.18)`, border-radius: `12px`.
- Card Header: Features an upper bar containing the metric label in `label-caps` (`#C4AD91`), with primary numerical readout rendered in `Oswald` at `metric-numeral-lg` (`#E6C6A4`).

### Period Comparison Charts
- **Period A (Historical / Benchmark):** Rendered in `#C4AD91` using a muted 1.5px stroke or semi-translucent bar fill (`rgba(196, 173, 145, 0.35)`).
- **Period B (Current Lot / Active Harvest):** Rendered in high-potency Caramel `#C86D2B` with a solid 2.5px stroke or vibrant gradient fill (`linear-gradient(180deg, rgba(200, 109, 43, 0.4) 0%, rgba(200, 109, 43, 0) 100%)`).
- Tooltips display an obsidian backing (`#140F0C`), 1px outline in `rgba(224, 193, 160, 0.25)`, and comparison delta metrics styled with Oswald numerals.

### Badges & Physical Tags
- Emulates raw roasted parcel tags: Background solid `#E6C6A4`, label `#1B160B`, uppercase typography via `badge-label`.
- Outlined Variant: Border `1px solid #C86D2B`, label `#C86D2B`, background `rgba(200, 109, 43, 0.1)`.

### Form Inputs & Selectors
- Input shells utilize `background: rgba(26, 19, 15, 0.85)`, border: `1px solid rgba(224, 193, 160, 0.2)`, text: `#E6C6A4`, placeholder: `rgba(196, 173, 145, 0.45)`. Focus ring: 1px solid `#C86D2B` with ambient glow `0 0 0 3px rgba(200, 109, 43, 0.15)`.

### Financial Data Tables
- Table headers: `#C4AD91` in `label-caps`, padded with `space-sm` bottom border in `rgba(224, 193, 160, 0.12)`.
- Rows: Background transparent, alternate zebra rows with `rgba(26, 19, 15, 0.4)`. Hover row: `rgba(200, 109, 43, 0.06)`. Numeric metrics right-aligned in Oswald tabular figures.