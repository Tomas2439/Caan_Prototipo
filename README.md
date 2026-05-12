---
name: Caan_Prototipo
colors:
  surface: '#f8faf6'
  surface-dim: '#d8dbd7'
  surface-bright: '#f8faf6'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f4f0'
  surface-container: '#eceeea'
  surface-container-high: '#e7e9e5'
  surface-container-highest: '#e1e3df'
  on-surface: '#191c1a'
  on-surface-variant: '#404943'
  inverse-surface: '#2e312f'
  inverse-on-surface: '#eff1ed'
  outline: '#707973'
  outline-variant: '#bfc9c1'
  surface-tint: '#2c694e'
  primary: '#0f5238'
  on-primary: '#ffffff'
  primary-container: '#2d6a4f'
  on-primary-container: '#a8e7c5'
  inverse-primary: '#95d4b3'
  secondary: '#895100'
  on-secondary: '#ffffff'
  secondary-container: '#fd9d1a'
  on-secondary-container: '#663b00'
  tertiary: '#713638'
  on-tertiary: '#ffffff'
  tertiary-container: '#8d4d4e'
  on-tertiary-container: '#ffcfce'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#b1f0ce'
  primary-fixed-dim: '#95d4b3'
  on-primary-fixed: '#002114'
  on-primary-fixed-variant: '#0e5138'
  secondary-fixed: '#ffdcbc'
  secondary-fixed-dim: '#ffb86b'
  on-secondary-fixed: '#2c1700'
  on-secondary-fixed-variant: '#683d00'
  tertiary-fixed: '#ffdad9'
  tertiary-fixed-dim: '#ffb3b3'
  on-tertiary-fixed: '#390b0e'
  on-tertiary-fixed-variant: '#6f3537'
  background: '#f8faf6'
  on-background: '#191c1a'
  surface-variant: '#e1e3df'
typography:
  h1:
    fontFamily: Plus Jakarta Sans
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
  h2:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '700'
    lineHeight: '1.2'
  h3:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Be Vietnam Pro
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Be Vietnam Pro
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-sm:
    fontFamily: Be Vietnam Pro
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.02em
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
  lg: 48px
  xl: 80px
  container_max: 1280px
  gutter: 24px
---

## Brand & Style

The brand personality of this design system is compassionate, reliable, and deeply human-centric. It targets animal lovers, potential adopters, and community advocates, evoking feelings of safety, warmth, and hope. The UI facilitates an emotional connection between the user and the animals through a "Soft Modern" aesthetic.

The design style blends **Minimalism** with **Tactile** elements. By using generous whitespace and high-quality photography, the focus remains on the animals. Subtle shadows and organic shapes provide a sense of approachability, moving away from corporate rigidity toward a welcoming, community-focused digital environment.

## Colors

The palette is anchored by an earthy "Forest Green" primary color, symbolizing growth and nature, paired with a "Soft Orange" secondary color for highlights and energy. 

- **Primary (Forest Green):** Used for main navigation, primary actions, and brand-heavy sections.
- **Secondary (Soft Orange):** Reserved for interaction accents like hover states and success indicators.
- **Denuncias (Alert Red):** A high-visibility, urgent red used exclusively for reporting abuse or emergencies.
- **Donaciones (Sky Blue):** A calming, trustworthy celeste used for financial support and contribution modules.
- **Neutrals:** Warm-tinted greys prevent the interface from feeling clinical, maintaining a "domestic" and cozy atmosphere.

## Typography

This design system utilizes **Plus Jakarta Sans** for headings to provide a modern, friendly, and slightly rounded character that feels optimistic. **Be Vietnam Pro** is used for body copy and labels because of its exceptional readability and contemporary warmth, ensuring that long-form adoption stories are easy to digest.

Text hierarchy should be strictly maintained to guide the user's eye from emotional storytelling (Headlines) to functional details (Body). Use darker shades of the primary green for headings instead of pure black to maintain the earthy, organic feel.

## Layout & Spacing

The layout follows a **Fixed Grid** model on desktop (12 columns) and a **Fluid Grid** on mobile devices. The spacing rhythm is based on an 8px scale, favoring generous padding to create a sense of calm and order. 

Section transitions should use large vertical padding (lg or xl units) to prevent the content from feeling cluttered. Content blocks should be centered with a maximum container width of 1280px to ensure line lengths remain readable for animal biographies and informational articles.

## Elevation & Depth

Visual hierarchy is achieved through **Ambient Shadows** and **Tonal Layers**. Instead of harsh borders, surfaces are defined by soft, diffused shadows with a slight tint of the primary color to keep the depth feeling natural.

- **Level 1 (Cards):** Very soft shadow (10% opacity, 15px blur) to lift animal profiles from the background.
- **Level 2 (Modals/Navigation):** Medium shadow (15% opacity, 30px blur) to indicate high-priority interaction.
- **Backgrounds:** Use subtle tonal shifts between #F8F9FA and pure white to separate content sections without using lines.

## Shapes

The shape language is defined by significant roundedness to evoke friendliness and safety. "Rounded" (Level 2) is the standard, ensuring that no sharp corners exist in the UI. 

Image containers for animal photos should use `rounded-xl` (1.5rem) to mimic the soft appearance of organic shapes. Buttons and input fields use `rounded-lg` (1rem) to maintain a consistent, approachable feel that invites interaction.

## Components

- **Buttons:** Primary buttons use a solid Forest Green fill with white text. The "Donar" button utilizes the Light Blue palette, while "Reportar Maltrato" uses the Prominent Red. All buttons feature a subtle scale-down effect on press to feel tactile.
- **Cards:** Adoptable animal cards feature a large image at the top with `rounded-xl` corners, a title in H3, and small chips for age/breed.
- **Chips:** Used for animal traits (e.g., "Friendly," "Vaccinated"). These should have a light secondary-color background with dark text and fully pill-shaped corners.
- **Input Fields:** Large tap targets with a soft grey border that turns Primary Green on focus. Labels should always be visible above the field.
- **Progress Bars:** For donation campaigns, use the Sky Blue color for the fill, with a rounded container to show "funding reached" in a non-stressful way.
- **Pet Badges:** Circular icons with soft illustrations to represent "Cat," "Dog," or "Special Needs" categories.
