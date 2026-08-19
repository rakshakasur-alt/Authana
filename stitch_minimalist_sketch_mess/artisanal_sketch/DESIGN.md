---
name: Artisanal Sketch
colors:
  surface: '#faf9f7'
  surface-dim: '#dadad8'
  surface-bright: '#faf9f7'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f4f3f1'
  surface-container: '#efeeec'
  surface-container-high: '#e9e8e6'
  surface-container-highest: '#e3e2e0'
  on-surface: '#1a1c1b'
  on-surface-variant: '#58423c'
  inverse-surface: '#2f3130'
  inverse-on-surface: '#f1f1ef'
  outline: '#8b716a'
  outline-variant: '#dfc0b8'
  surface-tint: '#a63a1a'
  primary: '#a33818'
  on-primary: '#ffffff'
  primary-container: '#c44f2e'
  on-primary-container: '#fffbff'
  inverse-primary: '#ffb5a0'
  secondary: '#5f5e5e'
  on-secondary: '#ffffff'
  secondary-container: '#e4e2e1'
  on-secondary-container: '#656464'
  tertiary: '#006578'
  on-tertiary: '#ffffff'
  tertiary-container: '#008098'
  on-tertiary-container: '#f9fdff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdbd1'
  primary-fixed-dim: '#ffb5a0'
  on-primary-fixed: '#3b0900'
  on-primary-fixed-variant: '#862303'
  secondary-fixed: '#e4e2e1'
  secondary-fixed-dim: '#c8c6c6'
  on-secondary-fixed: '#1b1c1c'
  on-secondary-fixed-variant: '#474747'
  tertiary-fixed: '#afecff'
  tertiary-fixed-dim: '#73d4ef'
  on-tertiary-fixed: '#001f27'
  on-tertiary-fixed-variant: '#004e5d'
  background: '#faf9f7'
  on-background: '#1a1c1b'
  surface-variant: '#e3e2e0'
typography:
  display-lg:
    fontFamily: Bricolage Grotesque
    fontSize: 48px
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Bricolage Grotesque
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-sm:
    fontFamily: Bricolage Grotesque
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.2'
  body-lg:
    fontFamily: Work Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Work Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-caps:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1.0'
    letterSpacing: 0.1em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 8px
  gutter: 24px
  margin-mobile: 20px
  margin-desktop: 64px
  stack-sm: 12px
  stack-md: 32px
  stack-lg: 64px
---

## Brand & Style

This design system is built on a "Conceptual Sketch" aesthetic, blending the precision of high-end minimalism with the warmth of a chef's hand-drawn notes. It targets urban professionals and students who value transparency, simplicity, and the human touch behind their daily meals. 

The visual narrative avoids the glossy, over-processed imagery of typical food apps, opting instead for an "In-Progress" creative feel. This evokes honesty and craft. The style utilizes heavy white space, organic line weights, and scribbled texture overlays to create a tactile, paper-like experience.

## Colors

The palette is strictly curated to maintain a monochromatic, paper-like foundation with a singular functional spark.

*   **Primary (Terracotta):** Used exclusively for Call-to-Action elements, critical status indicators, and subtle highlights in sketches. It represents heat, spices, and appetite.
*   **Secondary (Charcoal):** Used for all primary text, iconography, and hand-drawn borders. It provides a high-contrast, "ink on paper" feel.
*   **Neutral (Parchment):** A very light, warm off-white used for the global background to reduce the harshness of pure white and enhance the "sketchbook" vibe.
*   **Scribble Gray:** A mid-tone gray used for background textures and non-interactive decorative strokes.

## Typography

This design system uses a rhythmic contrast between three distinct typefaces:

1.  **Headlines (Bricolage Grotesque):** Selected for its quirky, variable-width characteristics that mimic the ink-bleed and personality of hand-lettering while remaining professional.
2.  **Body (Work Sans):** A neutral, highly legible sans-serif for menus, descriptions, and functional text.
3.  **Labels (JetBrains Mono):** Used for technical details (calories, time, price) to evoke the feeling of a stamped receipt or a kitchen order ticket.

**Implementation Note:** Use "Display" styles sparingly for hero sections. Headlines should often be paired with a subtle `2deg` rotation to enhance the "sketched" feel.

## Layout & Spacing

The layout philosophy follows a **"Breathing Grid."** While structured, it avoids rigid boxes.

*   **Fluidity:** Elements should have generous margins. Use a 12-column grid for desktop but allow components to offset slightly (3-5px) from the grid lines to break the digital perfection.
*   **Asymmetry:** Groupings should feel organic. For example, a tiffin description might be left-aligned while its price tag is "floating" nearby with an arrow sketch pointing to it.
*   **White Space:** Treat white space as a physical material. It represents the cleanliness of the kitchen and the focus of the service.

## Elevation & Depth

Standard shadows are strictly forbidden in this design system. Depth is communicated through **Layered Linework**:

*   **Tonal Stacking:** Higher elevation items (like modals) sit on a slightly darker neutral background or use a heavy 2px charcoal border to separate themselves.
*   **The "Double Stroke":** For primary cards, use a secondary "ghost" border offset by 4px to the bottom-right, mimicking a hand-drawn drop shadow effect.
*   **Scribble Fills:** Instead of semi-transparent overlays, use a light "cross-hatch" pattern or scribbled texture to indicate an area is disabled or in a background state.

## Shapes

Shapes are intentionally imperfect. 

*   **Borders:** Use a `border-width` of 1.5px to 2px for all containers. Apply a CSS `mask-image` or a slight `SVG` distortion to border strokes to make them look like ink on paper rather than a vector line.
*   **Corners:** Use "Soft" (0.25rem) roundedness to prevent the UI from feeling sharp or aggressive, but keep them tight enough to feel like a notebook.
*   **Abstract Shapes:** Use hand-drawn circles (circles that don't quite close) and "underline" scribbles to highlight key text.

## Components

*   **Buttons:** Rectangular with a heavy 2px border. The primary CTA uses a solid Terracotta fill with white text. On hover, the button should "wiggle" slightly using a subtle transform scale.
*   **Cards:** Use a simple outline with a "scribble" texture in the corner. No images—instead, use abstract sketch icons of ingredients (e.g., a simple line-art chili or a grain of rice).
*   **Input Fields:** A single bottom border (ink line) rather than a full box. The cursor should be slightly thicker than usual to match the Charcoal line weight.
*   **Chips/Tags:** Look like pieces of masking tape. Use a slightly different neutral tint (#F0EFEA) and no border, with a jagged edge effect on the left and right.
*   **Lists:** Separated by "pencil-thin" horizontal lines that don't reach the full width of the container, appearing like a handwritten list.
*   **Progress Indicators:** Use a "filling-in" scribble animation rather than a smooth loading bar.