---
name: Clinical Clarity
colors:
  surface: '#f9f9ff'
  surface-dim: '#cfdaf2'
  surface-bright: '#f9f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f0f3ff'
  surface-container: '#e7eeff'
  surface-container-high: '#dee8ff'
  surface-container-highest: '#d8e3fb'
  on-surface: '#111c2d'
  on-surface-variant: '#434655'
  inverse-surface: '#263143'
  inverse-on-surface: '#ecf1ff'
  outline: '#747686'
  outline-variant: '#c4c5d7'
  surface-tint: '#2151da'
  primary: '#0037b0'
  on-primary: '#ffffff'
  primary-container: '#1d4ed8'
  on-primary-container: '#cad3ff'
  inverse-primary: '#b7c4ff'
  secondary: '#0058be'
  on-secondary: '#ffffff'
  secondary-container: '#2170e4'
  on-secondary-container: '#fefcff'
  tertiary: '#3e454c'
  on-tertiary: '#ffffff'
  tertiary-container: '#555d64'
  on-tertiary-container: '#ced6de'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dce1ff'
  primary-fixed-dim: '#b7c4ff'
  on-primary-fixed: '#001551'
  on-primary-fixed-variant: '#0039b5'
  secondary-fixed: '#d8e2ff'
  secondary-fixed-dim: '#adc6ff'
  on-secondary-fixed: '#001a42'
  on-secondary-fixed-variant: '#004395'
  tertiary-fixed: '#dce3ec'
  tertiary-fixed-dim: '#c0c7d0'
  on-tertiary-fixed: '#151c23'
  on-tertiary-fixed-variant: '#40484f'
  background: '#f9f9ff'
  on-background: '#111c2d'
  surface-variant: '#d8e3fb'
typography:
  display-lg:
    fontFamily: Hanken Grotesk
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Hanken Grotesk
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Hanken Grotesk
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-sm:
    fontFamily: Hanken Grotesk
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Manrope
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Manrope
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Manrope
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.05em
  caption:
    fontFamily: Manrope
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 40px
---

## Brand & Style
The design system is engineered to foster an environment of professional growth and academic excellence. Targeting medical students and young healthcare professionals, the aesthetic prioritizes trust, precision, and efficiency. 

The visual style is **Corporate Modern** with a focus on high legibility and systematic organization. It leverages ample whitespace to reduce cognitive load—essential for a user base dealing with dense medical information. Subtle gradients and soft shadows are used to provide a sense of depth without distracting from the primary task: professional networking and skill acquisition. The atmosphere is clinical yet welcoming, bridging the gap between rigorous institutional standards and modern digital accessibility.

## Colors
The palette is rooted in medical blue tones to evoke reliability and authority.
- **Primary Blue:** Used for high-emphasis actions, branding, and active states.
- **Secondary Blue:** Used for secondary buttons, interactive highlights, and supportive iconography.
- **Tertiary Blue:** A soft wash for backgrounds, container fills, and subtle separation between sections.
- **Neutral:** A deep slate used for maximum text legibility and structural borders.

Maintain a minimum contrast ratio of 4.5:1 for all informative text against its background. Use the tertiary tint to create "card-on-canvas" layouts where the background is slightly darker than the white card surfaces.

## Typography
This design system utilizes two high-performance sans-serifs. **Hanken Grotesk** provides a sharp, contemporary look for headlines, conveying a sense of forward-thinking medical education. **Manrope** is used for body text and UI labels due to its exceptional clarity at small sizes and balanced proportions.

Hierarchy should be strictly enforced. Use `label-md` for small sub-headers above titles to provide context (e.g., "UPCOMING WORKSHOP"). `display-lg` is reserved for hero sections and major landing pages.

## Layout & Spacing
The design system employs a **12-column fluid grid** for desktop and a **4-column grid** for mobile. A strict 8px base unit (1rem = 16px) governs all spacing decisions to ensure vertical rhythm and alignment.

- **Desktop:** 1280px max-width, 24px gutters, 40px side margins.
- **Tablet:** Fluid width, 20px gutters, 24px side margins.
- **Mobile:** Fluid width, 16px gutters, 16px side margins.

**Motion Principles:** 
Animations must feel purposeful and light. 
1. **Fades:** Used for state changes and content loading (300ms expressive).
2. **Slides:** Used for modal entries (bottom-up) and navigation transitions (left-to-right) using the productive easing for a snappier feel.

## Elevation & Depth
Depth is created through a combination of tonal layering and soft, ambient shadows. We avoid heavy borders in favor of subtle contrast.

- **Level 0 (Flat):** Main background surface.
- **Level 1 (Card):** White surface on a light gray background with a soft shadow: `0 4px 6px -1px rgba(0, 0, 0, 0.05), 0 2px 4px -1px rgba(0, 0, 0, 0.03)`.
- **Level 2 (Hover/Active):** Slightly more pronounced shadow to indicate interactivity: `0 10px 15px -3px rgba(0, 0, 0, 0.08)`.
- **Level 3 (Modals/Overlays):** High depth to pull focus: `0 20px 25px -5px rgba(0, 0, 0, 0.1)`.

Interactive elements like buttons use a primary blue tint for their shadows when focused, reinforcing the brand color.

## Shapes
The design system uses a "Rounded" (Level 2) logic. This creates a friendly yet professional appearance that feels more modern than sharp corners but more serious than pill shapes.

- **Standard (0.5rem):** Buttons, input fields, small cards.
- **Large (1rem):** Seminar detail cards, featured section containers.
- **Extra Large (1.5rem):** Modals and bottom sheets on mobile.

## Components
- **Buttons:** Primary buttons use a solid blue fill with white text. Secondary buttons use a primary blue outline and transparent background. All buttons have a height of 48px for better touch targets.
- **Chips:** Used for seminar categories (e.g., "Cardiology", "Surgery"). They use the Tertiary Blue background with a Primary Blue text color and 0.25rem roundedness.
- **Input Fields:** Minimum height of 48px with a 1px slate-200 border. On focus, the border transitions to Primary Blue with a subtle 2px glow.
- **Cards:** White background, Level 1 elevation. Images within cards should have a top-only 1rem corner radius to match the card container.
- **Progress Indicators:** Simple, thin horizontal bars in Primary Blue for multi-step registration or booking processes.
- **Checkboxes & Radios:** Use Primary Blue for the checked state. Checkboxes should have a slightly rounded corner (2px) to match the overall shape language.