---
version: "2.1"
name: Attick & Keller Brand
description: "Dark premium grunge — the dual identity of ATTIC (raw, distressed) and KELLER (clean, refined). Built from the actual A&K logos and flyers: deep black backgrounds, warm cream text, rust/terracotta accents, and golden amber highlights. SmithyXT typography, grunge textures, and the signature K backdrop."
colors:
  # — Logo colors (from actual logo files, pixel analysis) —
  # Logo 1 (K backdrop, white bg): text slate-blue #34495E, K shape rust #9A4335
  # Logo 2 (two-tone, white bg): ATTIC & KELLER slate-blue #34495E, & rust #A65D4A
  # Logo 3 (black on white): black text #000000
  # Logo 4 (white on black): white text #FFFFFF
  slate-blue: "#34495E"
  rust-red: "#A0522D"
  brick-red: "#B24D42"
  cream-logo: "#F7F3E9"
  parchment: "#F2EBE1"
  # — Flyer palette (from 4 production flyers, pixel analysis) —
  flyer-black: "#0D1015"
  flyer-card: "#161B22"
  flyer-cream: "#F4ECE4"
  flyer-rust: "#8C4434"
  flyer-amber: "#E48C04"
  flyer-gold: "#FCCC04"
  flyer-steel: "#3C4C5C"
  flyer-muted: "#9BA8B7"
  # — Dark theme (from flyers, primary palette) —
  night: "#0D1015"
  night-card: "#161B22"
  night-input: "#1E2733"
  night-border: "#2D3748"
  night-text: "#F4ECE4"
  night-muted: "#9BA8B7"
  # — Accents (from flyers) —
  rust: "#8C4434"
  rust-light: "#A05840"
  amber: "#E48C04"
  amber-light: "#F0A030"
  gold: "#FCCC04"
  gold-dim: "#E48C04"
  borgona: "#B24D42"
  oliva: "#5C7A4D"
  # — Muted brand (from story-tipo flyer) —
  navy: "#2C435B"
  navy-light: "#3C5A7A"
  foxing: "#A67B5B"
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
    boxShadow: "0 2px 12px rgba(0,0,0,0.4)"
    border: "1px solid rgba(140,68,52,0.2)"
  card-hover:
    boxShadow: "0 8px 32px rgba(0,0,0,0.6)"
  kpi-hero:
    boxShadow: "0 4px 20px rgba(228,140,4,0.12)"
    border: "1px solid rgba(228,140,4,0.25)"
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
    color: "{colors.amber}"
    letterSpacing: "0.05em"
    textTransform: uppercase
    borderBottom: "2px solid {colors.rust}"
    paddingBottom: "8px"
  slide-subtitle:
    fontFamily: Caveat
    fontSize: "0.875rem"
    color: "{colors.night-muted}"
  kpi-card:
    backgroundColor: "{colors.night-card}"
    borderRadius: "{rounded.card}"
    padding: "12px"
    border: "1px solid rgba(140,68,52,0.2)"
    boxShadow: "{elevation.card.boxShadow}"
  kpi-card-hover:
    transform: "translateY(-2px)"
    boxShadow: "{elevation.card-hover.boxShadow}"
  kpi-value-amber:
    color: "{colors.amber}"
    fontFamily: SmithyXT
    fontWeight: "900"
    fontSize: "2rem"
  kpi-value-rust:
    color: "{colors.rust-light}"
  kpi-value-green:
    color: "{colors.oliva}"
  bar-fill:
    background: "linear-gradient(90deg, {colors.rust}, {colors.amber})"
  bar-fill-gold:
    background: "linear-gradient(90deg, {colors.amber}, {colors.gold})"
  badge:
    borderRadius: "{rounded.sm}"
    padding: "2px 8px"
    fontWeight: "600"
    fontSize: "0.625rem"
    letterSpacing: "0.05em"
    textTransform: uppercase
  badge-danger:
    backgroundColor: "rgba(178,77,66,0.15)"
    color: "{colors.borgona}"
  badge-success:
    backgroundColor: "rgba(92,122,77,0.15)"
    color: "#7BA86A"
  badge-warning:
    backgroundColor: "rgba(228,140,4,0.15)"
    color: "{colors.amber-light}"
  badge-info:
    backgroundColor: "rgba(60,76,92,0.2)"
    color: "{colors.night-muted}"
  divider:
    height: "1px"
    background: "linear-gradient(90deg, transparent, {colors.night-border}, transparent)"
    margin: "12px 0"
  ornament:
    color: "{colors.amber}"
    fontSize: "0.625rem"
    letterSpacing: "0.3em"
  texture-overlay:
    opacity: "0.04"
    pointerEvents: none
    mixBlendMode: overlay
---

## Overview

**Attick & Keller** is a restaurant and bar brand defined by dual identity: **ATTIC** (raw, distressed, vintage) vs **KELLER** (clean, refined, modern). This tension — rough vs smooth, old vs new — is the core of every visual decision.

The brand draws from vintage industrial signage, distressed print ephemera, and the warmth of aged leather and rusted metal. The visual identity is **dark premium**: deep black backgrounds, warm cream text, rust/terracotta and amber accents, SmithyXT headings, and grunge texture overlays that make data feel like it belongs in a leather-bound ledger, not a SaaS dashboard.

## Source of Truth

Colors are extracted from **4 actual A&K production flyers** and **4 logo variants** via pixel analysis:

### Logo Colors (from ak_brand_kit.json + pixel analysis)

| Logo | Background | Text Color | Accent Color | Notes |
|------|-----------|------------|--------------|-------|
| Logo 1 (K backdrop) | White `#FFFFFF` | Slate Blue `#34495E` | Rust `#9A4335` (K shape) | Full vertical logo with K |
| Logo 2 (two-tone) | White `#FFFFFF` | Slate Blue `#4A6274` | Rust `#A65D4A` (& only) | ATTIC grunge vs KELLER clean |
| Logo 3 (black on white) | White `#FFFFFF` | Black `#000000` | — | Monochrome, grunge vs clean |
| Logo 4 (white on black) | Black `#000000` | White `#FFFFFF` | — | Dark variant, inverted |

### Flyer Colors (from 4 production flyers)

| Flyer | Background | Primary Accent | Secondary Accent |
|-------|-----------|---------------|-----------------|
| Flyer 1 | `#0D1015` black | `#8C4434` rust/terracotta | `#FCCC04` gold |
| Flyer 2 | `#090C11` black | `#84443C` rust | `#3C4C5C` steel blue |
| Flyer 3 | `#090C11` black | `#E48C04` amber (dominant) | `#B07050` warm brown |
| Flyer 4 | `#0B0E13` black | `#8C4434` rust | `#FCDC04` gold |

All 4 flyers share: **deep black background**, **warm cream text**, and **rust/terracotta** as primary accent. Gold/amber appears in 3 of 4 as secondary accent.

## Colors

### Primary Palette (from flyers)

- **Flyer Black `#0D1015`**: The deep blue-black base from all 4 flyers. Not pure black — slightly cool, like night sky with a hint of navy. This is the foundation.
- **Flyer Cream `#F4ECE4`**: Warm off-white for all text. Not pure white — cream, like aged parchment. Easy on the eyes against the dark background.
- **Rust `#8C4434`**: The primary accent from the flyers. Terracotta, warm leather, aged brick. The K-backdrop color darkened for dark backgrounds. Used for headings, borders, bar fills, the K letter.
- **Amber `#E48C04`**: The golden accent from Flyer 3. Warm amber, firelight. Used for KPI values, interactive highlights, section labels.
- **Gold `#FCCC04`**: Bright gold from Flyers 1 & 4. For emphasis, sparkle, the "candlelight on brass" effect. Used sparingly for hero numbers and decorative accents.

### Secondary Palette

- **Flyer Card `#161B22`**: Elevated surfaces. Slightly lighter than the base black, with a cool undertone. Cards, panels, elevated sections.
- **Flyer Steel `#3C4C5C`**: Cool blue-steel from Flyer 2. Secondary text, muted labels, info badges. Like the slate-blue from the logos, darkened for dark backgrounds.
- **Flyer Muted `#9BA8B7`**: Muted blue-grey for secondary text and context. Between steel and cream.
- **Borgoña `#B24D42`**: Brick red from the grunge texture. Danger, alerts, negative metrics. More saturated than rust.
- **Oliva `#5C7A4D`**: Aged olive green. Success, positive metrics.

### Logo Colors (context-dependent)

**Dark theme (primary — flyers, app, dashboards):**
- Logo text: **Flyer Cream `#F4ECE4`** (cal) or **White `#FFFFFF`** — matches Logo 4 (white on black)
- Logo accent (K shape, &): **Rust `#8C4434`** or **Amber `#E48C04`**

**Light theme (app light mode, emails, print):**
- Logo text: **Slate Blue `#34495E`** — matches Logos 1 & 2
- Logo accent (K shape, &): **Rust `#9A4335`** (K backdrop) or **Ampersand Rust `#A65D4A`**
- Background: **Cream `#F7F3E9`** (primary bg) or **White `#FFFFFF`** (cards)
- Text primary: **Slate Blue `#34495E`**
- Text secondary: **Slate Blue-Grey `#4A6274`** (Logo 2)
- Text muted: **`#6B7B8D`**
- Borders: **Rust `rgba(154,67,53,0.2)`**
- Shadows: **Slate-blue `rgba(52,73,94,0.08)`**
- Danger: **Brick Red `#B2473D`** (mancha roja)
- Accent: **Rust `#9A4335`** (K backdrop from Logo 1)

**Never mix**: Do not use slate-blue (#34495E) in dark theme, or flyer-cream (#F4ECE4) in light theme logos.

### CSS Variable Mapping (light ↔ dark)

| Variable | Light (logo palette) | Dark (flyer palette) |
|----------|----------------------|---------------------|
| `--bg-primary` | `#F7F3E9` cream | `#0D1015` night |
| `--bg-card` | `#FFFFFF` white | `#161B22` night-card |
| `--bg-input` | `#F2EBE1` parchment | `#1E2733` night-input |
| `--text-primary` | `#34495E` slate-blue | `#F4ECE4` cream |
| `--text-secondary` | `#4A6274` slate-grey | `#9BA8B7` muted |
| `--text-muted` | `#6B7B8D` | `#6B7B8D` |
| `--accent-primary` | `#9A4335` logo rust | `#E48C04` amber |
| `--color-accent` | `#9A4335` logo rust | `#E48C04` amber |
| `--color-danger` | `#B2473D` brick red | `#EF5350` |
| `--border-default` | `rgba(154,67,53,0.2)` | `#2D3748` |
| `--shadow-sm` | `rgba(52,73,94,0.08)` | `rgba(0,0,0,0.4)` |
| `--color-ak-madera` | `#34495E` slate-blue | `#9BA8B7` steel |
| `--color-ak-cal` | `#34495E` slate-blue | `#F4ECE4` cream |
| `--color-ak-borgona` | `#9A4335` logo rust | `#8C4434` flyer rust |
| `--color-ak-carbon` | `#34495E` slate-blue | `#0D1015` night |
| `--color-ak-ladrillo` | `#A65D4A` ampersand rust | `#A0522D` |

### Accent Relationships

- **Rust** is the **primary accent** — headings, borders, the K letter, bar fill start, proposal borders
- **Amber** is the **secondary accent** — KPI values, section labels, interactive highlights, bar fill end
- **Gold** is **emphasis only** — hero numbers, sparkle accents, the ◆ ornament
- **Borgoña** is for **danger/negative** — alerts, gaps, losses. Never decorative.
- **Oliva** is for **success/positive** — growth, good metrics. Never decorative.

## Typography

### The SmithyXT System

SmithyXT is the **identity font family**. It's a condensed sans-serif with grunge variants:

- **SmithyXT-VeryHeavy (900)**: Hero KPI values, portada titles, slide numbers. The heaviest, most impactful weight.
- **SmithyXT-Heavy (700)**: Slide titles, section headings, badge labels. The workhorse.
- **SmithyXT-Faded**: The ATTIC voice — distressed, weathered. Used sparingly for decorative labels, era stamps, or the word "ATTIC" when contrast with clean "KELLER" is needed.
- **Old Press**: Distressed serif. For decorative accent text only — "est. 2024", location stamps. Never for data labels or body text.

### Body and Accent Fonts

- **Inter**: All data, body copy, small labels, numbers. Clean and legible at all sizes.
- **Caveat**: Handwritten accent. Slide subtitles, casual callouts, "datos con carácter" tagline.

### Typography Rules

1. **Never use SmithyXT below 14px** — the grunge detail becomes noise at small sizes
2. **Headings are always SmithyXT Heavy, uppercase, AMBER, with letter-spacing 0.05em**
3. **KPI values are always SmithyXT VeryHeavy, large (2rem+), AMBER or white**
4. **Body text is always Inter** — never SmithyXT or Old Press for paragraphs
5. **The ATTIC/KELLER contrast**: When both words appear together, ATTIC uses Faded (opacity 0.6, wider letter-spacing), KELLER uses Heavy/VeryHeavy — this is the brand's signature dual identity
6. **Limit to 3 fonts per slide**: SmithyXT (display) + Inter (body) + Caveat or Old Press (accent, pick one)
7. **Logo text**: SmithyXT Heavy or VeryHeavy. Dark theme = cream/white. Light theme = slate-blue.

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

Cards use warm shadows on the dark background:

- **Default card**: `0 2px 12px rgba(0,0,0,0.4)` with `1px solid rgba(140,68,52,0.2)` border
- **Hover**: `0 8px 32px rgba(0,0,0,0.6)` with `translateY(-2px)`
- **KPI hero**: `0 4px 20px rgba(228,140,4,0.12)` — amber glow for important numbers

### Texture Overlays

The grunge texture from the brand assets is applied as a **4% opacity overlay** across the entire slide deck. This is critical for the A&K identity — it makes the dark background feel like worn leather, not a flat screen.

```css
.texture-overlay {
  position: fixed;
  inset: 0;
  opacity: 0.04;
  pointer-events: none;
  mix-blend-mode: overlay;
  background: url("data:image/svg+xml,...") repeat;
}
```

## Shapes & Ornaments

- **Border radius**: Cards use `10px`, badges `4px`, buttons `8px`
- **Ornaments**: The ◆ diamond separator is the brand's signature divider. Used between title and content, between sections, and in the portada. Color: GOLD `#FCCC04`.
- **Corner ornaments**: Decorative corner brackets `┌ ┐ └ ┘` in amber at `opacity: 0.3` on key cards
- **Bar fills**: Always gradients, never flat colors. Rust-to-amber uses `linear-gradient(90deg, #8C4434, #E48C04)`. Gold uses `linear-gradient(90deg, #E48C04, #FCCC04)`.
- **Dividers**: `1px solid` with `linear-gradient(90deg, transparent, #2D3748, transparent)` — mimics the subtle stitching lines in the brand flyer

## Components

### Slide

Deep black background with warm cream text. Each slide has a numbered section label (e.g., "01 — ESTRUCTURA") in SmithyXT Heavy uppercase AMBER, followed by the title in larger SmithyXT, then a Caveat subtitle.

### KPI Card

Elevated card with subtle rust border. Label in small uppercase Inter (0.625rem, 0.1em tracking). Value in SmithyXT VeryHeavy 2rem. Context text in muted Inter below.

Variants:
- **Amber value**: Default for positive metrics and main KPIs
- **Rust value**: Secondary accent, headings, borders
- **Oliva value**: Success metrics

### Bar Chart

Horizontal bars with rounded ends. Labels in Inter 0.75rem, values right-aligned. Fill uses brand gradients (rust → amber). Track background is `rgba(140,68,52,0.08)`.

### Heatmap Cell

Grid cell with interpolated color between three stops:
- Cold (low): `#161B22` (flyer-card)
- Medium: `#E48C04` (amber)
- Hot (high): `#B24D42` (borgoña)

Cell size: `min 28px`, border-radius `3px`, gap `2px`.

### Badge

Small pill-shaped labels for status indicators:
- **Danger** (borgoña bg, borgoña text): PICO, INEFICIENTE, problems
- **Success** (oliva bg, oliva-light text): Good metrics
- **Warning** (amber bg, amber-light text): Gaps, caution
- **Info** (steel bg, muted text): Neutral labels

### Divider

Gradient line: `linear-gradient(90deg, transparent, #2D3748, transparent)` — subtle separator. Centered ◆ diamond optional in GOLD.

### Proposal Card

Numbered proposal with colored left border:
- I → `amber` border
- II → `rust` border
- III → `oliva` border
- IV → `borgoña` border

Title in SmithyXT Heavy uppercase, body in Inter.

## Do's and Don'ts

### Do
- Use SmithyXT for all headings and KPI values
- Use Inter for all body text and data labels
- Apply grunge texture overlay at 4% opacity
- Use ◆ diamond ornaments in GOLD as dividers
- Use brand gradients for bar fills (rust → amber)
- Maintain the ATTIC (raw/faded) vs KELLER (clean/bold) contrast
- Use deep black (#0D1015) for backgrounds — not pure black (#000), not brown-black
- Use RUST (#8C4434) as primary accent for headings and borders
- Use AMBER (#E48C04) for KPI values and section labels
- Use GOLD (#FCCC04) sparingly for hero numbers and ornaments
- Include the "K" backdrop letter in RUST on the portada slide
- Use cream (#F4ECE4) or white (#FFFFFF) for logo text in dark theme
- Use slate-blue (#34495E) for logo text in light theme only
- **HOME DARK-FIRST**: The home page (`page.tsx`) is ALWAYS dark — wrapped in `<div className="dark">`. Logo, hero, navbar, and footer use night/cream/rust palette unconditionally. No light-mode fallbacks on home.
- Logo dual identity: ATTIC = SmithyXT Heavy (700) at opacity 0.6 + wider letter-spacing (0.08em). KELLER = SmithyXT VeryHeavy (900) full opacity. ◆ diamond in gold (#FCCC04) between them.

### Don't
- Never use SmithyXT below 14px — it becomes illegible noise
- Never use borgoña as a decorative color — it's for danger/alerts only
- Never use pure black (#000) backgrounds — always #0D1015
- Never use emojis in data presentations
- Never use flat single-color bar fills — always use gradients
- Never mix Old Press and Caveat on the same slide — pick one accent font
- Never remove the texture overlay — it's the brand's signature
- Never use Playfair Display for A&K branded materials — SmithyXT is the identity font
- Never use GOLD (#FCCC04) as primary accent — it's for emphasis/ornaments only, not headings
- Never use cream-logo (#F7F3E9) or slate-blue (#34495E) in the dark flyer theme — those are light-theme/logo colors
- Never use DM Sans — Inter is the body font, SmithyXT is the identity font