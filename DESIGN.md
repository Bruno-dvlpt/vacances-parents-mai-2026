---
name: Lumina Antiqua
colors:
  surface: '#fcf9f8'
  surface-dim: '#dcd9d9'
  surface-bright: '#fcf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3f2'
  surface-container: '#f0eded'
  surface-container-high: '#eae7e7'
  surface-container-highest: '#e4e2e1'
  on-surface: '#1b1c1c'
  on-surface-variant: '#544438'
  inverse-surface: '#303030'
  inverse-on-surface: '#f3f0f0'
  outline: '#877366'
  outline-variant: '#d9c2b3'
  surface-tint: '#924c00'
  primary: '#8f4a00'
  on-primary: '#ffffff'
  primary-container: '#ae611a'
  on-primary-container: '#fffbff'
  inverse-primary: '#ffb781'
  secondary: '#586330'
  on-secondary: '#ffffff'
  secondary-container: '#d8e6a6'
  on-secondary-container: '#5c6834'
  tertiary: '#5e5c57'
  on-tertiary: '#ffffff'
  tertiary-container: '#77746f'
  on-tertiary-container: '#fffbff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdcc4'
  primary-fixed-dim: '#ffb781'
  on-primary-fixed: '#2f1400'
  on-primary-fixed-variant: '#6f3800'
  secondary-fixed: '#dbe9a9'
  secondary-fixed-dim: '#bfcd8f'
  on-secondary-fixed: '#171e00'
  on-secondary-fixed-variant: '#404b1b'
  tertiary-fixed: '#e6e2dc'
  tertiary-fixed-dim: '#cac6c0'
  on-tertiary-fixed: '#1c1c18'
  on-tertiary-fixed-variant: '#484742'
  background: '#fcf9f8'
  on-background: '#1b1c1c'
  surface-variant: '#e4e2e1'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 64px
    fontWeight: '700'
    lineHeight: 72px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 40px
    fontWeight: '600'
    lineHeight: 48px
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-md:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '500'
    lineHeight: 40px
  headline-sm:
    fontFamily: Playfair Display
    fontSize: 24px
    fontWeight: '500'
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
  label-lg:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.03em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 32px
  margin-desktop: 64px
  margin-mobile: 20px
  section-gap: 120px
---

## Brand & Style

This design system targets an intellectually curious, high-end demographic of cultural tourists and academics. The brand personality is prestigious, authoritative, and deeply rooted in history, yet it avoids being "dusty" by employing a modern editorial framework.

The style is a sophisticated blend of **Minimalism** and **Modern Editorial**. It prioritizes high-quality cinematic photography, using generous whitespace to create a sense of breath and curated luxury. The UI should evoke the feeling of walking through a well-lit, modern museum wing—quiet, respectful of the artifacts, and intentionally paced. Visual interest is generated through asymmetrical layouts and overlapping elements that mimic the composition of high-fashion or architectural journals.

## Colors

The palette is derived from the natural materials of the archaeological site: limestone, clay, and vegetation. 

- **Background (#F5F2ED):** A warm, limestone off-white that serves as the canvas, reducing the harshness of pure white to enhance the "archival" feel.
- **Primary Terracotta (#BC6C25):** Used for call-to-actions, highlight fragments, and active states. It represents the baked earth and pottery found on-site.
- **Secondary Olive (#606C38):** Reserved for environmental cues, subtle information tags, and botanical sections.
- **Neutral Charcoal (#2D2D2D):** Used for all primary text to ensure high legibility while maintaining a softer contrast than pure black.
- **Warm Stone (#E0DCD6):** Utilized for structural lines, borders, and dividers to maintain layout integrity without breaking the visual flow.

## Typography

The typography strategy relies on the tension between the historical prestige of **Playfair Display** and the functional precision of **Inter**.

- **Headlines:** Use Playfair Display for all major headings. Large display sizes should use tighter letter spacing to emphasize the high-contrast strokes of the letterforms.
- **Body:** Inter is used for all long-form content and UI labels. It provides a contemporary "edge" that keeps the site feeling modern and accessible.
- **Labels:** Use uppercase Inter with increased letter-spacing for category tags and small metadata to create a "curatorial label" effect similar to museum plaques.

## Layout & Spacing

This design system utilizes a **12-column fluid grid** with exceptionally wide margins and gutters to enforce the editorial feel. 

- **Asymmetry:** Elements should frequently break the grid. For example, an image might span columns 2 through 8, while its caption sits in column 10.
- **Overlaps:** Use negative margins to allow images to subtly overlap text blocks or background containers, creating depth.
- **Pacing:** Large vertical gaps (`section-gap`) are used between content blocks to allow the eye to rest and emphasize the importance of each "artifact" or story section.
- **Mobile:** On mobile, the 12-column grid collapses to a single column, but maintains a minimum of 20px side margins to prevent content from touching the screen edges.

## Elevation & Depth

Depth is conveyed through **Tonal Layers** and **Ambient Shadows** rather than heavy physical metaphors.

- **Surfaces:** Most content lives on the limestone background. Secondary information or cards use a slightly lighter tint or the Warm Stone (#E0DCD6) for subtle distinction.
- **Shadows:** Use extremely soft, high-diffusion shadows (Blur: 40px, Opacity: 4%) to lift "featured" cards or images. The shadow should feel like natural light hitting a flat surface.
- **Dividers:** Use 1px solid lines in Warm Stone for structural separation. These lines should often be incomplete (e.g., only a top border) to keep the layout feeling open.

## Shapes

The shape language is primarily rectilinear and sharp to reflect the geometry of Roman architecture.

- **Corners:** Use "Soft" (0.25rem) corner radii for buttons and input fields. This provides just enough softness to feel modern without losing the precision of the design system.
- **Images:** Photography should always have sharp, 0px corners to maintain a "framed" gallery appearance.
- **Buttons:** Primary buttons should be rectangular with the minimal 4px radius.

## Components

- **Buttons:** Use a "Ghost" style for secondary actions with a 1px Stone Grey border. Primary buttons use the Terracotta background with white text. Hover states should involve a subtle shift in background opacity rather than a color change.
- **Cards:** Cards should have no visible borders or heavy shadows. Use the "Overlapping" technique where the image exceeds the top of the card container by 24px.
- **Input Fields:** Bottom-border only inputs (archival style) or fully outlined boxes with 1px Stone Grey borders. Focus states transition the border to Terracotta.
- **Chips/Tags:** Small, rectangular tags with Inter Bold caps and a light Stone Grey background. No rounded corners for tags.
- **Lists:** Use wide spacing between list items, separated by 1px Stone Grey horizontal rules that do not span the full width of the container.
- **Navigation:** A minimal top bar with high-contrast serif links. Use a "Breadcrumb" style navigation for deeper pages to emphasize the hierarchical journey through the site's history.