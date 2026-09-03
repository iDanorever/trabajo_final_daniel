---
name: Voyage Intelligence
colors:
  surface: '#f8f9ff'
  surface-dim: '#cbdbf5'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff4ff'
  surface-container: '#e5eeff'
  surface-container-high: '#dce9ff'
  surface-container-highest: '#d3e4fe'
  on-surface: '#0b1c30'
  on-surface-variant: '#44474d'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#75777e'
  outline-variant: '#c5c6cd'
  surface-tint: '#515f78'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#0d1c32'
  on-primary-container: '#76849f'
  inverse-primary: '#b9c7e4'
  secondary: '#4059aa'
  on-secondary: '#ffffff'
  secondary-container: '#8fa7fe'
  on-secondary-container: '#1d3989'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#001e2f'
  on-tertiary-container: '#008cc7'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d6e3ff'
  primary-fixed-dim: '#b9c7e4'
  on-primary-fixed: '#0d1c32'
  on-primary-fixed-variant: '#39475f'
  secondary-fixed: '#dce1ff'
  secondary-fixed-dim: '#b6c4ff'
  on-secondary-fixed: '#00164e'
  on-secondary-fixed-variant: '#264191'
  tertiary-fixed: '#c9e6ff'
  tertiary-fixed-dim: '#89ceff'
  on-tertiary-fixed: '#001e2f'
  on-tertiary-fixed-variant: '#004c6e'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
typography:
  headline-xl:
    fontFamily: plusJakartaSans
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-xl-mobile:
    fontFamily: plusJakartaSans
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: plusJakartaSans
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.015em
  headline-lg-mobile:
    fontFamily: plusJakartaSans
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
    letterSpacing: -0.015em
  headline-md:
    fontFamily: plusJakartaSans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: plusJakartaSans
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 24px
    letterSpacing: 0em
  body-lg:
    fontFamily: plusJakartaSans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
  body-md:
    fontFamily: plusJakartaSans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
  body-sm:
    fontFamily: plusJakartaSans
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 18px
  label-md:
    fontFamily: plusJakartaSans
    fontSize: 13px
    fontWeight: '600'
    lineHeight: 18px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: plusJakartaSans
    fontSize: 11px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.04em
  data-metric:
    fontFamily: plusJakartaSans
    fontSize: 30px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.02em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter-xs: 0.25rem
  gutter-sm: 0.5rem
  gutter-md: 1rem
  gutter-lg: 1.5rem
  gutter-xl: 2rem
  margin-mobile: 1rem
  margin-tablet: 1.5rem
  margin-desktop: 2rem
  widget-gap: 1.5rem
---

## Brand & Style

This design system establishes a high-trust, editorial, and technologically sophisticated environment for high-performing travel advisors, agency owners, and corporate travel managers. The aesthetic balances corporate authority with the aspiration and energy of global travel.

The aesthetic blends **Modern Corporate** clarity with subtle **Ambient Tactility**. It relies on deep oceanic navies to command prestige and authority, anchored against bright, clean structural planes and accentuated by purposeful kinetic pops of cyan and warm coral. The interface feels executive, calm, and actionable—avoiding juvenile playfulness while actively resisting the sterile, dry feeling of legacy enterprise software.

## Colors

The palette is engineered to manage high-density travel data, itineraries, booking states, and analytics without visual fatigue.

- **Primary (`#0A192F`)**: Deep midnight navy. Used for core structural boundaries, high-priority navigation, dominant text tokens, and active selection anchors.
- **Secondary (`#1E3A8A`)**: Cobalt ocean navy. Applied to prominent interactive elements, chart primary series, secondary buttons, and active tabs.
- **Tertiary Accent (`#0EA5E9`)**: Sky cyan. Reserved for contextual actions, progress indicators, in-flight tracking, and actionable informational highlights.
- **Warm Accent (`#F97316`)**: Horizon coral. Denotes urgent trip updates, pending approvals, critical alerts, and revenue metrics.
- **Neutrals**:
  - `#0F172A`: Slate 900 for high-contrast headlines.
  - `#334155`: Slate 700 for secondary body and table metrics.
  - `#64748B`: Slate 500 for captions, hints, and structural icons.
  - `#CBD5E1`: Slate 300 for distinct divider rules.
  - `#E2E8F0`: Slate 200 for refined card borders and inactive containers.
  - `#F1F5F9`: Slate 100 for panel backgrounds, subtle pill tags, and table alternating rows.
  - `#F8FAFC`: Slate 50 for main canvas canvas background.
  - `#FFFFFF`: Pure White for elevated card surfaces, modals, and content blocks.

## Typography

The design system standardizes on **Plus Jakarta Sans** across all roles. Its geometric build coupled with open counters ensures exceptional readability across dense flight manifests, itinerary schedules, and analytical charts while retaining a sophisticated European luxury and contemporary hospitality feel.

- Data metric representations (`data-metric`) must always feature tabular figures (`font-variant-numeric: tabular-nums`) to prevent jitter across changing rates, currencies, and real-time flight changes.
- Uppercase styling is strictly reserved for `label-sm` when used as overline category markers, status tags, or flight IATA codes (e.g., `JFK`, `LHR`, `HND`).

## Layout & Spacing

The layout model uses a responsive **Fluid Grid** grounded on an 8pt architectural rhythm, with a supplementary 4pt sub-grid for dense micro-layouts (badges, table rows, and tooltips).

- **Desktop (>= 1280px)**: 12-column grid, 24px (`1.5rem`) gutters, 32px (`2rem`) outer margin. Maximum viewport content bound is 1600px.
- **Tablet (768px - 1279px)**: 8-column grid, 16px (`1rem`) gutters, 24px (`1.5rem`) outer margin. Dashboard widgets collapse from 4-across to 2-across.
- **Mobile (< 768px)**: 4-column fluid layout, 12px gutters, 16px (`1rem`) outer margin. Metric cards convert to a horizontal edge-to-edge scroll snapping carousel, and multi-column tables collapse into vertical card summaries.

Dashboard shell structure mandates a persistent collapsible left navigation rail (260px expanded, 72px condensed) on desktop, transitioning to a bottom action sheet or off-canvas drawer on mobile.

## Elevation & Depth

Visual hierarchy uses **ambient tinted shadows** combined with fine **low-contrast borders**, ensuring cards read as clean physical planes floating over the slate canvas background (`#F8FAFC`).

- **Surface Neutral**: Pure White (`#FFFFFF`) with a 1px solid border in `#E2E8F0`.
- **Level 1 (Card & Metric Containers)**: `box-shadow: 0 1px 3px rgba(10, 25, 47, 0.04), 0 4px 12px rgba(10, 25, 47, 0.03);` with `border: 1px solid #E2E8F0`.
- **Level 2 (Active States, Dropdowns & Popovers)**: `box-shadow: 0 4px 6px -1px rgba(10, 25, 47, 0.05), 0 10px 24px -3px rgba(10, 25, 47, 0.08);` with `border: 1px solid #CBD5E1`.
- **Level 3 (Modals & Itinerary Drawers)**: `box-shadow: 0 20px 30px -5px rgba(10, 25, 47, 0.12), 0 8px 10px -6px rgba(10, 25, 47, 0.04);` with a subtle backdrop blur overlay (`rgba(10, 25, 47, 0.45)` with `backdrop-filter: blur(4px)`).

## Shapes

The design system implements curved geometries to communicate approachability and modern elegance, balanced with structured borders for professional discipline.

- **Primary Cards & Dashboard Widgets**: Standardized on `rounded-2xl` (16px / 1rem radius) to frame key datasets and visual charts.
- **Inner Containers, Inputs, Buttons, & Table Headers**: Set to `rounded-xl` (12px / 0.75rem radius).
- **Badges, Tags, & Status Pills**: Fully rounded (`rounded-full` / 9999px) for clean pill silhouettes.
- **Form Selectors & Checkboxes**: `rounded-md` (6px radius) to maintain structural density.

## Components

### Buttons
- **Primary**: Solid Deep Navy (`#0A192F`) fill with white text, `rounded-xl` padding (`10px 20px`), font-weight 600. Hover transitions to `#1E3A8A` with Level 1 elevation.
- **Secondary**: Slate border (`#E2E8F0`), surface white, text `#0A192F`. Hover introduces `#F1F5F9` background.
- **Accent**: Solid Cyan (`#0EA5E9`) or Warm Coral (`#F97316`) for primary conversion hooks (e.g., "Create Booking", "Urgent Re-route").

### Metric & KPI Cards
- Housed in `rounded-2xl` containers with Level 1 elevation.
- Top row: Subdued uppercase label (`label-sm`) paired with a contextual micro-icon inside a light pastel circular container (e.g., `#0EA5E9` at 10% opacity).
- Core value: Displayed using `data-metric` in `#0A192F`.
- Footer: Trend indicator badge displaying green/red pill with subtle arrow icon, plus time comparison subtitle in `#64748B`.

### Data Tables
- Integrated within `rounded-2xl` structural panels with overflow-x scrolling on mobile.
- Headers: `#F8FAFC` fill, `label-sm` uppercase text in `#64748B`, height 44px.
- Rows: Clean 56px height, alternating hover highlight (`#F1F5F9`), bottom border 1px solid `#E2E8F0`.
- Data Cells: Feature customer avatar, flight itinerary status pills, and monospaced PNR/booking codes.

### Status Chips & Badges
- Pill-shaped (`rounded-full`), `label-sm` typography, padding `4px 10px`.
- **Confirmed / Active**: Background `#ECFDF5`, text `#059669`.
- **In-Transit**: Background `#E0F2FE`, text `#0284C7`.
- **Attention / Pending**: Background `#FFF7ED`, text `#EA580C`.
- **Canceled / Alert**: Background `#FEF2F2`, text `#DC2626`.

### Form Inputs & Search Filters
- Container: 44px height, `rounded-xl`, border 1px solid `#CBD5E1`, background `#FFFFFF`.
- Focus state: Border transitions to `#0EA5E9`, backed by a 3px soft focus ring (`rgba(14, 165, 233, 0.2)`).
- Prefix: Integrated travel-centric icons (calendar, globe, airport locator pin) in `#64748B`.

### Interactive Charts & Visuals
- Smooth cubic spline curves with soft gradient fills fading down to 0% opacity.
- Tooltips are dark `#0A192F` surfaces with pure white typography, Level 2 elevation, and `rounded-lg` geometry.