---
name: The Design System
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
  on-surface-variant: '#504442'
  inverse-surface: '#303030'
  inverse-on-surface: '#f3f0f0'
  outline: '#827472'
  outline-variant: '#d3c3c0'
  surface-tint: '#745853'
  primary: '#271310'
  on-primary: '#ffffff'
  primary-container: '#3e2723'
  on-primary-container: '#ae8d87'
  inverse-primary: '#e3beb8'
  secondary: '#5e604d'
  on-secondary: '#ffffff'
  secondary-container: '#e1e1c9'
  on-secondary-container: '#636451'
  tertiary: '#181915'
  on-tertiary: '#ffffff'
  tertiary-container: '#2c2d29'
  on-tertiary-container: '#95948f'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad4'
  primary-fixed-dim: '#e3beb8'
  on-primary-fixed: '#2b1613'
  on-primary-fixed-variant: '#5b403c'
  secondary-fixed: '#e4e4cc'
  secondary-fixed-dim: '#c8c8b0'
  on-secondary-fixed: '#1b1d0e'
  on-secondary-fixed-variant: '#474836'
  tertiary-fixed: '#e4e2dd'
  tertiary-fixed-dim: '#c8c6c1'
  on-tertiary-fixed: '#1b1c19'
  on-tertiary-fixed-variant: '#474743'
  background: '#fbf9f8'
  on-background: '#1b1c1c'
  surface-variant: '#e4e2e1'
typography:
  display-lg:
    fontFamily: notoSerif
    fontSize: 64px
    fontWeight: '600'
    lineHeight: 72px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: notoSerif
    fontSize: 40px
    fontWeight: '500'
    lineHeight: 48px
  headline-md:
    fontFamily: notoSerif
    fontSize: 32px
    fontWeight: '500'
    lineHeight: 40px
  body-lg:
    fontFamily: plusJakartaSans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: plusJakartaSans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: plusJakartaSans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.05em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 8px
  container-max: 1280px
  gutter: 32px
  margin: 64px
  section-gap: 120px
---

## Brand & Style

The brand personality of the design system is artisanal, intentional, and serene. It is designed to evoke the sensory experience of a high-end specialty cafe: the warmth of a ceramic mug, the aroma of fresh beans, and the quiet comfort of a well-lit corner. The target audience includes discerning coffee enthusiasts and urban professionals who value quality and "the third space" experience.

This design system utilizes a **Minimalist** design style with an editorial flair. By prioritizing large-scale, high-quality photography and expansive whitespace, the UI recedes to let the product and the atmosphere take center stage. The atmosphere is sophisticated yet welcoming, avoiding cold sterile minimalism in favor of a warm, tactile aesthetic.

## Colors

The palette is rooted in the natural tones of the coffee-making process. The primary color, **Deep Coffee Brown**, provides grounding and weight, used for key interactive elements and primary branding. The background is built on **Cream White**, a softer and more inviting alternative to pure white, paired with **Soft Beige** for secondary containers and surface differentiation.

Text is rendered in **Charcoal**, ensuring high legibility while maintaining a softer contrast than pure black. This combination creates a high-end, organic feel that mimics printed specialty menus and boutique editorial layouts.

## Typography

The typography strategy relies on the contrast between tradition and modernity. **Noto Serif** is used for headlines to convey elegance and a timeless, authoritative quality. Its classic letterforms provide the "sophisticated" element of the design system.

For body text and functional labels, **Plus Jakarta Sans** is employed for its clarity and slightly rounded, welcoming terminals. This sans-serif ensures that even dense menu descriptions remain approachable and easy to read. Tight tracking is used for large displays, while labels utilize increased letter spacing and uppercase styling to create a distinct hierarchy for navigation and metadata.

## Layout & Spacing

The design system employs a **Fixed Grid** layout model with a generous maximum width to maintain an editorial, boutique feel on larger displays. The rhythm of the layout is dictated by a spacious 8px baseline, with significant vertical gaps between sections to allow the design to "breathe."

Margins are intentionally wide to center the user's focus on the content. A 12-column grid is used for desktop layouts, but the philosophy encourages asymmetrical placements and large-scale imagery that may break the grid or span multiple columns to create a sense of movement and curated design.

## Elevation & Depth

To maintain a minimalist and modern aesthetic, the design system avoids heavy shadows in favor of **low-contrast outlines** and **tonal layers**. Depth is created through the stacking of Soft Beige surfaces on Cream White backgrounds.

When an element requires focus, a very subtle, diffused ambient shadow may be used, tinted with the primary coffee brown at a 5% opacity to maintain warmth. Borders are used sparingly; they are 1px thick and rendered in the primary brown at low opacity (10-15%) to define containers without adding visual clutter. This "flat-plus" approach keeps the interface light and sophisticated.

## Shapes

The shape language is characterized by **Soft** roundedness. A subtle corner radius (0.25rem to 0.75rem) is applied to buttons, input fields, and image containers. This choice strikes a balance between the precision of sharp minimalist corners and the friendly, organic nature of a cafe.

Image containers should occasionally use varied aspect ratios—such as tall portraits for coffee bean origins or wide landscapes for interior shots—to reinforce the editorial feel. Interaction elements like "Back to Top" or decorative icons may use circular shapes to provide a soft counterpoint to the structured grid.

## Components

### Buttons
Primary buttons use a solid Deep Coffee Brown fill with Cream White text, featuring a subtle hover state that slightly lightens the brown. Secondary buttons use a transparent background with a 1px Deep Coffee Brown border.

### Cards
Cards for menu items or blog posts are defined by their lack of heavy containers. They rely on high-quality imagery at the top, followed by Noto Serif headings. A subtle Soft Beige background may be used to group related content.

### Chips & Tags
Used for dietary labels (e.g., "Vegan," "Gluten-Free"), these are styled as Soft Beige pills with Charcoal text in a small, bolded Plus Jakarta Sans font.

### Input Fields
Forms use a Cream White fill with a 1px Soft Beige border. On focus, the border transitions to a 1px Deep Coffee Brown stroke to provide clear feedback.

### Menu Lists
The digital menu utilizes a traditional layout with Noto Serif item names and trailing prices, separated by a thin, dotted leader line or significant whitespace to maintain the sophisticated atmosphere.

### Navigation
The header is minimalist and airy, using the label-md typography style for links. It should remain pinned or use a "smart show" behavior to stay out of the way of the visual content.