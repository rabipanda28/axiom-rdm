---
name: Axiom Corporate Operations
colors:
  surface: '#fcf9f8'
  surface-dim: '#dcd9d9'
  surface-bright: '#fcf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3f2'
  surface-container: '#f0edec'
  surface-container-high: '#eae7e7'
  surface-container-highest: '#e5e2e1'
  on-surface: '#1c1b1b'
  on-surface-variant: '#414754'
  inverse-surface: '#313030'
  inverse-on-surface: '#f3f0ef'
  outline: '#727785'
  outline-variant: '#c1c6d6'
  surface-tint: '#005bbf'
  primary: '#0055b4'
  on-primary: '#ffffff'
  primary-container: '#006de3'
  on-primary-container: '#f6f6ff'
  inverse-primary: '#adc7ff'
  secondary: '#486081'
  on-secondary: '#ffffff'
  secondary-container: '#c0d9ff'
  on-secondary-container: '#465f80'
  tertiary: '#005f85'
  on-tertiary: '#ffffff'
  tertiary-container: '#0079a8'
  on-tertiary-container: '#f0f8ff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d8e2ff'
  primary-fixed-dim: '#adc7ff'
  on-primary-fixed: '#001a41'
  on-primary-fixed-variant: '#004493'
  secondary-fixed: '#d3e3ff'
  secondary-fixed-dim: '#afc8ee'
  on-secondary-fixed: '#001c39'
  on-secondary-fixed-variant: '#2f4868'
  tertiary-fixed: '#c6e7ff'
  tertiary-fixed-dim: '#82cfff'
  on-tertiary-fixed: '#001e2d'
  on-tertiary-fixed-variant: '#004c6b'
  background: '#fcf9f8'
  on-background: '#1c1b1b'
  surface-variant: '#e5e2e1'
  canvas: '#ffffff'
  surface-subtle: '#f7f8fa'
  surface-alt: '#f6f6f6'
  line: '#d7dadd'
  line-hairline: '#e2e2e2'
  ink: '#151515'
  ink-mid: '#515151'
  ink-muted: '#8e8e8e'
  nav-bg: '#001e3c'
  nav-deep: '#161b2f'
  nav-hover: '#082b4b'
  nav-active: '#00395d'
  nav-text: '#dbe7ef'
  nav-muted: '#8da6b9'
  interactive-hover: '#005bbe'
  interactive-tint: '#ecf8ff'
  status-success: '#087443'
  status-success-bg: '#eaf7f1'
  status-warning: '#9a6700'
  status-warning-bg: '#fff7df'
  status-danger: '#a61b1b'
  status-danger-bg: '#fff0ee'
  status-info: '#006de3'
  status-info-bg: '#e7f0fb'
  badge-counter: '#ffc21c'
  code-bg: '#111827'
  code-ink: '#e5e7eb'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 38px
    letterSpacing: -0.025em
  display-md:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 34px
    letterSpacing: -0.02em
  headline-sm:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 26px
    letterSpacing: -0.015em
  title-md:
    fontFamily: Inter
    fontSize: 17px
    fontWeight: '600'
    lineHeight: 24px
    letterSpacing: -0.01em
  title-sm:
    fontFamily: Inter
    fontSize: 15px
    fontWeight: '600'
    lineHeight: 22px
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  body-sm:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 18px
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
  caption:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '700'
    lineHeight: 14px
    letterSpacing: 0.07em
  nav-section:
    fontFamily: Inter
    fontSize: 10px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.1em
  code-sm:
    fontFamily: ui-monospace, SFMono-Regular, Menlo, monospace
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 20px
  code-xs:
    fontFamily: ui-monospace, SFMono-Regular, Menlo, monospace
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 16px
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 18px
  gutter-mobile: 12px
  margin: 44px
  margin-mobile: 16px
  space-xs: 4px
  space-sm: 8px
  space-md: 14px
  space-lg: 20px
  space-xl: 32px
---

## Brand & Style

The design system establishes a high-density, institutional visual environment tailored for enterprise financial governance, mission-critical reference data management, and operational Maker-Checker governance. Derived from Tier-1 corporate banking standards, the aesthetic balances uncompromising regulatory rigor with operational velocity. 

### Design Philosophy
The system follows a strict **Corporate / Modern Data Architecture** archetype:
- **Structural Integrity over Ornamentation:** Visual separation relies on crisp, high-contrast hairlines, structural dividers, and functional bounding boxes rather than floating drop shadows or ambient blurs.
- **Affordance Discipline:** Royal Blue is strictly an operational affordance indicator (buttons, interactive triggers, active tabs, link navigation, and focus rings). It is never applied decoratively.
- **Institutional Authority:** Midnight Deep Navy anchors system chrome, persistent vertical rail navigation, and structural authentication points, creating an explicit visual hierarchy between navigational context and mutable data canvases.
- **Audit-First Visibility:** Every reference entity, versioned state, and JSON payload is structured with strict typographic authority, pairing disciplined sans-serif headers with monospace string tokens to minimize perceptual friction during compliance reviews.

## Colors

The color palette enforces a deterministic hierarchy:

### Core Operational Spectrum
- **Primary Interactive (`#006de3`):** The primary operational trigger. Used exclusively for committed actions, selected navigation indices, input focus rings, and active control surfaces. State changes shift to **Interactive Hover (`#005bbe`)**.
- **Secondary Shell (`#001e3c`):** Deep Navy reserved for primary desktop sidebars, system banners, and high-security state enclosures. Secondary surfaces step deeper to `#161b2f` for specialized terminal and modal backdrops.
- **Tertiary Accent (`#00aeef`):** The brand highlight blue. Applied as a structural line indicator (top bar 4px accent stripe, 3px active navigation left-edge indicator, active tab base bar) and primary platform emblems. Never used for interactive body copy.
- **Neutral Charcoal Ladder:** Pure black is prohibited. Headings and primary values utilize `#151515` (`--ink`), secondary metadata and descriptive captions use `#515151` (`--ink-mid`), while passive placeholders, borders, and disabled controls resolve to `#8e8e8e` (`--ink-muted`).

### Reference & Maker-Checker Semantics
Status badges, diff view highlights, and workflow states must pair an authoritative 700-weight foreground token with a high-contrast muted tint background:
- **Approved / Active State:** `#087443` on `#eaf7f1`.
- **Pending Maker / Checker Authorization:** `#9a6700` on `#fff7df`.
- **Rejected / Terminated Entity:** `#a61b1b` on `#fff0ee`.
- **Draft / In-Revision Info:** `#006de3` on `#e7f0fb`.

## Typography

The typographic hierarchy uses Inter calibrated to match the proportions of corporate grotesque types. It balances rapid vertical scanning with unambiguous character differentiation.

### Systematic Hierarchy
1. **Headline & Section Anchors:** Display levels use negative letter spacing (`-0.025em`) and strong weight steps (700 for page titles, 600 for card headers) to declare unequivocal context before users digest reference data.
2. **Key-Value Pair Parity:** In high-density inspection panels, metadata labels are fixed at `label-sm` (`12px`, weight `600`, color `#515151`), while values render in `body-md` (`14px`, weight `400` or `600`, color `#151515`).
3. **Monospace Discipline:** Entity primary keys (`REF-*`), ISO currency codes, XML/JSON schema payloads, API paths, and Git/Audit commit hashes must strictly use the monospace stack (`code-sm` or `code-xs`). Monospace values maintain a 1.7 line-height ratio in code blocks to aid side-by-side diff comprehension.
4. **Microcopy & Metadata:** Status indicators, tabular counter badges, and section grouping bars render in uppercase with positive letter spacing (`0.07em` to `0.1em`).

## Layout & Spacing

The layout is built for complex, high-throughput financial work. It maximizes horizontal screen area while keeping visual lines of sight predictable.

### Spatial Model & Grid
- **Global Shell:** A split-viewport architecture comprising a fixed `246px` deep navy side rail and a fluid primary content canvas bound to a maximum width of `1360px`.
- **Top Navigation Bar:** Height fixed at `72px`, containing breadcrumbs, active operational partition indicators, and global search, with a direct 4px brand accent border along its top edge.
- **Grid Structures:**
  - **KPI Deck:** 4-column fluid layout with `14px` grid gaps.
  - **Maker-Checker Split Workflows:** Asymmetric split ratios (`1.65fr / 1fr` or `2fr / 1fr`) with `18px` gaps separating proposed changes from target runtime entities.
  - **Reference Detail Inspection:** Fixed two-column metadata specifier: `180px` fixed label column paired with a fluid `1fr` value column.

### Breakpoint Matrix
- **Desktop (>= 1280px):** Full navigation rail (`246px`), standard margin (`44px`), all side-by-side diff inspect panels unlocked.
- **Compact Desktop / Tablet Landscape (851px - 1279px):** Margins contract to `24px`; multi-column stat decks shift to a 2x2 matrix.
- **Tablet Portrait / Mobile (<= 850px):** Navigation rail collapses to a condensed `68px` icon rail; content wrapper padding reduces to `16px`; side-by-side comparison panes stack vertically.

## Elevation & Depth

Visual hierarchy does not use diffuse, floating SaaS drop shadows. Instead, it relies on strict planar containment and high-contrast structural borders.

### The Institutional Flat Model
- **Level 0 (Platform Base):** `#f7f8fa` operational base fill.
- **Level 1 (Data Surfaces & Workspaces):** Pure white (`#ffffff`) container cards, side panels, and topbars. Surfaces are defined by an explicit `1px solid #d7dadd` border. Ambient drop shadows are zeroed out (`box-shadow: none`).
- **Level 2 (Active Focus & Overlays):** Interactive flyouts, filter menus, and date pickers use a precise keyline shadow: `0 2px 4px rgba(0, 0, 0, 0.06), 0 0 0 1px #d7dadd`.
- **Level 3 (Modal Confirmation Shells):** Maker-Checker execution modals apply an explicit deep wash overlay (`rgba(15, 23, 42, 0.45)`) paired with high-containment elevation: `0 18px 60px rgba(0, 0, 0, 0.20)` with a `1px solid #d7dadd` border.
- **Structural Lines:** Structural division between functional zones uses crisp 1px to 4px borders rather than surface drops:
  - Global Topbar Accent: `4px solid #00aeef`
  - Active Tab Underline: `3px solid #00aeef`
  - Active Nav Left Edge: `3px solid #00aeef`

## Shapes

The design system enforces a compact shape language to maximize data density and convey architectural stability.

### Geometry Token Application
- **Standard UI Elements (`roundedness: 1`):** Form controls (inputs, dropdowns), key-value detail containers, cards, tables, status pills, and diff viewer code panels use a crisp `2px` to `4px` corner radius.
- **Primary Action Buttons:** High-level calls-to-action (e.g., "Submit for Checker Approval", "Commit Reference Override") apply a `99px` full pill radius to contrast sharply against tabular data grids.
- **Square System Marks:** Institutional identity marks, company badges, and system user avatars use a strict square geometry (`border-radius: 0px`).

## Components

### Buttons
- **Primary Operational Button:** Pill-shaped (`border-radius: 99px`), `44px` height, `#006de3` background, pure white text, Inter `label-md` (`font-weight: 500`). Hover transitions to `#005bbe`.
- **Secondary / Action Boundary:** Pill-shaped, `44px` height, white fill with a `2px solid #006de3` border and `#006de3` text.
- **Utility / Data Action Button:** Compact `32px` height, `2px` radius, white fill, `1px solid #d7dadd` border, `#151515` text. On hover, background shifts to `#f7f8fa`.
- **Destructive Action:** `2px` radius, `#a61b1b` fill, white text.

### Reference Data Tables
- **Structural Grid:** Container bounded by `1px solid #d7dadd`. Header row background uses `#fafbfc` with a bottom boundary of `1px solid #d7dadd`.
- **Header Cells:** Height `40px`, padding `0 14px`, text token `label-sm` (`font-size: 12px`, `font-weight: 600`, color `#3f4448`). Text is non-selectable, with inline sorting chevrons.
- **Body Rows:** Height `44px`, background `#ffffff`, alternate row fill `#fdfdfd`. Border bottom `1px solid #e2e3e5`. Hover state applies `#f5f8fc`.
- **Entity Code Column:** Rendered in monospace (`code-sm`), weight `500`, color `#001e3c`.

### Status Indicators & Pills
- **Geometry:** Height `22px`, padding `2px 8px`, `2px` radius, text token `caption` (uppercase, `letter-spacing: 0.07em`).
- **Approved / Validated:** Background `#eaf7f1`, text `#087443`.
- **Awaiting Checker:** Background `#fff7df`, text `#9a6700`.
- **Rejected / Quarantined:** Background `#fff0ee`, text `#a61b1b`.
- **Production Sync:** Background `#ecf8ff`, text `#006de3`.

### Maker-Checker Diff Viewer
- **Container Structure:** Dual-pane comparison interface wrapped in a `1px solid #d7dadd` perimeter with a `2px` radius.
- **Pane Headers:** Height `36px`, padding `0 14px`. Current Version pane uses `#f5f6f7` with `#515151` label. Proposed Version pane uses `#eaf7f1` with `#087443` label.
- **Diff Display Panel:** Monospace font (`code-sm`), line-height `1.7`, background `#ffffff`. Unmodified rows use transparent background. Additions use `#eaf7f1` with a `+` prefix and `#087443` text. Removals use `#fff0ee` with a `-` prefix and `#a61b1b` text.

### KPI Stat Cards
- **Card Shell:** Background `#ffffff`, border `1px solid #d7dadd`, padding `20px`, `2px` corner radius.
- **Metric Layout:** Title uses `label-sm` (`#515151`), value displays in `display-md` (`28px`, `font-weight: 700`, `#151515`). 
- **Delta Indicator:** Subtext layout displays trend arrows: positive changes use `#087443` (`↑ 8 this quarter`), negative/risk warnings use `#a61b1b`.

### Form Fields & Inputs
- **Text Inputs & Dropdowns:** Height `38px`, padding `8px 11px`, border `1px solid #9b9fa3`, radius `2px`, background `#ffffff`, text `body-md`. Focus state uses an outline of `2px solid #006de3` with zero offset.
- **Labels:** Displayed directly above the field, `label-sm` (`font-size: 12px`, `font-weight: 600`, color `#62676c`), gap `6px`.

### Audit Trail Timeline
- **Nodes:** Vertical continuous `2px` hairline (`#d7dadd`) connecting operational step anchors.
- **Anchor Nodes:** `12px x 12px` solid square markers (`border-radius: 0px`). Blue (`#006de3`) marks active steps; green (`#087443`) marks authorized actions; red (`#a61b1b`) marks rejected revisions.
- **Metadata Stack:** Inline timestamp and system user ID rendered in monospace (`code-xs`), with comments in `body-sm` (`#515151`).