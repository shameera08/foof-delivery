---
name: Zest & Velocity
colors:
  surface: '#f8f9fa'
  surface-dim: '#d9dadb'
  surface-bright: '#f8f9fa'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f4f5'
  surface-container: '#edeeef'
  surface-container-high: '#e7e8e9'
  surface-container-highest: '#e1e3e4'
  on-surface: '#191c1d'
  on-surface-variant: '#584235'
  inverse-surface: '#2e3132'
  inverse-on-surface: '#f0f1f2'
  outline: '#8c7263'
  outline-variant: '#e0c0af'
  surface-tint: '#994700'
  primary: '#994700'
  on-primary: '#ffffff'
  primary-container: '#ff7a00'
  on-primary-container: '#5c2800'
  inverse-primary: '#ffb68b'
  secondary: '#5f5e5e'
  on-secondary: '#ffffff'
  secondary-container: '#e2dfde'
  on-secondary-container: '#636262'
  tertiary: '#8c5000'
  on-tertiary: '#ffffff'
  tertiary-container: '#ea8800'
  on-tertiary-container: '#542d00'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdbc8'
  primary-fixed-dim: '#ffb68b'
  on-primary-fixed: '#321200'
  on-primary-fixed-variant: '#753400'
  secondary-fixed: '#e5e2e1'
  secondary-fixed-dim: '#c8c6c5'
  on-secondary-fixed: '#1c1b1b'
  on-secondary-fixed-variant: '#474746'
  tertiary-fixed: '#ffdcbf'
  tertiary-fixed-dim: '#ffb874'
  on-tertiary-fixed: '#2d1600'
  on-tertiary-fixed-variant: '#6a3b00'
  background: '#f8f9fa'
  on-background: '#191c1d'
  surface-variant: '#e1e3e4'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 48px
    fontWeight: '800'
    lineHeight: 56px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '800'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
rounded:
  sm: 0.5rem
  DEFAULT: 1rem
  md: 1.5rem
  lg: 2rem
  xl: 3rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 20px
  margin-desktop: 80px
---

## Brand & Style
This design system is engineered for a high-energy, modern food delivery platform. The brand personality is "The Reliable Connoisseur"—fast and efficient, yet deeply appreciative of culinary quality. It prioritizes clarity and speed of use while evoking an appetizing emotional response through vibrant accents and tactile depth.

The visual style follows a **Modern Corporate** aesthetic infused with **Soft-Tactile** elements. This is achieved through generous whitespace, ultra-refined typography, and "squishy" interactive elements that feel responsive to the touch. The interface avoids the sterile look of traditional SaaS by using organic shapes and warm lighting effects, ensuring the food remains the hero of the experience.

## Colors
The color palette is anchored by "Zest Orange," a high-chroma primary hue designed to stimulate appetite and signify urgency. 

- **Primary (#FF7A00):** Used for primary actions, progress indicators, and brand-critical touchpoints.
- **Secondary (#1A1A1A):** A deep charcoal used for maximum legibility in typography and high-contrast iconography.
- **Tertiary (#FF9500):** A lighter orange used specifically for gradient highlights and hover states to add dimensionality.
- **Neutral (#F8F9FA):** A cool, clean gray used for large background surfaces to allow food photography to pop without visual competition.
- **Surface:** Pure White (#FFFFFF) is reserved for interactive cards and input fields to create a clear "layered" hierarchy over the neutral background.

## Typography
The typography strategy utilizes a dual-font approach to balance personality with functional utility. 

**Plus Jakarta Sans** is used for all headlines and display text. Its slightly rounded terminals and wide apertures feel welcoming and modern, while the Bold and ExtraBold weights provide the "impact" required for food category headers.

**Inter** is used for all body copy, descriptions, and UI labels. It was chosen for its exceptional legibility at small sizes, which is critical for menu item descriptions, pricing, and nutritional information. All body text should maintain a minimum weight of 400 to ensure accessibility against the light gray backgrounds.

## Layout & Spacing
This design system employs a **Fluid Grid** model based on an 8px square rhythm. All spatial relationships must be multiples of 8 (8, 16, 24, 32, 48, 64).

- **Desktop:** A 12-column grid with a 1280px max-width container. 24px gutters provide breathing room between food cards.
- **Mobile:** A 4-column grid with 20px side margins. 
- **Rhythm:** Vertical spacing between disparate sections (e.g., "Trending Now" vs "Cuisines") should be 64px on desktop and 40px on mobile to maintain a "fresh" and airy feel.

## Elevation & Depth
Hierarchy is established through **Ambient Shadows** and tonal layering. This design system avoids harsh borders in favor of soft, diffused shadows that simulate a natural light source from the top-center.

1.  **Level 0 (Background):** The neutral gray background (#F8F9FA).
2.  **Level 1 (Cards/Surface):** White surfaces with a very soft shadow (0px 4px 20px rgba(0,0,0,0.05)).
3.  **Level 2 (Interactive/Hover):** When a user interacts with a restaurant card, the shadow intensifies (0px 12px 32px rgba(255,122,0,0.12)), adding a subtle orange tint to the glow to reinforce the brand color.
4.  **Level 3 (Modals/Overlays):** High-diffusion shadows to pull the element significantly forward from the rest of the UI.

## Shapes
The shape language is defined by **Pill-shaped** and highly rounded geometries. This friendliness reflects the "accessible" nature of a food delivery service.

- **Standard Elements:** Buttons and Input fields use a 1rem (16px) radius.
- **Containers:** Large cards (restaurants, promotions) use a 2rem (32px) radius to create a distinct, modern look.
- **Icons:** Should always be enclosed in a rounded square or circle container to maintain the soft visual language.

## Components

### Buttons
Primary buttons utilize a subtle linear gradient (from #FF7A00 at the top to #FF9500 at the bottom). They feature a 16px border radius and use White text in Bold weight. Shadow-based depth is applied on hover to make the button feel "clickable."

### Cards
Restaurant and food item cards are the cornerstone of the UI. They feature a 32px corner radius, a pure white background, and no border. The image should occupy the top 60% of the card with a "bottom-bleed" transition into the text area.

### Input Fields
Inputs are styled with the Neutral background (#F8F9FA) and a 16px radius. When focused, the background turns White and a 2px stroke of Primary Orange is applied.

### Chips (Cuisines/Filters)
Chips use a pill-shape (fully rounded). Inactive chips use a light gray stroke; active chips transition to a solid Primary Orange background with white text.

### Progress Indicators
Delivery tracking should use a custom "soft-line" indicator—thick 8px lines with rounded caps, using the primary gradient to indicate completion.