---
version: alpha
name: Y2K Millennium
description: A design system rooted in the techno-optimistic visual culture of 1998–2002 — translucent plastics, holographic surfaces, iridescent chrome, and the electric promise of the digital future.
colors:
  primary: "#C084FC"
  secondary: "#22D3EE"
  tertiary: "#F472B6"
  accent: "#A3E635"
  chrome: "#B8BCC8"
  surface: "#0B0B1A"
  surface-glass: "#1A1040"
  neutral: "#EDE8FF"
  on-surface: "#F5F0FF"
  error: "#FF3366"
typography:
  display:
    fontFamily: Orbitron
    fontSize: 80px
    fontWeight: 900
    lineHeight: 0.9
    letterSpacing: -0.03em
  headline-lg:
    fontFamily: Orbitron
    fontSize: 48px
    fontWeight: 700
    lineHeight: 1.0
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Orbitron
    fontSize: 32px
    fontWeight: 700
    lineHeight: 1.1
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Orbitron
    fontSize: 22px
    fontWeight: 600
    lineHeight: 1.2
  body-lg:
    fontFamily: Space Grotesk
    fontSize: 18px
    fontWeight: 400
    lineHeight: 1.6
  body-md:
    fontFamily: Space Grotesk
    fontSize: 15px
    fontWeight: 400
    lineHeight: 1.6
  body-sm:
    fontFamily: Space Grotesk
    fontSize: 13px
    fontWeight: 400
    lineHeight: 1.5
  label-md:
    fontFamily: Share Tech Mono
    fontSize: 13px
    fontWeight: 400
    lineHeight: 1.2
    letterSpacing: 0.08em
  label-sm:
    fontFamily: Share Tech Mono
    fontSize: 11px
    fontWeight: 400
    lineHeight: 1.2
    letterSpacing: 0.12em
rounded:
  none: 0px
  sm: 2px
  md: 8px
  lg: 20px
  xl: 32px
  bubble: 48px
  full: 9999px
spacing:
  base: 8px
  xs: 4px
  sm: 8px
  md: 16px
  lg: 32px
  xl: 64px
  xxl: 128px
  gutter: 24px
  margin: 40px
components:
  button-primary:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.surface}"
    rounded: "{rounded.full}"
    padding: 14px 32px
    typography: "{typography.label-md}"
  button-primary-hover:
    backgroundColor: "{colors.secondary}"
    textColor: "{colors.surface}"
  button-secondary:
    backgroundColor: "transparent"
    textColor: "{colors.primary}"
    rounded: "{rounded.full}"
    padding: 14px 32px
  button-secondary-hover:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.surface}"
  chip:
    backgroundColor: "{colors.surface-glass}"
    textColor: "{colors.neutral}"
    rounded: "{rounded.full}"
    padding: 6px 16px
    typography: "{typography.label-sm}"
  card:
    backgroundColor: "{colors.surface-glass}"
    textColor: "{colors.on-surface}"
    rounded: "{rounded.lg}"
    padding: "{spacing.lg}"
  input:
    backgroundColor: "{colors.surface-glass}"
    textColor: "{colors.on-surface}"
    rounded: "{rounded.md}"
    padding: 12px 16px
    typography: "{typography.body-md}"
  badge:
    backgroundColor: "{colors.tertiary}"
    textColor: "{colors.surface}"
    rounded: "{rounded.full}"
    padding: 4px 12px
    typography: "{typography.label-sm}"
---

# Y2K Millennium

## Overview

This design system captures the visual language of the turn of the millennium — a moment when pop culture, tech, and fashion collided in an explosion of iridescent optimism. The Y2K aesthetic is defined by the tension between sleek machine-made geometry and an almost organic fluidity: translucent plastic bodies glowing in electric cyan and violet, chrome surfaces catching imagined light, and bubble letterforms inflated like they're ready to float off the screen.

The emotional register is **bold, futuristic, and unapologetically digital**. This is not retro for nostalgia's sake — it is the visual promise of the internet era, when the future felt imminent and tangible. Products felt like they came from another decade ahead. Fashion models were styled as cyborgs. Magazine covers treated Nokia phones and PlayStation controllers as jewelry.

Target uses include music, fashion, gaming, streetwear, digital art, creative portfolios, and any product that wants to channel confidence, energy, and forward momentum. The tone should feel like a Japanese fashion magazine from 1999 designed the UI of a spaceship.

---

## Colors

The palette is built around **holographic iridescence and deep digital space**. Colors shift and glow — they are never flat or muted. The dark backgrounds evoke CRT screens and the void of cyberspace, while the accent colors pop with the oversaturated energy of early Photoshop renders, vaporwave posters, and translucent consumer electronics.

- **Primary — Electric Violet (#C084FC):** The signature Y2K hue. Derived from the purple-lilac of iridescent MiniDisc labels, holographic stickers, and translucent Sony and Nokia product plastics. Used for primary interactive elements, highlights, and key UI moments.
- **Secondary — Cyber Cyan (#22D3EE):** The cool counterpoint to violet. References the teal-lit LCD displays, Dreamcast startup screens, and the electric blue scan-line glow of early 2000s tech photography. Used for links, active states, and secondary emphasis.
- **Tertiary — Hot Pink (#F472B6):** Straight from the Y2K fashion runway — vinyl clothing, inflated bubblegum type, and the magenta of chunky flip-phone cases. Used for badges, accent callouts, and energetic secondary actions.
- **Accent — Electric Lime (#A3E635):** The hacker-green edge of the palette. References the neon underbelly of cyberpunk fashion and the green channel of early vector graphics. Use sparingly — a single highlight per screen maximum.
- **Chrome (#B8BCC8):** The neutral metallic that ties all surfaces together. Derived from the silver of PlayStation controllers, Nike watch casings, and stamped aluminum logos. Used for borders, dividers, and decorative chrome details.
- **Surface (#0B0B1A):** Deep space — an almost-black with a violet undertone. The foundational background that makes all neon colors vibrate at full intensity.
- **Surface Glass (#1A1040):** A slightly lighter translucent layer for cards and overlays, evoking frosted colored acrylic and the tinted plastic of consumer electronics.
- **Neutral (#EDE8FF):** A pale lavender-white for body text on dark backgrounds — softer and more digital than pure white.
- **On-Surface (#F5F0FF):** Near-white with a faint violet tint for headlines and high-emphasis text.
- **Error (#FF3366):** Digital alarm red — the warning light on a failing modem, unmistakably urgent.

---

## Typography

Y2K typography operates on **contrast between the monumental and the technical**. Headlines are enormous, compressed, and aggressive — set in geometric display faces that feel like they were designed on a CAD workstation. Body text uses clean, legible grotesques grounded enough to be read on screen. Data, labels, and metadata live in monospaced tech fonts, styled in small caps with wide tracking, evoking serial numbers, loading progress bars, and OS readouts.

- **Display / Headlines — Orbitron:** The definitive Y2K display face. Its geometric, all-caps construction references the racing-stripe boldness of late-90s product design — from the curved housing of the iMac G3 to the angular logos stamped on gaming peripherals. Set it large, tight, and fearless. Tracking should be negative at large sizes to pack letters together like steel plates.
- **Body — Space Grotesk:** A contemporary geometric sans with mechanical quirks that nod to digital letterforms without sacrificing readability. Handles long-form copy cleanly while keeping the aesthetic DNA coherent.
- **Labels / Metadata — Share Tech Mono:** Monospaced and clinical. Use for timestamps, system labels, version strings, coordinates, and all technical data. Always in wide tracking and small sizes — it should read like a readout from a machine, not a human.

Mixing Japanese and Latin type (as in the era's fashion magazines) is encouraged for editorial contexts. If bilingual, place the Japanese type as a vertical column or tight sidebar — never integrated into the same line as the Latin display text.

---

## Layout

The layout strategy is **structured-grid with deliberate tension**. The underlying grid is rigid — a 12-column system with generous gutters, inspired by the dense editorial layouts of late-90s Japanese fashion magazines and gaming publications. But the grid is meant to be broken: bleed images past margins, overlap type into image areas, let elements stack unexpectedly.

Content is organized through **proximity and contrast**, not whitespace alone. The dark background absorbs negative space, so use tighter margins than you would in a light-mode design. Group related information in frosted-glass containers with a visible border. Let sections breathe with generous vertical spacing between them.

Diagonal rules, scan-line textures, and grid-overlay motifs (thin lines forming a perspective grid, as in the Y2K Visual Report aesthetic) can be layered as decorative elements — they reference the vector art and 3D renders of the era.

On mobile, the grid collapses to 4 columns with a 16px margin. On desktop, max content width is 1280px, centered, with 40px outer margins.

---

## Elevation & Depth

Depth is created through **translucency, glow, and chromatic aberration** — not traditional drop shadows. The Y2K aesthetic inherits from the translucent iMac, the holographic MiniDisc label, and the see-through Nokia 3310 shell: you can always sense the layer beneath.

- **Frosted Glass Layering:** Cards and modals use a semi-transparent dark violet background (`surface-glass`) with a 1px border in a lighter, slightly chromatic color (a thin edge of cyan or violet). A subtle `backdrop-filter: blur` effect reinforces the frosted acrylic feel.
- **Chromatic Glow:** Key interactive elements — buttons, active chips, focus states — emit a soft outer glow in their element color. A violet button should have a violet box-shadow spread. This references the CRT phosphor bloom and the neon-light spill of cyberpunk environments.
- **Iridescent Shimmer:** For decorative surfaces, gradients shift between violet, cyan, and pink across a narrow angle — simulating the rainbow surface of a scratched MiniDisc or holographic foil sticker. Reserve this for hero backgrounds, card hover states, and loading skeletons.
- **No flat shadows:** Avoid `box-shadow: 0 2px 4px rgba(0,0,0,0.1)`. If a shadow is needed for lift, use a colored shadow in the element's primary color at low opacity.

---

## Shapes

The shape language holds two coexisting forms in productive tension: **inflated organic bubbles** and **sharp technical geometry**.

- **Bubble Forms:** Buttons, pills, chips, and tags use a generous `border-radius: full` (9999px), creating the inflated bubble letterform look of Y2K 3D-rendered type. Large call-to-action containers use `border-radius: bubble` (48px) — enough to feel soft, like a rounded plastic housing.
- **Sharp-Tech Frames:** Data panels, system readouts, and grid containers use the smallest radius (`sm: 2px`) or none at all — stark right angles that feel like circuit board traces or monitor bezels. The contrast between a bubbly button inside a sharp card is distinctly Y2K.
- **Circular Motifs:** Circular crop frames, radial gradients, and ring/orbit decorative elements reference the disc — the MiniDisc, the CD, the DVD. Use circles as accents in hero sections and loading indicators.
- **Checkerboard Accents:** Black-and-white checkerboard strips (as seen in the era's streetwear graphics) can be used as a border texture, divider, or background element in small doses. Always at a tight tile size (8–16px per square).
- **No mixed radii:** Do not combine bubble-rounded and sharp-cornered elements of the same component type in the same view. Cards are always sharp or always rounded — not both.

---

## Components

### Buttons

Primary buttons are fully pill-shaped (`rounded: full`), filled with Electric Violet, and emit a violet glow on hover. The label is set in Share Tech Mono, uppercase, wide-tracked — it should read like a command being issued to a system. On hover, the background transitions to Cyber Cyan with a cyan glow, shifting the color temperature from warm to cool.

Secondary buttons are transparent with a 1px violet border and violet text. On hover, they fill with violet — the inverse of the primary transition.

All buttons use `padding: 14px 32px`. Avoid small or compact button sizes; Y2K interfaces are confident and large.

### Cards

Cards use the `surface-glass` background with a 1px border in a low-opacity chromatic color. Corner radius is `lg` (20px) for content cards. A very subtle inset glow (1px inner shadow in violet or cyan) completes the frosted-panel effect. Cards should never feel paper-flat — they are windows into a system.

### Chips & Tags

Fully rounded, small, monospaced labels. Used for genre tags, status indicators, and filter controls. Background is `surface-glass`; text is `neutral`. Active/selected chips flip to a solid `primary` background with `surface` text and emit a small glow.

### Input Fields

Inputs have a `surface-glass` background, `md` corner radius (8px), and a 1px `chrome` border at rest. On focus, the border becomes `secondary` (Cyber Cyan) and emits a faint cyan glow — like a CRT cursor blinking to life. Placeholder text is `chrome`, in `body-md`.

### Badges

Small, fully rounded, filled with Hot Pink (`tertiary`). Set in `label-sm`, uppercase. Used for notification counts, "NEW" labels, and status flags. Should appear sparingly — one or two per view maximum.

---

## Do's and Don'ts

- Do use dark backgrounds as the default — the entire palette is calibrated for dark mode; on light backgrounds the neons lose their charge
- Do let headlines break out of the grid and overlap images or cards — compositional tension is part of the language
- Do use chromatic glow on interactive elements — it is not decoration, it is feedback
- Do mix monospaced label type with display headers to create the human/machine contrast that defines the era
- Do use iridescent shimmer gradients sparingly — one iridescent element per screen is striking; four is noise
- Don't use more than two accent colors in a single component — violet and cyan may coexist; adding lime and pink creates visual chaos
- Don't use pure black (#000000) for backgrounds — always use `surface` (#0B0B1A), which carries the violet undertone that keeps the palette coherent
- Don't apply border-radius values inconsistently — bubbles and sharp edges must each stay within their own semantic role
- Don't use lightweight fonts — the minimum usable weight in this system is 400; for display text, always go 700 or 900
- Don't create shadows without color — a colorless shadow breaks the chromatic logic of the system
- Do maintain WCAG AA contrast (4.5:1) for all body text; the dark surface and near-white neutral satisfy this by default — do not reduce text opacity below 90%
