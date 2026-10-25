---
name: Raees Feysal Temam
description: A gothic great hall at midnight (black marble, iron candelabra, leaded glass, a moonlit tracery window) carrying parchment inset-framed cards and numbered violet-glass tiles.
colors:
  plum: "#3b1f5a"
  plum-2: "#2a1640"
  plum-3: "#1d1029"
  plum-4: "#120a1c"
  lavender: "#b9a6e0"
  blood: "#c0283f"
  blood-light: "#f0a0aa"
  blood-ink: "#8c1426"
  parchment: "#ece2d0"
  frame: "#c3ab86"
  ink: "#1c1418"
  ink-2: "#433840"
  ink-3: "#66595f"
  white: "#ffffff"
  white-88: "rgba(255,255,255,.88)"
  white-72: "rgba(255,255,255,.72)"
  tile-glass: "rgba(26,13,38,.7)"
  tile-line: "rgba(255,255,255,.16)"
  scrim: "rgba(12,6,20,1)"
  void: "#06030a"
  moon: "#d6c8ff"
  moonlight: "#a894ff"
  blood-moon: "#ff3a30"
  blood-moonlight: "#ff4a4a"
  fog-violet: "#150c26"
  fog-blood: "#230816"
  shaft-violet: "#7a46d8"
  candle: "#ff9548"
  candle-pool: "#ff8a3c"
  marble-black: "#060409"
  marble-vein: "#d6cce6"
  iron: "#1c171f"
  old-gold: "#a8843a"
  wax: "#e6d8bd"
  velvet: "#3d0410"
  velvet-sheen: "#c41e3a"
  glass-ruby: "#5a0a1e"
  glass-sapphire: "#12206a"
  glass-amethyst: "#3a1260"
  lead: "#07040a"
typography:
  wordmark:
    fontFamily: "Gloock, Bodoni 72, Didot, Georgia, serif"
    fontSize: "clamp(4rem, 13vw, 11rem)"
    fontWeight: 400
    lineHeight: 0.9
  display:
    fontFamily: "Gloock, Bodoni 72, Didot, Georgia, serif"
    fontSize: "clamp(2.4rem, 6.2vw, 6.2rem)"
    fontWeight: 400
    lineHeight: 0.96
    letterSpacing: "0.005em"
  headline:
    fontFamily: "Gloock, Bodoni 72, Didot, Georgia, serif"
    fontSize: "clamp(2.6rem, 6vw, 5.6rem)"
    fontWeight: 400
    lineHeight: 0.96
    letterSpacing: "0.005em"
  numeral:
    fontFamily: "Gloock, Bodoni 72, Didot, Georgia, serif"
    fontSize: "clamp(4.4rem, 7.6vw, 7rem)"
    fontWeight: 400
    lineHeight: 0.82
    letterSpacing: "-0.01em"
    fontFeature: "lnum"
  title:
    fontFamily: "Gloock, Bodoni 72, Didot, Georgia, serif"
    fontSize: "clamp(1.9rem, 2.7vw, 2.6rem)"
    fontWeight: 400
    lineHeight: 0.98
    letterSpacing: "0.01em"
  title-sm:
    fontFamily: "Gloock, Bodoni 72, Didot, Georgia, serif"
    fontSize: "clamp(1.6rem, 2.2vw, 2.1rem)"
    fontWeight: 400
    lineHeight: 1
    letterSpacing: "0.01em"
  lede:
    fontFamily: "Rokkitt, Rockwell, Roboto Slab, Georgia, serif"
    fontSize: "1.25rem"
    fontWeight: 400
    lineHeight: 1.42
  body:
    fontFamily: "Rokkitt, Rockwell, Roboto Slab, Georgia, serif"
    fontSize: "1.125rem"
    fontWeight: 400
    lineHeight: 1.55
  label:
    fontFamily: "Rokkitt, Rockwell, Roboto Slab, Georgia, serif"
    fontSize: "0.78rem"
    fontWeight: 500
    lineHeight: 1
    letterSpacing: "0.14em"
  button:
    fontFamily: "Rokkitt, Rockwell, Roboto Slab, Georgia, serif"
    fontSize: "0.82rem"
    fontWeight: 600
    lineHeight: 1
    letterSpacing: "0.12em"
  data-label:
    fontFamily: "Rokkitt, Rockwell, Roboto Slab, Georgia, serif"
    fontSize: "0.74rem"
    fontWeight: 400
    letterSpacing: "0.12em"
rounded:
  none: "0px"
  cell: "2px"
  sticker: "3px"
  column: "12px"
  board: "18px"
  phone: "34px"
  pill: "999px"
spacing:
  frame-fan: "4px"
  frame-tile: "6px"
  frame-card: "9px"
  frame-plate: "12px"
  plate-gap: "clamp(18px, 2.2vw, 28px)"
  gutter: "clamp(16px, 4vw, 56px)"
  section-top: "clamp(110px, 15vh, 170px)"
  band-y: "clamp(80px, 12vh, 140px)"
  container: "1240px"
  nav-height: "68px"
components:
  button-parchment:
    backgroundColor: "{colors.parchment}"
    textColor: "{colors.ink}"
    typography: "{typography.button}"
    rounded: "{rounded.pill}"
    padding: "12px 20px"
  button-parchment-hover:
    backgroundColor: "{colors.white}"
  button-parchment-on-light-nav:
    backgroundColor: "{colors.plum}"
    textColor: "{colors.white}"
  button-ghost:
    backgroundColor: "rgba(255,255,255,.05)"
    textColor: "{colors.white}"
    rounded: "{rounded.pill}"
    padding: "12px 20px"
  button-ghost-hover:
    backgroundColor: "rgba(255,255,255,.12)"
  chip:
    backgroundColor: "rgba(255,255,255,.04)"
    textColor: "{colors.white-88}"
    rounded: "{rounded.pill}"
    padding: "7px 13px"
  chip-selected:
    backgroundColor: "rgba(192,40,63,.2)"
    textColor: "{colors.blood-light}"
  segmented-control:
    backgroundColor: "rgba(12,6,20,.72)"
    textColor: "{colors.white-88}"
    rounded: "{rounded.pill}"
    padding: "4px"
  segmented-thumb:
    backgroundColor: "{colors.parchment}"
    textColor: "{colors.ink}"
    rounded: "{rounded.pill}"
  card:
    backgroundColor: "{colors.parchment}"
    textColor: "{colors.ink}"
    rounded: "{rounded.none}"
    padding: "clamp(26px, 3vw, 44px)"
  plate-body:
    backgroundColor: "{colors.parchment}"
    textColor: "{colors.ink}"
    rounded: "{rounded.none}"
    padding: "clamp(30px, 3.6vw, 56px)"
  plate-tile:
    backgroundColor: "{colors.tile-glass}"
    textColor: "{colors.white}"
    rounded: "{rounded.none}"
    padding: "clamp(16px, 2vw, 26px)"
  statement-band:
    backgroundColor: "{colors.parchment}"
    textColor: "{colors.ink}"
    typography: "{typography.display}"
    padding: "clamp(80px, 12vh, 140px) clamp(16px, 4vw, 56px)"
  contact-tile:
    backgroundColor: "{colors.parchment}"
    textColor: "{colors.ink}"
    rounded: "{rounded.none}"
    size: "144px"
  email-pill:
    backgroundColor: "{colors.parchment}"
    textColor: "{colors.ink}"
    rounded: "{rounded.pill}"
    padding: "12px 12px 12px 26px"
  sticker:
    backgroundColor: "{colors.blood-ink}"
    textColor: "{colors.parchment}"
    rounded: "{rounded.sticker}"
    padding: "14px 22px"
  tag:
    backgroundColor: "transparent"
    textColor: "{colors.ink-2}"
    rounded: "{rounded.none}"
    padding: "4px 11px 4px 9px"
---

# Design System: Raees Feysal Temam

## Overview

**Creative North Star: "The Great Hall at Midnight"**

The page is one continuous WebGL night inside a gothic mansion. The camera stands at the doors of a ten-bay vaulted nave: pointed arcades on clustered piers, ribbed groin vaults, rough ashlar walls, and a floor of polished black Nero Marquina marble. A grand stair rises to a landing under a great traceried window, where the moon hangs behind leaded glass. Iron candelabra line the nave, sparse and uneven, and an iron chandelier hangs in silhouette against the window. Violet fog, moonbeams thick with dust, cobwebs, tattered crimson banners, bats and falling dark-rose petals fill the air. The scroll is the visit: the camera walks down the nave, looks up into the vault under the chandelier, rises above the stair, and pulls back to the doors as the moon turns blood red for the contact close.

Content does not sit on a page background. It sits on parchment objects and violet-glass tiles laid over the hall. These surfaces keep the THEMYSCIRA UI language: parchment cards with a hairline frame set just inside the edge, numbered violet-glass tiles checkerboarded against them, one giant-type parchment band for the creed, a turning round seal, and a numbered nav. Type is uppercase Gloock for anything that names (the wordmark, titles, numerals, tile labels) and Rokkitt slab for everything that explains. Blood red is the only warm UI accent. It appears as marks, never as large surfaces.

The daylight THEMYSCIRA garden (navy, periwinkle, rose and cream; the pool, blossom tree and stelae) and the earlier SKOTHYA night world are both retired. Their palettes are not reused (PRODUCT.md, Brand Commitments).

**Key Characteristics:**
- A full-bleed, realistic 3D gothic hall at midnight is the page background. No flat page colour sits behind content.
- Parchment surfaces carry a 1px inset frame and have zero corner radius on every card, tile and band.
- Numbered violet-glass project tiles alternate sides against parchment cards.
- Uppercase Gloock, with an arched SVG wordmark and a hand-built crossbar-less A.
- Rokkitt slab for body text and the numbered nav ("01/ WORK").
- One rotating round seal per context (the hero and the statement band).
- Motion is damped and physical: the page-turn tilt out of the hero, the pointer tilt on contact tiles, flickering flames, drifting petals and wheeling bats.

## Colors

A midnight palette of plum and lavender over black marble, with blood red as the one warm mark and parchment as the only light surface.

### Primary
- **Mansion Plum** (plum): the brand colour. It is used for links and icons on parchment, the `+` list markers, the email pill's icon disc, the "Let's talk" button when the nav sits over parchment, the Connect 4 board body and the favicon ground.
- **Deep Plums** (plum-2, plum-3, plum-4): the tile family. plum-3 grounds the fan-card thumbnails and the opaque reduced-transparency tile. plum-4 is the document background, the scrollbar track, the dim layer and the browser and phone frame fill. plum-2 appears in the painted fallback hall and the board gradient. Every scrim and halo behind white type is the plum-black scrim colour at 0.26 to 0.9 alpha.

### Secondary
- **Moonlit Lavender** (lavender): data on violet tiles: minimax score bars, K-factor bars and the server icon. It is never used as a text colour on parchment.

### Tertiary
- **Blood** (blood): accent marks only. It is used for focus rings, the selected chip border, the best-move bar, column hints, the win ring around discs, service dots, hours-grid cells, and the badge outline (at 60%).
- **Blood Light** (blood-light): blood as text on dark tiles. It is used for status emphasis, the best row, the highlighted table row, the "Simulated data" badge and step numerals.
- **Blood Ink** (blood-ink): blood on parchment. It is used for honesty notes, the caret, the seal on the statement band, and the single blood surface, the sticker. The tagline's hand-drawn underline uses a brighter one-off blood (#d63a52) so that it reads over the scene.

### Neutral
- **Parchment** (parchment): every reading surface: the intro card, plate bodies, the statement band, about cards, the experience list, contact tiles, the email pill, tooltips, the segmented thumb and the skip link.
- **Frame Tan** (frame): the 1px inset frame on parchment, fact-row rules and tag outlines.
- **Ink, Ink 2, Ink 3** (ink, ink-2, ink-3): headings, body text and quiet metadata on parchment.
- **White and its alphas** (white, white-88, white-72): all type on the scene and on violet tiles. 88% is for secondary copy; 72% is for captions, chart axes and sublines.
- **Tile Glass and Tile Line** (tile-glass, tile-line): the translucent violet tile, with a 10px blur, and its 1px hairline.

### Scene colours
- **Background:** the void behind the hall is void.
- **Moon and fog:** the moon disc (moon) and moonlight (moonlight) lerp to blood-moon and blood-moonlight over the contact close. The lerp is eased by mood squared, so the red arrives late. The exponential fog (density 0.0115) lerps from fog-violet to fog-blood. The clerestory shafts (shaft-violet) shift toward red with it.
- **Candles:** point lights are candle-coloured. The light pools painted on the floor use candle-pool.
- **Stone and marble:** ashlar is a desaturated violet stone (hue 268, 8% saturation, about 28% lightness). The vault and trim are tinted lighter (#bdb2cc and #d6cce0). The marble is marble-black slabs with marble-vein veining.
- **Metals and cloth:** iron (metalness 0.85, roughness 0.42) for the candelabra, chandelier and chain; old-gold for stair rods, curtain poles, banner borders and the banner star; wax for the candles; velvet with a velvet-sheen for the rug and the drapes.
- **Glass:** leaded glass in deep jewel tones, with glass-ruby, glass-sapphire and glass-amethyst quatrefoils, mottled violet-blue fields, and lead cames.
- **Petals:** drawn from four dark roses (#6a0a18, blood-ink, #4a0610, #a3192f).

### Named Rules
**The Midnight Violet Rule.** The hall reads violet-black: stone, fog, haze and the night sky stay in the plum family, and the only warm light comes from candle flames. Red enters the light only as the blood moon at the contact close.

**The Accent-as-Mark Rule.** In the UI, blood is a line, a dot, a ring or a cell. The only blood surface is the "Thanks for scrolling!" sticker.

**The Ink-on-Parchment Rule.** Near-black ink appears only on parchment. On the scene and on violet tiles, text is white at 100, 88 or 72%.

## Typography

**Display Font:** Gloock (with Bodoni 72, Didot, Georgia)
**Body Font:** Rokkitt 400/500/600 (with Rockwell, Roboto Slab, Georgia)

**Character:** A high-contrast Didone in capitals gives the hall its carved-inscription voice. A warm slab serif keeps the explaining copy plain and readable.

### Hierarchy
- **Wordmark** (Gloock 400, SVG): "RAEES" is set on an arc with a hand-built crossbar-less A (hairline left leg, heavy right leg, flat serifs). "FEYSAL TEMAM" is set small and widely spaced on a concentric arc above it. It is sized to min(60vw, 30vh) on desktop and min(92vw, 24svh) at 980px and below. A real `h1` carries the name for assistive technology and print.
- **Display** (Gloock 400, clamp(2.4rem, 6.2vw, 6.2rem), 0.96): the creed in the parchment statement band. The contact headline runs at clamp(2.8rem, 7vw, 6.4rem)/0.94.
- **Headline** (Gloock 400, clamp(2.6rem, 6vw, 5.6rem), 0.96, balanced): white section heads over the scene, with a double plum-black halo.
- **Numeral** (Gloock 400, clamp(4.4rem, 7.6vw, 7rem), 0.82, lining figures): the "01" to "05" on project tiles.
- **Title** (Gloock 400, clamp(1.9rem, 2.7vw, 2.6rem), 0.98): plate titles.
- **Title small** (clamp(1.6rem, 2.2vw, 2.1rem)): about cards and the hours tile. Experience orgs run at clamp(1.5rem, 2.2vw, 2rem) and the intro card at clamp(1.4rem, 1.9vw, 1.7rem). Contact tile labels and fan labels are Gloock at 1.05rem and 0.76rem.
- **Lede** (Rokkitt 400, 1.25rem, 1.42): the first paragraph of each plate, section-head intros and the contact lede.
- **Body** (Rokkitt 400, 1.125rem, 1.55): the base size. Secondary plate copy is 1.08rem in ink-2; card copy is 1rem/1.45.
- **Label** (Rokkitt 500, 0.78rem, 0.14em, uppercase): nav links, with the section number in a 65%-opacity `01/` prefix. Buttons use Rokkitt 600 at 0.82rem and 0.12em, uppercase.
- **Data label** (Rokkitt 400, 0.74 to 0.76rem, 0.12em, uppercase, ink-3): `dt` terms in fact, IB and kit rows. These label data; they never sit above a heading.

### Named Rules
**The Capitals Name, Slab Explains Rule.** Every Gloock string is uppercase and names something. Every sentence is Rokkitt in sentence case.

**The Tabular Numbers Rule.** Live and comparative numbers (minimax values, search meta, the K-factor table, the clock) use tabular figures. Display numerals use lining figures.

## Layout

- **Container:** 1240px maximum plus gutters. Each section opens with section-top spacing above it, so the hall shows between content.
- **Hero (above 980px):**
  - A two-column grid (a 26.5rem text column and a fluid fan column) sits over a full-width arch row.
  - The tagline and intro card sit upper left on a radial plum-black scrim (46%). The four-card fan sits upper right.
  - The arched wordmark is centred at the bottom over the marble, and the seal sits at the lower right.
  - A bottom gradient (up to 42%) seats the wordmark.
- **Hero (980px and below):**
  - The first screen is exactly one viewport tall. It holds the tagline, then the seal (right-aligned, 80px, or 68px at 560px), then the wordmark at the bottom.
  - The intro card and the fan follow below it.
  - The fan scales by a factor of 1, then 0.84 at 1180px, 0.78 at 980px and 0.6 at 560px.
- **Work plates:**
  - A 1.12fr tile sits beside a 1fr parchment body, and they swap sides on even rows (the checkerboard).
  - Tiles have a 480px minimum height.
  - At 980px the plates stack with the tile first, and the facts grid drops from three columns to two.
- **Statement band:** it breaks out to 100vw. The seal and the creed sit side by side on a two-column grid, with the body in two columns beneath. It becomes a single column at 900px.
- **About cards:** 5fr / 7fr (the profile card and the hours tile), with the kit card full width. They become a single column at 900px.
- **Experience:** one parchment list. Rows split 4fr / 7fr and become a single column at 760px.
- **Contact:** centred. The email pill comes first, then three 144px tiles in a row (106 x 122px at 560px), the Addis clock and the sticker.
- **Breakpoints in use:**
  - 1180px: fan scale.
  - 980px: the primary breakpoint.
  - 900px: about and statement layouts stack.
  - 860px: the nav CTA hides.
  - 760px: the scene's small mode and the experience stack.
  - 700px: the nav numbers hide.
  - 600px: chart label size.
  - 560px: the compact nav, fan and tiles.
- **Scene on narrow screens:** in portrait the camera's FOV widens from 42° up to 68° to keep the nave and window in frame. The paper plane prop is hidden, and the disc and medal move to the upper corners at 60% scale.
- **Horizontal scroll:** none from 360px to 1600px; `main` clips x overflow.

## Elevation & Depth

Depth comes from the 3D hall, not from stacked UI layers. UI surfaces are flat paper or flat glass. Shadows are soft, negatively spread plum-black drops that read as paper lifted a few millimetres off the scene. A fixed plum-4 dim layer rises to 30% opacity by the Work section, holds through Experience, and eases back to 16% at the blood-moon close.

### Shadow Vocabulary
- **Paper lift** (`0 14px 22px -12px rgba(12,6,20,.7)`; the email pill uses `0 14px 24px -14px rgba(12,6,20,.8)`; contact tiles use `0 16px 26px -16px rgba(12,6,20,.75)`): fan cards, newsletter covers, contact tiles and the email pill.
- **Paper lift, raised** (`0 22px 26px -14px rgba(12,6,20,.8)` and `0 24px 30px -16px rgba(12,6,20,.85)`): the hover state of fan cards and contact tiles.
- **Device drop** (`0 16px 24px -14px rgba(0,0,0,.8)`): browser and phone frames on tiles.
- **Text halo** (`0 1px 2px rgba(12,6,20,.85), 0 1px 18px rgba(12,6,20,.85)`, and variants for heads): all white text over the scene. The wordmark uses `drop-shadow(0 4px 22px rgba(12,6,20,.4))`, which tightens to a two-layer drop at 980px and below.

### Named Rules
**The Halo, Not Panel Rule.** White type over the 3D scene is made legible with a plum-black text-shadow halo or a local radial scrim, never by boxing it in a panel.

## Shapes

Every surface that holds content has square corners: cards, plates, tiles, the statement band, tags, contact tiles and tooltips all have zero radius.

The recurring form is the **inset frame**, a 1px frame-coloured border drawn inside the parchment edge. It sits 9px in on cards, 12px on plates and the experience list, 6px on contact tiles and 4px on fan cards.

Fully round pills are reserved for controls: buttons, the segmented control and its thumb, chips, the email pill and badges.

The only other radii belong to depicted objects: the Connect 4 board (18px), its column hit areas (12px), the phone frame (34px, with a 26px screen), hours cells (2px) and the sticker (3px). The seal is a circle.

In the hall, the dominant shape is the equilateral pointed arch, which recurs in the arcades, clerestory lancets, aisle lancets and the great window.

## Components

### Buttons
- **Shape:** full pill (999px).
- **Parchment:** ink on parchment in Rokkitt 600 uppercase, 12px 20px, with a soft drop (`0 10px 22px -14px rgba(0,0,0,.6)`). Hover goes to pure white. In the nav over parchment it inverts to plum with white text.
- **Ghost:** a 5% white fill and a 30% white hairline, with white sentence-case text at 0.95rem. Hover raises the fill to 12% and the line to 50%. Used for Undo, Hint and Restart on the Connect 4 tile.
- **Press:** every button and tappable card scales to 0.97 (0.96 for contact tiles and the sticker) over 160ms.

### Chips
- **Style:** a pill outline at 30% white on 4% white, with white-88 text, 7px 13px.
- **State:** `aria-pressed=true` takes a 20% blood fill, a blood border and blood-light text. Hover on an unpressed chip goes to white text with a 50% line.

### Segmented Control
A dark pill (plum-black at 72%) on the violet tiles, with a parchment thumb that slides between tabs over 320ms on the standard ease. The selected tab's text turns ink. Switching views plays a 300ms entrance that rises and clears a blur, or a fade alone under reduced motion. The control is hidden without JS.

### Cards / Containers
- **Corner Style:** square.
- **Background:** parchment with ink text and an inset frame.
- **Shadow Strategy:** none at rest on large cards. Small handled objects (fan cards, tiles, covers) get the paper lift.
- **Internal Padding:** clamp(26px, 3vw, 44px) for about cards; clamp(30px, 3.6vw, 56px) for plate bodies.
- **Facts row:** a three-column `dl` between frame-coloured rules, with uppercase data labels over 1.02rem values.
- **Tags:** a square outline in frame colour with a plum `+` marker.

### Project Plate (signature)
- **Tile:** a violet-glass tile (tile-glass, a 1px tile-line, and a 10px backdrop blur at 120% saturation).
  - A huge white Gloock numeral sits top left.
  - The segmented control sits top right, over a white-72 caption.
  - The live view fills the rest: a browser frame, a phone frame, a playable Connect 4 board, a chart, pipeline steps or the server rack.
- **Body:** a parchment card beside the tile, holding the title, lede, secondary copy, an honesty note in blood-ink, facts, tags, and a GitHub link in plum.

### Connect 4 Board
- **Board:** a plum gradient body with an inset highlight, and holes that are recessed plum-black wells.
- **Discs:** red (#ff5b45) and yellow (#ffc93d) radial-lit discs. A winning disc gets a parchment ring and then a blood ring.
- **Columns:** they hover at 10% white. The hint column takes a 22% blood fill with a blood hairline.
- **Reward:** solving a puzzle lights one candle on the chandelier's inner ring. The count persists in localStorage, up to 12.

### Fan Cards
Four small parchment cards (132px at scale 1) with a 4px inset frame and a plum-3 thumbnail, fanned at -10, -3.5, 3.5 and 10 degrees from a pivot below the fan. Hover lifts a card 22px, straightens it to 40% of its angle and raises the shadow, over 420ms.

### Statement Band and Seal
- **Band:** a full-bleed parchment band with the creed in giant uppercase Gloock beside the round seal in blood-ink.
- **Seal construction:** an SVG of two rings and a star, with "SANDFORD · SINCE 2014 · ADDIS ABABA" set on a 46px-radius circle in Rokkitt 500 at 2.2px tracking.
- **Motion:** it rotates once every 48 seconds and is static under reduced motion.
- **In the hero:** the seal is white with a plum-black double drop-shadow.

### Contact Tiles
- **Tile:** flat 144px parchment squares with a 6px inset frame. A 30px plum line icon (inline SVG, 1.7 stroke) sits over a Gloock label and an ink-3 subline.
- **Pointer tilt:** on fine pointers each tile leans toward the cursor by up to 8 degrees on each axis (rotateX and rotateY inside a 700px perspective). It eases back over 300ms on leave. The tilt is off under reduced motion.

### Email Pill
- **Pill:** a parchment pill with the address in Rokkitt 600 and a 42px plum disc holding a copy icon.
- **Copy:** on copy, the icon cross-fades to a check (scale 0.6 and a 3px blur out, 260ms in), and a live region announces the result.
- **Fallback:** when the clipboard API fails, the address text is selected instead.

### Navigation
- **At rest:** fixed and transparent over the scene, with a soft plum-black top gradient.
- **Links:** white Rokkitt labels at 82% opacity, rising to 100% when current or hovered, with a 1px sliding underline indicator (420ms).
- **Over parchment:** when at least two of three sample points across the links sit over a parchment surface, the nav switches to ink on a parchment fade over 300ms.
- **Logo:** a 12-point star SVG plus "RAEES".
- **Narrow screens:** at 860px the CTA hides, at 700px the `01/` numbers hide, and at 560px the logo text hides.

### Sticker
The one blood surface: a blood-ink, 3px-radius uppercase label in parchment, rotated -4 degrees. It straightens on hover. On click it wobbles through a 0.6s keyframe and releases a petal burst in the hall.

### Tooltips
Parchment, square, 10px 14px, scaling up from 0.96 over 200ms. Used for the 3D story props and for chart points.

### The 3D Hall (art direction)

**Architecture and materials**
- **Architecture:** a nave 13.6 units wide with ten 8-unit bays, and side aisles behind pointed arcades.
  - **Walls:** a clerestory of lancets above the arcades, and tall lancets in the aisle walls.
  - **Vault:** a groin vault built as the union of two pointed barrels, so the groins come out sharp, with diagonal ribs, transverse ribs, a ridge rib and bosses.
  - **Piers:** clustered piers, each with one tall vaulting shaft and two arcade shafts, on octagonal bases with lathed capitals.
  - **Stair:** a 12-step grand stair to a landing, with balusters and rails.
  - **Rule:** the hall is realistic and detailed, never rounded off or toy-like.
- **Procedural surfaces:**
  - Canvas-generated albedo, plus a normal map derived from a height field.
  - Ashlar is rough-dressed: uneven blocks with chipped arrises, recessed mortar, pits and damp streaks.
  - The marble has hand-set joints, branching veins and polish scratches.
  - UVs are projected from world position, so every surface shares one texel density.
- **Floor:**
  - Nero Marquina black marble (roughness 0.1) under an additive planar Reflector at 0.5x resolution (0.4x in small mode).
  - The reflection is **streaked and clamped**: a 9-tap vertical smear, clamped to 1.1, masked by the grout, and mixed by Fresnel from 7% to 50%. Polished stone, not a mirror.
- **Glass:**
  - The great window has clear diamond quarries with a jewel-glass border, and a moonlit sky shader behind it: a cratered moon, stars and drifting fbm cloud.
  - The clerestory and aisle lancets are mottled violet-blue fields with stacked quatrefoils in ruby, sapphire and amethyst. The clerestory is emissive at 2.0, the aisles at 0.75.
- **Tracery:** three mullions, a transom, six sub-arches and an oculus with six spokes. The tracery casts its shadow into the hall from the moon.
- **Drapes and rug:** crimson velvet drapes in folds flank the window. A crimson rug runs up the stair and across the landing, with gold stair rods.
- **Banners:** 16 tattered crimson banners with a gold border and the site's eight-point star hang from gold rods on the piers.
- **Cobwebs:** pale lavender webs at 10% opacity in the corners, plus two dark silhouette webs across the great window.

**Light**
- **Ambient and moon:**
  - A violet hemisphere light (`#3a2a6a` over `#0c0614`, intensity 0.95).
  - One moon directional light (5.5, rising to 7.0 at the blood moon) that casts 2048px soft shadows (1024px in small mode). The shadow map renders once.
- **Moonbeams:**
  - Volumetric moonbeams are additive shells extruded from the window outline, three nested layers per beam, with fbm noise and falloff along the beam.
  - Three fainter violet shafts fall through the clerestory.
  - The great-window beam is full of drifting dust motes.
- **Candles:**
  - Iron candelabra (three candles each) stand on piers 3 to 8, with two stands deliberately missing. Two larger stands sit on the landing.
  - The chandelier has three iron rings: 18 lit candles, 12 lit candles, and 12 earned candles.
  - Real point lights are few: 4 in the nave (2 in small mode), 2 at the landing and 1 for the chandelier. Every other candle is lit by an additive glow pool painted on the floor.

**Flames, atmosphere and props**
- **Flames:**
  - Flames are point sprites: a shader teardrop with a hot core and a blue base, flickering on three summed sines.
  - A soft halo sprite gives the bloom something to catch.
  - Point lights flicker on their own phase.
- **Atmosphere:**
  - Bats: 11 (6 in small mode), wheeling under the vault and the window.
  - Petals: 170 lit dark-rose petals (90 in small mode). They spawn in front of the camera, drift down and respawn.
  - Fog: violet exponential fog.
- **Story props:** a crimson Connect 4 disc, a gold sprint medal and a parchment paper plane float in the hero.
  - Hover grows a prop by 12% and shows a tooltip.
  - Click spins it and bursts petals.
  - The props shrink away as the hero exits.

**Camera and post**
- **Camera path:** five keys on centripetal Catmull-Rom curves: the doors, down the nave, up into the vault under the chandelier, above the stair, and back to the doors.
  - The keys are mapped to section positions and damped toward scroll (rate 4.2/s).
  - Fine pointers get a slight parallax.
  - Mood runs 0, 0.05, 0.15, 0.45 and then 1 at the close.
- **Post-processing:**
  - The render pass feeds a sanitize pass, then UnrealBloom (strength 0.6, radius 0.5, threshold 0.9), then the output pass.
  - The output uses ACES Filmic tone mapping (exposure 1.3) into sRGB.
  - A final grade adds 0.0016 radial chromatic offset, a vignette that darkens to 42% at the corners, and 2.8% animated grain.
- **Intro:** the candles catch over 2.4s (power2.out), then the props rise from 1.6s (back.out).

**Hard-won technical rules**
- **Per-material environment maps.** The reflection environment is a PMREM of a stand-in hall: dim violet stone, the bright moonlit window and warm candle glows. It is assigned to each MeshStandardMaterial's `envMap` individually, never via `scene.environment`. scene.environment overrides each material's envMapIntensity, which the floor (0.02), stair (0.04), stone (1.25) and props depend on.
- **No MSAA under bloom; supersample instead.** The composer's render target is a plain HalfFloat target with no samples, and the renderer runs with `antialias: false`. Desktop pixel ratio is floored at 1.25 and capped at 2. Small mode is capped at 1.5.
- **Sanitize before bloom.** A shader pass clamps the HDR buffer to [0, 48] and zeroes NaN texels before UnrealBloomPass, so one bad texel cannot smear across the frame.
- **Point lights stay off geometry.** Candle lights hang beside their candelabra, inboard of the stands (x ±5.2 against stands at ±5.55). The chandelier light is offset 0.9 units from the hub. The earned light sits 2.4 units above it.
- **Floor reflections are streaked and clamped**, never a clean mirror (see Floor above).
- **Sparse, uneven candles for dread.** Candelabra skip a pier on each side, at different bays. Real lights cover only the near nave and the landing, so the frame edges and far bays fall into dark.
- **Adaptive quality:**
  - After 150 frames, if the frame-time average stays above 28ms for three checks, step one sets `lowfx` (opaque tiles instead of glass blur) and drops the pixel ratio to 0.7x (minimum 1).
  - Step two disables bloom and renders at 1x.
  - Rendering stops while the tab is hidden.
  - Small mode (760px or a coarse pointer) uses 512px procedural textures, fewer dust motes, petals and bats, and coarser vault tessellation.

### Motion
- **Standard ease:** cubic-bezier(.23,1,.32,1) for all UI transitions:
  - 160ms for press;
  - 200ms for colour;
  - 300ms for tiles and nav tone;
  - 320ms for the segment thumb;
  - 420ms for the fan and the nav indicator;
  - 1.2s for the scene fade-in.
- **Spring:** cubic-bezier(.34,1.4,.64,1) over 520ms for score bars. Chart and hours-grid reveals use GSAP `back.out`.
- **Load:** one authored GSAP timeline (expo.out): the nav, the tagline clearing a blur, the underline drawing, the intro card, the wordmark letters staggered, the fan cards rising, and the seal.
- **Page turn:** leaving the hero, its content tilts back 14 degrees, recedes 180px and fades, scrubbed with a 0.6s lag. On the stacked mobile first screen it uses 12 degrees and 140px.

## Do's and Don'ts

### Do:
- **Do** put every reading surface on parchment with the 1px inset frame and square corners.
- **Do** number project tiles with a large white Gloock numeral, and alternate the tile and parchment body sides.
- **Do** set names, titles and numerals in uppercase Gloock and all running copy in Rokkitt.
- **Do** keep white text over the hall legible with the plum-black halo or a local scrim.
- **Do** keep the hall violet-black with warm candle flames, and save red light for the blood moon at the close.
- **Do** assign environment maps per material, keep the bloom input finite, supersample instead of MSAA, and keep point lights off geometry.
- **Do** keep candles sparse and uneven, and let the frame edges fall into dark.
- **Do** give every motion a reduced-motion state:
  - The camera rests at the hero view and re-renders a still frame on scroll, resize or a solved puzzle.
  - Time stops: flames, bats, petals and dust freeze.
  - The seal stops, and the tiles do not tilt.
  - The load timeline and the page turn are skipped.
  - Smooth scrolling is off.
- **Do** keep all content readable without WebGL. The painted CSS hall stands in: a vertical gradient from near-black through plum-3 and plum to a violet glow (#5a2a6e) at the horizon, then down through plum-2 and plum-4. The same fallback applies if the 3D modules fail to load.
- **Do** keep the print stylesheet working:
  - The page prints as a one-column résumé on white with a print-only name header.
  - The scene, nav, fan, tiles, games, covers, medals and contact controls are removed.
  - Link URLs are printed after project links, and Experience starts on a new page.
- **Do** follow PRODUCT.md for all content limits.

### Don't:
- **Don't** reuse the retired palettes: the THEMYSCIRA daylight navy, periwinkle and rose, or the SKOTHYA night palette and its Noto Serif Display and Karla type.
- **Don't** round cards, plates, tiles or the statement band. Radius belongs to controls and depicted objects.
- **Don't** fill large UI surfaces with blood. The sticker is the only blood surface.
- **Don't** smooth the hall into soft toy shapes or clean CG surfaces. Stone is rough, marble is veined and jointed, and glass is leaded and mottled.
- **Don't** light every candle or line the nave evenly.
- **Don't** let the floor become a clean mirror or let reflections run unclamped.
- **Don't** put a small uppercase label above a heading. Uppercase tracked Rokkitt labels belong to the nav, buttons and data terms only.
- **Don't** set ink on the scene or white on parchment.
