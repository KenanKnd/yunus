---
name: Kinetic High-Contrast
colors:
  surface: '#fff8f7'
  surface-dim: '#ffcfc8'
  surface-bright: '#fff8f7'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#fff0ee'
  surface-container: '#ffe9e6'
  surface-container-high: '#ffe2dd'
  surface-container-highest: '#ffdad5'
  on-surface: '#32120e'
  on-surface-variant: '#58413e'
  inverse-surface: '#4b2621'
  inverse-on-surface: '#ffedea'
  outline: '#8c716d'
  outline-variant: '#e0bfba'
  surface-tint: '#9e4033'
  primary: '#9b3e31'
  on-primary: '#ffffff'
  primary-container: '#bb5647'
  on-primary-container: '#fffbff'
  inverse-primary: '#ffb4a8'
  secondary: '#6a5b59'
  on-secondary: '#ffffff'
  secondary-container: '#f3dedb'
  on-secondary-container: '#70615f'
  tertiary: '#5c5e60'
  on-tertiary: '#ffffff'
  tertiary-container: '#757779'
  on-tertiary-container: '#030506'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad4'
  primary-fixed-dim: '#ffb4a8'
  on-primary-fixed: '#410000'
  on-primary-fixed-variant: '#7f291e'
  secondary-fixed: '#f3dedb'
  secondary-fixed-dim: '#d6c2bf'
  on-secondary-fixed: '#241917'
  on-secondary-fixed-variant: '#514442'
  tertiary-fixed: '#e1e2e4'
  tertiary-fixed-dim: '#c5c6c9'
  on-tertiary-fixed: '#191c1e'
  on-tertiary-fixed-variant: '#444749'
  background: '#fff8f7'
  on-background: '#32120e'
  surface-variant: '#ffdad5'
typography:
  display:
    fontFamily: Hanken Grotesk
    fontSize: 64px
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Hanken Grotesk
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Hanken Grotesk
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
  headline-md:
    fontFamily: Hanken Grotesk
    fontSize: 24px
    fontWeight: '600'
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
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
spacing:
  base: 4px
  xs: 8px
  sm: 16px
  md: 24px
  lg: 48px
  xl: 80px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
---

## Brand & Style
The design system evolves into a high-impact, authoritative environment designed for precision and speed. The brand personality is decisive, energetic, and uncompromisingly professional. By utilizing a high-contrast palette with deep, earthen tones and technical grays, the UI commands attention and establishes a clear hierarchy of information.

The visual style blends **Minimalism** with **High-Contrast / Bold** elements. It relies on expansive white space to let deep oxblood accents and dark architectural neutrals create a rhythmic, structured experience. The emotional response should be one of confidence, clarity, and urgency, suitable for high-stakes decision-making environments.

## Colors
This design system utilizes a restricted, high-chroma palette to maximize legibility and intent.

- **Primary Oxblood (#711F15):** A deep, high-contrast red used for primary actions and critical brand signifiers. It provides a more aggressive, authoritative energy.
- **Secondary Charcoal Brown (#463937):** A dark, desaturated neutral used for secondary interactive elements and supporting accents.
- **Tertiary Technical Gray (#8C8E90):** A mid-tone steel gray used for specialized data points, functional icons, or distinct auxiliary areas.
- **Neutral Deep Earth (#6B413B):** A dark brown-tinted neutral used for structural elements, borders, and secondary text, ensuring the interface feels grounded and professional.

## Typography
The typographic scale is designed for rapid scanning and data clarity. 

**Hanken Grotesk** provides a sharp, contemporary feel for large headlines, using heavy weights to anchor the page. **Inter** handles body copy with systematic neutrality, ensuring long-form data remains legible. **JetBrains Mono** is introduced for labels, captions, and data points, lending a technical, "ledger-like" precision to the design system.

Headlines should always favor a tighter letter-spacing for a more "impactful" look, while labels use slight tracking increases to ensure readability at small sizes.

## Layout & Spacing
The layout follows a rigorous **8-point grid** system to maintain mathematical harmony. 

A **12-column fluid grid** is used for desktop layouts with generous 64px outer margins to focus the user's eye on the central content. On mobile devices, the grid shifts to a **4-column layout** with 16px margins. 

Spacing is used aggressively to separate disparate data sets. Prefer "white space as a separator" over lines wherever possible to maintain the minimalist aesthetic. Elements should align strictly to the grid to reinforce the professional, structured nature of the system.

## Elevation & Depth
This design system avoids traditional soft shadows in favor of **Tonal Layers** and **High-Contrast Outlines**.

Depth is communicated through:
1.  **Z-Axis Layering:** Interactive surfaces use a 1px solid border using the Neutral color (#6B413B) at low opacity to distinguish themselves from the background.
2.  **Translucency:** Modals and overlays use a heavy wash of the Neutral tone to isolate the active task.
3.  **Hard Insets:** Instead of drop shadows, use subtle Neutral fills for container backgrounds to create "wells" for content.
4.  **Active Elevation:** On hover, elements do not rise; instead, they shift in color (e.g., to Primary Oxblood) or gain a 2px solid "block" shadow for a brutalist-inspired tactile feel.

## Shapes
The shape language is **Sharp (0px)**. 

To reinforce the professional and technical nature of the system, all buttons, inputs, cards, and containers utilize hard 90-degree corners. This creates an architectural, precise aesthetic that aligns with the high-contrast color palette and monospaced typography. Circles are reserved strictly for icons or status indicators to provide a distinct visual break from the structural grid.

## Components

- **Buttons:** Primary buttons are Solid Primary Oxblood with White text. Secondary buttons are Ghost-style with a 1px Neutral border and Neutral text. On hover, Primary buttons shift to the Secondary Charcoal Brown.
- **Inputs:** Text fields use a bottom-border only (2px Neutral) or a full 1px border. Focus state is indicated by a Primary Oxblood border and a Label that shifts to Oxblood.
- **Cards:** Cards have 0px corner radius, a 1px Neutral border, and no shadow. The header of a card may have a 4px Primary top-accent line to indicate priority.
- **Chips:** Small, rectangular tags with a light Technical Gray background and JetBrains Mono text.
- **Lists:** High-density rows with 1px horizontal separators. Use Primary Oxblood for "active" or "selected" list items as a vertical bar on the left edge.
- **Data Tables:** Pure white backgrounds with alternating subtle Neutral-tinted rows for readability. Headers are uppercase JetBrains Mono in bold Neutral.