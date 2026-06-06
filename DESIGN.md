---
name: Midnight Editorial
colors:
  surface: '#111318'
  surface-dim: '#111318'
  surface-bright: '#37393e'
  surface-container-lowest: '#0c0e13'
  surface-container-low: '#191c20'
  surface-container: '#1d2024'
  surface-container-high: '#282a2f'
  surface-container-highest: '#33353a'
  on-surface: '#e2e2e8'
  on-surface-variant: '#c6c6ca'
  inverse-surface: '#e2e2e8'
  inverse-on-surface: '#2e3035'
  outline: '#8f9094'
  outline-variant: '#45474a'
  surface-tint: '#c6c6ca'
  primary: '#c6c6ca'
  on-primary: '#2f3034'
  primary-container: '#121417'
  on-primary-container: '#7d7e82'
  inverse-primary: '#5d5e62'
  secondary: '#e9c349'
  on-secondary: '#3c2f00'
  secondary-container: '#af8d11'
  on-secondary-container: '#342800'
  tertiary: '#c5c7c8'
  on-tertiary: '#2e3132'
  tertiary-container: '#111415'
  on-tertiary-container: '#7c7f80'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e2e2e6'
  primary-fixed-dim: '#c6c6ca'
  on-primary-fixed: '#1a1c1f'
  on-primary-fixed-variant: '#45474a'
  secondary-fixed: '#ffe088'
  secondary-fixed-dim: '#e9c349'
  on-secondary-fixed: '#241a00'
  on-secondary-fixed-variant: '#574500'
  tertiary-fixed: '#e1e3e4'
  tertiary-fixed-dim: '#c5c7c8'
  on-tertiary-fixed: '#191c1d'
  on-tertiary-fixed-variant: '#454748'
  background: '#111318'
  on-background: '#e2e2e8'
  surface-variant: '#33353a'
typography:
  headline-xl:
    fontFamily: Bodoni Moda
    fontSize: 64px
    fontWeight: '600'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Bodoni Moda
    fontSize: 40px
    fontWeight: '500'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Bodoni Moda
    fontSize: 32px
    fontWeight: '500'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Bodoni Moda
    fontSize: 24px
    fontWeight: '500'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Hanken Grotesk
    fontSize: 18px
    fontWeight: '300'
    lineHeight: '1.6'
    letterSpacing: 0.01em
  body-md:
    fontFamily: Hanken Grotesk
    fontSize: 16px
    fontWeight: '300'
    lineHeight: '1.6'
  label-sm:
    fontFamily: Hanken Grotesk
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1'
    letterSpacing: 0.1em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 8px
  container-max: 1440px
  gutter: 32px
  margin-desktop: 80px
  margin-tablet: 40px
  margin-mobile: 24px
---

## Brand & Style

This design system embodies a prestige editorial aesthetic, blending the gravity of a luxury legacy brand with the clarity of modern digital interfaces. The target audience consists of high-net-worth individuals and connoisseurs who value discretion, timelessness, and meticulous attention to detail.

The visual direction is a fusion of **Minimalism** and **High-Contrast Editorial**. It prioritizes a "less but better" philosophy, where every element must justify its existence. The UI evokes an emotional response of calm authority and exclusive sophistication, utilizing vast negative space to frame content as if it were a curated art gallery.

## Colors

The palette is anchored by a deep **Midnight Navy (#121417)** which serves as the primary canvas, providing a sense of infinite depth. High-contrast **Metallic Gold (#D4AF37)** is used sparingly for primary actions, subtle accents, and brand moments, acting as a beacon of luxury against the dark background. 

**Crisp White (#F8F9FA)** is reserved for primary typography and essential iconography to ensure maximum legibility and a "sharp" feel. Background surfaces are layered with a secondary neutral **Charcoal (#2C2E33)** to create subtle structural differentiation without breaking the dark-mode immersion.

## Typography

Typography is the cornerstone of this design system. It utilizes **Bodoni Moda** for headlines to provide a high-contrast, fashion-forward serif feel that signals prestige. Headlines should be set with tight letter spacing and generous leading to maintain an "expensive" look.

For functional text, **Hanken Grotesk** is used in its lighter weights (300/400). This provides a sharp, technical counterpoint to the romanticism of the serif. Labels and small metadata should always be uppercase with increased letter spacing to evoke the feeling of a high-end watch face or architectural blueprint.

## Layout & Spacing

The layout follows a **Fixed Grid** philosophy on desktop to preserve the intentionality of the white space. Content is centered within a 1440px container, utilizing a 12-column grid. 

The spacing rhythm is "breathable." We favor large margins (80px+) to isolate sections, preventing the UI from feeling cluttered or "app-like." On mobile, the grid collapses to 4 columns, but vertical rhythm remains expansive. Avoid dense clusters of information; if a layout feels tight, increase the padding by 1.5x.

## Elevation & Depth

Elevation is achieved through **low-contrast outlines** and **tonal layering** rather than heavy shadows. 

1.  **Base Layer:** Midnight Navy (#121417).
2.  **Elevated Surfaces (Cards/Modals):** A slight shift to Charcoal (#2C2E33) with a 0.5px hairline border in a semi-transparent white (10% opacity).
3.  **Floating Elements:** Use a very large, ultra-soft "ambient" shadow (40px blur, 5% opacity black) to suggest a gentle lift from the surface without creating a "heavy" physical presence.

The goal is to make elements feel like they are floating in a dark, airy void.

## Shapes

The shape language is architectural and precise. We utilize **Soft (0.25rem)** rounding for standard components like buttons and input fields to take the edge off the "brutalist" sharpness while maintaining a professional, rigid structure. 

Larger containers or sections should remain strictly square (0px) to reinforce the editorial grid. This contrast between "slightly soft" interactive elements and "sharp" structural containers creates a sophisticated visual tension.

## Components

### Buttons
Primary buttons should be ghost-style with a fine Gold border or solid Gold with Midnight Navy text. Hover states involve a subtle glow or a slight scale increase (1.02x) rather than a drastic color change.

### Input Fields
Inputs are minimalist: a single 1px bottom border in Charcoal, moving to Gold on focus. Placeholders should be set in Hanken Grotesk 300 with high transparency.

### Cards
Cards should not have backgrounds by default. Use 1px borders to define their boundaries. For featured content, use a background of Charcoal (#2C2E33) to create a "container within a container" effect.

### Chips & Tags
Small, pill-shaped outlines with uppercase label-sm typography. These act as subtle metadata markers and should never compete with primary actions.

### Navigation
Top-level navigation should be centered with generous spacing between items. Use a "fade-in" transition for hover states to maintain the graceful, premium feel of the system.