---
name: Success Path Academy
colors:
  surface: '#f8f9fb'
  surface-dim: '#d9dadc'
  surface-bright: '#f8f9fb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f4f6'
  surface-container: '#edeef0'
  surface-container-high: '#e7e8ea'
  surface-container-highest: '#e1e2e4'
  on-surface: '#191c1e'
  on-surface-variant: '#434655'
  inverse-surface: '#2e3132'
  inverse-on-surface: '#f0f1f3'
  outline: '#737686'
  outline-variant: '#c3c6d7'
  surface-tint: '#0053db'
  primary: '#004ac6'
  on-primary: '#ffffff'
  primary-container: '#2563eb'
  on-primary-container: '#eeefff'
  inverse-primary: '#b4c5ff'
  secondary: '#5d5f5f'
  on-secondary: '#ffffff'
  secondary-container: '#dfe0e0'
  on-secondary-container: '#616363'
  tertiary: '#784b00'
  on-tertiary: '#ffffff'
  tertiary-container: '#996100'
  on-tertiary-container: '#ffeedd'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dbe1ff'
  primary-fixed-dim: '#b4c5ff'
  on-primary-fixed: '#00174b'
  on-primary-fixed-variant: '#003ea8'
  secondary-fixed: '#e2e2e2'
  secondary-fixed-dim: '#c6c6c7'
  on-secondary-fixed: '#1a1c1c'
  on-secondary-fixed-variant: '#454747'
  tertiary-fixed: '#ffddb8'
  tertiary-fixed-dim: '#ffb95f'
  on-tertiary-fixed: '#2a1700'
  on-tertiary-fixed-variant: '#653e00'
  background: '#f8f9fb'
  on-background: '#191c1e'
  surface-variant: '#e1e2e4'
typography:
  display-kh:
    fontFamily: Kantumruy Pro
    fontSize: 42px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-lg:
    fontFamily: Be Vietnam Pro
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-lg-mobile:
    fontFamily: Be Vietnam Pro
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
  headline-md:
    fontFamily: Be Vietnam Pro
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Be Vietnam Pro
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Be Vietnam Pro
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Be Vietnam Pro
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.02em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 4px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
  max-width: 1280px
---

## Brand & Style

The design system is engineered for a premium Cambodian tutoring center, balancing academic rigor with an encouraging, modern atmosphere. The brand personality is **Professional, Trustworthy, and Aspirational**. It targets students and parents who value high-quality education and clear results.

The visual style follows a **Modern Corporate** aesthetic with a heavy emphasis on **Minimalism** and **Soft-Tactile** elements. We utilize generous white space to reduce cognitive load, paired with large-radius corners and subtle depth to make the interface feel approachable and student-friendly. The emotional response should be one of confidence and clarity—where the path to "Success" (ជោគជ័យ) is visually structured and attainable.

## Colors

The palette is anchored by a deep **Modern Blue**, symbolizing stability and intelligence. **Gold** is used sparingly as an accent to highlight achievements, calls-to-action, and "Success" moments.

- **Primary (#2563EB):** Brand identity, primary buttons, and active states.
- **Secondary/Surface (#FFFFFF):** Core card backgrounds and navigation bars.
- **Accent (#F59E0B):** Badges, high-importance alerts, and progress indicators.
- **Background (#F3F4F6):** Systematic page background to provide contrast for white cards.
- **Text (Neutral-900):** #111827 for maximum legibility on white surfaces.

## Typography

This design system uses **Be Vietnam Pro** for its modern, clean metrics that pair exceptionally well with Khmer scripts like **Kantumruy Pro**. For the Khmer implementation, ensure the font weight is slightly heavier than the Latin counterpart to maintain visual optical weight.

- **Headlines:** Always bold or semi-bold. Use Primary Blue for sub-headers and Neutral-900 for main headers.
- **Khmer Script:** Prioritize `Kantumruy Pro` for all UI elements to ensure modern legibility and proper diacritic placement.
- **Body Text:** Use a line height of 1.5x (24px on 16px font) to ensure ease of reading for educational content.

## Layout & Spacing

The design system employs a **Fluid 12-Column Grid** for desktop and a **Single Column Flow** for mobile.

- **Desktop:** 12 columns with 24px gutters. Content is centered with a max-width of 1280px.
- **Mobile:** 16px side margins. Cards should span the full width of the safe area.
- **Spacing Rhythm:** Use a 4px/8px base unit. 
    - Card internal padding: 24px or 32px.
    - Section vertical spacing: 80px (Desktop), 48px (Mobile).

## Elevation & Depth

We use **Ambient Shadows** to create a sense of organized layers without overwhelming the user. 

- **Surface Level:** The main background is Neutral (#F3F4F6).
- **Raised Level (Cards):** White (#FFFFFF) surfaces with a subtle, large-spread shadow: `0 4px 20px -2px rgba(0, 0, 0, 0.05)`.
- **Interactive Level (Hover):** When hovering over course cards or buttons, the shadow deepens and the element lifts slightly (Y-offset -4px) to signal interactivity.
- **Overlays:** Modals and dropdowns use a more pronounced shadow to separate from the academic content below.

## Shapes

The design system adopts a **Rounded** shape language to appear friendly and modern.

- **Standard Elements:** 0.5rem (8px) for buttons and input fields.
- **Container Elements:** 1rem (16px) for cards and profile containers.
- **Feature Elements:** 1.5rem (24px) for prominent "Hero" cards and large callouts.
- **Icons:** Use rounded icon sets (e.g., Lucide or Phosphor) to match the UI radius.

## Components

### Cards
- **Course Cards:** Must include a thumbnail image at the top (16:9), title in `headline-md`, a price badge in the top-right corner using the Accent Gold, and a "Enroll Now" primary button at the bottom.
- **Feature Cards:** Centered icons in Primary Blue circles, followed by `headline-md` text and `body-md` descriptions.
- **Teacher Profiles:** Use circular avatars (80px) with a soft border. Include small social icons or "Bio" labels.

### Interactive Elements
- **Buttons:** Primary buttons use White text on Primary Blue. Secondary buttons use a Blue outline with White background. Action text should be in `label-md`.
- **Test Cards:** Highlight the "Start" action using a full-width Primary Blue button. Use a progress bar style if the test has been partially completed.
- **Registration Form:** Input fields use a 1px border (#D1D5DB) which turns Primary Blue on focus. Use `body-md` for labels and include helpful placeholder text.

### Galleries
- **Book Gallery:** A 4 or 5 column grid on desktop. Books should have a slight "lift" hover effect.
- **Student Achievement:** A horizontal scroll on mobile, or a masonry grid on desktop, showcasing photos with small "Success Story" captions in `body-md`.