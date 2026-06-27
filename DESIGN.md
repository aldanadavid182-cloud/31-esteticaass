---
name: Vibrant Elegance
colors:
  surface: '#f9f9f9'
  surface-dim: '#dadada'
  surface-bright: '#f9f9f9'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f3f4'
  surface-container: '#eeeeee'
  surface-container-high: '#e8e8e8'
  surface-container-highest: '#e2e2e2'
  on-surface: '#1a1c1c'
  on-surface-variant: '#594049'
  inverse-surface: '#2f3131'
  inverse-on-surface: '#f0f1f1'
  outline: '#8d6f79'
  outline-variant: '#e1bdc8'
  surface-tint: '#b8006d'
  primary: '#ac0066'
  on-primary: '#ffffff'
  primary-container: '#d90082'
  on-primary-container: '#fff3f5'
  inverse-primary: '#ffb0cd'
  secondary: '#6b38d4'
  on-secondary: '#ffffff'
  secondary-container: '#8455ef'
  on-secondary-container: '#fffbff'
  tertiary: '#6d5439'
  on-tertiary: '#ffffff'
  tertiary-container: '#876c4f'
  on-tertiary-container: '#fff5ed'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffd9e4'
  primary-fixed-dim: '#ffb0cd'
  on-primary-fixed: '#3e0021'
  on-primary-fixed-variant: '#8d0052'
  secondary-fixed: '#e9ddff'
  secondary-fixed-dim: '#d0bcff'
  on-secondary-fixed: '#23005c'
  on-secondary-fixed-variant: '#5516be'
  tertiary-fixed: '#ffddbb'
  tertiary-fixed-dim: '#e3c19f'
  on-tertiary-fixed: '#291803'
  on-tertiary-fixed-variant: '#5a4229'
  background: '#f9f9f9'
  on-background: '#1a1c1c'
  surface-variant: '#e2e2e2'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 34px
  headline-md:
    fontFamily: Playfair Display
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Montserrat
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Montserrat
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-lg:
    fontFamily: Montserrat
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.1em
  button:
    fontFamily: Montserrat
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 24px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  xs: 4px
  sm: 12px
  md: 24px
  lg: 40px
  xl: 64px
  touch-target-min: 44px
  container-margin: 20px
---

## Brand & Style
The design system for Elite Beauty is built on a foundation of "Vibrant Elegance," specifically tailored for the Mexican beauty and wellness market. The brand personality is high-end, energetic, and authoritative, balancing the traditional sophistication of luxury cosmetics with the vivid, contemporary energy of Mexican aesthetics.

The design style avoids digital abstractions like glassmorphism or heavy blurs, opting instead for a **High-Contrast / Modern** approach. It utilizes solid architectural planes, crisp borders, and deliberate shadows to create a tactile sense of premium physical packaging. The UI serves as a minimal, structured frame to showcase high-fidelity photography of real people and products, ensuring the focus remains on tangible results and authentic beauty.

## Colors
The palette is dominated by a "Pure White" base to provide a clean, clinical, yet luxurious environment. The primary signature color is **Fuchsia (#D90082)**, used for high-intent actions and brand recognition. 

- **Primary (Fuchsia):** Used for primary buttons, active states, and critical branding.
- **Secondary (Vibrant Lilac/Purple):** Used for category accents and subtle highlights.
- **Tertiary (Dusty Rose/Gold):** Gold is reserved for "Elite" or "Premium" tiers and membership status. Dusty Rose acts as a soft neutral-adjacent color for backgrounds or secondary UI elements.
- **Typography:** Deep charcoal or near-black is used for text to maintain accessibility and high contrast against the white base.

## Typography
The typographic hierarchy utilizes a high-contrast pairing to evoke editorial luxury. 

**Playfair Display** is used for all headlines and display text. Its high-contrast strokes reflect the elegance of fashion mastheads. **Montserrat** is the workhorse for body copy and UI elements, chosen for its geometric clarity and readability at various scales. 

In accordance with the mobile-first focus, the minimum body size is 16px to ensure effortless legibility. Mexican Spanish often requires more horizontal space than English; therefore, line heights are generous (1.5x for body) to prevent dense text blocks and maintain a light, airy feel.

## Layout & Spacing
The layout follows a **Fluid Grid** model with a heavy emphasis on mobile ergonomics. For mobile devices, a 4-column grid is used with 20px side margins. For desktop, a 12-column grid centers the content with a max-width of 1280px.

Spacing is strictly based on an 8px scale. To ensure accessibility, all interactive elements (buttons, inputs, toggles) have a minimum height of **44px**. White space is treated as a luxury asset; generous padding (24px+) between sections is encouraged to prevent the UI from feeling cluttered or "discount."

## Elevation & Depth
This design system rejects soft blurs and gradients in favor of **Sharp Shadows** and defined boundaries. Depth is communicated through:

1.  **Solid Borders:** Elements are defined by 1px solid borders in light grey or gold.
2.  **Hard Shadows:** Elevation is achieved using small offsets (e.g., 4px or 8px) with higher opacity and 0-4px blur radii. This creates a "cut-out" or "stacked paper" effect.
3.  **Flat Planes:** Backgrounds remain solid white or very light Dusty Rose. There are no translucent or "glassy" layers. Higher elevation levels use more pronounced, darker shadows rather than changing background opacity.

## Shapes
The shape language combines the structural integrity of the grid with the approachable softness of beauty products. 

A standard **8px (0.5rem)** radius is used for small components like inputs and secondary buttons. Large components, such as product cards and promotional banners, use a **16px (1rem)** radius to create a more inviting, modern aesthetic. Circular shapes are reserved strictly for avatars or specific status indicators.

## Components

### Buttons
Primary buttons are solid Fuchsia with white Montserrat Bold text. They use the `rounded-lg` (16px) treatment to feel premium. Secondary buttons use a 1px Gold or Magenta border with a white background. All buttons must maintain a 44px minimum height for mobile touch-targets.

### Input Fields
Fields use a solid 1px border (#E5E5E5) that shifts to Fuchsia on focus. Labels are always visible above the field in Montserrat (Label-lg) for clarity. Error states use a clear Magenta highlight.

### Cards
Cards are the primary container for product and treatment photography. They feature a white background, the "Sharp Shadow" elevation, and 16px rounded corners. Photography within cards should be full-bleed at the top to emphasize real-world results.

### Chips & Tags
Used for skin types (e.g., "Piel Grasa", "Piel Seca") or treatment categories. These use the "Dusty Rose" background with dark text and a pill-shape (rounded-full) to contrast against the more rectangular card structures.

### Imagery
Real photography only. No illustrations for people. Images should have high saturation and clear lighting to match the "Vibrant" brand pillar. People should be depicted in natural, high-quality settings that reflect the Elite Beauty lifestyle.