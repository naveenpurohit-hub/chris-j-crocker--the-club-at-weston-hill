---
name: Apex Performance
colors:
  surface: '#fbf9f8'
  surface-dim: '#dbdad9'
  surface-bright: '#fbf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3f3'
  surface-container: '#efeded'
  surface-container-high: '#e9e8e7'
  surface-container-highest: '#e4e2e2'
  on-surface: '#1b1c1c'
  on-surface-variant: '#444748'
  inverse-surface: '#303031'
  inverse-on-surface: '#f2f0f0'
  outline: '#747878'
  outline-variant: '#c4c7c7'
  surface-tint: '#5f5e5e'
  primary: '#0a0a0a'
  on-primary: '#ffffff'
  primary-container: '#212121'
  on-primary-container: '#898888'
  inverse-primary: '#c8c6c5'
  secondary: '#bb0027'
  on-secondary: '#ffffff'
  secondary-container: '#e0283c'
  on-secondary-container: '#fffbff'
  tertiary: '#080a0a'
  on-tertiary: '#ffffff'
  tertiary-container: '#1f2121'
  on-tertiary-container: '#878888'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e5e2e1'
  primary-fixed-dim: '#c8c6c5'
  on-primary-fixed: '#1b1c1c'
  on-primary-fixed-variant: '#474746'
  secondary-fixed: '#ffdad8'
  secondary-fixed-dim: '#ffb3b1'
  on-secondary-fixed: '#410007'
  on-secondary-fixed-variant: '#92001c'
  tertiary-fixed: '#e2e2e2'
  tertiary-fixed-dim: '#c6c6c7'
  on-tertiary-fixed: '#1a1c1c'
  on-tertiary-fixed-variant: '#454747'
  background: '#fbf9f8'
  on-background: '#1b1c1c'
  surface-variant: '#e4e2e2'
  surface-cream: '#F4EDE4'
  stroke-gray: '#E0E0E0'
  deep-red: '#9B0D24'
typography:
  display-xl:
    fontFamily: Hanken Grotesk
    fontSize: 64px
    fontWeight: '800'
    lineHeight: 72px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Hanken Grotesk
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Hanken Grotesk
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
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
  label-caps:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.1em
  button:
    fontFamily: Hanken Grotesk
    fontSize: 14px
    fontWeight: '700'
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
  unit: 8px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
  stack-sm: 12px
  stack-md: 32px
  stack-lg: 80px
---

## Brand & Style

This design system is built for a high-performance golf coaching experience that balances technical precision with premium approachability. The aesthetic is rooted in **Modern Corporate** principles but injected with **Minimalist** discipline to ensure that complex data and coaching techniques remain digestible and authoritative.

The brand personality is "The Professional Edge"—it is fact-based, disciplined, and elite, yet remains accessible to students of all levels. The visual language uses high contrast to evoke the clarity of a perfect swing, while generous whitespace ensures a focused, "quiet" environment conducive to learning and improvement.

## Colors

The palette is a sophisticated evolution of traditional golf colors. 
- **Primary Black (#212121):** Used for primary headings and main UI elements to ground the design in authority.
- **Performance Red (#C8102E):** Reserved for surgical precision—calls to action, data highlights, and status indicators. It should be used sparingly to maintain its impact.
- **Surface & Depth:** We utilize a layered approach with off-whites and subtle grays. `#F4EDE4` (Surface Cream) is used for specific section backgrounds to provide a premium, editorial feel that contrasts against the stark `#FFFFFF` of the main workspace.
- **Interactive States:** Use `deep-red` for hovered button states and `stroke-gray` for subtle borders that define technical modules without adding visual clutter.

## Typography

Typography is the primary tool for communicating "Fact-Based Coaching." 
- **Headlines:** `Hanken Grotesk` provides a sharp, contemporary geometric feel that suggests engineering and modern athletics. Use heavy weights for impact.
- **Body:** `Inter` ensures maximum legibility for long-form coaching notes and technical explanations. It is neutral and professional.
- **Technical Labels:** `JetBrains Mono` is used for data points, swing metrics (e.g., Club Path, Face Angle), and breadcrumbs to lean into the "technical/scientific" aspect of the brand.
- **Hierarchy:** Maintain a strict vertical rhythm. Use `label-caps` for section overlines to categorize content before the main headline.

## Layout & Spacing

The layout follows a **Fixed Grid** philosophy on desktop to ensure content remains focused and readable, preventing line lengths from becoming too wide. 

- **Grid:** Use a 12-column grid for desktop with 24px gutters. Content should be centered within a 1280px max-width container.
- **Rhythm:** An 8px base unit drives all spacing. 
- **Whitespace:** Use `stack-lg` (80px) between major sections to create a sense of premium "breathability."
- **Mobile:** Transition to a fluid single-column layout. Reduce side margins to 16px and stack all grid elements vertically.
- **Alignment:** Use consistent left-alignment for all technical data and coaching text to maintain a structured, "fact-sheet" appearance.

## Elevation & Depth

This design system avoids heavy shadows to maintain its "crisp" and "technical" aesthetic. Depth is communicated through **Tonal Layers** and **Low-Contrast Outlines**:

- **Layering:** Backgrounds use `#FFFFFF`. Secondary content modules or "technical cards" use the `#F4F4F4` or `#F4EDE4` surface colors to distinguish themselves from the base.
- **Borders:** Instead of shadows, use 1px solid strokes in `stroke-gray` (#E0E0E0) to define card boundaries and input fields.
- **Active Elevation:** Only use a very subtle, highly diffused ambient shadow (0px 4px 20px, 5% opacity black) for primary "floating" elements like mobile navigation menus or modal overlays.
- **Interaction:** On hover, interactive cards should shift from a light gray border to a 1px `primary-black` border, rather than lifting off the page.

## Shapes

The shape language is **Soft (0.25rem)**. 

While the brand is technical, purely sharp corners (0px) can feel too aggressive and dated. A subtle 4px radius on buttons, input fields, and cards softens the professional edge just enough to remain approachable. 

- **Buttons:** Use `rounded-sm` (4px) for a precise, "tooled" look.
- **Data Tags:** Use pill shapes (full radius) for status indicators or category tags to differentiate them from functional buttons.
- **Media:** Photography and video players should maintain the 4px corner radius to ensure visual consistency across the interface.

## Components

### Buttons
- **Primary:** Solid `#212121` background, white text, 4px radius. High-impact uppercase typography.
- **Secondary:** Transparent background, 1px `#212121` border, black text.
- **Action:** Solid Performance Red (#C8102E) for high-priority conversions (e.g., "Book Now").

### Cards
- Use for coaching modules and blog posts. White background, 1px `stroke-gray` border, 4px radius. No shadow. Internal padding should follow `stack-md`.

### Input Fields
- 1px `stroke-gray` border, 4px radius. On focus, the border changes to `primary-black`. Labels should use `label-caps` typography.

### Lists & Data Tables
- Used for swing metrics. Alternate row backgrounds with `#F4F4F4`. Use `JetBrains Mono` for all numeric values to emphasize the fact-based nature of the coaching.

### Chips/Tags
- Small, pill-shaped elements for "New," "Online," or "In-Person." Use `label-caps` for the text. Use `#F4EDE4` background for neutral tags and light red tints for alerts.