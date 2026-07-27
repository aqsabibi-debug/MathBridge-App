---
name: MathBridge
colors:
  surface: '#fcf8ff'
  surface-dim: '#dcd8e5'
  surface-bright: '#fcf8ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f2ff'
  surface-container: '#f0ecf9'
  surface-container-high: '#eae6f4'
  surface-container-highest: '#e4e1ee'
  on-surface: '#1b1b24'
  on-surface-variant: '#464555'
  inverse-surface: '#302f39'
  inverse-on-surface: '#f3effc'
  outline: '#777587'
  outline-variant: '#c7c4d8'
  surface-tint: '#4d44e3'
  primary: '#3525cd'
  on-primary: '#ffffff'
  primary-container: '#4f46e5'
  on-primary-container: '#dad7ff'
  inverse-primary: '#c3c0ff'
  secondary: '#515f74'
  on-secondary: '#ffffff'
  secondary-container: '#d5e3fc'
  on-secondary-container: '#57657a'
  tertiary: '#7e3000'
  on-tertiary: '#ffffff'
  tertiary-container: '#a44100'
  on-tertiary-container: '#ffd2be'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e2dfff'
  primary-fixed-dim: '#c3c0ff'
  on-primary-fixed: '#0f0069'
  on-primary-fixed-variant: '#3323cc'
  secondary-fixed: '#d5e3fc'
  secondary-fixed-dim: '#b9c7df'
  on-secondary-fixed: '#0d1c2e'
  on-secondary-fixed-variant: '#3a485b'
  tertiary-fixed: '#ffdbcc'
  tertiary-fixed-dim: '#ffb695'
  on-tertiary-fixed: '#351000'
  on-tertiary-fixed-variant: '#7b2f00'
  background: '#fcf8ff'
  on-background: '#1b1b24'
  surface-variant: '#e4e1ee'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Inter
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Inter
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
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 4px
  xs: 4px
  sm: 8px
  md: 16px
  lg: 24px
  xl: 32px
  2xl: 48px
  3xl: 64px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 40px
  max-width: 1280px
---

## Brand & Style
The design system is built on a foundation of **Modern Minimalism** with a focus on cognitive clarity and academic confidence. The target audience includes students and educators who require an environment that is professional yet approachable.

The aesthetic prioritizes generous whitespace to reduce cognitive load, utilizing a "Soft-Scale" approach where depth is communicated through subtle layering rather than aggressive borders. The emotional response should be one of "Structured Curiosity"—where the UI feels like a clean, well-organized workspace that invites exploration and rewards progress.

## Colors
This design system employs a sophisticated **Indigo and Slate** palette. The Primary Indigo (#4F46E5) serves as the "Action" color, highlighting interactive elements and progress. The Secondary Slate (#475569) provides a grounded, professional tone for navigation and secondary information.

A neutral background of #F8FAFC ensures high contrast for the pure white (#FFFFFF) surface cards. Success states use a vibrant Emerald (#10B981) to provide positive reinforcement during learning activities. Grays are carefully stepped to ensure WCAG 2.1 AA compliance for all text elements against the light background.

## Typography
The system utilizes **Inter** exclusively to maintain a systematic and utilitarian feel that doesn't distract from mathematical content. 

- **Headlines:** Use tighter letter spacing and semi-bold weights to create a strong visual hierarchy.
- **Body:** Standardized at 16px for optimal readability in instructional text, with 18px used for introductory paragraphs.
- **Labels:** Higher weights (Medium/Semi-bold) are used at smaller sizes to ensure legibility in functional UI components like buttons and data tables.

## Layout & Spacing
The layout follows a **Fluid Grid** model with a maximum container width of 1280px. A 12-column system is used for desktop, collapsing to 4 columns on mobile devices.

Spacing is governed by a 4px baseline grid. Internal component padding typically uses `md` (16px) or `lg` (24px) to maintain the "breathable" feel of the brand. Vertical rhythm between major sections should utilize `2xl` or `3xl` spacing to clearly demarcate different learning modules or content blocks.

## Elevation & Depth
Elevation is expressed through **Tonal Layering** and **Ambient Shadows**. 

The background (#F8FAFC) serves as Level 0. Primary content containers (Cards) are Level 1, using a white fill, a 1px border (#E2E8F0), and a soft shadow (0px 4px 6px -1px rgba(0, 0, 0, 0.05)). 

Interactive elements like hovered buttons or active modals move to Level 2, featuring a more pronounced shadow (0px 10px 15px -3px rgba(0, 0, 0, 0.1)) to simulate physical proximity to the user. No heavy drop shadows are permitted; the goal is a soft, natural lift.

## Shapes
The shape language is defined by **High Roundedness** to evoke a friendly, non-intimidating atmosphere. 

Standard components (buttons, inputs) use `rounded-md` (0.5rem). Main content containers and instructional cards use `rounded-2xl` (1rem) or `rounded-3xl` (1.5rem) to create the signature "soft card" look. This curvature helps distinguish MathBridge from traditional, more rigid academic software.

## Components
- **Buttons:** Primary buttons use the Indigo fill with white text and a subtle 1px inner glow. Secondary buttons use a transparent background with a Slate border.
- **Cards:** The hallmark of the system. Large corner radii (1.5rem), white background, and a soft #E2E8F0 border. Cards should have generous internal padding (24px).
- **Input Fields:** Use a 0.5rem radius, #F1F5F9 background, and a 1px border that turns Indigo on focus.
- **Progress Bars:** Thicker, rounded tracks (12px height) with the Success Green used for completed steps and Primary Indigo for active progress.
- **Chips/Badges:** Small, fully rounded (pill-shaped) elements with low-opacity background tints of the primary or success colors to denote categories or difficulty levels.
- **Lists:** Clean, borderless list items separated by 8px of vertical whitespace, using a soft gray hover state.