---
version: alpha
name: "Barclays Corporate (home.barclays)"
website: "https://home.barclays"
description: >-
  Editorial corporate site for a British universal bank. One proprietary
  typeface (Barclays Effra), one chromatic interactive colour (Royal Blue),
  hairline-only card surfaces, and a binary radius scale (8px surfaces, 99px
  pill buttons). Dark photographic hero above a light, dense news and insights
  grid.
provenance:
  source: "Third-party token extraction of home.barclays (shadcn.io/design/barclays), captured 2026-05-19"
  verified_against_live_css: false

colors:
  primary: "#006de3"
  primary-hover: "#005bbe"
  brand-logo: "#00aeef"
  midnight: "#1a2142"
  midnight-deep: "#161b2f"
  ink: "#272727"
  ink-mid: "#515151"
  ink-muted: "#8e8e8e"
  canvas: "#ffffff"
  surface-1: "#f6f6f6"
  info-tint: "#e7f0fb"
  hairline: "#e2e2e2"
  error: "#e3000f"
  error-tint: "#fde7e9"
  success: "#09821f"
  success-tint: "#f4f9f5"
  warning: "#ffba00"
  warning-tint: "#fff8e7"
  dark-text: "#cbccd1"
  interactive-dark: "#3696fc"

typography:
  display-xl:
    fontFamily: "\"Barclays Effra\", Arial, sans-serif"
    fontSize: 80px
    fontWeight: 700
    lineHeight: 76px
    letterSpacing: "-2.56px"
  display-lg:
    fontFamily: "\"Barclays Effra\", Arial, sans-serif"
    fontSize: 48px
    fontWeight: 700
    lineHeight: 58px
    letterSpacing: "-1.152px"
  display-md:
    fontFamily: "\"Barclays Effra\", Arial, sans-serif"
    fontSize: 48px
    fontWeight: 500
    lineHeight: 58px
    letterSpacing: "-1.152px"
  heading-md:
    fontFamily: "\"Barclays Effra\", Arial, sans-serif"
    fontSize: 32px
    fontWeight: 500
    lineHeight: 38px
    letterSpacing: "-0.512px"
  heading-sm:
    fontFamily: "\"Barclays Effra\", Arial, sans-serif"
    fontSize: 16px
    fontWeight: 700
    lineHeight: 24px
  body-md:
    fontFamily: "\"Barclays Effra\", Arial, sans-serif"
    fontSize: 16px
    fontWeight: 400
    lineHeight: 24px
  body-sm:
    fontFamily: "\"Barclays Effra\", Arial, sans-serif"
    fontSize: 14px
    fontWeight: 400
    lineHeight: 21px
  label-md:
    fontFamily: "\"Barclays Effra\", Arial, sans-serif"
    fontSize: 16px
    fontWeight: 500
    lineHeight: 24px
  button-md:
    fontFamily: "\"Barclays Effra\", Arial, sans-serif"
    fontSize: 16px
    fontWeight: 500
    lineHeight: 24px
  caption:
    fontFamily: "\"Barclays Effra\", Arial, sans-serif"
    fontSize: 12px
    fontWeight: 400
    lineHeight: 18px

rounded:
  none: "0px"
  sm: "4px"
  md: "8px"
  lg: "16px"
  full: "99px"

spacing:
  xxs: "4px"
  xs: "8px"
  sm: "12px"
  base: "16px"
  lg: "24px"
  xl: "32px"
  2xl: "40px"
  3xl: "56px"
  4xl: "80px"

components:
  button-primary:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.canvas}"
    typography: "{typography.button-md}"
    rounded: "{rounded.full}"
    padding: "10px 28px"
    height: "44px"
  button-primary-hover:
    backgroundColor: "{colors.primary-hover}"
    textColor: "{colors.canvas}"
  button-secondary:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.primary}"
    borderColor: "{colors.primary}"
    rounded: "{rounded.full}"
    padding: "10px 28px"
    height: "44px"
  button-small:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.canvas}"
    rounded: "{rounded.full}"
    padding: "2px 16px"
    height: "32px"
  top-nav:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.label-md}"
    padding: "24px 24px"
    height: "72px"
  hero-section:
    backgroundColor: "{colors.midnight}"
    textColor: "{colors.canvas}"
    typography: "{typography.display-xl}"
    padding: "80px 24px"
  card:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.body-md}"
    rounded: "{rounded.md}"
    padding: "24px"
    borderColor: "{colors.hairline}"
  link-text:
    textColor: "{colors.primary}"
    typography: "{typography.label-md}"
  tag-chip:
    textColor: "{colors.ink-mid}"
    typography: "{typography.body-sm}"
    rounded: "{rounded.sm}"
    padding: "2px 16px"
    borderColor: "{colors.hairline}"
  footer:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink-mid}"
    typography: "{typography.body-sm}"
    padding: "40px 24px"
---

## Overview

A corporate editorial surface, not a retail banking one. The first viewport is a full-bleed dark photographic hero carrying a heavy white display headline. Below it the page flips to a white canvas and a dense grid of news and insight cards. Colour is almost entirely monochrome (charcoal, mid-grey, hairline grey), with Royal Blue reserved for interaction.

Design intent in four moves:

1. Heavy, tightly tracked display type at newspaper-headline scale.
2. Royal Blue used only where the user can act (buttons, links, focus, toggles, active nav).
3. Binary shape language: 8px on surfaces, full pill on buttons. No middle values in use.
4. Flat depth: hairline borders, no shadows on cards.

## Colour

| Role | Token | Hex | Notes |
|---|---|---|---|
| Interactive | `primary` | #006de3 | Button fill and border, link text, focus ring, toggle track, active tab indicator, progress |
| Interactive hover | `primary-hover` | #005bbe | One stop darker, hover/press |
| Logo only | `brand-logo` | #00aeef | Sky blue of the eagle mark. Do not use on buttons, links or decoration |
| Heading text | `ink` | #272727 | Warm charcoal, not pure black |
| Body text | `ink-mid` | #515151 | Running text |
| Disabled / muted | `ink-muted` | #8e8e8e | Disabled text, icons, resting input border |
| Page | `canvas` | #ffffff | Below-fold floor, text on blue fills |
| Tinted surface | `surface-1` | #f6f6f6 | Disabled fills, subtle section backgrounds |
| Info tint | `info-tint` | #e7f0fb | Informational alerts, soft hover fills |
| Dark panel | `midnight` / `midnight-deep` | #1a2142 / #161b2f | Hero fallback and dark editorial panels |
| Border | `hairline` | #e2e2e2 | Effectively the only border colour (card edges, separators) |
| Status | `error` / `success` / `warning` | #e3000f / #09821f / #ffba00 | Each with a pale tint for alert backgrounds |
| Dark mode | `dark-text` / `interactive-dark` | #cbccd1 / #3696fc | Body text and brighter blue on dark surfaces |

Rules:
- Heading `ink`, body `ink-mid`. Do not collapse them to one value; the two-tone ladder drives the reading rhythm in the card grid.
- Never place `primary` on decorative elements or section headings. It must stay a pure affordance signal.
- Use semantic tokens in code (for example `--button-primary-bg`) that all resolve to `primary`, so a brand-blue change propagates to every interactive surface at once.

## Typography

Single family: **Barclays Effra**, fallback `Arial, sans-serif`. No secondary, serif or mono family. Proprietary and not publicly licensed.

| Token | Size / Line | Weight | Tracking | Use |
|---|---|---|---|---|
| `display-xl` | 80 / 76 | 700 | -2.56px | Hero h1 |
| `display-lg` | 48 / 58 | 700 | -1.152px | Bold section variants |
| `display-md` | 48 / 58 | 500 | -1.152px | Section h2 |
| `heading-md` | 32 / 38 | 500 | -0.512px | Card and article headings |
| `heading-sm` | 16 / 24 | 700 | 0 | Inline labels |
| `body-md` | 16 / 24 | 400 | 0 | Default text |
| `body-sm` | 14 / 21 | 400 | 0 | Tags, footer |
| `label-md` / `button-md` | 16 / 24 | 500 | 0 | Nav links, buttons |
| `caption` | 12 / 18 | 400 | 0 | Metadata |

Rules:
- Weight ladder is 700 (hero and major display), 500 (section headings, labels, buttons), 400 (body). Do not render headings below 500.
- Do not put weight 700 on section h2s that sit under the hero; keep a clear authority gap.
- Keep the negative tracking on display sizes. At zero tracking the hero loses its compressed look.
- Substitute if Effra is unavailable: Helvetica Neue or Inter, applying roughly -0.032em at 48px and -0.032em to -0.064em at 80px. Inter lacks Effra's slightly condensed feel at large sizes, so verify visually.

## Layout

- Base unit 16px. Scale: 4, 8, 12, 16, 24, 32, 40, 56, 80.
- Max content width 1280px (hero aperture up to 1440px). Hero content sits left-aligned at roughly 1200px.
- Major section spacing about 80px. Card padding 24px. Nav padding 24px.
- News and insights grids: 3 columns at desktop with equal-width cards (image, 32px/500 heading, 16px body). "About" section: 4 columns of text-only cards.
- Rhythm alternates between dense editorial grids and generous display moments, using the same 24px card padding in both.

## Elevation and Shape

- No shadows on cards. Depth comes from hairline borders and from the dark-hero to white-canvas colour contrast. A raised shadow token exists in the source CSS (`0 0 20px rgba(39,39,39,0.2)`) but is not used on marketing cards.
- Radius: `md` 8px for cards, panels, form surfaces; `full` 99px for every button; `sm` 4px for chips and form fields; `none` for hero and nav edges. 16px is declared but unused on the captured surface.

## Components

- **Primary button:** `primary` fill, white 16px/500 label, pill, 10x28 padding, 44px high. Hover shifts to `primary-hover`.
- **Secondary button:** white fill, `primary` text and 2px border, same pill and size.
- **Small button:** 32px high, 2x16 padding (the "Online Banking" pill in the header).
- **Top nav:** white, 72px, logo left, text links, compact pill CTA right. Active link gets a 4px `primary` bottom border.
- **Hero:** `midnight` fallback under full-bleed photography, 80px vertical padding, white `display-xl` headline.
- **Card:** white, 1px `hairline` border, 8px radius, 24px padding, no shadow.
- **Link:** `primary`, 16px/500, used for "learn more" style links.
- **Tag chip:** `ink-mid` 14px text, `hairline` border, 4px radius, 2x16 padding.
- **Footer:** white, `ink-mid` 14px text, 40x24 padding, no tonal separation from the page.
- **Focus:** double ring, 2px white inner and 4px `primary` outer.

## Do and Do Not

Do:
- Keep display headings heavy and tightly tracked.
- Restrict Royal Blue to interactive surfaces.
- Hold the 8px / 99px split without introducing 12px or 16px on cards.
- Separate heading and body ink colours.

Do not:
- Use `brand-logo` (#00aeef) for UI.
- Add card shadows or tonal elevation.
- Use pure black for text.
- Introduce a second typeface.

## Known Gaps

- **Provenance:** values come from a third-party extraction dated 2026-05-19, not from the live stylesheet. Re-verify against computed styles and the site's CSS custom properties (`--tkn-*`, `--scl-*`, `--t-*`) before treating as authoritative.
- **Content drift:** the extraction's hero reads "Q1 2026 Results"; the live page's lead item is currently a defence-sector statement. Layout tokens should hold, but hero content and imagery will differ.
- Only resting and one hover state are documented. Active, disabled and full focus behaviour are inferred from CSS variable names.
- Mega-menu and dropdown panels are not captured.
- Dark mode tokens are declared but no dark rendering was captured.
- Motion (hero parallax or scroll behaviour) is not captured.
- Sub-brands (barclays.co.uk, Barclaycard, Wealth) may use different colour sets on the same Effra base.
- Barclays Effra and the Barclays logo are proprietary. This file is for reference and prototyping; use official brand assets for anything shipped.
