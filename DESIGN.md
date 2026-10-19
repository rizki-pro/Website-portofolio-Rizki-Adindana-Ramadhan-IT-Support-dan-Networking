---
name: Modern Technical Portfolio
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
  on-surface-variant: '#bec8d2'
  inverse-surface: '#dae2fd'
  inverse-on-surface: '#283044'
  outline: '#88929b'
  outline-variant: '#3e4850'
  surface-tint: '#89ceff'
  primary: '#89ceff'
  on-primary: '#00344d'
  primary-container: '#0ea5e9'
  on-primary-container: '#003751'
  inverse-primary: '#006591'
  secondary: '#4edea3'
  on-secondary: '#003824'
  secondary-container: '#00a572'
  on-secondary-container: '#00311f'
  tertiary: '#7bd0ff'
  on-tertiary: '#00354a'
  tertiary-container: '#00a7e0'
  on-tertiary-container: '#00384e'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#c9e6ff'
  primary-fixed-dim: '#89ceff'
  on-primary-fixed: '#001e2f'
  on-primary-fixed-variant: '#004c6e'
  secondary-fixed: '#6ffbbe'
  secondary-fixed-dim: '#4edea3'
  on-secondary-fixed: '#002113'
  on-secondary-fixed-variant: '#005236'
  tertiary-fixed: '#c4e7ff'
  tertiary-fixed-dim: '#7bd0ff'
  on-tertiary-fixed: '#001e2c'
  on-tertiary-fixed-variant: '#004c69'
  background: '#0b1326'
  on-background: '#dae2fd'
  surface-variant: '#2d3449'
typography:
  display-hero:
    fontFamily: Plus Jakarta Sans
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.03em
  display-hero-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '600'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 26px
    fontWeight: '600'
    lineHeight: 34px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 26px
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
  label-mono:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.04em
  label-code:
    fontFamily: JetBrains Mono
    fontSize: 11px
    fontWeight: '400'
    lineHeight: 14px
    letterSpacing: 0.02em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-sm: 1rem
  margin: 2rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system expresses high-calibre systems engineering, technical mastery, and analytical clarity. It bridges the gap between deep infrastructure engineering (networks, cloud architecture, system operations) and forward-facing digital product craft.

The aesthetic blends **Modern Technical Minimalism** with **Subtle Glassmorphism**:
- Ultra-deep, saturated slate and navy canvas foundations creating deep optical depth.
- Luminescent electric cyan and emerald accents signaling active states, data flows, and operational readiness.
- Laser-sharp structural alignment inspired by network topology maps, telemetry consoles, and developer workbenches.
- Tactile, frosted surfaces with microscopic luminescence along borders rather than heavy blur artifacts.

## Colors

The palette operates in strict dark mode, establishing an immersive command-center visual hierarchy.

- **Foundations (Neutrals):**
  - Canvas Deep: `#0f172a` (Slate 900) - Base background plane.
  - Surface Mid: `#1e293b` (Slate 800) - Container surfaces, timeline nodes, panels.
  - Surface Elevated: `#334155` (Slate 700) - Hover states, floating palettes, active controls.
  - Border Glass: `rgba(148, 163, 184, 0.12)` - Delicate structural tracing.
  - Border Active: `rgba(56, 189, 248, 0.4)` - Focused or highlighted boundaries.

- **Accents:**
  - **Electric Cyan (`#0ea5e9` / `#38bdf8`):** The primary signal color. Used for interactive triggers, primary focus states, key technical metrics, and active network connections.
  - **Terminal Emerald (`#10b981`):** Functional validation and operational health. Applied to active status indicators, validated certifications, successful deployment tags, and production metrics.

- **Text & Contrast:**
  - Headings & High Emphasis: `#f8fafc` (Slate 50)
  - Body & Medium Emphasis: `#cbd5e1` (Slate 300)
  - Subdued / Technical Meta: `#64748b` (Slate 500)

## Typography

The typographic hierarchy employs a tri-font pairing to communicate hierarchy, readability, and engineering authenticity:

1. **Plus Jakarta Sans (Headings):** Modern, clean geometric shapes with subtle humanist curvature, providing polish without sacrificing modernism.
2. **Inter (Body & Narrative):** Highly legible, neutral workhorse engineered for crisp screen rendering in dense technical contexts.
3. **JetBrains Mono (Technical Metadata & System Overlays):** Monospaced precision for IP addresses, tech tags, timestamps, commit hashes, metrics, and architecture specs.

## Layout & Spacing

The layout is built on a structured **12-column fluid grid** centered within a max-width container of `1280px`.

- **Desktop (1024px+):** 12 columns, `1.5rem` (`24px`) gutters, `2rem` (`32px`) canvas margins.
- **Tablet (768px - 1023px):** 8 columns, `1rem` (`16px`) gutters, `1.5rem` (`24px`) canvas margins.
- **Mobile (320px - 767px):** 4 columns, `1rem` (`16px`) gutters, `1rem` (`16px`) canvas margins.

Spacial pacing follows an explicit 4px baseline module. Vertical stacks between distinct portfolio sections maintain `4rem` to `6rem` of breathing room to preserve clean separation between narrative units (e.g., Timeline vs. Project Grid vs. Architecture Showcase).

## Elevation & Depth

Depth is established through translucent atmospheric layers, razor-thin luminous borders, and ambient colored glows rather than traditional opaque shadows.

- **Ground Floor (Base Canvas):** Solid `#0f172a`.
- **Level 1 (Card & Section Containers):** Glass translucent background `rgba(30, 41, 59, 0.7)` with `backdrop-filter: blur(12px)` and a `1px` border of `rgba(148, 163, 184, 0.1)`.
- **Level 2 (Hovered & Active Items):** Background `rgba(30, 41, 59, 0.95)`, border `rgba(56, 189, 248, 0.35)`, and an ambient box-shadow: `0 8px 30px -4px rgba(14, 165, 233, 0.15)`.
- **Level 3 (Modals, Overlays, Floating Nav):** Background `rgba(15, 23, 42, 0.85)` with `backdrop-filter: blur(16px)`, border `rgba(148, 163, 184, 0.2)`, and shadow `0 20px 40px -10px rgba(0, 0, 0, 0.6)`.

## Shapes

The interface balances precision engineering with modern softness by setting standard structural corners to `0.5rem` (`8px`).

- **Base Components (Inputs, Buttons, Cards, Timeline Nodes):** `0.5rem` (`8px`).
- **Feature Cards & Modal Panels (`rounded-lg`):** `1rem` (`16px`).
- **Status Pills, Badges, & Network Nodes (`rounded-full`):** 9999px pill shapes to contrast against rectangular cards.

## Components

### Buttons
- **Primary:** Background `#0ea5e9`, text `#0f172a`, font weight `600`. Outer glow on hover: `box-shadow: 0 0 20px rgba(14, 165, 233, 0.4)`. Transitions are crisp (`150ms ease-out`).
- **Secondary / Ghost:** Translucent slate background (`rgba(30, 41, 59, 0.6)`), border `1px solid rgba(148, 163, 184, 0.2)`, text `#f8fafc`. Hover triggers border color change to `#38bdf8` with foreground color shift.
- **Icon Actions:** `36px x 36px` bounding box, centered network/terminal SVG iconography with `1px` inner stroke.

### Glowing Badges & Tech Chips
- **Format:** Height `24px`, padding `0 10px`, typography `label-mono`, border radius `9999px`.
- **Active / Verified (Emerald):** Background `rgba(16, 185, 129, 0.1)`, border `1px solid rgba(16, 185, 129, 0.3)`, text `#10b981`. Includes an animated pulsing `6px` circular beacon on live statuses.
- **Protocol / Stack (Cyan):** Background `rgba(14, 165, 233, 0.1)`, border `1px solid rgba(56, 189, 248, 0.25)`, text `#38bdf8`.

### Experience & Education Timeline
- **Spine:** `2px` vertical guideline colored `rgba(51, 65, 85, 0.8)` anchored to the left of content.
- **Timeline Indicator:** Concentric circular node (`14px` diameter). Solid `#0f172a` center with a `2px` border in `#0ea5e9` and an exterior ambient glow (`box-shadow: 0 0 10px rgba(14, 165, 233, 0.5)`).
- **Node Cards:** Suspended card containers with a subtle left border highlight indicating promotion, degree completion, or major career milestones.

### Technical Cards
- **Construction:** Frosted slate backdrop (`rgba(30, 41, 59, 0.65)`), `1px` subtle rim border (`rgba(148, 163, 184, 0.12)`).
- **Header:** Features monospace meta badges (e.g., latency, stack tags, role duration) aligned right.
- **Interactive State:** Translates `-2px` on the Y-axis with a subtle cyan gradient illumination along the top border edge.

### Form Inputs
- Background `rgba(15, 23, 42, 0.75)`, border `1px solid rgba(148, 163, 184, 0.2)`, text `#f8fafc`, placeholder `#64748b`.
- Focus state activates an electric cyan hairline border (`#0ea5e9`) and an inner ring glow: `box-shadow: 0 0 0 1px #0ea5e9, 0 0 12px rgba(14, 165, 233, 0.2)`.

### Networking & IT Iconography Accent
- Line-weight: Unified `1.75px` stroke, square caps, rounded joins.
- Presentation: Enclosed within a `40px` glass enclosure with a radial gradient centered behind the icon glyph (`rgba(14, 165, 233, 0.15)` fading to transparent).