---
version: alpha
name: Attick & Keller Brand
description: "Vintage industrial grunge meets premium dark analytics — the dual identity of ATTIC (raw, distressed) and KELLER (clean, refined). Inspired by the official A&K brand assets: SmithyXT typography, rust/terracotta accents, and stippled grunge textures."
colors:
  # — Core brand (from logos) —
  slate-blue: "#34495E"
  rust-red: "#A0522D"
  brick-red: "#B24D42"
  cream: "#F7F3E9"
  parchment: "#F2EBE1"
  # — Dark theme (analytics UI) —
  night: "#1A1412"
  night-card: "#2C2018"
  night-input: "#362A22"
  night-border: "#4A3A30"
  night-text: "#E8DDD0"
  night-muted: "#A89788"
  # — Accents —
  gold: "#C9A94E"
  gold-dim: "#9A7B2E"
  borgona: "#C44D63"
  borgona-light: "#E06B82"
  oliva: "#5C7A4D"
  oliva-light: "#7BA86A"
  ambar: "#D4922A"
  ambar-light: "#E8A840"
  # — Muted brand (from story-tipo flyer) —
  navy-flyer: "#2C435B"
  rust-flyer: "#A5423A"
  foxing: "#A67B5B"
  ink-black: "#1E1E1E"
typography:
  display:
    fontFamily: SmithyXT
    fontSize: "3rem"
    fontWeight: "900"
    lineHeight: "1.05"
    letterSpacing: "0.04em"
  display-heavy:
    fontFamily: SmithyXT
    fontSize: "2rem"
    fontWeight: "700"
    lineHeight: "1.1"
    letterSpacing: "0.03em"
  heading:
    fontFamily: SmithyXT
    fontSize: "1.5rem"
    fontWeight: "700"
    lineHeight: "1.2"
    letterSpacing: "0.05em"
  subheading:
    fontFamily: SmithyXT
    fontSize: "0.875rem"
    fontWeight: "700"
    letterSpacing: "0.12em"
    textTransform: uppercase
  decorative:
    fontFamily: OldPress
    fontSize: "1rem"
    fontWeight: "400"
    lineHeight: "1.4"
  body:
    fontFamily: Inter
    fontSize: "0.875rem"
    fontWeight: "400"
    lineHeight: "1.6"
  body-small:
    fontFamily: Inter
    fontSize: "0.75rem"
    fontWeight: "500"
    lineHeight: "1.5"
  accent:
    fontFamily: Caveat
    fontSize: "1rem"
    fontWeight: "600"
    lineHeight: "1.3"
  kpi-value:
    fontFamily: SmithyXT
    fontSize: "2rem"
    fontWeight: "900"
    lineHeight: "1"
  kpi-label:
    fontFamily: Inter
    fontSize: "0.625rem"
    fontWeight: "600"
    letterSpacing: "0.1em"
    textTransform: uppercase
rounded:
  sm: "4px"
  md: "8px"
  lg: "12px"
  xl: "16px"
  card: "10px"
spacing:
  xs: "4px"
  sm: "8px"
  md: "16px"
  lg: "24px"
  xl: "32px"
  slide-padding: "24px 20px 100px"
elevation:
  card:
    boxShadow: "0 2px 8px rgba(0,0,0,0.3)"
    border: "1px solid rgba(201,169,78,0.12)"
  card-hover:
    boxShadow: "0 8px 24px rgba(0,0,0,0.5)"
  kpi-hero:
    boxShadow: "0 4px 20px rgba(201,169,78,0.15)"
    border: "1px solid rgba(201,169,78,0.25)"
components:
  slide:
    backgroundColor: "{colors.night}"
    color: "{colors.night-text}"
    padding: "{spacing.slide-padding}"
    overflowY: auto
  slide-title:
    fontFamily: SmithyXT
    fontWeight: "700"
    fontSize: "1.375rem"
    color: "{colors.gold}"
    letterSpacing: "0.05em"
    textTransform: uppercase
    borderBottom: "2px solid {colors.gold}"
    paddingBottom: "8px"
  slide-subtitle:
    fontFamily: Caveat
    fontSize: "0.875rem"
    color: "{colors.night-muted}"
  kpi-card:
    backgroundColor: "{colors.night-card}"
    borderRadius: "{rounded.card}"
    padding: "12px"
    border: "1px solid rgba(201,169,78,0.12)"
    boxShadow: "{elevation.card.boxShadow}"
  kpi-card-hover:
    transform: "translateY(-2px)"
    boxShadow: "{elevation.card-hover.boxShadow}"
  kpi-value-gold:
    color: "{colors.gold}"
    fontFamily: SmithyXT
    fontWeight: "900"
    fontSize: "2rem"
  kpi-value-borgona:
    color: "{colors.borgona}"
  kpi-value-green:
    color: "{colors.oliva}"
  bar-fill:
    background: "linear-gradient(90deg, {colors.rust-red}, {colors.ambar})"
  bar-fill-alt:
    background: "linear-gradient(90deg, {colors.gold-dim}, {colors.gold})"
  badge:
    borderRadius: "{rounded.sm}"
    padding: "2px 8px"
    fontWeight: "600"
    fontSize: "0.625rem"
    letterSpacing: "0.05em"
    textTransform: uppercase
  badge-danger:
    backgroundColor: "rgba(196,77,99,0.15)"
    color: "{colors.borgona}"
  badge-success:
    backgroundColor: "rgba(93,184,122,0.15)"
    color: "{colors.oliva-light}"
  badge-warning:
    backgroundColor: "rgba(212,146,42,0.15)"
    color: "{colors.ambar-light}"
  badge-info:
    backgroundColor: "rgba(90,158,196,0.15)"
    color: "{colors.night-muted}"
  divider:
    height: "1px"
    background: "linear-gradient(90deg, transparent, {colors.night-border}, transparent)"
    margin: "12px 0"
  ornament:
    color: "{colors.gold}"
    fontSize: "0.625rem"
    letterSpacing: "0.3em"
  texture-overlay:
    opacity: "0.03"
    pointerEvents: none
    mixBlendMode: overlay

---

## Overview

**Attick & Keller** is a restaurant and bar brand defined by dual identity: **ATTIC** (raw, distressed, vintage) vs **KELLER** (clean, refined, modern). This tension — rough vs smooth, old vs new — is the core of every visual decision.

The brand draws from vintage industrial signage, distressed print ephemera, and the warmth of aged leather and rusted metal. In the analytics context, this translates to a **dark premium** aesthetic: warm brown-blacks, gold and borgoña accents, SmithyXT headings, and grunge texture overlays that make data feel like it belongs in a leather-bound ledger, not a SaaS dashboard.

## Colors

### Brand Core (from official logos)

- **Slate Blue `#34495E`**: The text color of ATTIC & KELLER in the logo. Deep blue-grey with authority. Used for headings in light themes and as a secondary accent in dark mode.
- **Rust Red `#A0522D`**: The signature K-backdrop color. Terracotta, earthy, warm. This is the primary brand accent — the color of aged brick, leather, and candlelight.
- **Brick Red `#B24D42`**: The stippled grunge texture from `mancha roja.jpg`. More saturated than Rust Red, used for hover states, danger badges, and emphasis.
- **Cream `#F7F3E9`**: Vintage paper background from `fondo-story.jpg`. The light theme foundation — warm, aged, inviting.

### Dark Analytics Palette

- **Night `#1A1412`**: The deep brown-black base. Not pure black — warmer, like dark wood.
- **Night Card `#2C2018`**: Elevated surfaces, cards, panels. Warm brown.
- **Night Text `#E8DDD0`**: Warm off-white for body text. Easy on the eyes.
- **Gold `#C9A94E`**: Primary interactive accent. The color of candlelight on brass.
- **Borgoña `#C44D63`**: Secondary accent, danger, alerts. Wine red.
- **Ámbar `#D4922A`**: Warning, warmth, heat maps. Amber firelight.
- **Oliva `#5C7A4D`**: Success, positive metrics. Aged olive green.

### Accent Relationships

- Gold is **always** the primary accent for interactive elements and headings
- Borgoña is for **alerts, danger, negative metrics** — never as decorative accent
- Ámbar sits between gold and borgoña — **warning, heat, caution**
- Oliva is **success only** — never for decoration

## Typography

### The SmithyXT System

SmithyXT is the **identity font family**. It's a condensed sans-serif with grunge variants:

- **SmithyXT-VeryHeavy (900)**: Hero KPI values, portada titles, slide numbers. The heaviest, most impactful weight.
- **SmithyXT-Heavy (700)**: Slide titles, section headings, badge labels. The workhorse.
- **SmithyXT-Faded**: The ATTIC voice — distressed, weathered. Used sparingly for decorative labels, era stamps, or the word "ATTIC" when contrast with clean "KELLER" is needed.
- **Old Press**: Distressed serif. For decorative accent text only — "est. 2024", location stamps, or handwritten-style asides. Never for data labels or body text.

### Body and Accent Fonts

- **Inter**: All data, body copy, small labels, numbers. Clean and legible at all sizes.
- **Caveat**: Handwritten accent. Slide subtitles, casual callouts, "datos con carácter" tagline.

### Typography Rules

1. **Never use SmithyXT below 14px** — the grunge detail becomes noise at small sizes
2. **Headings are always SmithyXT Heavy, uppercase, gold, with letter-spacing 0.05em**
3. **KPI values are always SmithyXT VeryHeavy, large (2rem+), white or gold**
4. **Body text is always Inter** — never SmithyXT or Old Press for paragraphs
5. **The ATTIC/KELLER contrast**: When both words appear together, ATTIC uses Faded, KELLER uses Heavy/VeryHeavy — this is the brand's signature dual identity
6. **Limit to 3 fonts per slide**: SmithyXT (display) + Inter (body) + Caveat or Old Press (accent, pick one)

## Layout & Spacing

### Slide Deck (9:16 Mobile-First)

- **Viewport**: 450×800px base, scales to fit
- **Slide padding**: 24px 20px 100px (100px bottom for nav dots)
- **Gap between elements**: 16px
- **KPI grid**: `grid-template-columns: repeat(auto-fill, minmax(140px, 1fr))` with 10px gap
- **Bar charts**: Full width, 24px bar height, 4px radius

### Spacing Scale

- `xs` (4px): Tight gaps inside badges, inline spacing
- `sm` (8px): Between badge label and value, list item gaps
- `md` (16px): Between sections, below dividers
- `lg` (24px): Slide top/bottom padding, major section breaks
- `xl` (32px): Between slides, hero spacing

## Elevation & Depth

Cards use subtle warm shadows on the dark background:

- **Default card**: `0 2px 8px rgba(0,0,0,0.3)` with `1px solid rgba(201,169,78,0.12)` border
- **Hover**: `0 8px 24px rgba(0,0,0,0.5)` with `translateY(-2px)`
- **KPI hero**: `0 4px 20px rgba(201,169,78,0.15)` — gold glow for important numbers

### Texture Overlays

The grunge texture from the brand assets is applied as a **3% opacity overlay** across the entire slide deck. This is critical for the A&K identity — it makes the dark background feel like worn leather, not a flat screen.

```css
.texture-overlay {
  position: fixed;
  inset: 0;
  opacity: 0.03;
  pointer-events: none;
  mix-blend-mode: overlay;
  background: url("data:image/svg+xml,...") repeat;
}
```

## Shapes & Ornaments

- **Border radius**: Cards use `10px`, badges `4px`, buttons `8px`
- **Ornaments**: The ◆ diamond separator is the brand's signature divider. Used between title and content, between sections, and in the portada.
- **Corner ornaments**: Decorative corner brackets `┌ ┐ └ ┘` in gold at `opacity: 0.3` on key cards
- **Bar fills**: Always gradients, never flat colors. Gold uses `linear-gradient(90deg, #9A7B2E, #C9A94E)`. Heat uses `linear-gradient(90deg, #A0522D, #D4922A)`.
- **Dashed dividers**: `1px solid` with `linear-gradient(90deg, transparent, #4A3A30, transparent)` — mimics the stitching lines in the brand flyer

## Components

### Slide

Dark brown-black background with warm text. Each slide has a numbered section label (e.g., "01 — ESTRUCTURA") in SmithyXT Heavy uppercase gold, followed by the title in larger SmithyXT, then a Caveat subtitle.

### KPI Card

Elevated card with subtle gold border. Label in small uppercase Inter (0.625rem, 0.1em tracking). Value in SmithyXT VeryHeavy 2rem. Context text in muted Inter below.

Variants:
- **Gold value**: Default for positive metrics
- **Borgoña value**: Negative metrics, alerts
- **Oliva value**: Success metrics

### Bar Chart

Horizontal bars with rounded ends. Labels in Inter 0.75rem, values right-aligned. Fill uses brand gradients. Track background is `rgba(201,169,78,0.08)`.

### Heatmap Cell

Grid cell with interpolated color between three stops:
- Cold (low): `#362A22` (night-input)
- Medium: `#D4922A` (ámbar)
- Hot (high): `#C44D63` (borgoña)

Cell size: `min 28px`, border-radius `3px`, gap `2px`.

### Badge

Small pill-shaped labels for status indicators:
- **Danger** (`borgoña` bg, `borgoña-light` text): PICO, INEFICIENTE, problems
- **Success** (`oliva` bg, `oliva-light` text): Good metrics
- **Warning** (`ámbar` bg, `ámbar-light` text): Gaps, caution
- **Info** (`night-border` bg, `night-muted` text): Neutral labels

### Divider

Gradient line: `linear-gradient(90deg, transparent, #4A3A30, transparent)` — the stitching line from the brand flyer. Centered ◆ diamond optional.

### Proposal Card

Numbered proposal with colored left border:
- I → `gold` border
- II → `ámbar` border
- III → `oliva` border
- IV → `borgoña` border

Title in SmithyXT Heavy uppercase, body in Inter.

## Do's and Don'ts

### Do
- Use SmithyXT for all headings and KPI values
- Use Inter for all body text and data labels
- Apply grunge texture overlay at 3% opacity
- Use ◆ diamond ornaments as dividers
- Use brand gradients for bar fills
- Maintain the ATTIC (raw) vs KELLER (clean) contrast
- Use warm brown-blacks (#1A1412, #2C2018) for dark mode — never pure black
- Use gold (#C9A94E) as the primary interactive accent
- Include the "K" backdrop letter on the portada slide

### Don't
- Never use SmithyXT below 14px — it becomes illegible noise
- Never use borgoña as a decorative color — it's for alerts only
- Never use pure black (#000) backgrounds — always warm brown-black
- Never use emojis in data presentations
- Never use flat single-color bar fills — always use gradients
- Never mix Old Press and Caveat on the same slide — pick one accent font
- Never remove the texture overlay — it's the brand's signature
- Never use Playfair Display for A&K branded materials — SmithyXT is the identity font