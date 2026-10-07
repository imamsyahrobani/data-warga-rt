---
name: Warga Harmoni
colors:
  surface: '#fff9ed'
  surface-dim: '#e2dac1'
  surface-bright: '#fff9ed'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#fcf3d9'
  surface-container: '#f6eed4'
  surface-container-high: '#f1e8ce'
  surface-container-highest: '#ebe2c9'
  on-surface: '#1f1c0c'
  on-surface-variant: '#444650'
  inverse-surface: '#35301f'
  inverse-on-surface: '#f9f0d7'
  outline: '#757781'
  outline-variant: '#c4c6d1'
  surface-tint: '#435c9b'
  primary: '#294381'
  on-primary: '#ffffff'
  primary-container: '#425b9a'
  on-primary-container: '#c9d6ff'
  inverse-primary: '#b2c5ff'
  secondary: '#00658c'
  on-secondary: '#ffffff'
  secondary-container: '#88d2ff'
  on-secondary-container: '#005b7e'
  tertiary: '#792a3a'
  on-tertiary: '#ffffff'
  tertiary-container: '#974151'
  on-tertiary-container: '#ffc9cf'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dae2ff'
  primary-fixed-dim: '#b2c5ff'
  on-primary-fixed: '#001848'
  on-primary-fixed-variant: '#2a4482'
  secondary-fixed: '#c5e7ff'
  secondary-fixed-dim: '#85cffc'
  on-secondary-fixed: '#001e2d'
  on-secondary-fixed-variant: '#004c6a'
  tertiary-fixed: '#ffd9dd'
  tertiary-fixed-dim: '#ffb2bc'
  on-tertiary-fixed: '#400012'
  on-tertiary-fixed-variant: '#7a2b3b'
  background: '#fff9ed'
  on-background: '#1f1c0c'
  surface-variant: '#ebe2c9'
typography:
  headline-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 40px
    fontWeight: '800'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-xl-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 30px
    fontWeight: '800'
    lineHeight: 38px
    letterSpacing: -0.015em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.015em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '700'
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
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
  label-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 15px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 13px
    fontWeight: '600'
    lineHeight: 18px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 11px
    fontWeight: '700'
    lineHeight: 16px
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

This design system serves a modern Indonesian neighborhood administrative platform (*Rukun Tetangga / RT*). It bridges formal civic administration with the warm, collectivist spirit of *gotong royong* (mutual cooperation). 

### Personality & Demographics
- **Target Audience:** Multi-generational residents, neighborhood unit administrators (*Pengurus RT/RW*), local treasurers, and security coordinators ranging from tech-savvy young renters to elderly long-term homeowners.
- **Emotional Resonance:** Trustworthy, transparent, inviting, and secure. The interface eliminates bureaucratic coldness while preserving municipal integrity, providing reassuring civic utility alongside quick social cohesion.

### Design Movement: Warm Institutional Modernism
The visual system blends clean Nordic layout discipline with warm, hospitable Indonesian hospitality accents:
- **Clean Structural Grids:** High clarity, legible data lists, and organized administrative modules inspired by modern Scandinavian civic portals.
- **Warm Tactile Grounding:** Crisp white surfaces supported by soft cream foundations (`#FFF6DC`) prevent clinical sterility.
- **Vibrant Accent Signaling:** Crisp cyan (`#76C0EC`) for navigational freshness and vivid coral (`#FF95A5`) strictly reserved for urgent neighborhood alerts (*Pos Ronda*, security dispatches, and emergency broadcast banners).

## Colors

The palette establishes an accessible, high-contrast civic hierarchy that balances official record-keeping with community warmth.

### Roles & Application

- **Primary (`#425B9A` - Deep Slate Blue):** Anchors official hierarchy. Used for structural headers, primary action buttons, key navigation bars, high-level administrative stats, and core brand elements. Guarantees WCAG AAA compliance against white and warm ivory backgrounds.
- **Secondary (`#76C0EC` - Sky Cyan):** Provides interactive levity. Used for active tabs, selected states, informative indicators, badge backgrounds, and link accents. Must pair with `#0F172A` or `#425B9A` text for readability.
- **Tertiary / Alert (`#FF95A5` - Coral Pink):** High-priority emotional signal. Reserved exclusively for citizen panic buttons (*Tombol Darurat*), overdue dues warnings, urgent neighborhood announcements, and critical status badges.
- **Neutral Canvas (`#FFF6DC` - Soft Ivory Cream):** Serves as an atmospheric backdrop tint. Softens the harshness of sterile screens, used on page-level backdrops, informational alert boxes, and secondary summary cards.
- **Functional Neutrals:**
  - Base White (`#FFFFFF`): Surface cards, form inputs, and modal canvases.
  - Soft Slate (`#F8FAFC`): Table alternates and interactive hover states.
  - Border Slate (`#E2E8F0`): Dividers, subtle borders, and structural contours.
  - Body Text Slate (`#0F172A`): High-legibility typography for administrative documents, logs, and family cards (*Kartu Keluarga*).
  - Secondary Text (`#475569`): Metadata, timestamps, and descriptive hints.

## Typography

The typography leverages **Plus Jakarta Sans** across all roles. Created in Indonesia, its geometric clarity and contemporary humanist curves provide the ideal balance between formal public administration and welcoming community communication.

### Typesetting Guidelines
- **Headlines:** Use dense letter-spacing (`-0.01em` to `-0.02em`) and heavy weights (700/800) for page titles and ledger statistics to establish confident authority.
- **Body Text:** Standard weight is 400 with a generous line-height multiplier (~1.55 - 1.6) to ensure optimal legibility for long-form meeting notes (*Notulensi Musyawarah*), community bylaws (*Tata Tertib*), and financial reports.
- **Numerical & Tabular Data:** Financial dues balances (*Iuran Kas RT*), population counters, and citizen IDs (*NIK/No. KK*) require font features `font-variant-numeric: tabular-nums` to maintain vertical alignment inside audit tables.
- **Labels & Badges:** Micro-labels utilize weight 700 with uppercase styling and slight tracking (`letterSpacing: 0.04em`) to ensure legibility across status chips.

## Layout & Spacing

The design system is constructed on a 4px/8px incremental grid, emphasizing modular clarity and fast visual scanning.

### Layout Philosophy
- **Fluid Multi-tier Grid:** A 12-column fluid grid for desktop administrative dashboards (max container width: `1280px`), adapting to an 8-column format on tablets, and a 4-column layout on mobile devices.
- **Canvas Composition:** The main viewport background defaults to the warm tint `#FFF6DC` at a subtle opacity or direct wash, framed by pure white `#FFFFFF` cards and surfaces to prevent visual fatigue.
- **Form Factors & Breakpoints:**
  - **Desktop (1024px+):** Fixed side-navigation rail (260px width) combined with a flexible 12-column content space. Gutters are fixed at `1.5rem` (`24px`).
  - **Tablet (768px - 1023px):** Collapsible navigation drawer; 8 columns with `1.25rem` gutters.
  - **Mobile (< 768px):** Single-column stack with bottom app navigation bar. Gutters tighten to `1rem` (`16px`) and screen margins to `1rem` to maximize screen real estate for quick resident actions.

## Elevation & Depth

Visual hierarchy uses a hybrid approach: **subtle tonal layering combined with tinted ambient drop shadows** that reflect natural tropical light rather than stark black shadows.

### Elevation Levels

- **Level 0 (Flat / Canvas):** Applied to the main screen background (`#FFF6DC` or `#F8FAFC`). No shadow.
- **Level 1 (Subtle Inset / Card):** Standard citizen cards, ledger rows, and module containers (`#FFFFFF`).
  - `box-shadow: 0 1px 3px 0 rgba(66, 91, 154, 0.06), 0 1px 2px -1px rgba(66, 91, 154, 0.04);`
  - Border: 1px solid `#E2E8F0`.
- **Level 2 (Interactive Floating / Raised):** Hovered cards, quick action tiles, and dropdown panels.
  - `box-shadow: 0 4px 12px -2px rgba(66, 91, 154, 0.08), 0 2px 6px -2px rgba(66, 91, 154, 0.05);`
- **Level 3 (Sticky Navigation / Sheets):** Fixed headers, sticky bottom action sheets, and side drawers.
  - `box-shadow: 0 10px 24px -4px rgba(66, 91, 154, 0.12), 0 4px 8px -3px rgba(66, 91, 154, 0.06);`
- **Level 4 (Emergency Modal / Critical Alert Overlays):** Panic broadcasts, urgent confirmation dialogs, and citizen verification popups.
  - `box-shadow: 0 20px 32px -6px rgba(15, 23, 42, 0.18), 0 8px 16px -4px rgba(255, 149, 165, 0.25);`

## Shapes

The system implements `roundedness: 2` (Standard Rounded), establishing a friendly, approachable aesthetic that softens administrative rigidity.

### Corner Radii Guidelines
- **Base (0.5rem / 8px):** Checkboxes, form text inputs, small badges, status tags, and action buttons.
- **Rounded-LG (1rem / 16px):** Content cards, profile summaries, citizen ledger containers, and filter bars.
- **Rounded-XL (1.5rem / 24px):** Administrative dialog modals, bottom mobile navigation sheets, and emergency banner cards.
- **Full Pill (`9999px`):** Status chips, counter badges, citizen avatar frames, and floating action buttons (FAB).

## Components

### Buttons
- **Primary:** Background `#425B9A`, text `#FFFFFF`, rounded `8px`, font weight 600. Focus ring 3px `#76C0EC` at 50% opacity. Hover: `#354A80`.
- **Secondary / Informational:** Background `#76C0EC`, text `#0F172A`, hover: `#5EB1E3`.
- **Emergency / Panic Button:** Background `#FF95A5`, text `#0F172A`, font weight 700. Features an active pulse keyframe shadow: `0 0 0 0 rgba(255, 149, 165, 0.7)`.
- **Ghost / Tertiary:** Transparent background, text `#425B9A`, hover background `rgba(66, 91, 154, 0.06)`.

### Chips & Badges
- **Civic Status Chips:** Full pill radius (`9999px`), padding `4px 12px`, typography `label-sm`.
  - *Lunas / Verified:* Background `#ECFDF5`, text `#065F46`, border 1px solid `#A7F3D0`.
  - *Belum Bayar / Pending:* Background `#FFF6DC`, text `#854D0E`, border 1px solid `#FDE047`.
  - *Darurat / Keamanan:* Background `rgba(255, 149, 165, 0.2)`, text `#9F1239`, border 1px solid `#FF95A5`.
  - *Warga Tetap / Info:* Background `rgba(118, 192, 236, 0.2)`, text `#0369A1`, border 1px solid `#76C0EC`.

### Input Fields
- White surface `#FFFFFF`, border 1px solid `#CBD5E1`, rounded `8px`, padding `10px 14px`.
- Typography: `body-md` (`#0F172A`), placeholder `#94A3B8`.
- Focus state: Border transitions to `#425B9A` with an ambient glow of `0 0 0 3px rgba(118, 192, 236, 0.35)`.
- Error state: Border `#FF95A5`, text message `label-sm` in `#E11D48`.

### Checkboxes & Radio Buttons
- Default: Border 2px solid `#94A3B8`, background `#FFFFFF`, rounded `4px` for checkboxes, circular for radios.
- Selected state: Background `#425B9A`, border-color `#425B9A`, white check/dot icon.

### Cards
- Constructed with `#FFFFFF`, subtle 1px border `#E2E8F0`, rounded `16px` (`rounded-lg`), internal padding `20px` to `24px`.
- Highlighting cards (e.g., Monthly Summary, *Kas RT*) utilize a top accent bar (4px height) colored `#425B9A` or `#76C0EC`.

### Civic-Specific Components
- **Emergency Broadcast Banner (*Banner Waspada/Darurat*):** Full-width card with background `rgba(255, 149, 165, 0.15)`, high-contrast `#9F1239` typography, accompanied by a pulsing alert icon and direct quick-call triggers (*Satpam / Bhabinkamtibmas*).
- **Citizen Family Card Tile (*Info Kartu Keluarga*):** Structured grid block displaying family head (*Kepala Keluarga*), house address code (*Blok/No*), and member count with quick verification actions.
- **Dues Ledger Row (*Iuran Bulanan*):** Tabular data list alternating with subtle background `#F8FAFC`, presenting nominal dues, payment timestamps, proof-of-transfer popovers, and status pills.