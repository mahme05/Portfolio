---
name: Mahmood Abdul Razak Portfolio
description: A friendly assembly booklet of shipped software, with parts lists, numbered steps and the finished build shown large.
colors:
  action-light: "#1a3a73"
  action-dark: "#ff8f7a"
  action-ink-light: "#ffffff"
  action-ink-dark: "#14233b"
  action-hover-light: "#c8351f"
  action-hover-dark: "#ffffff"
  focus-light: "#1a3a73"
  focus-dark: "#ff8f7a"
  marker-light: "#1a3a73"
  marker-dark: "#ff8f7a"
  marker-ink-light: "#ffffff"
  marker-ink-dark: "#14233b"
  signal-light: "#c8351f"
  signal-dark: "#ff8f7a"
  field-light: "#cfe3f6"
  field-dark: "#1d3a6e"
  on-field-light: "#14233b"
  on-field-dark: "#ffffff"
  on-field-2-light: "#14233b"
  on-field-2-dark: "#dfe8f5"
  page-light: "#ffffff"
  page-dark: "#0f1726"
  card-light: "#ffffff"
  card-dark: "#111a2c"
  panel-light: "#eaf2fa"
  panel-dark: "#1c2a42"
  line-light: "#d6e0ea"
  line-dark: "#33435f"
  ink-light: "#14233b"
  ink-dark: "#f2f5fa"
  ink-2-light: "#3a4a61"
  ink-2-dark: "#c8d2e2"
  muted-light: "#56657b"
  muted-dark: "#9dabc2"
typography:
  display:
    fontFamily: "Gabarito, ui-rounded, system-ui, sans-serif"
    fontSize: "clamp(3rem, 5.4vw + 1rem, 6rem)"
    fontWeight: 800
    lineHeight: 1
    letterSpacing: "-0.025em"
  numeral:
    fontFamily: "DM Serif Display, Georgia, serif"
    fontSize: "clamp(4rem, 8vw, 7.5rem)"
    fontWeight: 400
    lineHeight: 0.8
  headline:
    fontFamily: "Gabarito, ui-rounded, system-ui, sans-serif"
    fontSize: "clamp(2.25rem, 3vw + 1rem, 4rem)"
    fontWeight: 700
    lineHeight: 1.08
    letterSpacing: "-0.02em"
  figure:
    fontFamily: "Gabarito, ui-rounded, system-ui, sans-serif"
    fontSize: "clamp(2.5rem, 3vw + 1rem, 3.5rem)"
    fontWeight: 800
    lineHeight: 1
  title:
    fontFamily: "Gabarito, ui-rounded, system-ui, sans-serif"
    fontSize: "clamp(1.25rem, 0.5vw + 1.05rem, 1.5rem)"
    fontWeight: 700
    lineHeight: 1.2
    letterSpacing: "-0.015em"
  subtitle:
    fontFamily: "Gabarito, ui-rounded, system-ui, sans-serif"
    fontSize: "1.5rem"
    fontWeight: 700
  control:
    fontFamily: "Gabarito, ui-rounded, system-ui, sans-serif"
    fontSize: "1.25rem"
    fontWeight: 700
  mark:
    fontFamily: "Gabarito, ui-rounded, system-ui, sans-serif"
    fontSize: "1.25rem"
    fontWeight: 800
  folio:
    fontFamily: "Gabarito, ui-rounded, system-ui, sans-serif"
    fontSize: "1rem"
    fontWeight: 700
  lead:
    fontFamily: "Figtree, system-ui, sans-serif"
    fontSize: "clamp(1.125rem, 0.4vw + 1rem, 1.375rem)"
    fontWeight: 400
    lineHeight: 1.4
  body:
    fontFamily: "Figtree, system-ui, sans-serif"
    fontSize: "1.0625rem"
    fontWeight: 400
    lineHeight: 1.55
  label:
    fontFamily: "Figtree, system-ui, sans-serif"
    fontSize: "1rem"
    fontWeight: 500
rounded:
  chip: "10px"
  control: "12px"
  card: "20px"
spacing:
  2xs: "4px"
  xs: "8px"
  sm: "12px"
  md: "16px"
  lg: "24px"
  xl: "40px"
  2xl: "64px"
  3xl: "96px"
components:
  button-primary:
    backgroundColor: "{colors.action-light}"
    textColor: "{colors.action-ink-light}"
    typography: "{typography.control}"
    rounded: "{rounded.control}"
    height: "52px"
    padding: "0 24px"
  button-primary-hover:
    backgroundColor: "{colors.action-hover-light}"
    textColor: "{colors.action-ink-light}"
  button-primary-dark:
    backgroundColor: "{colors.action-dark}"
    textColor: "{colors.action-ink-dark}"
    typography: "{typography.control}"
    rounded: "{rounded.control}"
    height: "52px"
    padding: "0 24px"
  button-primary-dark-hover:
    backgroundColor: "{colors.action-hover-dark}"
    textColor: "{colors.action-ink-dark}"
  button-secondary-on-field:
    textColor: "{colors.on-field-light}"
    typography: "{typography.control}"
    rounded: "{rounded.control}"
    height: "52px"
    padding: "0 24px"
  button-secondary-on-field-hover:
    backgroundColor: "{colors.action-light}"
    textColor: "{colors.action-ink-light}"
  button-secondary-on-field-dark:
    textColor: "{colors.on-field-dark}"
    typography: "{typography.control}"
    rounded: "{rounded.control}"
    height: "52px"
    padding: "0 24px"
  button-secondary-on-field-dark-hover:
    backgroundColor: "{colors.action-dark}"
    textColor: "{colors.action-ink-dark}"
  box-panel:
    backgroundColor: "{colors.page-light}"
    textColor: "{colors.ink-light}"
    rounded: "{rounded.card}"
    padding: "24px"
  box-panel-dark:
    backgroundColor: "{colors.page-dark}"
    textColor: "{colors.ink-dark}"
    rounded: "{rounded.card}"
    padding: "24px"
  step-panel:
    backgroundColor: "{colors.panel-light}"
    textColor: "{colors.ink-light}"
    rounded: "{rounded.card}"
    padding: "24px"
  step-panel-dark:
    backgroundColor: "{colors.panel-dark}"
    textColor: "{colors.ink-dark}"
    rounded: "{rounded.card}"
    padding: "24px"
  part:
    backgroundColor: "{colors.card-light}"
    textColor: "{colors.ink-light}"
    typography: "{typography.label}"
    padding: "8px 12px"
  part-dark:
    backgroundColor: "{colors.card-dark}"
    textColor: "{colors.ink-dark}"
    typography: "{typography.label}"
    padding: "8px 12px"
  assembled-result:
    backgroundColor: "{colors.marker-light}"
    textColor: "{colors.marker-ink-light}"
    rounded: "{rounded.card}"
    padding: "24px"
  assembled-result-dark:
    backgroundColor: "{colors.marker-dark}"
    textColor: "{colors.marker-ink-dark}"
    rounded: "{rounded.card}"
    padding: "24px"
  speech-bubble:
    backgroundColor: "{colors.marker-light}"
    textColor: "{colors.marker-ink-light}"
    typography: "{typography.control}"
    rounded: "{rounded.control}"
    padding: "12px 16px"
  speech-bubble-dark:
    backgroundColor: "{colors.marker-dark}"
    textColor: "{colors.marker-ink-dark}"
    typography: "{typography.control}"
    rounded: "{rounded.control}"
    padding: "12px 16px"
  callout:
    backgroundColor: "{colors.panel-light}"
    textColor: "{colors.ink-light}"
    rounded: "{rounded.chip}"
    padding: "8px 16px"
  callout-dark:
    backgroundColor: "{colors.panel-dark}"
    textColor: "{colors.ink-dark}"
    rounded: "{rounded.chip}"
    padding: "8px 16px"
  status-chip:
    backgroundColor: "{colors.panel-light}"
    textColor: "{colors.ink-light}"
    typography: "{typography.label}"
    rounded: "{rounded.chip}"
    padding: "4px 12px"
  status-chip-dark:
    backgroundColor: "{colors.panel-dark}"
    textColor: "{colors.ink-dark}"
    typography: "{typography.label}"
    rounded: "{rounded.chip}"
    padding: "4px 12px"
  tool-chip:
    backgroundColor: "{colors.panel-light}"
    textColor: "{colors.ink-light}"
    typography: "{typography.subtitle}"
    rounded: "{rounded.control}"
    padding: "12px 24px"
  tool-chip-dark:
    backgroundColor: "{colors.panel-dark}"
    textColor: "{colors.ink-dark}"
    typography: "{typography.subtitle}"
    rounded: "{rounded.control}"
    padding: "12px 24px"
---

# Design System: Mahmood Abdul Razak Portfolio

## Overview

**Creative North Star: "The Build Instructions Booklet"**

The system reads like the friendly booklet folded inside a flat-pack box. A coloured cover opens and closes the document, white pages sit between, and the content is organised the way assembly instructions are: a parts list with quantities, large step numerals, callouts with pointers, the finished build shown large, and a folio in the corner of every page. It is clean and professional, with enough play in its rounded type and snapping parts to feel made by a person.

Colour is flat and structural. Pale blue sub-assembly panels group the steps on white, navy carries ink and action, and tomato is kept for the things a booklet would mark in red: arrows, numerals and links. Dark mode is the same booklet printed on deep navy, with soft coral as its single accent. Depth comes only from tonal layers and 1.5px rules.

The system refuses the developer-terminal look, the warm editorial page, and the hero followed by interchangeable feature cards. Density is comfortable and sections are long, with 96px of vertical air on desktop.

**Key Characteristics:**
- Sky blue covers front and back, deep navy in dark mode.
- Rounded Gabarito at weights 700 and 800 for everything structural, Figtree for reading.
- Booklet devices: quantity marks, step numerals, pointer callouts, folios.
- Flat surfaces with no shadows, separated by tone and 1.5px rules.
- Light and dark modes from one token set, defaulting to the device.

## Colors

A cool sky-and-navy paper palette with one warm accent, defined per mode in the token file.

### Primary
- **Booklet Navy** (light #1a3a73): Primary action fill, focus ring, selection, assembled result and speech bubble in light mode.
- **Soft Coral** (dark #ff8f7a): Takes every one of those roles in dark mode, where action, signal, focus and marker are one colour.
- **Action and Marker Ink** (light #ffffff, dark #14233b): Text on those fills.
- **Action Hover** (light #c8351f, dark #ffffff): The primary button's hover fill, tomato in light mode and white in dark.

### Secondary
- **Tomato** (light #c8351f, dark #ff8f7a): Arrows, step and build numerals, quantity marks, parts list icons, content links and link hover. In dark mode the tomato role becomes Soft Coral so that it stays legible on navy.

### Tertiary
- **Cover Field** (light #cfe3f6, dark #1d3a6e): The first and last sections only, sky blue in light mode and deep navy in dark.
- **Cover Ink** (light #14233b, dark #ffffff): Headlines and button text on the field.
- **Cover Ink Soft** (light #14233b, dark #dfe8f5): Lead text and folios on the field.

### Neutral
- **Page** (light #ffffff, dark #0f1726): Default background, and the parts list and contact panels set on the field.
- **Panel** (light #eaf2fa, dark #1c2a42): Sub-assembly panels, status and tool chips, callouts, image wells, and the tinted band section.
- **Card** (light #ffffff, dark #111a2c): Parts and pipeline cards nested on a panel.
- **Line** (light #d6e0ea, dark #33435f): Every rule and divider.
- **Ink** (light #14233b, dark #f2f5fa): Headlines and primary text.
- **Ink Soft** (light #3a4a61, dark #c8d2e2): Lead and running text.
- **Muted** (light #56657b, dark #9dabc2): Captions, folios, stack lines, organisation names and parts list counts.

### Named Rules
**The Never Yellow Rule.** Yellow is banned from the palette in both modes. The user rejected it as too bright; the booklet's warmth comes from tomato alone.

**The Tomato Off The Field Rule.** Never set tomato directly on the light sky field, where it falls to 4.01:1. Field text uses cover ink, and interactive tomato stays on white panels.

**The Single Source Rule.** Every colour lives in the token file, and stylesheets and markup carry none of their own. A new colour is a new token with a light and a dark value, or it does not ship.

## Typography

**Display Font:** Gabarito (with ui-rounded, system-ui, sans-serif)
**Body Font:** Figtree (with system-ui, sans-serif)

**Character:** Gabarito is a rounded, friendly grotesk that does the booklet's shouting in numerals and headlines. Figtree is a clean, quiet sans for reading. The two are close enough in spirit to sit together without strain.

### Hierarchy
- **Numeral** (DM Serif Display 400, clamp 4rem to 7.5rem, 0.8): The large tomato build number that heads each build. The one serif on the page, a printed-booklet accent against the rounded sans.
- **Display** (800, clamp 3rem to 6rem, 1, -0.025em): The cover headline only.
- **Headline** (700, clamp 2.25rem to 4rem, 1.08, -0.02em): Section headings.
- **Figure** (800, clamp 2.5rem to 3.5rem, 1): Automatic step numbers inside panels.
- **Title** (700, clamp 1.25rem to 1.5rem, 1.2, -0.015em): Step and item headings.
- **Subtitle** (700, 1.5rem): Panel headings, tool chips, contact values.
- **Control** (700, 1.25rem): Buttons, speech bubble and small sub-headings.
- **Mark** (800, 1.25rem): Quantity marks in tomato, such as a count with a multiplication sign.
- **Lead** (400, clamp 1.125rem to 1.375rem, 1.4): Opening sentences, capped at 34 to 46ch.
- **Body** (400, 1.0625rem, 1.55): Running text, capped at 60 to 70ch.
- **Label** (500 to 600, 1rem): Navigation, captions, stack lines, chips and dates.
- **Folio** (700, 1rem): Tabular page numbers in the section corner.

### Named Rules
**The No Monospace Rule.** Monospace never appears, including for code names, dates and figures. Columns of numbers use tabular numerals from Gabarito or Figtree.

**The Numeral Leads Rule.** A build or step is identified by a large numeral (DM Serif Display for builds, Gabarito for steps), generated in order, before any heading competes with it.

## Layout

Content sits in a 1280px container with a fluid gutter (16px to 64px) under a 72px sticky navigation bar. Each section is a booklet page with 96px of vertical padding and a folio in its lower right corner, dropping to 64px at 60rem. The spacing scale runs 4, 8, 12, 16, 24, 40, 64 and 96px.

Covers are asymmetric two-column grids (7fr to 5fr, or 6fr to 6fr at the close), and the opening cover fills the viewport below the navigation. Build sections stack a header of numeral, title and status above a three-column step grid, where the first step can span the full width. Two-column splits collapse at 60rem. At 40rem navigation moves behind a Menu button, grids become one column, and callouts are removed. Interactive targets keep a 44px minimum height.

## Elevation & Depth

The system is entirely flat. Depth is tonal, built from page, panel and card, with cover fields as the strongest colour change. Rules of 1.5px separate rows and sections, and stacked sheets are implied by nesting tone, never by a cast shadow.

### Named Rules
**The No Shadow Rule.** No box, text or filter shadow on any element, at rest or in any state.

**The Hairline Only Rule.** Strokes stop at the 1.5px rule weight. Panels and cards carry no outline; only the secondary button and dividing rules draw a line. Drawn assembly arrows are illustration, not outlines.

## Shapes

Corners are soft and step down with size: 20px for panels, cards and images, 12px for controls, tools and speech bubbles, 10px for chips, parts and callouts. Stacked parts share one rounded outer shape, with square inner joints and a rule between them. Speech bubbles and callouts carry a small triangular pointer cut with a clip path, and the timeline is a single rule with 15px round tomato nodes.

Icons are inline line drawings at 20 to 24px, stroked at 2 with rounded caps and joins.

## Components

### Buttons
Large, rounded and direct, set in the display face.
- **Shape:** Softly rounded (12px), 52px tall, 24px side padding.
- **Primary:** Action fill with action ink.
- **Secondary:** Transparent with a 1.5px border in the current text colour, using cover ink on fields.
- **Hover / Focus:** Primary fills with action hover. Secondary fills with action on fields. Colour eases over 220ms, press moves down 1px over 120ms, and focus is a 2px ring offset by 2px.

### Status and Tool Chips
- **Status:** Panel fill (card on tinted bands), 10px corners, weight 600.
- **Tools:** Panel fill, 12px corners, display face at 1.5rem, wrapping in a row. Neither is interactive.

### Panels and Image Wells
- **Corner Style:** 20px.
- **Background:** Panel for steps and image wells, card for nested pipeline steps, page for panels on a field.
- **Shadow Strategy:** None, as in Elevation & Depth.
- **Border:** None.
- **Internal Padding:** 24px.

### Navigation
A flat bar on the page colour with a 1.5px rule beneath it. The wordmark is display 800, links are Figtree 500 in soft ink and turn tomato on hover. The theme toggle is a 44px icon button with two states, light and dark. Below 40rem the links open from a Menu text button as a full-width sheet, closing on selection or Escape.

### In This Box Parts List
The booklet's signature index. A panel on the cover headed by a title and a total piece count, with rows of quantity, line icon in tomato and label, each a 56px link to its section, separated by 1.5px rules.

### Assembly Figure
Stacked parts, a tomato arrow, and an assembled result in the marker colour. Once as it enters view, the parts arrive scattered and snap together over 560ms on a strong ease-out, then the arrow and result follow at 260 to 320ms. With reduced motion, the figure shows in its finished state.

### Pointer Callouts
Speech bubbles use the marker fill on a portrait; callouts use the panel fill above a finished image. Both carry a triangular pointer and are never interactive. Callouts are removed at 40rem.

### Timeline
A single 1.5px vertical rule with round tomato nodes, and three columns of date, role and detail that collapse to one at 60rem.

### Scale Drawing
Two proportional marker and signal bars with labels below, used for comparing quantities honestly to scale.

## Do's and Don'ts

### Do:
- **Do** take every colour from the token file, with both a light and a dark value.
- **Do** default to the device colour scheme, keep a stored choice once made, and offer exactly two toggle states, light and dark.
- **Do** build new sections from booklet devices: quantity marks, numbered steps, pointer callouts and folios.
- **Do** group content with tone and 1.5px rules.
- **Do** keep tap targets at 44px or more, a 2px visible focus ring, and a finished static state under reduced motion.
- **Do** treat SBB's design system as method only: tokens as the single source of truth, with consistent, accessible components.

### Don't:
- **Don't** use yellow in any mode, surface or accent. It was rejected as too bright.
- **Don't** use monospace type anywhere.
- **Don't** add shadows of any kind.
- **Don't** use heavy outlines, or outline a panel or card. The 1.5px rule and secondary button stroke are the limit.
- **Don't** add a third system option to the theme toggle.
- **Don't** use SBB's look, logo, name or font.
- **Don't** set tomato directly on the light sky field.
- **Don't** open a section with a hero and a row of interchangeable feature cards. Multi-column panels here are numbered steps or lettered models.
