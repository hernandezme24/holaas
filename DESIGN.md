---
name: Executive Slate
colors:
  surface: '#111317'
  surface-dim: '#111317'
  surface-bright: '#37393d'
  surface-container-lowest: '#0c0e12'
  surface-container-low: '#1a1c20'
  surface-container: '#1e2024'
  surface-container-high: '#282a2e'
  surface-container-highest: '#333539'
  on-surface: '#e2e2e7'
  on-surface-variant: '#c5c6cb'
  inverse-surface: '#e2e2e7'
  inverse-on-surface: '#2e3035'
  outline: '#8f9195'
  outline-variant: '#44474b'
  surface-tint: '#c2c7cf'
  primary: '#ccd0d9'
  on-primary: '#2b3137'
  primary-container: '#b0b5bd'
  on-primary-container: '#41474e'
  inverse-primary: '#595f66'
  secondary: '#c1c7d0'
  on-secondary: '#2b3138'
  secondary-container: '#41474f'
  on-secondary-container: '#b0b5bf'
  tertiary: '#dfcdbf'
  on-tertiary: '#392e24'
  tertiary-container: '#c3b2a4'
  on-tertiary-container: '#504439'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#dee3eb'
  primary-fixed-dim: '#c2c7cf'
  on-primary-fixed: '#171c22'
  on-primary-fixed-variant: '#42474e'
  secondary-fixed: '#dde3ed'
  secondary-fixed-dim: '#c1c7d0'
  on-secondary-fixed: '#161c23'
  on-secondary-fixed-variant: '#41474f'
  tertiary-fixed: '#f2dfd0'
  tertiary-fixed-dim: '#d5c3b5'
  on-tertiary-fixed: '#231a11'
  on-tertiary-fixed-variant: '#51453a'
  background: '#111317'
  on-background: '#e2e2e7'
  surface-variant: '#333539'
typography:
  display-lg:
    fontFamily: Manrope
    fontSize: 48px
    fontWeight: '600'
    lineHeight: 56px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Manrope
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Manrope
    fontSize: 36px
    fontWeight: '600'
    lineHeight: 44px
    letterSpacing: -0.015em
  headline-lg-mobile:
    fontFamily: Manrope
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 34px
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Manrope
    fontSize: 24px
    fontWeight: '500'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Manrope
    fontSize: 20px
    fontWeight: '500'
    lineHeight: 28px
    letterSpacing: -0.005em
  body-lg:
    fontFamily: DM Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: DM Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: DM Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-lg:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.02em
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.04em
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.06em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1.5rem
  margin: 3rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system is crafted for a high-stakes business consulting presentation interface. Its personality is authoritative, composed, analytical, and discreet—designed to command attention in boardrooms and executive briefings without visual noise.

**Target Audience & Emotional Response:**
Built for C-suite executives, board members, and strategic stakeholders, the interface evokes clarity, confidence, and intellectual rigor. Every visual decision prioritizes content legibility and executive focus, allowing complex financial models, strategic roadmaps, and market insights to take center stage.

**Design Style:**
The aesthetic merges **Minimalism** with **Subtle Glassmorphism**:
- **Minimalism:** Generous negative space, disciplined typographic hierarchy, and a restrained monochromatic lead-gray palette eliminate distractions.
- **Subtle Glassmorphism:** Translucent slate surfaces with soft backdrop blurs and hair-thin metallic borders create a modern, layered depth without heavy shadows or skeuomorphic clutter.

## Colors

The palette is anchored in lead gray (*gris plomo*) gradients and cool metallic neutrals, engineered for low-glare legibility in darkened presentation rooms and high-contrast clarity on modern displays.

- **Canvas & Background Gradients:** The primary presentation canvas uses a vertical or diagonal lead-gray gradient transitioning from `#2B2E33` to `#1A1C20`, providing subtle atmospheric depth rather than a flat black void.
- **Surface Tiers:** Elevated containers, slide cards, and sidebars step through slate grays `#3A3F47` and `#4A5058` to establish clear structural separation.
- **Typography & Accents:** Primary headings and key data points use crisp off-white (`#F4F5F7`), while secondary copy, axis labels, and metadata use light silver (`#B0B5BD`). Interactive highlights and active indicators rely on cool metallic silver tones rather than saturated hues.

## Typography

The typographic system pairs **Manrope** for geometric, authoritative headlines with **DM Sans** for clean, legible body copy and **Inter** for precise UI labels and tabular metadata.

- **Presentation Scaling:** Display and large headline roles (`display-lg`, `headline-lg`) are calibrated for widescreen projection and desktop viewing, with dedicated mobile alternatives (`display-lg-mobile`, `headline-lg-mobile`) to preserve hierarchy on smaller screens without overflow.
- **Numerical Precision:** Use tabular numerals (`font-variant-numeric: tabular-nums`) across all financial figures, KPIs, and table columns to ensure vertical alignment.
- **Uppercase Micro-Labels:** `label-sm` and `label-md` are intended for section kickers, slide numbers, and chart legends, utilizing subtle positive tracking (`0.04em` to `0.06em`) for executive polish.

## Layout & Spacing

The layout philosophy uses a **12-column fluid grid** with generous outer margins and breathing room, ensuring every slide and analytical view feels uncrowded and deliberate.

- **Desktop (>= 1200px):** 12-column fluid grid with `3rem` outer canvas margins and `1.5rem` column gutters. Content blocks typically span 4, 6, 8, or 12 columns, with ample negative space reserved around key takeaways.
- **Tablet (768px – 1199px):** Collapses to an 8-column fluid grid with `2rem` outer margins and `1.25rem` gutters. Multi-column comparison cards reflow into 2-column grids.
- **Mobile (< 768px):** Collapses to a 4-column fluid grid with `1.25rem` outer margins and `1rem` gutters. Side-by-side presentation modules stack vertically with `space-xl` separation.

## Elevation & Depth

Visual hierarchy is achieved through **tonal layers**, **subtle glassmorphism**, and **low-contrast outlines** rather than heavy drop shadows.

- **Tonal Layering:** The base canvas (`#1A1C20` to `#2B2E33`) sits at the lowest plane. Primary content cards and slide containers step up to `#3A3F47`, while interactive popovers and active controls step up to `#4A5058`.
- **Glassmorphism:** Floating toolbars, presenter notes, and modal overlays use translucent slate surfaces (`rgba(43, 46, 51, 0.72)`) paired with a `12px` backdrop blur (`backdrop-filter: blur(12px)`).
- **Low-Contrast Outlines:** All elevated surfaces are defined by `1px` ghost borders in cool metallic silver at low opacity (`rgba(176, 181, 189, 0.14)`), brightening slightly to `rgba(244, 245, 247, 0.28)` on hover or focus.

## Shapes

The design system adopts a **Soft** (`1`) roundedness language—architectural and disciplined, with just enough corner softening to feel contemporary and approachable.

- **Base (`0.25rem` / `4px`):** Applied to compact controls, checkboxes, badges, and inline tags.
- **Large (`0.5rem` / `8px`):** Applied to buttons, input fields, and standard content cards.
- **Extra-Large (`0.75rem` / `12px`):** Applied to primary presentation containers, modal dialogs, and executive summary panels.

## Components

All components adhere to the lead-gray tonal palette, soft `0.25rem`–`0.75rem` radii, and low-contrast metallic borders.

- **Buttons:**
  - *Primary:* Solid crisp off-white (`#F4F5F7`) background with deep lead-gray (`#1A1C20`) text and `0.5rem` radius. Hover shifts to `#B0B5BD`.
  - *Secondary:* Translucent slate (`#3A3F47`) with a `1px` metallic border (`rgba(176, 181, 189, 0.22)`) and `#F4F5F7` text.
  - *Ghost:* Transparent background with `#B0B5BD` text, revealing a `#3A3F47` fill on hover.
- **Chips & Tags:** Compact `0.25rem` radius pills in `#3A3F47` with `1px` ghost borders and `label-md` uppercase typography in `#B0B5BD`.
- **Lists:** Clean vertical stacks separated by `1px` horizontal dividers (`rgba(176, 181, 189, 0.1)`), generous `space-md` vertical padding, and subtle `#3A3F47` row highlights on hover.
- **Checkboxes & Radio Buttons:** `1px` `#B0B5BD` borders on `#1A1C20` backgrounds. Active states fill with `#F4F5F7` and display a `#1A1C20` checkmark or inner dot.
- **Input Fields:** `#1A1C20` or `#2B2E33` recessed backgrounds with `1px` `#4A5058` borders, `0.5rem` radius, `#F4F5F7` input text, and `#B0B5BD` placeholders. Focus states illuminate the border to `#F4F5F7`.
- **Cards:** `#3A3F47` (or frosted glass `rgba(58, 63, 71, 0.65)`) containers with `0.75rem` radius, `space-lg` internal padding, and `1px` `rgba(176, 181, 189, 0.14)` borders.
- **Presentation-Specific Components:**
  - *KPI Metric Tiles:* Oversized `display-lg` tabular numerals in `#F4F5F7` paired with `label-sm` uppercase descriptors in `#B0B5BD`.
  - *Slide Navigation Rail:* A minimal, frosted-glass floating dock at the bottom or side of the viewport with subtle step indicators and keyboard-shortcut hints.