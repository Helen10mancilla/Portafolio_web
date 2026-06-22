---
name: Lumina Tech Portfolio
colors:
  surface: '#0b1326'
  surface-dim: '#0b1326'
  surface-bright: '#31394d'
  surface-container-lowest: '#060e20'
  surface-container-low: '#131b2e'
  surface-container: '#171f33'
  surface-container-high: '#222a3d'
  surface-container-highest: '#2d3449'
  on-surface: '#dae2fd'
  on-surface-variant: '#c2c6d6'
  inverse-surface: '#dae2fd'
  inverse-on-surface: '#283044'
  outline: '#8c909f'
  outline-variant: '#424754'
  surface-tint: '#adc6ff'
  primary: '#adc6ff'
  on-primary: '#002e6a'
  primary-container: '#4d8eff'
  on-primary-container: '#00285d'
  inverse-primary: '#005ac2'
  secondary: '#4cd7f6'
  on-secondary: '#003640'
  secondary-container: '#03b5d3'
  on-secondary-container: '#00424e'
  tertiary: '#c4c7c9'
  on-tertiary: '#2d3133'
  tertiary-container: '#8e9193'
  on-tertiary-container: '#272a2c'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#d8e2ff'
  primary-fixed-dim: '#adc6ff'
  on-primary-fixed: '#001a42'
  on-primary-fixed-variant: '#004395'
  secondary-fixed: '#acedff'
  secondary-fixed-dim: '#4cd7f6'
  on-secondary-fixed: '#001f26'
  on-secondary-fixed-variant: '#004e5c'
  tertiary-fixed: '#e0e3e5'
  tertiary-fixed-dim: '#c4c7c9'
  on-tertiary-fixed: '#191c1e'
  on-tertiary-fixed-variant: '#444749'
  background: '#0b1326'
  on-background: '#dae2fd'
  surface-variant: '#2d3449'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 64px
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Inter
    fontSize: 40px
    fontWeight: '800'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.3'
  headline-sm:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-mono:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1.5'
    letterSpacing: 0.05em
  label-caps:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '700'
    lineHeight: '1'
    letterSpacing: 0.1em
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
  margin-desktop: 64px
  margin-mobile: 20px
  stack-sm: 12px
  stack-md: 24px
  stack-lg: 48px
  section-gap: 120px
---

## Brand & Style

This design system is engineered for a Senior Software Developer's portfolio, prioritizing a high-end, engineering-focused aesthetic. The brand personality is authoritative yet innovative, blending professional reliability with a "forward-looking" technical edge.

The visual style utilizes **Minimalism** and **Glassmorphism** to create a sense of depth and sophistication. By leveraging translucent layers and vibrant accent colors against a deep, nocturnal background, the interface evokes the feel of a premium IDE or a high-performance SaaS dashboard. The emotional response should be one of trust in the developer's technical mastery and appreciation for their attention to detail.

## Colors

The palette is anchored by a deep slate-navy (#0f172a) to provide a rich, expansive backdrop that reduces eye strain and emphasizes contrast. 

- **Primary (Electric Blue):** Used for primary actions, active states, and key branding elements.
- **Secondary (Cyan):** Used for supplemental highlights, data visualization, and accentuating the glassmorphism glows.
- **Tertiary (Crisp White):** Reserved for high-priority typography and icons to ensure maximum legibility.
- **Neutral (Slate):** Various shades of slate are used for borders and secondary surfaces to create a tiered visual hierarchy.

A signature linear gradient combining Electric Blue and Cyan should be applied to high-impact elements like progress bars, primary buttons, and hero typography.

## Typography

The system utilizes **Inter** for its systematic, clean, and highly legible characteristics across all UI scales. Its variable weight axes allow for precise control over hierarchy.

To reinforce the technical nature of the portfolio, **JetBrains Mono** is introduced as a secondary label font for code snippets, technical tags, and metadata. 

- **Headlines:** Use tight tracking and heavy weights (700-800) for a confident, editorial look.
- **Body Text:** Use a comfortable 1.6 line height to ensure long-form project descriptions remain readable.
- **Micro-copy:** Use uppercase labels with increased letter spacing for category headers and small tags to differentiate from body prose.

## Layout & Spacing

The layout follows a **12-column fluid grid** for desktop, transitioning to a **4-column grid** for mobile devices. 

- **Grid Logic:** Elements should align to a strict 8px base unit. Gutters are fixed at 24px to maintain breathing room between technical cards.
- **Sectioning:** Large vertical gaps (120px) are used to separate major portfolio sections (Experience, Projects, Skills), allowing each content block to feel distinct.
- **Mobile Reflow:** On mobile, side-by-side elements (like dashboard metrics) should stack vertically, while navigation transitions to a bottom-docked glass bar or a full-screen overlay.

## Elevation & Depth

Depth is achieved through **Glassmorphism** and **Tonal Layering** rather than traditional heavy shadows.

1.  **Base:** The #0f172a background serves as the canvas.
2.  **Surface:** Secondary containers use a slightly lighter slate (#1e293b) with 0.5 opacity and a 12px backdrop blur.
3.  **Borders:** Use 1px "ghost borders" (white or cyan at 0.1 opacity) to define shapes without creating heavy visual weight.
4.  **Glows:** Subtle, large-radius ambient glows (color-tinted to #3b82f6 at 0.05 opacity) are placed behind primary cards to simulate light emitting from the screen.

## Shapes

The shape language is **Rounded**, balancing the "hard" technical feel of the content with an "approachable" modern UI.

- **Standard Elements:** Buttons, input fields, and tags use a 0.5rem (8px) radius.
- **Containers:** Large cards and glass panels use a 1rem (16px) radius to create a soft, premium container effect.
- **Interactive States:** On hover, cards may subtly increase their corner radius or expand slightly (1.02x scale) to indicate interactivity.

## Components

### Premium Cards
Cards are the primary content vehicle. They feature a 1px border (#ffffff10), a 20px backdrop blur, and a subtle inner glow on the top edge. Project cards should include a hover state that reveals a Cyan accent border.

### Elegant Timelines
For the "Experience" section, use a vertical line in semi-transparent slate. Milestones are marked by "Electric Blue" glowing rings. Dates should use the `label-mono` typography level for a technical feel.

### Dashboard Widgets
Include SaaS-inspired metrics for "Github Stats" or "Languages Known." Use small sparkline charts (Cyan) and circular progress indicators. Backgrounds for these should be darker than the main surface to create an inset look.

### Buttons
- **Primary:** Gradient fill (Electric Blue to Cyan) with white text. High-contrast, no border.
- **Secondary:** Outline style with 1px slate-400 border. Transitions to a full white border on hover.
- **Ghost:** No background, `label-mono` text, Electric Blue color.

### Input Fields
Darker slate background (#020617) with a 1px border. Focus state triggers a Cyan glow (`box-shadow: 0 0 0 2px #06b6d440`).