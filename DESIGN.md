---
name: Serengeti Horizon
colors:
  surface: '#fbf9f8'
  surface-dim: '#dcd9d9'
  surface-bright: '#fbf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3f2'
  surface-container: '#f0eded'
  surface-container-high: '#eae8e7'
  surface-container-highest: '#e4e2e1'
  on-surface: '#1b1c1c'
  on-surface-variant: '#404940'
  inverse-surface: '#303030'
  inverse-on-surface: '#f3f0f0'
  outline: '#717970'
  outline-variant: '#c0c9be'
  surface-tint: '#2d6a3e'
  primary: '#125229'
  on-primary: '#ffffff'
  primary-container: '#2e6b3f'
  on-primary-container: '#a8e9b2'
  inverse-primary: '#95d5a0'
  secondary: '#795900'
  on-secondary: '#ffffff'
  secondary-container: '#ffc641'
  on-secondary-container: '#715300'
  tertiary: '#494740'
  on-tertiary: '#ffffff'
  tertiary-container: '#615f57'
  on-tertiary-container: '#ded9cf'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#b0f2ba'
  primary-fixed-dim: '#95d5a0'
  on-primary-fixed: '#00210b'
  on-primary-fixed-variant: '#115228'
  secondary-fixed: '#ffdfa0'
  secondary-fixed-dim: '#f6be39'
  on-secondary-fixed: '#261a00'
  on-secondary-fixed-variant: '#5c4300'
  tertiary-fixed: '#e7e2d8'
  tertiary-fixed-dim: '#cac6bd'
  on-tertiary-fixed: '#1d1c16'
  on-tertiary-fixed-variant: '#494740'
  background: '#fbf9f8'
  on-background: '#1b1c1c'
  surface-variant: '#e4e2e1'
  safari-green: '#2E6B3F'
  savanna-gold: '#D4A017'
  desert-sand: '#F5F0E6'
  charcoal: '#333333'
  whatsapp-green: '#25D366'
typography:
  display-lg:
    fontFamily: ebGaramond
    fontSize: 64px
    fontWeight: '600'
    lineHeight: 72px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: ebGaramond
    fontSize: 48px
    fontWeight: '500'
    lineHeight: 56px
  headline-lg-mobile:
    fontFamily: ebGaramond
    fontSize: 32px
    fontWeight: '500'
    lineHeight: 40px
  headline-md:
    fontFamily: ebGaramond
    fontSize: 32px
    fontWeight: '500'
    lineHeight: 40px
  title-lg:
    fontFamily: montserrat
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: 0.05em
  body-lg:
    fontFamily: montserrat
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: montserrat
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: montserrat
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.1em
  price-display:
    fontFamily: ebGaramond
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 20px
  margin-desktop: 60px
  section-gap: 120px
---

## Brand & Style

The design system is built to evoke a sense of "Refined Adventure." It targets high-net-worth travelers seeking authentic yet luxurious African safari experiences. The brand personality is authoritative and expert, yet deeply hospitable and warm.

The visual style is a sophisticated blend of **Modern Minimalism** and **Glassmorphism**. It utilizes expansive white space to let high-resolution wildlife photography breathe, while layering functional interface elements over these visuals using frosted glass effects. This creates a sense of depth and immersion, mimicking the layered landscapes of the savanna. The aesthetic is "Safari Chic"—clean lines, organic colors, and premium textures that suggest trust and meticulous attention to detail.

## Colors

The palette is derived from the natural African landscape. **Safari Green** serves as the primary brand anchor, representing conservation and life. **Gold** is used sparingly for high-value actions, premium badges, and accents to denote luxury. 

**Sand Beige** is the primary background surface color, providing a softer, more organic feel than pure white, which is reserved for high-contrast text or specific UI components. **Charcoal Gray** provides the necessary grounding for typography, ensuring legibility and a modern professional feel. A specific **WhatsApp Green** is included as a functional named color to drive the primary booking confirmation channel.

## Typography

This design system utilizes a classic Serif/Sans-Serif pairing. **EB Garamond** brings a literary, timeless, and prestigious quality to headlines, evoking the golden age of travel. It should be used for all editorial content and section headers.

**Montserrat** provides a clean, geometric contrast for body copy and functional labels. Its high x-height ensures readability for itinerary details and booking forms. All labels and small headers in Montserrat should utilize increased letter spacing and uppercase styling to maintain a modern, organized information hierarchy. The `price-display` role is specifically designed for the currency switcher integration, ensuring costs look elegant and clear.

## Layout & Spacing

The layout follows a **Fixed Grid** model on desktop, centered within a 1280px container to maintain an editorial feel. On mobile, it shifts to a fluid single-column layout with 20px side margins.

A generous 8px base unit drives the spacing scale. Key to this luxury aesthetic is the `section-gap` of 120px, which prevents the UI from feeling cluttered and ensures each safari package or wildlife feature feels like a distinct "chapter." Content should be aligned to a 12-column grid, with frequent use of offset layouts (e.g., text spanning 5 columns, images spanning 7) to create visual interest reminiscent of high-end travel magazines.

## Elevation & Depth

Hierarchy is established through **Glassmorphism** and **Ambient Shadows**. 

1.  **The Glass Layer:** Navigation headers and "Quick Book" bars use a high-refraction backdrop blur (20px) with a 60% opaque White or Sand Beige fill. A subtle 1px inner border in 10% White adds a "glint" to the edges.
2.  **The Shadow Profile:** Elevated elements like cards do not use heavy black shadows. Instead, they use "Sun-Drenched Shadows"—diffused, large-radius blurs with a slight warm tint (#2E6B3F at 5% opacity) to feel more natural and integrated with the safari theme.
3.  **Depth Tiers:**
    *   **Level 0:** Background imagery or Sand Beige canvas.
    *   **Level 1:** Content cards with soft shadows and 2xl rounding.
    *   **Level 2:** Floating glass elements (Navigation, Currency Switcher).
    *   **Level 3:** Modals and WhatsApp confirmation overlays.

## Shapes

The system uses a highly approachable and premium "Rounded" language. Main content containers and image wrappers must use the `rounded-2xl` (1.5rem / 24px) property to soften the technical feel of the site and mimic organic shapes found in nature.

Buttons and input fields follow the standard `rounded` (0.5rem / 8px) scale to maintain a sense of structural integrity. Interactive chips (for currency or tags) should use the `rounded-xl` setting to feel like smooth river stones.

## Components

### Buttons
*   **Primary:** Safari Green background, White text, 8px radius. Hover state adds a subtle Gold bottom border.
*   **Secondary:** Ghost style with a 2px Safari Green border or Gold border for "Luxury" tiers.
*   **WhatsApp CTA:** Distinctive WhatsApp Green with a white icon. This button is often "sticky" on mobile booking steps.

### Cards
All cards feature `rounded-2xl` corners. Destination cards use a "vignette" overlay on the bottom third to allow white EB Garamond typography to sit legibly over photography.

### Currency Switcher
A glassmorphic dropdown located in the global header. It displays the currency code (KES, USD, etc.) in Montserrat Bold. When active, the selected currency is highlighted with a Gold underline.

### Input Fields
Soft Sand Beige backgrounds with 1px Safari Green borders on focus. Labels are always Montserrat, Uppercase, 12px.

### Booking Tracker
A horizontal stepper for the booking process using thin Gold lines and Safari Green nodes, signifying the path from "Inquiry" to "WhatsApp Confirmation."