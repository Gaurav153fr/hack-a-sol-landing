---
name: Obsidian Kinetic
colors:
  surface: '#111317'
  surface-dim: '#111317'
  surface-bright: '#37393d'
  surface-container-lowest: '#0c0e11'
  surface-container-low: '#1a1c1f'
  surface-container: '#1e2023'
  surface-container-high: '#282a2d'
  surface-container-highest: '#333538'
  on-surface: '#e2e2e6'
  on-surface-variant: '#e4bdbc'
  inverse-surface: '#e2e2e6'
  inverse-on-surface: '#2f3034'
  outline: '#ab8888'
  outline-variant: '#5b403f'
  surface-tint: '#ffb3b2'
  primary: '#ffb3b2'
  on-primary: '#680013'
  primary-container: '#ff525e'
  on-primary-container: '#5b0010'
  inverse-primary: '#bc0d2e'
  secondary: '#ffb86b'
  on-secondary: '#492900'
  secondary-container: '#ed9000'
  on-secondary-container: '#583300'
  tertiary: '#c6bfff'
  on-tertiary: '#2900a0'
  tertiary-container: '#8c7fff'
  on-tertiary-container: '#23008d'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffdad9'
  primary-fixed-dim: '#ffb3b2'
  on-primary-fixed: '#410008'
  on-primary-fixed-variant: '#920020'
  secondary-fixed: '#ffdcbc'
  secondary-fixed-dim: '#ffb86b'
  on-secondary-fixed: '#2c1700'
  on-secondary-fixed-variant: '#683d00'
  tertiary-fixed: '#e4dfff'
  tertiary-fixed-dim: '#c6bfff'
  on-tertiary-fixed: '#160066'
  on-tertiary-fixed-variant: '#4029ba'
  background: '#111317'
  on-background: '#e2e2e6'
  surface-variant: '#333538'
  background-base: '#060709'
  surface-glass: rgba(20, 23, 29, 0.72)
  surface-elevated: '#14171D'
  accent-crimson: '#FF3B30'
  accent-coral: '#FF6B4A'
  glow-cyan: '#00F2FE'
  border-luminous: rgba(255, 255, 255, 0.08)
  border-active: rgba(255, 71, 87, 0.45)
typography:
  headline-display:
    fontFamily: Geist
    fontSize: 56px
    fontWeight: '600'
    lineHeight: 64px
    letterSpacing: -0.03em
  headline-display-mobile:
    fontFamily: Geist
    fontSize: 36px
    fontWeight: '600'
    lineHeight: 44px
    letterSpacing: -0.025em
  headline-lg:
    fontFamily: Geist
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Geist
    fontSize: 26px
    fontWeight: '600'
    lineHeight: 34px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Geist
    fontSize: 24px
    fontWeight: '500'
    lineHeight: 32px
    letterSpacing: -0.015em
  headline-sm:
    fontFamily: Geist
    fontSize: 18px
    fontWeight: '500'
    lineHeight: 26px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Geist
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: -0.01em
  body-md:
    fontFamily: Geist
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0em
  body-sm:
    fontFamily: Geist
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
    letterSpacing: 0.01em
  label-code:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.02em
  label-kbd:
    fontFamily: JetBrains Mono
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.04em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 2rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system channels the uncompromising precision and velocity of next-generation developer tooling. Built around a foundation of deep cosmic obsidian surfaces, it pairs dark tonal discipline with high-energy crimson, coral, and amber luminance. The aesthetic synthesizes **Dark-Mode Minimalism** and **Refined Glassmorphism**—delivering high tactile responsiveness, ultra-sharp border definitions, and atmospheric radial auras that suggest computing power humming beneath the glass.

Targeting power users, engineers, and digital craftspeople, the interface prioritizes keyboard-driven speed, spatial clarity, and zero cognitive bloat. Every element feels machined, engineered, and instant:
- **Atmospheric Depth:** Layered translucent glass floats above obsidian voids, accented by subtle directional gradient rings and diffused glow fields.
- **Surgical Precision:** Strict 1px luminous borders define interactable planes without cluttering information density.
- **Luminescent Energy:** High-saturation red-coral accents pierce through dark backgrounds with calculated vibrancy, indicating focal points, active states, and rapid feedback loops.

## Colors

The color system operates on an absolute dark foundation where chromatic accents act as light sources rather than flat fills.

- **Foundational Surfaces:** `#060709` forms the root backdrop canvas. Secondary layers use `#0D0F12` for container grouping, stepping up to `#14171D` for floating palettes, modals, and key interactive planes.
- **Primary Energy (`#FF4757` & `#FF6B4A`):** The signature vibrant coral-red represents primary actions, focus rings, hotkeys, and system status indicators.
- **Secondary Luminescence (`#FF9F1C`):** Warm amber is reserved for modifier tags, warnings, search ranking accents, and energetic micro-interactions.
- **Tertiary Accent (`#6C5CE7` & `#00F2FE`):** Deep electric violet and piercing cyan serve as developer-centric highlights, plugin tags, and gradient blend stops.
- **Text & Contrast Ratios:** All primary copy defaults to high-clarity near-white (`#F8FAFC`, 95% opacity), secondary metadata sits at 65% opacity (`#94A3B8`), and muted shortcuts or unselected states fall to 40% opacity (`#64748B`).

## Typography

Typography is clean, modern, and calibrated for ultra-dense informational clarity. 

- **Primary Interface Typeface (Geist):** Chosen for its neo-grotesque technical discipline, neutral geometric shapes, and distinct character rendering in dark interfaces. Headings feature tightened tracking (`-0.015em` to `-0.03em`) to anchor authority and visual weight.
- **Monospaced Utility Typeface (JetBrains Mono):** Dedicated to technical metadata, keybindings (`kbd`), command arguments, line counters, and raw data outputs.
- **Micro-Copy Hierarchy:** Key bindings and status badges employ uppercase styling or monospaced metrics, ensuring visual consistency across interactive command bars and quick-select rows.

## Layout & Spacing

The layout model is governed by a **fixed-fluid hybrid container system** engineered for power-user command bars and dense modular dashboards:

- **Grid Architecture:** Desktop views utilize a 12-column layout capped at a maximum width of 1280px for standard marketing/content flows, while command palettes and overlay windows adhere to fixed mathematical widths (640px compact, 768px standard, 960px wide).
- **Rhythmic Scale:** Spacing follows an absolute 4px/8px modular base scale. Internal component gaps lean towards tight, high-efficiency spacing (`space-xs` and `space-sm`), reserving wide breathing room (`space-lg` to `space-xl`) strictly for separating distinct semantic panes and hero sections.
- **Adaptive Breakpoints:**
  - **Mobile (< 768px):** Drops to a single-column stack, compresses gutters to `1rem`, pulls margin boundaries to screen edges, and translates floating command modals into full-bleed bottom sheets.
  - **Tablet (768px – 1024px):** Adapts multi-column tools into an 8-column canvas with persistent sidebars collapsing to icon-only rails.
  - **Desktop (> 1024px):** Expands to full 12-column grids with generous peripheral canvas margins.

## Elevation & Depth

Visual hierarchy uses a refined combination of dark glassmorphic materials, luminous rim lighting, and backdrop radial glows.

- **Backdrop Atmosphere (The Hero Aura):** Deep atmospheric fields are constructed by placing diffuse radial gradients behind primary interactive anchors. A typical hero cluster blends a 400px–600px radius spotlight (`#FF4757` at 12% opacity mixed with `#6C5CE7` at 8% opacity) blurred with an extreme 120px Gaussian falloff against the `#060709` substrate.
- **Glass Surfaces:** Elevated command modals, popovers, and sticky bars use translucent backgrounds (`rgba(20, 23, 29, 0.72)`) paired with a `backdrop-filter: blur(20px) saturate(180%)`.
- **Luminous 1px Borders:** Elevation tiers are separated by hair-thin, 1px top-lit borders rather than traditional dropshadows. Surfaces feature a subtle vertical gradient border: top edges catch white light (`rgba(255, 255, 255, 0.12)`), bleeding down into subtle side boundaries (`rgba(255, 255, 255, 0.04)`), and dissolving at the base.
- **Ambient Shadows:** When an overlay floats above layered content, it casts a compound shadow:
  - Specular rim: `0 0 0 1px rgba(255, 255, 255, 0.08)`
  - Direct drop: `0 12px 32px -8px rgba(0, 0, 0, 0.65)`
  - Accent flare: `0 24px 64px -16px rgba(255, 71, 87, 0.08)`

## Shapes

The design system adopts a **Balanced Rounded** silhouette (`roundedness: 2`), delivering an engineered, contemporary feel without leaning into soft playfulness:

- **Inputs, Cards & Panels:** Standard buttons, text inputs, list selections, and command bar panels use `0.5rem` (8px) corner radii.
- **Large Panels & Window Frames:** Modal containers, floating preview sheets, and hero cards step up to `1rem` (16px) corner radii (`rounded-lg`).
- **Pill Badges & Keystroke Badges:** Keyboard shortcuts (`kbd`), status indicators, search chips, and command tags use fully rounded pill geometry (`9999px`) or compact rounded-md (`6px`) for micro-keys to emphasize discrete tokenization.

## Components

### Buttons & Interactive Controls
- **Primary Buttons:** High-energy fill using `#FF4757` transitioning to `#FF6B4A` via a subtle 135-degree linear gradient. Text is crisp white with semi-bold weighting. On hover, the button emits a targeted crimson aura (`box-shadow: 0 0 20px -2px rgba(255, 71, 87, 0.45)`).
- **Secondary / Ghost Buttons:** Composed of translucent obsidian glass (`rgba(255, 255, 255, 0.04)`), framed by a 1px border (`rgba(255, 255, 255, 0.08)`). On hover, the surface lightens to `rgba(255, 255, 255, 0.08)` with border color shifting to `#FF4757`.
- **Keyboard Shortcut Accents (`<kbd>`):** Inset micro-keys rendered in `#14171D` with a top-lit border (`rgba(255, 255, 255, 0.15)`), distinct 1px drop shadow, and typography set in `JetBrains Mono` at `11px`.

### Command Palette & Lists
- **Result Rows:** Dense, 40px to 48px height rows with flush 8px horizontal padding.
- **Active / Focused Row:** Indicated by a glowing horizontal pill treatment (`rgba(255, 71, 87, 0.12)`) bounded by a subtle left accent edge or full border tint (`rgba(255, 71, 87, 0.35)`). Active icons take the `#FF4757` coral hue.
- **List Dividers:** Replaced with contextual categorical headers using `JetBrains Mono` 10px uppercase tracking, avoiding disruptive continuous horizontal rules.

### Input Fields
- **Search & Input Bars:** Floating glass input fields without heavy inset wells. Background is dark translucent (`rgba(13, 15, 18, 0.8)`).
- **Focus Rings:** No native browser rings; inputs trigger a 1px glowing perimeter (`#FF4757`) coupled with a soft external ambient crimson flare (`0 0 12px rgba(255, 71, 87, 0.25)`).

### Chips & Badges
- **Status Pills:** Pill-shaped indicators (`padding: 2px 10px`) utilizing low-opacity chromatic fills (`rgba(255, 159, 28, 0.12)` for amber, `rgba(255, 71, 87, 0.12)` for red) anchored by a 6px glowing center dot.

### Cards & Panels
- **Bento & Feature Cards:** Crafted from dark obsidian plates (`#0D0F12`) overlaid with a luminous perimeter border (`rgba(255, 255, 255, 0.06)`). Inner hover states reveal an interactive cursor-following radial gradient highlight.