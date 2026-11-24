---
name: "Thunder Deals"
description: "A high-energy, contrast-forward global deal discovery design system built for worldwide offers across Tech, Fashion, and Home."
---

## Overview

Thunder Deals is a worldwide deal-discovery platform designed for decisive shoppers hunting verified price drops across Tech, Fashion, and Home. The aesthetic pairs **High-Contrast Editorial Commerce** with crisp, scannable product cards and bold promotional banners. It evokes urgency and trust without visual clutter: generous breathing room around featured deal banners, sharp typographic hierarchy for pricing and savings, and effortless switching between bright daylight browsing and a deep-navy dark mode.

## Colors

The palette pairs an electric cobalt primary (`#0037B0` in light mode, `#B7C4FF` in dark mode) with a high-energy thunder-amber secondary (`#904D00` / `#FE932C`) reserved for savings badges, flash-drop highlights, and featured deal callouts. Surfaces use cool-tinted slate neutrals (`#F9F9FF` in light mode, `#081425` deep navy-slate in dark mode—never pure `#000000`) to keep product photography and price tags crisp.

- **Primary:** Anchors primary "Get Deal" click-through actions, active category states, and brand trust marks.
- **Secondary:** Highlights discount percentages, limited-time global drops, and promotional banner accents.
- **Neutral Surfaces:** Stepped tonal containers (`surface-container-low`, `surface-container`, `surface-container-high`) separate deal cards and filter bars without heavy borders.

```yaml
colors:
  brand-bolt: "#F59E0B"
  success: "#15803D"
  on-success: "#FFFFFF"
  light:
    primary: "#0037B0"
    on-primary: "#FFFFFF"
    primary-container: "#1D4ED8"
    on-primary-container: "#CAD3FF"
    secondary: "#904D00"
    on-secondary: "#FFFFFF"
    secondary-container: "#FE932C"
    on-secondary-container: "#663500"
    tertiary: "#7F2500"
    on-tertiary: "#FFFFFF"
    tertiary-container: "#A73400"
    on-tertiary-container: "#FFC9B7"
    error: "#BA1A1A"
    on-error: "#FFFFFF"
    error-container: "#FFDAD6"
    on-error-container: "#93000A"
    background: "#F9F9FF"
    on-background: "#111C2D"
    surface: "#F9F9FF"
    surface-dim: "#CFDAF2"
    surface-bright: "#F9F9FF"
    surface-container-lowest: "#FFFFFF"
    surface-container-low: "#F0F3FF"
    surface-container: "#E7EEFF"
    surface-container-high: "#DEE8FF"
    surface-container-highest: "#D8E3FB"
    on-surface: "#111C2D"
    surface-variant: "#E0E1F4"
    on-surface-variant: "#434655"
    outline: "#747686"
    outline-variant: "#C4C5D7"
    inverse-surface: "#263143"
    inverse-on-surface: "#ECF1FF"
    inverse-primary: "#B7C4FF"
  dark:
    primary: "#B7C4FF"
    on-primary: "#002682"
    primary-container: "#1D4ED8"
    on-primary-container: "#CAD3FF"
    secondary: "#FFB77D"
    on-secondary: "#4D2600"
    secondary-container: "#D97707"
    on-secondary-container: "#3C1C00"
    tertiary: "#FFB59C"
    on-tertiary: "#5C1900"
    tertiary-container: "#A73400"
    on-tertiary-container: "#FFC9B7"
    error: "#FFB4AB"
    on-error: "#690005"
    error-container: "#93000A"
    on-error-container: "#FFDAD6"
    background: "#081425"
    on-background: "#D8E3FB"
    surface: "#081425"
    surface-dim: "#081425"
    surface-bright: "#2F3A4C"
    surface-container-lowest: "#040E1F"
    surface-container-low: "#111C2D"
    surface-container: "#152031"
    surface-container-high: "#1F2A3C"
    surface-container-highest: "#2A3548"
    on-surface: "#D8E3FB"
    surface-variant: "#434655"
    on-surface-variant: "#C4C5D7"
    outline: "#8E90A0"
    outline-variant: "#434655"
    inverse-surface: "#D8E3FB"
    inverse-on-surface: "#263143"
    inverse-primary: "#2151DA"
```

## Typography

A three-family pairing balances bold promotional impact with fast price scanning. **Alatsi** brings geometric punch to hero banners and section headlines; **Instrument Sans** keeps product titles, retailer metadata, and navigation crisp at small sizes; **Spline Sans Mono** gives prices, discount percentages, and countdowns tabular precision.

```yaml
typography:
  display-lg:
    fontFamily: "Alatsi"
    fontSize: 48px
    fontWeight: 400
    lineHeight: 54px
    letterSpacing: -0.5px
  display-lg-mobile:
    fontFamily: "Alatsi"
    fontSize: 32px
    fontWeight: 400
    lineHeight: 38px
    letterSpacing: -0.25px
  headline-lg:
    fontFamily: "Alatsi"
    fontSize: 32px
    fontWeight: 400
    lineHeight: 38px
    letterSpacing: -0.25px
  headline-md:
    fontFamily: "Alatsi"
    fontSize: 24px
    fontWeight: 400
    lineHeight: 30px
    letterSpacing: 0px
  title-lg:
    fontFamily: "Instrument Sans"
    fontSize: 18px
    fontWeight: 600
    lineHeight: 24px
    letterSpacing: 0px
  title-md:
    fontFamily: "Instrument Sans"
    fontSize: 16px
    fontWeight: 600
    lineHeight: 22px
    letterSpacing: 0px
  body-md:
    fontFamily: "Instrument Sans"
    fontSize: 14px
    fontWeight: 400
    lineHeight: 20px
    letterSpacing: 0px
  label-lg:
    fontFamily: "Instrument Sans"
    fontSize: 14px
    fontWeight: 600
    lineHeight: 20px
    letterSpacing: 0.1px
  label-sm:
    fontFamily: "Instrument Sans"
    fontSize: 12px
    fontWeight: 600
    lineHeight: 16px
    letterSpacing: 0.2px
  mono-price:
    fontFamily: "Spline Sans Mono"
    fontSize: 20px
    fontWeight: 700
    lineHeight: 24px
    letterSpacing: -0.5px
  mono-sm:
    fontFamily: "Spline Sans Mono"
    fontSize: 12px
    fontWeight: 600
    lineHeight: 16px
    letterSpacing: 0.2px
```

## Layout & Spacing

Thunder Deals uses a **Fixed-Max-Width 12-Column Grid** (`max-w-7xl`, up to `1280px`) on desktop and a **Fluid 4-Column Grid** on mobile (`< 768px`). An 8px base spacing unit (with a 4px half-step) governs all padding and gutters. Category sections stack vertically with generous `48px` section breaks, while deal grids collapse from 4 columns on desktop to 2 columns on tablet and 1 column on mobile.

```yaml
spacing:
  gutter-xs: 4px
  gutter-sm: 8px
  gutter-md: 16px
  gutter-lg: 24px
  gutter-xl: 32px
  section: 48px
  page-margin: 24px
```

## Elevation & Depth

Depth is conveyed through **Tonal Layers** paired with **Low-Contrast Outlines** (`outline-variant`), avoiding heavy drop shadows. Cards sit on `surface-container-lowest` (light) or `surface-container-low` (dark) with a crisp 1px `outline-variant` border, stepping up to `surface-container` on hover. Featured promotional banners use rich photography with a directional dark scrim so overlaid white typography remains legible.

## Shapes

A confident, slightly squared geometry keeps product cards structured while keeping interactive pills approachable. Cards and banners use `12px` (`md`) or `16px` (`lg`) corners; buttons use `8px` (`DEFAULT`); discount badges and category filter chips use `full` (`9999px`).

```yaml
rounded:
  sm: 4px
  DEFAULT: 8px
  md: 12px
  lg: 16px
  xl: 24px
  full: 9999px
```

## Motion & Micro-interaction

Motion is crisp and immediate, matching the "thunder" brand speed. Hover transitions on deal cards and buttons resolve in `150ms` using `transform`, `opacity`, and color changes only—never animating layout properties.

```yaml
motion:
  state-change:
    duration: 150ms
    delay: 0ms
    timingFunction: ease-out
  surface-enter:
    duration: 220ms
    delay: 0ms
    timingFunction: cubic-bezier(0.2, 0, 0, 1)
  surface-exit:
    duration: 150ms
    delay: 0ms
    timingFunction: cubic-bezier(0.3, 0, 1, 1)
```

## Voice & Content Strategy

- **Tone of voice:** Direct, sharp, and deal-savvy. Copy focuses on real savings, verified retailers, and regional availability ("42% off at B&H Photo", "Ships Worldwide") rather than hype ("Unbelievable", "Reimagine").
- **Capitalisation:** Title Case for navigation items, category headings, and primary buttons ("Get Deal", "Shop Tech Deals"); Sentence case for deal descriptions and banners.
- **Action labels:** Clear click-through verbs (`Get Deal`, `View Offer`, `Explore Tech`).
- **Numbers & currency:** Tabular monospace figures (`tabular-nums`) for all prices, original strikethrough prices, and percentage-off badges (`$199`, `40% OFF`).

## Components

Component implementations live as individual HTML sticker sheet files in
`components/`. Each file contains the canonical, styled HTML components with
`<!-- COMPONENT: name -->` comment markers. Read each file before use.

- **Badge** → `@components/badge.html` — `badge-numeric`, `badge-dot`
- **Button** → `@components/button.html` — `button-primary`, `button-icon`, `button-with-icon`
- **Card** → `@components/card.html` — `card-elevated`, `card-action`, `card-interactive`, `card-interactive-2`
- **Chip** → `@components/chip.html` — `chip-action`, `chip-input`, `chip-with-icon`
- **Searchbar** → `@components/searchbar.html` — `searchbar-standard`, `searchbar-with-suggestions`
