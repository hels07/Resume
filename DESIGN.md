---
name: Raees Feysal Temam
description: One night under one tree, a portfolio lit by a particle canopy and a gold horizon.
colors:
  night-0: "#040814"
  night-1: "#071029"
  night-2: "#0c1a3d"
  night-3: "#14275c"
  ink: "#f4efe4"
  ink-2: "#c6cbe0"
  ink-3: "#9aa4c4"
  blue: "#4f8cff"
  blue-2: "#8fb8ff"
  blue-3: "#cfe0ff"
  gold: "#ffb347"
  ember: "#ff7a1f"
  gold-ink: "#ffd08a"
  disc-red: "#ff5b45"
  disc-yellow: "#ffc93d"
  glass: "rgba(8,16,42,.62)"
  glass-strong: "rgba(6,13,34,.8)"
  line: "rgba(255,255,255,.12)"
  line-2: "rgba(255,255,255,.2)"
  sky-zenith: "#01030b"
  sky-mid: "#081d4e"
  sky-horizon: "#164a86"
  sky-gold: "#ffae42"
  sky-ember: "#ff6417"
typography:
  display:
    fontFamily: "Noto Serif Display, Iowan Old Style, Palatino Linotype, Georgia, serif"
    fontSize: "clamp(4.4rem, 17vw, 15rem)"
    fontWeight: 300
    lineHeight: 0.9
    letterSpacing: "-0.01em"
  headline:
    fontFamily: "Noto Serif Display, Iowan Old Style, Palatino Linotype, Georgia, serif"
    fontSize: "clamp(2.6rem, 5.6vw, 5rem)"
    fontWeight: 300
    lineHeight: 1.02
    letterSpacing: "-0.025em"
  counter:
    fontFamily: "Noto Serif Display, Iowan Old Style, Palatino Linotype, Georgia, serif"
    fontSize: "clamp(2.6rem, 4.2vw, 3.6rem)"
    fontWeight: 300
    lineHeight: 1
    letterSpacing: "-0.02em"
    fontFeature: "lnum"
  title:
    fontFamily: "Noto Serif Display, Iowan Old Style, Palatino Linotype, Georgia, serif"
    fontSize: "clamp(1.6rem, 2.3vw, 2.1rem)"
    fontWeight: 400
    lineHeight: 1.12
    letterSpacing: "-0.012em"
  body:
    fontFamily: "Karla, Avenir Next, Segoe UI, sans-serif"
    fontSize: "1.0625rem"
    fontWeight: 400
    lineHeight: 1.6
  lede:
    fontFamily: "Karla, Avenir Next, Segoe UI, sans-serif"
    fontSize: "1.1rem"
    fontWeight: 400
    lineHeight: 1.55
  label:
    fontFamily: "Karla, Avenir Next, Segoe UI, sans-serif"
    fontSize: "0.875rem"
    fontWeight: 500
    lineHeight: 1
  caption:
    fontFamily: "Karla, Avenir Next, Segoe UI, sans-serif"
    fontSize: "0.8rem"
    fontWeight: 400
    lineHeight: 1.4
rounded:
  cell: "3px"
  thumb: "12px"
  frame: "14px"
  card: "18px"
  board: "20px"
  key: "22px"
  panel: "26px"
  plate: "30px"
  pill: "999px"
spacing:
  gutter: "clamp(16px, 4vw, 48px)"
  max-width: "1240px"
  nav-height: "64px"
  section-top: "clamp(110px, 15vh, 170px)"
  section-head-gap: "clamp(40px, 6vw, 72px)"
  plate-gap: "clamp(28px, 4vw, 52px)"
  plate-padding: "clamp(14px, 2vw, 26px)"
  row: "12px"
components:
  button-ink:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.night-0}"
    typography: "{typography.label}"
    rounded: "{rounded.pill}"
    padding: "12px 20px"
  button-ink-hover:
    backgroundColor: "#ffffff"
    textColor: "{colors.night-0}"
  button-ghost:
    backgroundColor: "rgba(255,255,255,.04)"
    textColor: "{colors.ink}"
    typography: "{typography.label}"
    rounded: "{rounded.pill}"
    padding: "12px 20px"
  button-ghost-hover:
    backgroundColor: "rgba(255,255,255,.09)"
  nav-pill:
    backgroundColor: "rgba(6,13,34,.58)"
    textColor: "{colors.ink-2}"
    typography: "{typography.label}"
    rounded: "{rounded.pill}"
    padding: "5px"
  nav-link-active:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.night-0}"
    rounded: "{rounded.pill}"
    padding: "9px 16px"
  segmented:
    backgroundColor: "rgba(4,8,22,.75)"
    textColor: "{colors.ink-2}"
    rounded: "{rounded.pill}"
    padding: "4px"
  segmented-tab-selected:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.night-0}"
    rounded: "{rounded.pill}"
    padding: "8px 16px"
  chip:
    backgroundColor: "rgba(255,255,255,.03)"
    textColor: "{colors.ink-2}"
    rounded: "{rounded.pill}"
    padding: "7px 13px"
  chip-pressed:
    backgroundColor: "rgba(255,179,71,.14)"
    textColor: "{colors.gold-ink}"
  tag:
    backgroundColor: "rgba(255,255,255,.03)"
    textColor: "{colors.ink-2}"
    rounded: "{rounded.pill}"
    padding: "6px 12px"
  plate:
    backgroundColor: "rgba(8,16,42,.44)"
    textColor: "{colors.ink}"
    rounded: "{rounded.plate}"
    padding: "{spacing.plate-padding}"
  panel:
    backgroundColor: "{colors.glass}"
    textColor: "{colors.ink}"
    rounded: "{rounded.panel}"
    padding: "clamp(20px, 2.4vw, 30px)"
  fan-card:
    backgroundColor: "{colors.glass-strong}"
    textColor: "{colors.ink}"
    rounded: "{rounded.card}"
    padding: "7px 7px 10px"
    width: "140px"
  email-pill:
    backgroundColor: "rgba(4,8,22,.78)"
    textColor: "{colors.ink}"
    rounded: "{rounded.pill}"
    padding: "14px 16px 14px 26px"
  contact-key:
    backgroundColor: "#1b3478"
    textColor: "{colors.ink}"
    rounded: "{rounded.key}"
    size: "76px"
---

# Design System: Raees Feysal Temam

## Overview

**Creative North Star: "One Night Under One Tree"**

The whole system is a single night scene. A full-bleed WebGL sky runs from near-black zenith to a lit blue horizon. A particle tree glows electric blue above a gold horizon, and the camera drifts through it as the reader scrolls until dawn breaks at the contact close. Everything the reader touches sits on that night as frosted glass: plates, panels, pills and cards, edged with one-pixel white hairlines and lit by a warm-white ink. Nothing is printed on a page. Each surface floats in the sky.

There are exactly two lights, and each has one job. Blue is the cool light of the canopy, used for data, links and anything that grows. Gold is the warm horizon, used for the one answer that matters: the best move, the forecast, the focus ring, the highlighted row. Type follows the same split. A light, high-contrast serif carries the voice: names, headings and plate numbers. Karla does the work underneath. The page is spacious and cinematic at the top and denser inside the plates, where the reader operates real things such as tabs, a playable board and charts.

Motion is damped and physical. Numbers and marks overshoot slightly, then settle. The camera eases toward the scroll position and never jumps to it. With reduced motion on, the night holds still at its first key, and all content stays readable without WebGL.

**Key Characteristics:**
- A fixed WebGL night as the only background, with a CSS gradient as the painted fallback
- Two lights only: blue canopy (cool, data) and gold horizon (warm, the answer)
- Frosted night-glass surfaces with 1px white hairlines and an inset top highlight
- Light serif display (300) for voice and counters, Karla for everything else
- Pill controls throughout, with an ink "thumb" that slides to the active option
- Damped, overshoot-then-settle motion; a scroll-driven camera that ends at dawn

## Colors

A deep ink-blue night, one electric-blue cool light, one molten gold warm light and a warm-white ink. No other hues are used, apart from the Connect 4 disc pair.

### Primary
- **Canopy Blue** (`blue`): the cool light. It marks data fills (bar tracks, the hours grid, chart marks for "my" series), the tagline underline stroke, and the tree's point glow. **Pale Canopy** (`blue-2`) draws chart lines, list markers and service dots. **Moonlit Blue** (`blue-3`) is link text and the highlighted tagline phrase.

### Secondary
- **Horizon Gold** (`gold`): the warm light. It marks the focus ring, the pressed chip, the winning or best row, the forecast line, the nav emblem and the hover border warmth on cards. **Ember** (`ember`) is gold's deep end and appears only in the horizon glow and the painted sky fallback. **Gold Ink** (`gold-ink`) is gold set as legible text for notes, status lines, best values and step numbers.

### Tertiary
- **Disc Red** (`disc-red`) and **Disc Yellow** (`disc-yellow`): reserved for Connect 4 counters, in the board, the move log and the 3D disc. They are a game palette, not brand accents.

### Neutral
- **Night 0 to Night 3** (`night-0` … `night-3`): page ground, theme colour, text on ink fills, and the deepest panel fills, from darkest to lightest.
- **Warm-White Ink** (`ink`): primary text, the canvas wordmark tint, and the fill of every active pill thumb and primary button.
- **Mist** (`ink-2`): secondary body text and inactive controls. **Dusk** (`ink-3`): captions, `dt` labels and meta text.
- **Night Glass** (`glass`, `glass-strong`): translucent surface fills over the sky.
- **Hairline** (`line`, `line-2`): 1px borders and row dividers. `line` is used at rest and `line-2` for controls and framed media.

### The Sky Material
The shader sky has its own ramp: `sky-zenith` → `sky-mid` → `sky-horizon`, with `sky-gold` and `sky-ember` as the horizon glow. The canopy points mix #3f7dff, #8cc0ff, #eaf3ff, #59d6ff and a little #ffb347. Fireflies and sparks mix #ffd27a, #7fe0ff, #ffc76a and #8cc0ff, pushed above 1.0 so the bloom catches them. The sky values are slightly hotter than the UI gold and ember (#ffae42/#ff6417 vs #ffb347/#ff7a1f) because they pass through NeutralToneMapping and bloom. Keep the two sets separate.

### Named Rules
**The Two Lights Rule.** Blue is the cool light and gold is the warm light. Any new accent must be one of these two. Gold marks the single answer in a view (best move, forecast, focus), never decoration.

**The Blue-to-Gold Sky Rule.** The sky's gradient runs from ink to blue to gold to ember. It never passes through violet or magenta.

## Typography

**Display Font:** Noto Serif Display (with Iowan Old Style, Palatino Linotype, Georgia, serif)
**Body Font:** Karla (with Avenir Next, Segoe UI, sans-serif)

**Character:** A light, high-contrast didone-leaning display serif set at weight 300 with tight negative tracking, paired with a friendly grotesque. The serif is the voice and Karla is the instrument panel. Noto Serif Display stands in for the reference's IvyPresto Display.

### Hierarchy
- **Display** (300, clamp 4.4–15rem, 0.9): the name. With WebGL on, it is drawn in canvas as "RAEES" with 0.035em tracking, tinted `ink`, and placed behind the tree. The HTML h1 stays in the DOM, visually hidden.
- **Headline** (300, clamp 2.6–5rem, 1.02, -0.025em): section heads, balanced wrap, soft night text-shadow. The contact close goes larger (clamp 2.8–6rem, -0.03em, max 14ch). The About quote sits between them (clamp 2.4–4.4rem).
- **Counter** (300, clamp 2.6–3.6rem, lining numerals): the plate number "01" with a small `ink-3` "/ 05". Step numbers in the forecaster use the same face at 2.1rem in `gold-ink`.
- **Title** (400, clamp 1.6–2.1rem, 1.12): plate titles. Panel and experience-org heads use 400 at 1.35–1.9rem.
- **Body** (400, 1.0625rem, 1.6): running text. Ledes are 1.1rem in `ink`, supporting paragraphs 1rem in `ink-2`, and line length is capped around 36–40rem.
- **Label** (500, 0.875rem, 1): nav links, buttons, segmented tabs and chips (0.8–0.95rem).
- **Caption** (400, 0.76–0.84rem): `dt` labels, captions and chart axes in `ink-3`. Numbers in data use tabular figures.

### Named Rules
**The Light Voice Rule.** Display type is weight 300 (400 for titles), never bold and never uppercase. Hierarchy comes from size and the serif/sans switch, not from weight.

**The Sentence-Case Rule.** No uppercase tracking labels, kickers or eyebrows sit above headings. A heading stands alone, and context goes in a sentence below it.

## Layout

Content sits in a centred column with a maximum width of 1240px plus fluid gutters (16–48px). The hero fills the viewport: a fixed three-column nav (monogram, centred glass pill, CTA), the canvas wordmark, a centred tagline, and a bottom row with the intro text on the left and the fanned project cards on the right. Sections start 110–170px apart.

Project plates use a 7:5 media/body grid and alternate sides on even plates. The glass gradient darkens toward the text side so copy stays legible over the sky. About uses the same 7:5 split for text and the IB panel. Experience is one tall glass list of 4:7 org/body rows divided by hairlines. Contact is centred.

Breakpoints: 1100 (fan scales to 0.84), 980 (plates stack), 900 (hero bottom and About stack), 820 (nav emblem hides), 760 (experience rows stack), 700 (hours grid goes from 40 to 20 columns), 640 (nav collapses to the centred pill only), 560 (intro columns and contact tiles compress). No horizontal scroll from 360 to 1600px.

## Elevation & Depth

Depth comes from the night itself. The WebGL scene sits behind everything, a `.dim` veil (opacity 0 → 0.5 through the content, easing back to 0.3 at dawn) pushes it back under reading sections, and glass surfaces blur what is behind them (backdrop blur 14–24px, saturate 130–160%). Shadows are soft, dark and pulled in with negative spread, so they read as shade under an object rather than an outline. Each glass surface carries an inset 1px top highlight. Text over the open sky carries a large, soft night-coloured text-shadow.

### Shadow Vocabulary
- **Glass highlight** (`box-shadow: inset 0 1px 0 rgba(255,255,255,.06)`): plates, panels and the experience list.
- **Lifted control** (`box-shadow: 0 10px 24px -12px rgba(0,0,0,.9), inset 0 1px 0 rgba(255,255,255,.7)`): the ink button.
- **Floating card** (`box-shadow: 0 14px 22px -12px rgba(0,0,0,.85), inset 0 1px 0 rgba(255,255,255,.08)`): fan cards, the email pill and contact keys.
- **Framed media** (`box-shadow: 0 16px 24px -14px rgba(0,0,0,.9)`): the browser frame and phone mock.
- **Sky text** (`text-shadow: 0 2px 30px rgba(4,8,20,.7)`): headings over the open night.

### Named Rules
**The Shade-Not-Outline Rule.** Shadows always use a negative spread and pure black at 0.85–0.95 alpha. A shadow never shows as a hard offset copy of the shape.

**The Glass Fallback Rule.** Every blurred surface has a solid fallback. Under `lowfx` (slow frames) or `prefers-reduced-transparency`, the blur drops and the fill becomes opaque night (#081333 or rgba(6,13,34,.9)).

## Shapes

Shapes are soft and rounded, with radius growing with the size of the object. Pills (999px) are used for every control. Fan cards are 18px, the Connect 4 board is 20px, contact keys are 22px, panels 26px and plates 30px. Framed media uses 14px (browser) and 34/26px (phone). Inner thumbnails are 12px and data cells 3px. Borders are always 1px hairlines in white alpha. Fanned cards and newsletter covers tilt a few degrees and straighten on hover.

## Components

### Buttons
Calm pills that press down slightly.
- **Shape:** full pill (999px), 1px border.
- **Primary (ink):** warm-white fill, night text, Karla 500 at 0.95rem, 12px × 20px. Used for "Let's talk".
- **Ghost:** 4% white fill with a `line-2` border, used for Undo, Hint and Restart (with 18px stroked icons at a 1.7 stroke).
- **Hover / Focus / Active:** hover changes fill or border only, and only on fine pointers. Active scales to 0.97 over 160ms. Focus is a 2px gold outline with a 3px offset.

### Navigation
A centred frosted pill (blur 16px) holding Work, About, a gold tree emblem, Experience and Contact. One warm-white indicator slides under the current section (transform and width at 420ms ease-out), and the active link turns night-coloured. The monogram on the left is serif 300 at 1.6rem. Below 640px only the pill remains.

### Segmented Control
The plate view switcher. It is a dark pill track (4px padding, `line` border) with an ink thumb that slides to the selected tab (320ms). The selected label turns night-coloured. Switching views fades the new panel in from a 6px blur (300ms). Without JS it hides and both views stack.

### Chips and Tags
- **Chip (selectable):** pill, `line-2` border, 3% white fill, `ink-2` label. When pressed it gets a gold wash (14%), a gold border (60%) and a `gold-ink` label.
- **Tag (static):** the same pill at 0.84rem, used for stacks and tools.

### Cards / Containers
- **Plate:** a numbered glass slab (30px radius, blur 24px, saturate 160%) with a 7:5 media/body grid, a counter, a title, a lede, a facts strip (3-column `dl` between hairlines) and tags.
- **Panel:** smaller glass (26px, `glass`, blur 20px) for the IB panel, hours, toolkit and experience list.
- **Fan card:** a 140px glass card with a 12px thumbnail and a serif label. Four sit fanned at -10°, -3.5°, 3.5° and 10°. On hover a card lifts 22px, straightens and picks up a gold-tinted border.

### Inputs / Fields
There are no text fields. The email is a pill button (`rgba(4,8,22,.78)`, blur 14px) holding the address and a round ink icon well. On copy, the icon cross-fades from copy to check by blur-and-scale, and a status line appears in `gold-ink`.

### Contact Keys
Three glossy 3D keys (GitHub, Email, Résumé) rendered in their own WebGL canvas: rounded boxes (bevel 0.19) with extruded glyphs, clearcoat finish, a warm key light and a gold rim light, under NeutralToneMapping. Bodies are #11182f, #1f46bf and #efe9dc. The keys bob gently, tilt toward the pointer and spin once on click. Under them, flat CSS tiles (76px, 22px radius, blue gradient) stay in place as the fallback and remain the real links.

### Data Displays
Charts are inline SVG with hairline grids (white 9%), `ink-3` Karla labels and tabular figures. "My" series are blue, the answer or forecast is gold, and comparison series are #7d8cb8. Bars and dots reveal with overshoot. The hours grid is 200 blue 3px-radius squares that light up once.

### Motion
- **Intro (GSAP, expo.out):** the nav drops in at 0.6s, the tagline unblurs at 0.9s, the underline draws at 1.4s, and the fan cards rise in a 0.07s stagger. In the scene, the tree grows over 3.2s, the wordmark fades in from 0.9s, fireflies arrive from 1.6s and story objects pop with back.out(1.7) at 2.3s.
- **Camera:** five keys along a centripetal Catmull-Rom path (hero → into the canopy → above it → looking out → back at the water). Each segment is pinned to a section boundary and smoothstepped, and the dawn uniform rises 0 → 0.05 → 0.35 → 1.0. The camera follows scroll with exponential damping (rate 4.2/s), with a light pointer parallax.
- **Data:** back.out(1.6–2) and cubic-bezier(.34,1.4,.64,1) overshoot. Connect 4 discs drop with bounce.out.
- **Reduced motion:** no intro, no camera flight, no parallax and no idle bob. The scene renders as a still at the first key, smooth scrolling is off, and view changes become plain fades.

### Print
Printing turns the page into a one-column résumé. Background, sky, canvas, nav, fan, media, controls and contact are removed. A print-only header with name and contacts is added. Ink switches to #111/#333/#555 with #ccc rules, the serif is set at 22pt/14pt/11.5pt, body at 9.5–10pt, and link URLs are printed after each project link.

## Do's and Don'ts

### Do:
- **Do** set every new surface as night glass: a `glass` or `glass-strong` fill, a 1px `line` hairline, an inset top highlight and a backdrop blur, with an opaque fallback for `lowfx` and reduced transparency.
- **Do** make every control a pill, and show selection with a sliding warm-white ink thumb and a night-coloured label.
- **Do** keep blue for data and links and gold for the one answer in each view.
- **Do** set headings in Noto Serif Display 300 with negative tracking, and everything else in Karla.
- **Do** number project plates with one consistent "01 / 05" serif counter.
- **Do** let moving values overshoot and settle (back.out, cubic-bezier(.34,1.4,.64,1)), and give every animation a reduced-motion state.
- **Do** keep content readable with WebGL off. The CSS sky gradient and flat contact tiles are the fallback.

### Don't:
- **Don't** add a third light colour. Violet, magenta and green accents break the two-light night. The canopy's cyan tints (#59d6ff, #7fe0ff) are part of the blue light, not a separate accent.
- **Don't** put uppercase eyebrows or kickers above headings.
- **Don't** use hard offset shadows or visible drop outlines. Shadows are soft shade with negative spread.
- **Don't** set display type bold or in all caps (the canvas wordmark is the single uppercase word).
- **Don't** put light or white page sections into the night. Print is the only light mode.
- **Don't** snap state changes. Pills, thumbs and cards move on `cubic-bezier(.23,1,.32,1)`.
