---
name: Panel de búsqueda de empleo
description: A launcher-grade personal job-search panel; dark violet-black ground, one coral action colour, keyboard first.
colors:
  ground: "#0b0a0f"
  panel: "#131218"
  raise: "#1c1b22"
  field: "#0f0e14"
  ink: "#ececf1"
  muted: "#9c9ba8"
  hairline: "rgba(255,255,255,.075)"
  hairline-strong: "rgba(255,255,255,.13)"
  hover-wash: "rgba(255,255,255,.045)"
  select-wash: "rgba(255,255,255,.06)"
  coral: "#ff6363"
  coral-ink: "#1d0a0c"
  coral-text: "#ff8a8a"
  coral-soft: "rgba(255,99,99,.11)"
  violet: "#a78bfa"
  violet-text: "#c4b5fd"
  fit-green: "#4ade80"
  fit-amber: "#fbbf24"
  fit-rose: "#fb7185"
  info-blue: "#7cb4ff"
  remote-teal: "#2dd4bf"
typography:
  greeting:
    fontFamily: "Inter, system-ui, -apple-system, Segoe UI, Roboto, sans-serif"
    fontSize: "28px"
    fontWeight: 600
    lineHeight: 1.15
    letterSpacing: "-0.022em"
  greeting-mobile:
    fontFamily: "Inter, system-ui, -apple-system, Segoe UI, Roboto, sans-serif"
    fontSize: "24px"
    fontWeight: 600
    lineHeight: 1.15
    letterSpacing: "-0.022em"
  headline:
    fontFamily: "Inter, system-ui, -apple-system, Segoe UI, Roboto, sans-serif"
    fontSize: "24px"
    fontWeight: 650
    lineHeight: 1.2
    letterSpacing: "-0.02em"
  state-title:
    fontFamily: "Inter, system-ui, -apple-system, Segoe UI, Roboto, sans-serif"
    fontSize: "20px"
    fontWeight: 650
    letterSpacing: "-0.01em"
  dialog-title:
    fontFamily: "Inter, system-ui, -apple-system, Segoe UI, Roboto, sans-serif"
    fontSize: "18px"
    fontWeight: 650
  home-panel-title:
    fontFamily: "Inter, system-ui, -apple-system, Segoe UI, Roboto, sans-serif"
    fontSize: "17px"
    fontWeight: 650
    letterSpacing: "-0.01em"
  empty-title:
    fontFamily: "Inter, system-ui, -apple-system, Segoe UI, Roboto, sans-serif"
    fontSize: "17px"
    fontWeight: 600
  palette-input:
    fontFamily: "Inter, system-ui, -apple-system, Segoe UI, Roboto, sans-serif"
    fontSize: "16px"
    fontWeight: 400
  title:
    fontFamily: "Inter, system-ui, -apple-system, Segoe UI, Roboto, sans-serif"
    fontSize: "15px"
    fontWeight: 600
    lineHeight: 1.5
  body:
    fontFamily: "Inter, system-ui, -apple-system, Segoe UI, Roboto, sans-serif"
    fontSize: "14px"
    fontWeight: 400
    lineHeight: 1.5
    fontFeature: "\"cv11\", \"ss01\""
  body-secondary:
    fontFamily: "Inter, system-ui, -apple-system, Segoe UI, Roboto, sans-serif"
    fontSize: "13px"
    fontWeight: 400
    lineHeight: 1.5
  label:
    fontFamily: "Inter, system-ui, -apple-system, Segoe UI, Roboto, sans-serif"
    fontSize: "12px"
    fontWeight: 500
    lineHeight: 1.5
  column-label:
    fontFamily: "Inter, system-ui, -apple-system, Segoe UI, Roboto, sans-serif"
    fontSize: "11.5px"
    fontWeight: 500
    letterSpacing: "0.06em"
  kbd:
    fontFamily: "Inter, system-ui, -apple-system, Segoe UI, Roboto, sans-serif"
    fontSize: "11px"
    fontWeight: 500
    lineHeight: 1
rounded:
  kbd: "5px"
  pill: "6px"
  sm: "7px"
  md: "8px"
  tile: "9px"
  lg: "10px"
  card: "14px"
  panel: "16px"
  full: "99px"
spacing:
  xs: "6px"
  sm: "10px"
  md: "14px"
  lg: "18px"
  xl: "24px"
  section: "28px"
components:
  button-primary:
    backgroundColor: "{colors.coral}"
    textColor: "{colors.coral-ink}"
    rounded: "{rounded.md}"
    padding: "7px 13px"
  button-secondary:
    backgroundColor: "{colors.raise}"
    textColor: "{colors.ink}"
    rounded: "{rounded.md}"
    padding: "7px 13px"
  button-ghost:
    backgroundColor: "transparent"
    textColor: "{colors.muted}"
    rounded: "{rounded.md}"
    padding: "7px 13px"
  button-ghost-hover:
    backgroundColor: "{colors.hover-wash}"
    textColor: "{colors.fit-rose}"
  button-danger:
    backgroundColor: "transparent"
    textColor: "{colors.fit-rose}"
    rounded: "{rounded.md}"
    padding: "7px 13px"
  button-small:
    rounded: "{rounded.sm}"
    padding: "4px 9px"
  input:
    backgroundColor: "{colors.field}"
    textColor: "{colors.ink}"
    rounded: "{rounded.md}"
    padding: "8px 10px"
  nav-tab:
    backgroundColor: "transparent"
    textColor: "{colors.muted}"
    rounded: "{rounded.md}"
    padding: "6px 11px"
  nav-tab-active:
    backgroundColor: "{colors.raise}"
    textColor: "{colors.ink}"
  chip:
    backgroundColor: "{colors.raise}"
    textColor: "{colors.muted}"
    rounded: "{rounded.md}"
    padding: "5px 11px"
  chip-on:
    backgroundColor: "{colors.coral-soft}"
    textColor: "{colors.coral-text}"
  pill:
    rounded: "{rounded.pill}"
    padding: "2px 8px"
    typography: "{typography.label}"
  pill-neutral:
    backgroundColor: "{colors.raise}"
    textColor: "{colors.muted}"
    rounded: "{rounded.pill}"
  kbd:
    backgroundColor: "{colors.raise}"
    textColor: "{colors.muted}"
    rounded: "{rounded.kbd}"
    height: "20px"
    typography: "{typography.kbd}"
  count-badge:
    backgroundColor: "{colors.coral}"
    textColor: "{colors.coral-ink}"
    rounded: "{rounded.full}"
    height: "20px"
  count-badge-zero:
    backgroundColor: "{colors.raise}"
    textColor: "{colors.muted}"
    rounded: "{rounded.full}"
    height: "20px"
  company-tile:
    rounded: "{rounded.tile}"
    size: "34px"
  command-icon:
    backgroundColor: "{colors.raise}"
    textColor: "{colors.muted}"
    rounded: "{rounded.tile}"
    size: "34px"
  card:
    backgroundColor: "{colors.panel}"
    rounded: "{rounded.card}"
    padding: "18px"
  panel:
    backgroundColor: "{colors.panel}"
    rounded: "{rounded.panel}"
  list-row:
    padding: "12px 18px"
  decision-strip:
    backgroundColor: "{colors.raise}"
    rounded: "{rounded.lg}"
    padding: "12px 14px"
  command-palette:
    backgroundColor: "{colors.panel}"
    rounded: "{rounded.panel}"
    width: "640px"
  decision-dialog:
    backgroundColor: "{colors.panel}"
    rounded: "{rounded.panel}"
    padding: "22px"
    width: "600px"
  chat-bubble:
    rounded: "{rounded.card}"
    padding: "9px 12px"
---

# Design System: Panel de búsqueda de empleo

## Overview

**Creative North Star: "The Morning Launcher"**

The panel behaves like a launcher, not a dashboard. It is a list you clear from the keyboard: one row selected, one coral light on it, S / A / E to decide, Ctrl+K to jump anywhere. Every screen is stacked rows inside raised panels on a near-black, violet-tinted ground, separated by 1px light hairlines rather than heavy borders or card grids.

Density is compact (14px body, 12px rows of padding on 18px gutters) and the surface is quiet: the only atmosphere is a single soft coral-and-violet glow behind the top of the viewport. Colour is spent on meaning: coral for the action and the selection, violet for its partner role, and green / amber / rose for how well an offer fits. Dark is the default theme; a light theme mirrors every token and is remembered per browser. Clearing the list ends in a quiet reward, not a blank: a drawn green check and today's tally.

The world explicitly refuses the default admin template: no big metric cards, no bordered grid of cards as the home view, no generic blue accent.

**Key Characteristics:**
- Near-black violet ground with three tonal layers (ground, panel, raise) and translucent white hairlines.
- One coral action colour; selection is a coral wash plus a coral inset ring.
- Keyboard chips (kbd) appear wherever a shortcut exists: buttons, action bars, the search trigger.
- Company identity is an initial on a hue derived from the company name.
- Authored 24px-grid stroke icons at 1.8 stroke width; no icon fonts, no glyph icons.
- Dark default, full light mirror via `data-theme="light"`.
- Irreversible choices go through a named-button decision dialog whose default is the safe option.

## Colors

A violet-tinted near-black neutral stack carrying one warm coral voice, a violet partner, and a small fit-state triad.

### Primary
- **Launcher Coral** (`coral`): primary buttons, the count badge, the selected-row ring and wash, focus outlines, the text caret, input focus border, the user chat bubble. In light theme it becomes a softer salmon coral carrying dark ink text (not white), because a saturated red fill on white read as an erase/danger signal.
- **Coral Ink** (`coral-ink`): text on coral fills. Near-black red in both themes; never white.
- **Coral Text** (`coral-text`): links on hover or on the selected row, the active chip and active stat label. A lighter coral in dark theme, a deep brick red in light theme, used whenever coral must be read as text rather than filled.
- **Coral Wash** (`coral-soft`): background of active chips, active stat segments, and the 3px input focus halo.

### Secondary
- **Launcher Violet** (`violet`, text form `violet-text`): default pill colour, "Híbrido" modality, the "Me interesa" pill on liked Radar offers, the "HOY" badge, Radar's 7px "Sin revisar" dot, the informational note box (9% violet wash, 22% violet border), and the far end of the logo mark and match-meter gradients. It is the coral's partner, never a second action colour.

### Tertiary
- **Fit Green / Amber / Rose** (`fit-green`, `fit-amber`, `fit-rose`): match-likelihood pills and status selects (probable / medio / poco). Green also draws the inbox-zero check. Amber also marks the 6px dot of the header's "Conectar" hint. Rose marks destructive actions: ghost hover and the danger button. Always shown as text on a wash of the same colour, or as a rose outline; never as a solid fill.
- **Info Blue** (`info-blue`) and **Remote Teal** (`remote-teal`): in-progress application status and the "Remoto" modality pill only.
- In light theme the state hues are deep enough to read at 4.5:1 on their own 14% wash (green, amber, blue and teal at the 800-level of their family); dark theme keeps the bright forms above.

### Neutral
- **Violet Black** (`ground`): page background.
- **Panel** (`panel`): every list container, card, modal, dialog and the palette.
- **Raise** (`raise`): secondary buttons, chips, kbd chips, neutral pills and status selects, the zero count badge, palette command icons, active nav tab, assistant chat bubbles, meter track, the offer modal's decision strip.
- **Field** (`field`): inputs, the search trigger, icon buttons, draft text blocks; slightly below the panel.
- **Ink** (`ink`) and **Muted** (`muted`): primary and secondary text. Inicio's "Abrir" is an ink ghost link that exists only on the selected row; the Radar external-link icon rests muted; the "ver más" link rests in ink; each turns coral text only on the row being acted on or on hover. Location cells and the "Presencial" modality read as plain muted text.
- **Hairline** (`hairline`) and **Strong Hairline** (`hairline-strong`): row dividers and container borders; control borders and kbd edges.
- **Hover Wash** / **Select Wash**: translucent white overlays for hovered rows and the palette's active item.

### Named Rules
**The One Coral Light Rule.** In any list, exactly one row carries coral: the selected one. On Inicio only the selected row shows its actions at all (hidden on the others, removed under 700px); Radar's "Ya aplicada" and external-link icon stay neutral until their row is hovered or focused; the "ver más" link is ink until hovered; the count badge goes neutral at zero. Coral only lights the row being acted on.

**The Wash, Not Fill Rule.** Status and category colours appear as same-hue text on a 14% `color-mix` wash, and must read at 4.5:1 on that wash in both themes. Solid fills belong to coral alone (primary button, count badge, user chat bubble). Destructive actions use rose as text or outline, never as fill.

**The Calm Default Rule.** The normal waiting state carries no colour: "Sin respuesta" and unrated fit render as neutral raise/muted, not amber, and the default "Presencial" modality is plain muted text with no wash at all. Colour appears only when something has actually happened or differs from the default.

**The Mirrored Theme Rule.** Every colour is a custom property defined twice: dark on `:root`, light on `:root[data-theme="light"]`. New surfaces use the variables, never literal hex.

## Typography

**Display Font:** Inter (with system-ui, -apple-system, Segoe UI, Roboto, sans-serif)
**Body Font:** Inter
**Label/Mono Font:** Inter (kbd chips use Inter at 11px, no monospace)

**Character:** One family, tuned: loaded as a variable font over the 400..700 range so the in-between 550 and 650 weights render as drawn; character variants cv11 and ss01 on, tight negative tracking on large sizes, tabular numerals wherever numbers line up.

### Hierarchy
- **Greeting** (600, 28px, 1.15, -0.022em): the Inicio greeting only; a caption above the offers panel, not a display headline.
- **Greeting Mobile** (600, 24px, 1.15, -0.022em): the same greeting under 700px.
- **Headline** (650, 24px, 1.2, -0.02em): page titles on Radar, Candidaturas, Perfil, Agente, Ajustes; they sit on the ground, outside any card.
- **State Title** (650, 20px, -0.01em): the inbox-zero "Todo revisado" title only.
- **Dialog Title** (650, 18px): decision dialog titles and the offer modal's heading.
- **Home Panel Title** (650, 17px, -0.01em): the "Ofertas de hoy" panel header on Inicio; its explanation lives in a title tooltip, not a subtitle line.
- **Empty Title** (600, 17px): empty-state titles inside list panels.
- **Palette Input** (400, 16px): the command palette's borderless input (16px also keeps mobile browsers from zooming).
- **Title** (600, 15px): panel headers, collapsible section headers and the Mi perfil group headings. Plain sub-headings inside a card ("Ajustes de la búsqueda") and the modal's collapsible summaries drop to 14px/600.
- **Body** (400, 14px, 1.5): everything else; row company names at 600, stat numbers at 650.
- **Body Secondary** (400, 13px): row subtitles, role lines, chip text, palette item subtitles, the one-line "soon" placeholder. Panel subtitles and the header hint sit at 12.5px muted.
- **Label** (500, 12px, muted): form labels, status line; pills at 550.
- **Column Label** (500, 11.5px, 0.06em, uppercase, muted): list column headers and palette group headers only.
- **Kbd** (500, 11px, line-height 1): keyboard chips.

### Named Rules
**The Panel Leads Rule.** On Inicio the offers panel is the first thing read; the greeting above it is a 28px caption, never the largest-feeling element on the screen.

**The Tabular Count Rule.** Dates, counts, stat numbers and badges use `font-variant-numeric: tabular-nums` so columns of numbers never jitter.

**The Uppercase Is For Columns Rule.** Uppercase tracking appears only on list column headers, the command palette's group headers (which act as column headers for its list), and the small "HOY" badge. Section, panel, dialog and state titles stay sentence case.

## Layout

A single centred column (max-width 1180px) under a sticky, blurred top bar. In the bar, the search trigger and theme toggle sit right-aligned; when the "Conectar" hint or a status message is showing, it takes the right push and the search follows it. Content is stacked full-width panels with 16px between them and 28px between sections; there is no dashboard grid. Lists are CSS grids with fixed-width trailing columns and flexible leading columns; city and country merge into one muted "Lugar" cell. Candidaturas: name 2.4fr | lugar 1.4fr | modalidad 100px | fecha 100px | encaje 100px | estado 170px | link 40px; when no application has a fit value, the fit column drops entirely rather than showing empty. Radar: name 2.4fr | encaje 100px | lugar 1.3fr | modalidad 100px | fecha 90px | actions 240px (link icon, Ya aplicada, Descartar). Under 980px each row collapses to two columns with the company line spanning both, and column headers hide. Under 700px: the tab nav becomes a single horizontally scrolling strip with a fade mask, the selected Inicio row's actions wrap to full width with 40px touch-height buttons and kbd hints hidden (other rows show none), the action bar hides, the search trigger shrinks to its icon, the header hint shrinks to its dot and "Conectar", and page gutters drop from 24px to 16px. Forms use 2- and 3-column grids that collapse to one column under 700px. Safe-area insets are honoured on the root, header, modal and toast.

Candidaturas reads: page title, the segmented stats strip (12px above, 20px below), then the "En curso" panel (title, count badge and a muted subtitle in its header; no column header row), then the collapsible full list. The list's search, the small secondary "Filtros" toggle (with a coral count of active filters) and the result count share one row; the filter selects live in a collapsible panel that stays open whenever a filter is active. Backup export lives in Ajustes and the palette, not on this screen.

Radar's header carries "Importar ofertas" as its primary button and "Añadir a mano" as secondary; the sort select is compact (5px 8px, 13px).

Mi perfil: the page title sits on the ground, followed by five grouped cards (Quién soy, Qué busco, Qué sé hacer, Trayectoria, Notas para el agente), each with a 15px heading and 16px between groups.

Agente IA: the search card comes first, with a one-line explanation and the primary "Copiar prompt" right under it, then the "Ajustes de la búsqueda" sub-heading and its fields, then the full prompt collapsed in a disclosure; the rules card sits below.

Spacing rhythm: 6 / 10 / 14 / 18 / 24 / 28px. Rows pad 10-12px vertically and 16-18px horizontally; panels pad 18px; the main column pads 28px top, 24px sides.

## Elevation & Depth

Depth is mostly tonal: ground, panel, raise, each a step lighter (in light theme, panel is white and raise a lavender grey), separated by 1px translucent hairlines. Shadows are small at rest and large only for things that float above the page. The top bar uses a 78% ground tint with a 16px blur. One decorative layer exists: two overlapping radial glows (coral left, violet right) behind the top 520px of the page.

### Shadow Vocabulary
- **Rest** (`box-shadow: 0 1px 2px rgba(0,0,0,.4)`; light: `rgba(30,15,60,.08)`): cards and panels on the page.
- **Float** (`box-shadow: 0 18px 50px -18px rgba(0,0,0,.75)`; light: `0 18px 50px -20px rgba(30,15,60,.28)`): modals, the decision dialog, the command palette, toasts.
- **Inset hairline ring** (`box-shadow: inset 0 0 0 1px ...`): active nav tab, company tiles, palette command icons, selected row (coral at 45%). Used instead of a border change so layout never shifts.

### Named Rules
**The Float Only When Floating Rule.** The large shadow is reserved for overlays (modal, dialog, palette, toast). In-page surfaces get the rest shadow or none.

**The One Glow Rule.** The coral-violet glow lives once, behind the top of the viewport. Do not add glows to components.

## Shapes

Softly rounded, scaled by size: 5px kbd and the remove button inside tags, 6px pills, 7-8px buttons, tags, inputs, chips, nav tabs and the header hint, 9px company tiles, command icons and icon buttons, 10px palette items, notes, toasts and the modal's decision strip, 14px cards, list containers and chat bubbles, 16px panels, modals, dialogs and the palette, full rounding for the count badge, meter, status dots and scrollbar thumb. Borders are always 1px. Lists clip their rows inside the container radius; rows separate by a single hairline with no gap.

## Components

### Buttons
Compact and quiet; colour does the work, not size.
- **Shape:** gently rounded (8px; small variant 7px).
- **Primary:** coral fill, coral-ink text, 600 weight, 7px 13px; hover brightens 8%. May carry an icon and a trailing kbd chip. One per surface: in the offer modal it is "Analizar con IA" when AI is available, and "Guardar" becomes primary when it is not.
- **Secondary:** raise fill, ink text, strong hairline border, 500 weight; hover strengthens the border toward ink.
- **Ghost (reversible destructive):** transparent and muted until hover, then rose text on a hover wash. Used for row-level actions like Descartar that the toast can undo.
- **Danger (irreversible or overwriting):** transparent with a 55% rose outline and rose text; hover adds a 10% rose wash. Appears only inside the decision dialog, on the action that destroys or overwrites data.
- **Icon button:** 32px square, field fill, strong hairline, 9px radius.
- **Focus:** 2px coral outline at 2px offset (global `:focus-visible`). Disabled: 50% opacity.

### Chips
- **Style:** raise fill, hairline border, muted 13px/500 text, 8px radius.
- **State:** selected chips switch to coral wash, coral text and a 45% coral border. The stats strip is a segmented control of the same logic inside a 10px panel; its segments are real buttons that report their pressed state. Radar's chip row includes "Me interesan" for liked offers.

### Pills
Status and category labels: 12px/550, 2px 8px, 6px radius, same-hue text on a 14% wash. Variants: violet (default/hybrid, "Me interesa"), green / amber / rose (fit), blue (in progress), teal (remote), neutral (raise fill, muted text: unrated, tally counts), outline "new" (inset hairline), and the "HOY" badge (10.5px, 700, 0.06em tracking). "Presencial" is the exception: plain muted 500 text with no wash and no left padding, because it is the default case. Fit pills, including the neutral "Sin valorar", carry a title tooltip explaining what the rating means. Status selects in table rows reuse the same washes; "Sin respuesta" uses the neutral form.

### Count Badge
20px tall, fully rounded, 12px/700 tabular. Coral fill with coral-ink text when there is something to act on; raise fill with muted text at zero.

### Cards / Containers
- **Corner Style:** 14px cards and list containers, 16px home panels.
- **Background:** panel.
- **Shadow Strategy:** rest shadow (see Elevation).
- **Border:** 1px hairline; panel headers and footers divide with hairlines. A panel header holds its title (with count badge) and, where needed, one 12.5px muted subtitle; Inicio's panel moves that explanation into a tooltip.
- **Internal Padding:** 18px.

### List Rows
Candidaturas and Radar rows are focusable (in tab order, Enter or Space opens the ficha) and show the coral focus outline inset 2px so it stays inside the clipped container. Radar pins liked offers to the top of every chip view. An unseen Radar offer carries a 7px violet dot before its name; the dot is suppressed when every offer is unseen (or the "Sin revisar" chip is active), since marking all of them says nothing.

### Inputs / Fields
- **Style:** field fill, 1px strong hairline, 8px radius, 8px 10px padding, muted placeholders.
- **Focus:** border shifts to 70% coral with a 3px coral-wash halo; keyboard focus adds the 2px coral outline at 1px offset.
- **Forms:** the profile saves as you type (no save button); removing a tag shows an undo toast. The offer modal opens with focus on Notas for an existing record and on Empresa for a new one and, if closed with unsaved edits, asks through the decision dialog: Seguir editando (safe) / Descartar cambios (danger) / Guardar cambios (primary). Modal labels sit at 8px above, 4px below.

### Offer Modal
Ordered by decision, not by data entry: heading (company · role), AI analysis if present, then the decision strip (raise fill, 10px radius, 12px 14px padding) holding "Abrir oferta" as a coral text link, the Encaje select and, for candidaturas, the Estado select; then Notas, then Descripción, then a "Datos de la oferta/candidatura" disclosure (hairline top border, 14px/600 summary with a muted marker) holding identity fields. The disclosure is open for new or incomplete records and closed otherwise. Footer actions close the card.

### Navigation
Top bar: a 22px, 7px-radius mark with a 135° coral-to-violet gradient, 14.5px/600 title, tab nav (Inicio, Candidaturas, Radar, Mi perfil, Agente, Ajustes) of 500-weight muted buttons (hover: ink on hover wash; active: raise fill with inset hairline ring), then, when the data has no cloud copy, a quiet hint button (12.5px muted text, 6px amber dot, underlined "Conectar"; hover: ink on hover wash), then a right-aligned search trigger styled as a field with a Ctrl+K chip, then the theme toggle icon button. On mobile the nav drops to its own scrolling row and the hint keeps only its dot and "Conectar". Switching tabs fades the new section in over 220ms with a 4px rise. Collapsible section headers report their expanded state.

### Company Tile (signature)
A 34px square, 9px radius, with the company's initial at 650 weight. The hue comes from a stable hash of the name (0-359); background is that hue at 16% alpha (13% light), text at 72% lightness (38% light), with a 22% inset ring. The same company always gets the same colour.

### Selected Row and Action Bar (signature)
Home rows are flex rows with a tile, a title line (date or HOY, name, role) and a muted subtitle, inside a listbox whose active option is the selected row. The selected row gets a 9% coral wash and an inset 45% coral ring; only it shows its actions ("Abrir" as an ink ghost link with the external-link icon, then buttons with kbd chips S, A, E) and only it reveals the row's note after the subtitle. Unselected rows keep their action space reserved but invisible (removed entirely under 700px). Hover selects; on touch, a first tap selects the row and a second opens it. Single-key shortcuts can be switched off in Ajustes (Teclado). Each list panel ends with an action bar on a 55% raise wash listing the shortcuts as kbd chips. A row that is acted on slides 14px right and fades out over 180ms before the list re-renders.

### Inbox Zero (signature)
When the morning list is cleared, the panel shows a centred state instead of an empty message: a 56px green check (circle and tick, 2.4 stroke) drawn on with a stroke-dash animation (circle 500ms, tick 350ms after a 350ms delay), the 20px "Todo revisado" title, a muted line, and a row of neutral pills tallying today's decisions (guardadas / aplicadas / descartadas). When liked offers exist, a coral text link leads to them in Radar. The check is fully visible without the animation. With no decisions yet, it falls back to the plain empty state (17px title, muted line, 44px vertical padding).

### Decision Dialog
Replaces the browser's confirm(). A centred 600px card (16px radius, 22px padding, float shadow) over the modal scrim, with an 18px/650 title, muted body text and a right-aligned row of buttons named for their outcome ("Reemplazar mis datos", not "Aceptar"). The safe option is a secondary button and receives focus on open; Esc or closing always resolves to it. Options that destroy or overwrite data use the danger button. When choosing between local and GitHub copies, each side shows its "último cambio" time.

### Command Palette (signature)
Ctrl+K opens a 640px panel 12vh from the top over a lightly blurred scrim. A borderless 16px input sits above a list grouped under column-label section headers; items are 10px-radius rows (company tile or a 34px raise command icon with inset hairline, title, subtitle, trailing muted location), and the active item takes the select wash. Its footer reuses the action bar on raise. Enters with a 220ms fade and 6px lift on `cubic-bezier(.16,1,.3,1)`.

### Kbd Chip
20px tall, 5px radius, raise fill, strong hairline border with a 1px bottom shadow, muted 11px/500 text. Inside a coral button it goes transparent with coral-ink-tinted borders.

### Chat
Messages are 14px-radius bubbles padded 9px 12px, max 85% wide. The user's bubble is the coral fill with coral-ink text, right-aligned; the assistant's is raise with a hairline, left-aligned. AI-only controls (chat, Analizar con IA) are hidden, not disabled, when AI is unavailable.

### Placeholder Line
Features that are not built yet appear as a single muted 13px line with a leading icon, never as an empty panel or a disabled card.

## Do's and Don'ts

### Do:
- **Do** use the custom properties (`--accent`, `--panel`, `--line` and friends) so both themes stay in sync.
- **Do** keep exactly one coral-lit row per list and show the keys that act on it as kbd chips.
- **Do** keep row-level links and icons muted or hidden until their row is selected, hovered or focused.
- **Do** check that any coloured text reaches 4.5:1 on its own wash in both themes.
- **Do** give every company a tile from the name hash instead of a logo or generic icon.
- **Do** draw new icons on the 24px grid with 1.8 stroke, round caps and joins, `currentColor`, through the shared icon helper.
- **Do** set tabular numerals on any number that sits in a column or badge.
- **Do** route irreversible actions through the decision dialog with outcome-named buttons and the safe option focused.
- **Do** respect `prefers-reduced-motion`; all transitions and animations switch off under it, and row exits complete instantly.

### Don't:
- **Don't** build big metric cards or a bordered grid of cards as a home view; counts live in the segmented stats strip and the count badge.
- **Don't** introduce a blue or second solid accent; coral is the only fill colour.
- **Don't** use the large float shadow on in-page surfaces.
- **Don't** use emoji, icon fonts or text glyphs as icons.
- **Don't** add uppercase labels above titles; uppercase is for column and palette group headers only.
- **Don't** colour a normal waiting state; "no news" is neutral.
- **Don't** announce a system state with a full-bleed coloured band; a quiet header hint carries it.
