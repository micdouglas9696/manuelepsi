---
name: Serene Equilibrium
colors:
  surface: '#fcf9f4'
  surface-dim: '#dcdad5'
  surface-bright: '#fcf9f4'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3ee'
  surface-container: '#f0ede9'
  surface-container-high: '#ebe8e3'
  surface-container-highest: '#e5e2dd'
  on-surface: '#1c1c19'
  on-surface-variant: '#54433e'
  inverse-surface: '#31302d'
  inverse-on-surface: '#f3f0eb'
  outline: '#87736c'
  outline-variant: '#dac1ba'
  surface-tint: '#95482f'
  primary: '#91452c'
  on-primary: '#ffffff'
  primary-container: '#af5d42'
  on-primary-container: '#fffaf9'
  inverse-primary: '#ffb59e'
  secondary: '#675d4d'
  on-secondary: '#ffffff'
  secondary-container: '#f0e0cc'
  on-secondary-container: '#6e6353'
  tertiary: '#69584b'
  on-tertiary: '#ffffff'
  tertiary-container: '#827062'
  on-tertiary-container: '#fffaf8'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdbd0'
  primary-fixed-dim: '#ffb59e'
  on-primary-fixed: '#390b00'
  on-primary-fixed-variant: '#77321a'
  secondary-fixed: '#f0e0cc'
  secondary-fixed-dim: '#d3c4b1'
  on-secondary-fixed: '#221a0e'
  on-secondary-fixed-variant: '#4f4537'
  tertiary-fixed: '#f6decd'
  tertiary-fixed-dim: '#d9c2b2'
  on-tertiary-fixed: '#25190f'
  on-tertiary-fixed-variant: '#534437'
  background: '#fcf9f4'
  on-background: '#1c1c19'
  surface-variant: '#e5e2dd'
typography:
  display-lg:
    fontFamily: Libre Caslon Text
    fontSize: 48px
    fontWeight: '400'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Libre Caslon Text
    fontSize: 32px
    fontWeight: '400'
    lineHeight: '1.3'
  headline-lg-mobile:
    fontFamily: Libre Caslon Text
    fontSize: 28px
    fontWeight: '400'
    lineHeight: '1.3'
  headline-md:
    fontFamily: Libre Caslon Text
    fontSize: 24px
    fontWeight: '400'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Manrope
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Manrope
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-md:
    fontFamily: Manrope
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  section-padding-desktop: 120px
  section-padding-mobile: 64px
  gutter: 24px
  max-width: 1140px
---

## Brand & Style

This design system is built for a clinical psychology practice that prioritizes human connection over clinical sterility. The brand personality is empathetic, grounded, and sophisticated, aiming to evoke a sense of immediate psychological safety and professional reliability. 

The visual style is **Sophisticated Minimalism**. It leverages generous whitespace to provide "breathing room" for the user, mirroring the mental space provided in therapy. By avoiding harsh edges and high-contrast clinical whites, the interface feels organic and welcoming. The aesthetic is informed by editorial design, using high-quality typography and a warm, earth-toned palette to establish a premium, trustworthy presence that feels more like a wellness retreat or a high-end lifestyle journal than a medical portal.

## Colors

The palette is rooted in nature and warmth. The primary color is a muted **Terracotta**, used strategically for calls to action and key brand moments to provide a sense of grounded energy. The secondary **Soft Beige** and neutral **Off-White** (Bone) form the foundation of the interface, ensuring the UI feels soft and non-threatening.

- **Primary (Terracotta):** Reserved for primary buttons, active states, and meaningful accents.
- **Secondary (Sand):** Used for subtle section backgrounds and decorative elements.
- **Tertiary (Warm Taupe):** Ideal for secondary text, icons, and borders where high contrast isn't required.
- **Neutral (Bone/Off-White):** The primary background color to avoid the "blue-light" harshness of pure white.
- **Text:** A deep, warm charcoal (#2D2926) is used instead of pure black to maintain the soft visual hierarchy.

## Typography

The typography pairing balances tradition with modernity. **Libre Caslon Text** provides an authoritative yet graceful serif for headlines, conveying years of academic and clinical experience. **Manrope** is used for body text and functional labels; its geometric yet friendly structure ensures high legibility across all age groups.

Maintain a "loose" line height (1.6) for body text to improve readability for users who may be under stress. Headlines should use "tight" tracking (-0.01em) to feel cohesive and editorial. Use the uppercase label style sparingly for navigation or small categorizations to maintain a clean, uncluttered look.

## Layout & Spacing

The layout follows a **Fixed Grid** philosophy on desktop to ensure content remains centered and focused, preventing visual overwhelm. On mobile, it transitions to a fluid model with generous margins.

- **Desktop:** 12-column grid, 1140px max-width, 24px gutters.
- **Tablet:** 8-column grid, 32px side margins.
- **Mobile:** 4-column grid, 20px side margins.

Horizontal spacing between sections should be significant (120px on desktop) to enforce the minimalist aesthetic. Elements within a group (e.g., a header and its subtext) should use a consistent 16px or 24px vertical rhythm.

## Elevation & Depth

To maintain the "humanized" feel, this design system avoids heavy, artificial drop shadows. Instead, it uses **Tonal Layers** and **Ambient Shadows**.

- **Surface Tiers:** Use subtle shifts between Neutral (Bone) and Secondary (Sand) to define different content areas.
- **Shadows:** When necessary (e.g., for cards or hover states), use a very soft, diffused shadow: `0 8px 30px rgba(125, 107, 93, 0.08)`. The shadow color should be tinted with the Tertiary taupe rather than pure black to keep the depth feeling natural and "warm."
- **Interactive Depth:** On hover, buttons and cards should lift slightly (2-4px) rather than glow, mimicking a physical tactile response.

## Shapes

The shape language is deliberately soft. Sharp corners are avoided to minimize any sense of "edge" or aggression. 

- **Primary UI Elements:** Buttons, input fields, and small containers use a 0.5rem (8px) radius.
- **Large Containers:** Cards and image containers use a 1.5rem (24px) radius to create a distinct, friendly framing effect.
- **Icons:** Should feature rounded terminals and soft joins to match the typography and container language.

## Components

### Buttons
Primary buttons are solid Terracotta with white or Bone text. Secondary buttons use a taupe outline with a 1px border. All buttons have a gentle 300ms transition on hover, where the primary button slightly darkens or adds a subtle ambient shadow.

### Input Fields
Inputs feature a Bone background and a soft Sand border. On focus, the border transitions to Terracotta. Labels sit above the field in the `label-md` style. Error states should use a muted sage green or deep rose rather than a jarring bright red.

### Cards
Cards are used for blog posts or service descriptions. They feature a 24px corner radius, a subtle Sand border, and no shadow in their default state. On hover, they gain the "Ambient Shadow" and lift 4px.

### Chips/Tags
Used for categorizing therapeutic areas (e.g., "Anxiety," "CBT"). These are pill-shaped with a Sand background and Taupe text.

### Imagery
Images should have soft, rounded corners and focus on natural light, organic textures (linen, wood, plants), and genuine human emotion. Avoid stock photography that feels overly staged or "corporate."