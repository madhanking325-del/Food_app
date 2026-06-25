---
name: High-Velocity Fluo
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#393939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1b1c1c'
  surface-container: '#1f2020'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353535'
  on-surface: '#e4e2e1'
  on-surface-variant: '#c4c9ac'
  inverse-surface: '#e4e2e1'
  inverse-on-surface: '#303030'
  outline: '#8e9379'
  outline-variant: '#444933'
  surface-tint: '#abd600'
  primary: '#ffffff'
  on-primary: '#283500'
  primary-container: '#c3f400'
  on-primary-container: '#556d00'
  inverse-primary: '#506600'
  secondary: '#c8c6c5'
  on-secondary: '#313030'
  secondary-container: '#474746'
  on-secondary-container: '#b7b5b4'
  tertiary: '#ffffff'
  on-tertiary: '#002f66'
  tertiary-container: '#d7e2ff'
  on-tertiary-container: '#0062c7'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#c3f400'
  primary-fixed-dim: '#abd600'
  on-primary-fixed: '#161e00'
  on-primary-fixed-variant: '#3c4d00'
  secondary-fixed: '#e5e2e1'
  secondary-fixed-dim: '#c8c6c5'
  on-secondary-fixed: '#1c1b1b'
  on-secondary-fixed-variant: '#474746'
  tertiary-fixed: '#d7e2ff'
  tertiary-fixed-dim: '#abc7ff'
  on-tertiary-fixed: '#001b3f'
  on-tertiary-fixed-variant: '#004590'
  background: '#131313'
  on-background: '#e4e2e1'
  surface-variant: '#353535'
typography:
  display-lg:
    fontFamily: Anybody
    fontSize: 72px
    fontWeight: '900'
    lineHeight: '1.0'
    letterSpacing: -0.04em
  headline-lg:
    fontFamily: Anybody
    fontSize: 48px
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Anybody
    fontSize: 32px
    fontWeight: '800'
    lineHeight: '1.1'
  headline-md:
    fontFamily: Anybody
    fontSize: 24px
    fontWeight: '700'
    lineHeight: '1.2'
  body-lg:
    fontFamily: Hanken Grotesk
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Hanken Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.5'
  label-technical:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1.0'
    letterSpacing: 0.05em
  label-price:
    fontFamily: JetBrains Mono
    fontSize: 20px
    fontWeight: '700'
    lineHeight: '1.0'
spacing:
  unit: 4px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 32px
---

## Brand & Style
The brand personality is electric, high-octane, and unapologetically bold. It merges the elite precision of Formula 1 with the rebellious, playful energy of digital "comic-glitch" culture. The target audience consists of Gen Z and Millennial foodies who value speed, performance, and a distinctive aesthetic that feels more like a lifestyle brand than a utility.

The design style is **High-Contrast / Bold** with **Brutalist** undertones. It utilizes heavy blacks to make fluorescent accents "pop," creating a sense of nighttime racing under neon lights. Motion is baked into the static UI through italicized typography and "glitch" motifs, ensuring the interface feels as fast as the delivery service promises.

## Colors
The palette is built on deep, technical foundations to allow the "Lando Yellow" to act as a high-visibility beacon for actions.

- **Primary (Lando Yellow):** Used exclusively for primary actions, buttons, and "Live Track" status indicators. It represents speed and urgency.
- **Secondary (Carbon Black):** The primary canvas. It provides the depth needed for the fluo effects to glow.
- **Neutral (Deep Charcoal):** Used for card surfaces and container elevations to create subtle separation from the background.
- **Tertiary (Electric Blue):** Used for secondary highlights, "Pro" features, or delivery milestones.
- **System Colors:** Errors are rendered in a vibrant, high-saturation red to maintain the aggressive energy of the brand.

## Typography
The typography system is designed to feel like a heads-up display (HUD) in a cockpit. 

- **Headlines:** Use **Anybody** in its boldest, italicized weights. This creates a forward-leaning "motion" effect. For hero sections, use "Ultra" weights with tight tracking.
- **Body:** **Hanken Grotesk** provides a sharp, contemporary, and highly legible counterpoint to the aggressive headlines. 
- **Technical Data:** All delivery times, prices, and nutritional info must use **JetBrains Mono**. This nods to sim-racing telemetry and adds a layer of "precision" to the food data.

## Layout & Spacing
The layout follows a **Fixed Grid** model on desktop (12 columns) and a fluid 4-column model on mobile. 

- **The "Speed-Line" Grid:** Use 4px increments for all internal component spacing.
- **Horizontal Alignment:** Align text-heavy elements to a strict vertical axis to mimic the structure of a technical manual or racing program.
- **Halftone Gutters:** The space between large sections (gutters) can occasionally be filled with a subtle, low-opacity halftone dot pattern (#FFFFFF at 5% opacity) to add texture without cluttering the UI.

## Elevation & Depth
This design system avoids traditional shadows in favor of **Tonal Layers** and **High-Contrast Outlines**.

- **Surfaces:** Use "Deep Charcoal" (#2D2D2D) for cards over the "Carbon Black" (#1A1A1A) background. 
- **The "Glitch" Offset:** Instead of a drop shadow, use a 2px offset solid border in "Lando Yellow" or "Electric Blue" to indicate active states or focus.
- **Backdrop Blurs:** Use heavy blurs (20px+) behind navigation bars, but keep the fill dark (Carbon Black at 80%) to maintain the "luxury racing" feel.
- **Depth through Texture:** Use "Motion Lines" (thin diagonal 45-degree strokes) on the background of secondary containers to create a sense of depth and kinetic energy.

## Shapes
The shape language is **Sharp (0px)**. Rounded corners are strictly forbidden for primary UI containers to maintain the "aggressive" and "technical" brand identity. 

- **Buttons:** Perfectly rectangular.
- **Images:** Use hard 90-degree corners.
- **Exceptions:** Use a 45-degree "chamfered" cut on the top-right corner of cards and buttons to mimic aerodynamic components or carbon fiber sheets.

## Components
- **Buttons:** Solid "Lando Yellow" background with "Carbon Black" text in all-caps Anybody Italic. On hover, apply a "Glitch" effect (a 2px horizontal shake and color split).
- **Chips/Tags:** Monospace font inside a thin Electric Blue border. Used for "Fast Delivery," "Hot," or "High Protein."
- **Cards:** Food items are displayed in Deep Charcoal containers. The food image should "break" the top boundary of the card for a comic-book pop-out effect.
- **Inputs:** Underlined only (no full box) with a Lando Yellow indicator that "fills" from left-to-right as the user types, mimicking a tachometer.
- **Icons:** Custom "Racing-Food" set. Icons must have a thick 2pt black stroke and a 1px offset fluo-yellow highlight.
- **The "Pit Stop" Tracker:** A horizontal progress bar for delivery tracking that resembles a race track map, with the delivery rider represented by a stylized racing helmet icon.