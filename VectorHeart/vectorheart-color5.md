---
version: alpha
name: Vectorheart
description: A diagonal-force design aesthetic combining industrial precision with kinetic urgency. Geometric stripe bundles, territorial color fields, and architectural typography define a visual surface that vibrates at a specific, irreproducible frequency.
colors:
  neutral:    "#100906"
  primary:    "#FF6200"
  secondary:  "#F8F0E0"
  tertiary:   "#0044FF"
  steel:      "#886655"
  accent:     "#006640"
  glow:       "#CC4400"
  cream:      "#D4B898"
typography:
  display-hero:
    fontFamily: Big Shoulders Display
    fontSize: 500px
    fontWeight: 700
    lineHeight: 0.9
    letterSpacing: -0.01em
  display-lg:
    fontFamily: Big Shoulders Display
    fontSize: 180px
    fontWeight: 700
    lineHeight: 0.95
    letterSpacing: -0.005em
  system-id:
    fontFamily: Tektur
    fontSize: 40px
    fontWeight: 500
    lineHeight: 1.2
    letterSpacing: 0.02em
  data-label:
    fontFamily: JetBrains Mono
    fontSize: 22px
    fontWeight: 400
    lineHeight: 1.4
    letterSpacing: 0.04em
  data-sm:
    fontFamily: JetBrains Mono
    fontSize: 15px
    fontWeight: 400
    lineHeight: 1.4
    letterSpacing: 0.05em
  ui-header:
    fontFamily: Instrument Sans
    fontSize: 28px
    fontWeight: 700
    lineHeight: 1.2
    letterSpacing: 0.10em
  ui-body:
    fontFamily: Instrument Sans
    fontSize: 26px
    fontWeight: 400
    lineHeight: 1.3
    letterSpacing: 0.08em
spacing:
  base:         60px
  xs:           15px
  sm:           24px
  md:           60px
  lg:          120px
  xl:          240px
  stripe-width: 15px
  stripe-gap:    8px
  stripe-step:  23px
  margin:       80px
  gutter:       60px
rounded:
  none: 0px
  sm:   0px
  md:   0px
  lg:   0px
  full: 0px
components:
  stripe-bundle:
    backgroundColor: "{colors.primary}"
    stripeWidth: "{spacing.stripe-width}"
    stripeGap: "{spacing.stripe-gap}"
    angle: 35deg
  stripe-bundle-spine:
    backgroundColor: "{colors.neutral}"
  flanking-slab-primary:
    backgroundColor: "{colors.secondary}"
  flanking-slab-secondary:
    backgroundColor: "{colors.cream}"
  accent-plane:
    backgroundColor: "{colors.tertiary}"
  corner-accent:
    backgroundColor: "{colors.accent}"
  glow-bloom:
    backgroundColor: "{colors.glow}"
  data-tag:
    textColor: "{colors.steel}"
    typography: "{typography.data-sm}"
  system-header:
    textColor: "{colors.secondary}"
    typography: "{typography.ui-header}"
  reg-mark:
    strokeColor: "{colors.steel}"
    size: 32px
---

# Vectorheart

## Overview

Vectorheart is the aesthetic of the machine in motion. The visual language emerges from industrial systems — power grids, circuit traces, mechanical tolerances, signal flow — yet everything it builds carries an undercurrent of emotional urgency. The form is hard; the force behind it is not. It is designed for outputs, interfaces, and print surfaces where the primary audience is someone who recognizes the energy of precision: a designer, a technician, a listener at a club in the year 2001.

The tone is neither cold nor warm. It is *charged*. Compositions do not rest; they accelerate. Every surface element is placed as if physics demanded it and nothing else would do. The system draws directly from the visual tradition of early-2000s electronic music posters, industrial illustration, and data-dense technical graphics — filtered through an absolute commitment to geometric rigor. The result should feel as though it was labored over by someone at the frontier of their craft: precise, dense, and kinetically alive.

## Colors
The palette channels the thermal register — heat-camera gradients, industrial warning markings, and the glow of overclocked hardware. A warm near-black field cut by signal orange at maximum luminosity.

- **Neutral (#100906):** Warm near-black. The ground has the quality of a dark ceramic surface — fractionally warm, suggesting a material that has absorbed and retained heat over long use.
- **Primary (#FF6200):** Thermal orange. The stripe bundle's signal color. The hue sits at the peak of the thermal scale — not the yellow of flame nor the red of danger, but the orange of maximum-output energy. It is the most luminous primary in the Vectorheart variant set.
- **Secondary (#F8F0E0):** Warm cream white. Flanking slabs and hero typography. Its amber-warm temperature pairs naturally with the primary, reinforcing the thermal character of the system without competing with the orange signal.
- **Tertiary (#0044FF):** Electric blue. The accent plane counterweight. Maximum chromatic opposition to the orange primary — the cold precision of a cutting laser against the thermal diffusion of the main signal.
- **Steel (#886655):** Warm terracotta steel. All technical labels and structural marks. Its brown-red character ties to the warm primary family while remaining subdued enough to function as infrastructure.
- **Accent (#006640):** Deep teal. Reserved for the single corner accent element. Its cool green anchors the composition's opposite pole from the primary without introducing the full opposition of the tertiary blue.

The `glow` token (#CC4400) is a deeper, lower-saturation orange used exclusively for the multi-layer bloom behind the stripe bundle. It should never appear as a solid fill in a visible element.
## Typography

Vectorheart uses three typefaces in strict, non-negotiable roles. Mixing roles breaks the system.

- **Hero Display — Big Shoulders Display Bold:** The structural typeface. Used only for the two or three dominant words in any composition. Set at extreme sizes (typically 400–600px in print contexts), rotated along the composition's diagonal axis, and treated as a load-bearing architectural element rather than text. The letters are as much shape as language.
- **System Identifier — Tektur Medium:** The authority typeface. Used for node IDs, layer names, and short system-level labels (e.g., "VELOCITY.CORE", "LAYER_04"). Always uppercase. Never used for running text.
- **Data Label — JetBrains Mono Regular:** The technical texture. Used for all coordinates, measurements, version strings, and scattered reference codes. Its monospace rhythm creates a sense of systematic observation. Two sizes are defined: `data-label` (22px) for primary labels, `data-sm` (15px) for secondary annotations.
- **UI Header — Instrument Sans Bold:** The masthead typeface. Used only at the very top or bottom of a composition for the identity line ("V E C T O R H E A R T") and footer copy. Always letter-spaced generously. Never used mid-composition.

No italic variants are used. No decorative or script faces. The system achieves tonal range through scale, opacity, and placement — not through typeface variety.

## Layout

The layout is governed by a **diagonal grid** at **35 degrees** overlaid on an orthogonal base grid of 60px. Every primary visual element is aligned to either the orthogonal grid (labels, margins, data blocks) or the diagonal grid (the stripe bundle, accent planes, flanking slabs, hero type). Nothing floats freely.

The stripe bundle defines the primary compositional axis. All other elements are either parallel to it, perpendicular to it, or in deliberate angular opposition to it. The composition is implicitly divided into four zones by the diagonal: the **leading edge** (the zone the bundle enters from), the **trailing edge** (the zone it exits into), and the two **flanking fields** on either side. Each zone has a defined visual density expectation.

The `margin` token (80px) defines the minimum safe zone from any canvas edge to any text element. The `gutter` token (60px) defines the minimum horizontal separation between any two data label columns.

## Elevation & Depth

There are no drop shadows in Vectorheart. Depth is achieved exclusively through **slab stacking** and **glow blooming**.

Slab stacking places a deep `neutral`-toned parallelogram (the shadow slab) behind the primary stripe bundle at a slight offset, creating the visual illusion that the bundle is raised off the surface. The shadow slab uses the `neutral` color at reduced opacity — never a blur, always a hard-edged flat fill.

Glow blooming places multiple semi-transparent fills using the `glow` color at decreasing opacities and increasing widths radiating outward from the bundle center. The layers are stacked in this sequence:

| Layer         | Half-Width | Opacity |
|---------------|-----------|---------|
| Bloom outer   | 520px     | 8       |
| Bloom mid-far | 470px     | 12      |
| Bloom mid     | 420px     | 17      |
| Bloom inner   | 380px     | 22      |
| Bloom core    | 345px     | 20      |

No element in the system uses a CSS `box-shadow`, `filter: drop-shadow`, or equivalent. The only "softness" allowed in the system is achieved through layered flat fills.

## Shapes

Vectorheart has zero border radius across the entire system. Every shape is a polygon — a parallelogram, triangle, or angular irregular form. The `rounded` token scale is defined for completeness, but all values are `0px`. Any circle or arc element is used only as a technical annotation (registration mark, arc callout) — never as a container or background shape.

The **parallelogram** is the native shape of Vectorheart. It is constructed by taking a center line at 35 degrees and offsetting two parallel edges by a `half-width` value perpendicular to that line. The shape has no softness, no chamfer, no taper.

A **flanking slab** is a parallelogram with a narrow half-width (~120px), placed parallel to and adjacent to the main stripe bundle. It creates a sense of lateral pressure and reinforces the directional energy of the composition.

An **accent plane** is an irregular polygon (typically 5–6 points) that occupies a corner of the composition as a flat, solid color field. It always opposes the dominant diagonal energy — if the bundle runs lower-left to upper-right, the accent plane lives in the upper-right or lower-left corner.

## Components

### Stripe Bundle

The core visual engine. A cluster of parallel lines rendered as filled stripes along the 35-degree diagonal axis.

- Stripe width: `{spacing.stripe-width}` (15px)
- Stripe gap: `{spacing.stripe-gap}` (8px)
- Step: `{spacing.stripe-step}` (23px, derived as width + gap)
- Bundle half-width: 290–300px (adjust per canvas scale)
- Color: `{colors.primary}`
- Accompanied always by a dark spine (3–5px wide parallelogram at bundle center, `{colors.neutral}` at high opacity)

### Flanking Slab

A thin parallel parallelogram flanking the stripe bundle on its leading or trailing edge.

- Primary flanking slab: `{colors.secondary}` at ~240 opacity, half-width ~122px
- Secondary echo slab: `{colors.secondary}` at ~115 opacity, half-width ~46px
- Cream ghost slab: `{colors.cream}` at ~50 opacity, half-width ~28px

### Accent Plane

A solid-fill angular polygon acting as a compositional counterweight.

- `{colors.tertiary}` fill, opacity 228
- Thin outline: `{colors.secondary}` at opacity 42, width 1px
- Inner echo outline: same color at opacity 18

### Registration Mark

A crosshair-circle annotation used as a systematic precision detail. Placed at compositional anchor points, canvas corners, grid intersections, and midpoints of canvas edges.

- Circle radius: 16px
- Arm length: 38px (2.4× radius)
- Stroke: `{colors.steel}` at opacity 72, width 1px

### Data Tag

A short text label positioned at a node in the composition.

- Typography: `{typography.data-sm}`
- Color: `{colors.steel}` at opacity 68–140 (varies by label hierarchy)
- Always uppercase
- No background, no border

### System Header

The topmost identity line of the composition.

- Typography: `{typography.ui-header}`
- Color: `{colors.secondary}` at opacity 205
- Letter spacing: 0.10em minimum
- Always accompanied by a subtitle line in `{typography.ui-body}` at reduced opacity

## Do's and Don'ts

- **Do** run hero display type along the diagonal axis (rotated to match the 35° bundle angle)
- **Do** use registration marks at every canvas corner, midpoint, and key compositional node
- **Don't** use more than four colors in a single composition — `neutral`, `primary`, `secondary`, and one of either `tertiary` or `accent`
- **Do** let the lower-right compositional zone breathe with ghost elements (echo stripes, dot fields, arc annotations) rather than heavy solids
- **Don't** use any border radius on any container, button, or shape — Vectorheart has zero softness in its geometry
- **Do** treat data labels as texture: scatter coordinates, version strings, and system IDs throughout the composition at low opacity
- **Don't** use the `primary` color for typography — white or `secondary` on the stripe bundle only
- **Do** always precede the stripe bundle with a shadow slab and glow bloom layers in the draw order
- **Don't** place more than two typefaces on any visible surface; the third (data label) is texture, not type
- **Do** maintain the 80px margin from canvas edge for all text elements
- **Don't** center-align any text element — all labels are left-aligned or positioned at deliberate non-centered offsets
- **Do** use tick marks at regular intervals along the outer edge of the stripe bundle as precision detail
- **Don't** use gradients anywhere in the system; all depth effects are achieved through stacked flat fills
