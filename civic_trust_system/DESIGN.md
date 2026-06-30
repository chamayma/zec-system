---
name: Civic Trust System
colors:
  surface: '#fdf8f8'
  surface-dim: '#ddd9d8'
  surface-bright: '#fdf8f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f7f3f2'
  surface-container: '#f1edec'
  surface-container-high: '#ebe7e6'
  surface-container-highest: '#e5e2e1'
  on-surface: '#1c1b1b'
  on-surface-variant: '#444748'
  inverse-surface: '#313030'
  inverse-on-surface: '#f4f0ef'
  outline: '#747878'
  outline-variant: '#c4c7c7'
  surface-tint: '#5f5e5e'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#1c1b1b'
  on-primary-container: '#858383'
  inverse-primary: '#c8c6c5'
  secondary: '#5e5e5e'
  on-secondary: '#ffffff'
  secondary-container: '#e1dfdf'
  on-secondary-container: '#626262'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#1c1b1a'
  on-tertiary-container: '#868382'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e5e2e1'
  primary-fixed-dim: '#c8c6c5'
  on-primary-fixed: '#1c1b1b'
  on-primary-fixed-variant: '#474746'
  secondary-fixed: '#e4e2e2'
  secondary-fixed-dim: '#c7c6c6'
  on-secondary-fixed: '#1b1c1c'
  on-secondary-fixed-variant: '#464747'
  tertiary-fixed: '#e6e2df'
  tertiary-fixed-dim: '#cac6c4'
  on-tertiary-fixed: '#1c1b1a'
  on-tertiary-fixed-variant: '#484645'
  background: '#fdf8f8'
  on-background: '#1c1b1b'
  surface-variant: '#e5e2e1'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  headline-sm:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-lg:
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
    letterSpacing: 0.04em
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
  gutter: 16px
  margin-mobile: 16px
  margin-tablet: 32px
---

## Brand & Style
The design system for the Zanzibar Electoral Commission (ZEC) is built upon the pillars of **Authority, Transparency, and Accessibility**. The visual language reflects a modern government institution that prioritizes clear communication and civic duty.

The style is **Corporate Modern**, characterized by a rigorous commitment to legibility and a balanced use of white space. By utilizing a neutral primary palette with high-contrast accents, the UI directs user attention toward critical democratic actions—such as voter registration and polling station location—without unnecessary visual noise. The bilingual nature of the application (Swahili/English) is supported through a spacious layout that accommodates varying text lengths, ensuring the interface remains stable and professional regardless of the selected language.

## Colors
The palette is rooted in a monochromatic foundation to establish a sense of permanence and official weight. **#1A1A1A** acts as the anchor for headers and primary interactions, while **#6B6B6B** provides a soft hierarchy for metadata and secondary descriptions.

Functional accents are deployed with strict intent:
- **ZEC Blue (#2980B9):** Used for active states, interactive links, and informational signifiers.
- **Alert Red (#C0392B):** Reserved for critical deadlines, errors, and urgent warnings.
- **Success Green (#27AE60):** Indicates completed registrations, verified status, and successful form submissions.

In **Dark Mode**, surfaces are elevated using tonal grey steps rather than pure black to maintain depth, ensuring that high-contrast text remains legible and reduces eye strain during extended reading of electoral guidelines.

## Typography
This design system utilizes **Inter** for all levels of the hierarchy. Inter's tall x-height and exceptional legibility make it ideal for government services where clarity is non-negotiable. 

- **Headlines:** Use Semi-Bold (600) to Bold (700) weights with slight negative letter-spacing to create a compact, authoritative presence.
- **Body Text:** Set at a minimum of 14px/16px to ensure accessibility for all age groups. Line heights are generous (1.5x) to facilitate comfortable reading of long-form Swahili and English legal texts.
- **Bilingual Context:** When displaying dual-language content (e.g., a label in English with a Swahili subtitle), the secondary language should utilize the `body-md` or `label-sm` role with the secondary grey color to maintain a clear primary focal point.

## Layout & Spacing
The layout follows a **fluid grid system** tailored for mobile-first consumption. 

- **Padding:** A standard 16px (`md`) inner padding is applied to all cards and containers to ensure content doesn't feel cramped.
- **Margins:** Screen edges maintain a consistent 16px margin on mobile devices, expanding to 32px on tablets to preserve line-length readability.
- **Rhythm:** All vertical spacing must be a multiple of 4px. Use `lg` (24px) spacing between distinct sections or cards to provide clear visual separation.
- **Grid:** On tablet and larger views, use a 12-column grid. On mobile, components should span the full width of the safe area unless they are part of a horizontal scroll pattern (e.g., news chips).

## Elevation & Depth
To convey hierarchy and "clickability," the design system employs **Ambient Shadows** and **Tonal Layering**.

- **Level 0 (Background):** Pure White (Light Mode) or Deep Grey (Dark Mode).
- **Level 1 (Cards/Surface):** Uses a very soft, diffused shadow: `0px 2px 8px rgba(0, 0, 0, 0.05)`. This elevates the card slightly without creating a heavy "floating" effect.
- **Level 2 (Active/Floating):** For elements like "Check Status" floating action buttons or active modals, use a more pronounced shadow: `0px 4px 16px rgba(0, 0, 0, 0.12)`.
- **Contrast Outlines:** In addition to shadows, cards use a 1px subtle border (`#E0E0E0`) to maintain structural integrity when multiple cards are stacked.

## Shapes
The design system uses a **Rounded** shape language to soften the institutional feel, making the government interface feel more approachable and modern.

- **Primary Components:** Cards, input fields, and standard buttons utilize a **12px to 16px** corner radius.
- **Small Components:** Chips and checkboxes use a smaller **4px** radius to maintain precision at small scales.
- **Full Rounding:** Notification badges and search bars may use pill-shaped (fully rounded) styling to differentiate them from functional data containers.

## Components
- **Buttons:** Primary buttons are solid `#1A1A1A` with White text. Secondary buttons use an outline style with `#2980B9`. All buttons have a minimum height of 48px for touch accessibility.
- **Cards:** The primary container for information. Cards feature 16px padding, 12px rounded corners, and a subtle Level 1 shadow. Use cards to group Voter Info, Election Dates, and News.
- **Input Fields:** Text fields have a 1px `#E0E0E0` border that transforms to a 2px `#2980B9` border on focus. Labels must always be visible (not just placeholder text) to support accessibility.
- **Chips:** Small, rounded indicators for "Verified," "Pending," or "Voted" status. Use high-contrast background tints with darker text for readability.
- **Lists:** Use for navigation menus or election results. Each item should have a minimum height of 56px and a 1px bottom divider.
- **Language Switcher:** A prominent toggle or dropdown, typically in the top navigation bar or footer, allowing instant transition between Swahili and English.