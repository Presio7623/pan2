---
name: Academic Compute & Lab Booking
colors:
  surface: '#f9f9ff'
  surface-dim: '#d3daea'
  surface-bright: '#f9f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f0f3ff'
  surface-container: '#e7eefe'
  surface-container-high: '#e2e8f8'
  surface-container-highest: '#dce2f3'
  on-surface: '#151c27'
  on-surface-variant: '#494454'
  inverse-surface: '#2a313d'
  inverse-on-surface: '#ebf1ff'
  outline: '#7b7486'
  outline-variant: '#cbc3d7'
  surface-tint: '#6d3bd7'
  primary: '#6b38d4'
  on-primary: '#ffffff'
  primary-container: '#8455ef'
  on-primary-container: '#fffbff'
  inverse-primary: '#d0bcff'
  secondary: '#6f46b9'
  on-secondary: '#ffffff'
  secondary-container: '#b188ff'
  on-secondary-container: '#44118d'
  tertiary: '#5d587a'
  on-tertiary: '#ffffff'
  tertiary-container: '#757093'
  on-tertiary-container: '#fffbff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e9ddff'
  primary-fixed-dim: '#d0bcff'
  on-primary-fixed: '#23005c'
  on-primary-fixed-variant: '#5516be'
  secondary-fixed: '#ebdcff'
  secondary-fixed-dim: '#d3bbff'
  on-secondary-fixed: '#260059'
  on-secondary-fixed-variant: '#572ba0'
  tertiary-fixed: '#e5deff'
  tertiary-fixed-dim: '#c8c2e9'
  on-tertiary-fixed: '#1b1735'
  on-tertiary-fixed-variant: '#474363'
  background: '#f9f9ff'
  on-background: '#151c27'
  surface-variant: '#dce2f3'
typography:
  headline-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-xl-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 30px
    fontWeight: '700'
    lineHeight: 38px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  title-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 24px
  body-lg:
    fontFamily: Geist
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Geist
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  body-sm:
    fontFamily: Geist
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
  label-md:
    fontFamily: Geist
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 18px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Geist
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.04em
  mono-code:
    fontFamily: Geist
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.05em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-md: 1.5rem
  gutter-lg: 2rem
  margin: 1rem
  margin-md: 2rem
  margin-lg: 3rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
---

## Brand & Style

This design system targets students, faculty researchers, and university lab managers navigating shared high-performance computing clusters, specialty hardware, and physical laboratory spaces. The brand balance sits strictly between institutional authority and frictionless, modern utility.

### Visual Aesthetic & Philosophy
The aesthetic is built upon **Clean Institutional Modernism with Tactile Ticket Metaphors**. It rejects the clunky, bureaucratic enterprise software common in higher education in favor of an airy, accessible interface characterized by:
- Soft lavender atmospheric foundations that reduce visual fatigue during marathon booking and study sessions.
- Clear physical references to digital access passes, laboratory clearance vouchers, and clean ticket stubs featuring subtle perforated dividers and sharp micro-matrix barcodes.
- High legibility and effortless scanning, prioritizing hardware specifications, status indicators, and booking windows.
- Tactile, quiet precision: zero decorative noise, intentional use of semantic tints, and structured containment grids that build confidence for institutional compliance and resource allocation.

## Colors

The palette establishes an academic environment that feels luminous and calm rather than sterile. Built around soft lavenders and anchored by deep structural purples, it meets strict WCAG AA contrast standards across all functional and informational tiers.

### Canvas & Surface Hierarchy
- **Base Canvas (`#F5F3FF`)**: Soft violet ambient ground providing a low-strain alternative to stark white.
- **Card & Surface Background (`#FFFFFF`)**: Pure crisp white surfaces elevating active modules and reservation blocks over the base canvas.
- **Surface Variant / Tinted Wells (`#EDE9FE`)**: Used for nested parameter tables, code blocks, and hardware specification trays.
- **Structural Borders (`#E0E7FF` / `#DDD6FE`)**: Delicate perimeters that define hierarchy without visual weight.

### Semantic & Hardware State Tints
Functional status accents use desaturated, pastel-supported tones paired with deep text tokens for optimal contrast:
- **Approved / Optimal (`#10B981` / Background: `#ECFDF5` / Border: `#A7F3D0`)**: Signifies confirmed bookings, operational labs, and equipment graded as "Excelente".
- **Pending Review / Virtual Queue (`#F59E0B` / Background: `#FFFBEB` / Border: `#FDE68A`)**: Indicates waiting queues, hardware graded as "Bueno", and pending advisor clearances.
- **Alert / Maintenance / Denied (`#EF4444` / Background: `#FEF2F2` / Border: `#FECACA`)**: Marks offline hardware, decommissioned benches, and equipment graded as "En revisión".

## Typography

The typographic hierarchy pairs **Plus Jakarta Sans** for prominent administrative titles and laboratory identifiers with **Geist** for technical specifications, dense tabular data, and operational forms.

### Type Roles & Pairing Logic
- **Plus Jakarta Sans** delivers a friendly yet disciplined institutional tone for top-level headers, equipment classifications, and room numbers.
- **Geist** delivers uncompromised neutrality and monospace-grade alignment for technical hardware configurations (e.g., GPU memory, core counts, IP/MAC assignments, reservation timestamps).
- Numerical metrics, booking slots, and ticket identity codes should lean into standard tabular figures (`tnum`) to ensure time slots and quota counters align cleanly across vertical card stacks.

## Layout & Spacing

The system is constructed on an adaptable 8px baseline rhythm (with a 4px half-step for micro-badges and indicators), enforcing rigid horizontal and vertical alignment across multi-lab booking calendars.

### Grid Architecture
- **Desktop (1024px and above)**: 12-column responsive fluid grid. Outer margins are set to `margin-lg` (48px) with internal column gutters at `gutter-lg` (32px). Used for dual-pane views: interactive lab floorplans on the primary canvas with sticky reservation dockets on the right.
- **Tablet (640px to 1023px)**: 8-column layout with `margin-md` (32px) and `gutter-md` (24px). Floorplans collapse into scrollable horizontal clusters, and equipment ticket cards become single-column blocks.
- **Mobile (< 640px)**: 4-column layout constrained by `margin` (16px) and `gutter` (16px). Cards span the full fluid width, optimizing vertical tap targets for on-the-go room access and instant check-in.

### Density and Rhythms
- Compact data displays (workstation specs, schedule matrices) maintain an internal padding of `space-sm` to `space-md`.
- Content containment cards (lab rooms, machine profiles, active passes) use `space-lg` padding to preserve an uncluttered, modern feel.

## Elevation & Depth

Visual hierarchy uses **tonal layer stacking combined with ultra-diffused atmospheric ambient shadows**. Heavy drop shadows are omitted to maintain an academic, minimalist look.

### Elevation Levels
1. **Level 0 (Base Canvas)**: Background color `#F5F3FF`. Flat, non-interactive ground.
2. **Level 1 (Structural Cards & Modules)**: Pure white `#FFFFFF` surface enclosed by a fine 1px border of `#E0E7FF`. Ambient shadow: `0px 2px 8px -2px rgba(76, 29, 149, 0.04)`.
3. **Level 2 (Interactive Floating States & Booking Slips)**: Active selection cards, popovers, and reservation vouchers. Ambient shadow: `0px 8px 24px -4px rgba(76, 29, 149, 0.08)`, with an active outline of `#DDD6FE`.
4. **Level 3 (Modal Overlays & QR Access Slips)**: High-priority check-in passes and confirmation sheets. Ambient shadow: `0px 16px 36px -6px rgba(76, 29, 149, 0.12)`, backed by an accessible scrim of `rgba(76, 29, 149, 0.25)` with a `backdrop-blur-sm` (4px).

### Perforated Depth Metaphor
For ticket cards and lab passes, depth is reinforced by a physical voucher silhouette: a crisp white card visually segmented by a delicate dashed divider (`#DDD6FE`), flanked by symmetrical inward circular notches on the left and right card boundaries.

## Shapes

The design system employs **Soft roundedness (`roundedness: 1`)**, translating to a baseline radius of 4px (`rounded-sm`), 8px (`rounded-md`), and 12px (`rounded-lg`). 

### Radius Allocation
- **Control Elements (Inputs, Buttons, Chips, Badges)**: 6px–8px radius, providing a crisp, technical feel that maintains button integrity in compact forms.
- **Cards & Data Modules**: 8px (`rounded-md`) to 12px (`rounded-lg`), establishing clear containment boundaries without excessive bubble-like curvature.
- **Interactive Vouchers / Access Passes**: 8px perimeter with masked circular edge cutouts (radius 10px) that align with dashed perforated guides.
- **Pills**: Reserved exclusively for hardware status indicators ("Excelente", "Bueno", "En revisión") and short categorical tags.

## Components

### Buttons
- **Primary**: Solid background `#8B5CF6`, text `#FFFFFF`, height 40px (desktop) / 44px (mobile), font `Geist Medium`, 8px radius. Hover state: `#7C3AED`. Active: `#6D28D9`. Focus-visible: 2px ring of `#DDD6FE` with 2px offset.
- **Secondary**: Surface `#FFFFFF`, border 1px solid `#DDD6FE`, text `#4C1D95`. Hover state: `#F5F3FF`.
- **Ghost / Tertiary**: Transparent surface, text `#4C1D95`. Hover state: `#EDE9FE`.
- **Destructive**: Pale red background `#FEF2F2`, border 1px solid `#FECACA`, text `#B91C1C`.

### Chips & Equipment Quality Badges
Hardware health tokens feature a compact pill shape (`rounded-full`), `space-xs` vertical padding, and `space-sm` horizontal padding:
- **Excelente**: Background `#ECFDF5`, border 1px solid `#A7F3D0`, text `#065F46`. Accompanied by a 6px solid emerald dot.
- **Bueno**: Background `#FFFBEB`, border 1px solid `#FDE68A`, text `#92400E`. Accompanied by a 6px solid amber dot.
- **En revisión**: Background `#FEF2F2`, border 1px solid `#FECACA`, text `#991B1B`. Accompanied by a 6px solid rose dot.

### Reservation Ticket Cards
The centerpiece for active reservations and room vouchers:
- **Structure**: Multi-zone card with an upper metadata section (Lab Name, Workstation ID, Time Slot) and a lower verification section (QR code, barcode string, pin pass).
- **Perforation**: Separated by an SVG or CSS dashed line: `border-t-2 border-dashed border-[#DDD6FE]`.
- **Notches**: Inset semi-circles on the left and right borders of the card along the dashed line, revealing the background `#F5F3FF` to complete the institutional lab-pass voucher metaphor.
- **Identity Barcode / QR**: High-contrast, minimal black-on-white SVG matrix enclosed within a subtle `#EDE9FE` framing border with micro-monospace verification numbers below (`mono-code`).

### Lists & Lab Schedule Grids
- **Rows**: Alternating subtle states or separated by hairline `#E0E7FF` dividers. 
- **Time Slot Selector**: Segmented horizontal pill groups. Available slots appear as `#FFFFFF` with `#E0E7FF` border; selected slots take `#8B5CF6` fill with white text; occupied slots are greyed out `#F3F4F6` with diagonal slash patterns.

### Form Inputs & Checkboxes
- **Text Inputs**: Height 40px, background `#FFFFFF`, border 1px solid `#E0E7FF`, text `#1F2937`, placeholder `#9CA3AF`. Hover: `#DDD6FE`. Focus: border `#8B5CF6` accompanied by an ambient purple ring glow (`0 0 0 3px rgba(139, 92, 246, 0.15)`).
- **Checkboxes & Radios**: 18px box with 4px border radius. Unchecked: `#FFFFFF` with `#D1D5DB` stroke. Checked: `#8B5CF6` background with sharp white verification checkmark.

### Workstation Cards
- White `#FFFFFF` card body with 1px `#E0E7FF` border.
- Header holds station naming (`title-md`) alongside the Equipment Quality Badge.
- Body displays specification specs in a 2-column key-value grid (e.g., "GPU: RTX 4090", "RAM: 64GB DDR5") rendered in `Geist` regular and medium weights.
- Footer features a direct-action "Reservar" micro-button or dynamic availability countdown badge.