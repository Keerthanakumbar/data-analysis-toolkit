---
name: Precision Analytical Framework
colors:
  surface: '#f7fafc'
  surface-dim: '#d7dadc'
  surface-bright: '#f7fafc'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f1f4f6'
  surface-container: '#ebeef0'
  surface-container-high: '#e5e9eb'
  surface-container-highest: '#e0e3e5'
  on-surface: '#181c1e'
  on-surface-variant: '#43474e'
  inverse-surface: '#2d3133'
  inverse-on-surface: '#eef1f3'
  outline: '#74777f'
  outline-variant: '#c4c6cf'
  surface-tint: '#455f88'
  primary: '#002045'
  on-primary: '#ffffff'
  primary-container: '#1a365d'
  on-primary-container: '#86a0cd'
  inverse-primary: '#adc7f7'
  secondary: '#0061a5'
  on-secondary: '#ffffff'
  secondary-container: '#66affe'
  on-secondary-container: '#004172'
  tertiary: '#122234'
  on-tertiary: '#ffffff'
  tertiary-container: '#28374a'
  on-tertiary-container: '#91a0b7'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d6e3ff'
  primary-fixed-dim: '#adc7f7'
  on-primary-fixed: '#001b3c'
  on-primary-fixed-variant: '#2d476f'
  secondary-fixed: '#d2e4ff'
  secondary-fixed-dim: '#9fcaff'
  on-secondary-fixed: '#001d37'
  on-secondary-fixed-variant: '#00497e'
  tertiary-fixed: '#d4e4fc'
  tertiary-fixed-dim: '#b8c8e0'
  on-tertiary-fixed: '#0d1c2e'
  on-tertiary-fixed-variant: '#39485c'
  background: '#f7fafc'
  on-background: '#181c1e'
  surface-variant: '#e0e3e5'
typography:
  display-lg:
    fontFamily: Hanken Grotesk
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Hanken Grotesk
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-sm:
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
  body-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  code-sm:
    fontFamily: JetBrains Mono
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 18px
  label-caps:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.05em
  headline-md-mobile:
    fontFamily: Hanken Grotesk
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
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
  margin-desktop: 32px
  stack-sm: 12px
  stack-md: 24px
  stack-lg: 48px
---

## Brand & Style

The design system is engineered for a **Data Analysis Toolkit** that bridges the gap between academic rigor and modern software usability. The brand personality is intellectual, meticulous, and authoritative, yet accessible to students and researchers who may have limited programming experience.

The visual direction follows a **Corporate / Modern** aesthetic with a heavy emphasis on **Minimalism**. By prioritizing extreme clarity, structured information hierarchy, and functional whitespace, the system ensures that complex statistical data remains the focus. The design avoids unnecessary ornamentation, opting instead for a "lab-grade" precision that evokes trust and reliability.

**Key Attributes:**
- **Modular:** Components are designed to be "pluggable," reflecting the step-by-step nature of data exploration, processing, and inference.
- **Utilitarian:** Every visual element serves a functional purpose, facilitating rapid scanning of tables and charts.
- **Refined:** A sophisticated palette and sharp typography elevate the toolkit from a simple script to a professional-grade research environment.

## Colors

The color palette is rooted in "Analytical Blue" tones to communicate stability and logical depth. 

- **Primary (#1A365D):** A deep Navy used for brand headers, primary navigation, and high-level structural elements. It provides the academic weight required for a university-level tool.
- **Secondary (#3182CE):** A bright, clear blue used for interactive elements, primary buttons, and active states. It draws the eye to essential actions without being fatiguing.
- **Neutral (#F7FAFC):** A crisp, cool-toned white/grey used for the background to reduce glare during long analysis sessions.
- **Slate Greys:** Used for typography and secondary UI borders to maintain a soft contrast that is easier on the eyes than pure black.

Data visualization should utilize a distinct categorical palette that is color-blind accessible, ensuring that line graphs and scatter plots remain legible for all users.

## Typography

Typography is the most critical element for a data-heavy toolkit. 

- **Headings:** **Hanken Grotesk** is chosen for its sharp, contemporary geometry. It feels professional and modern, providing a clear "anchor" for different analysis modules.
- **Body:** **Inter** is the workhorse font. It is specifically optimized for computer screens and excels in high-density data views, ensuring that statistical summaries are easily digestible.
- **Data & Labels:** **JetBrains Mono** is utilized for any data values, statistical outputs (like p-values or coefficients), and code snippets. The monospaced nature ensures that columns of numbers align perfectly, aiding in visual comparison.

For mobile views, heading sizes are aggressively scaled down to ensure that the content remains the hero and fits within the narrower viewport without excessive wrapping.

## Layout & Spacing

This design system employs a **Fixed Grid** philosophy for desktop to maintain a "dashboard" feel, while transitioning to a **Fluid** model for mobile.

- **Desktop (1280px+):** A 12-column grid with a 24px gutter. This allows for modular "cards" that can span 4 columns (for small metrics), 6 columns (for charts), or 12 columns (for large data tables).
- **Tablet:** 8-column grid. Modules reflow to stack vertically where necessary.
- **Mobile:** 4-column grid with a 16px side margin. Charts should maintain a minimum aspect ratio to remain legible.

Spacing follows an 8px base unit. Component internal padding should be generous (16px or 24px) to prevent data from feeling "cluttered," which is a common pitfall in analytical tools. Use the "stack" variables to create consistent vertical rhythm between different sections of the analysis report.

## Elevation & Depth

To maintain a clean, academic look, this design system uses **Tonal Layers** and **Low-contrast Outlines** rather than heavy shadows.

- **Surface Levels:** The main background is the lightest neutral. Content "modules" (cards) sit on a pure white background with a subtle 1px border (#E2E8F0).
- **Subtle Depth:** A very soft, diffused shadow (0px 4px 12px rgba(0,0,0,0.05)) is used only for "active" or "floating" elements like dropdown menus or tooltips to differentiate them from the base analytical plane.
- **State Changes:** Hovering over a data row or a card should result in a slight background tint change (to a light blue-grey) rather than a vertical lift. This keeps the interface feeling "grounded" and precise.

## Shapes

The design system utilizes **Soft (0.25rem)** roundedness. 

This level of rounding strikes a balance between the "mathematical" precision of sharp corners and the "user-friendly" approachability of rounded corners. 
- **Small Elements:** Buttons, checkboxes, and input fields use the base 0.25rem radius.
- **Container Elements:** Cards and modular sections use `rounded-lg` (0.5rem) to clearly define different areas of the analysis without appearing too "bubbly" or casual.

## Components

### Buttons
- **Primary:** Solid #3182CE with white text. High contrast for the "Run Analysis" or "Export" actions.
- **Secondary:** Outlined with #3182CE. Used for non-primary actions like "Reset Filters."
- **Ghost:** Minimal padding, no border. Used for navigation within tabs.

### Input Fields
Inputs must include clear labels in `label-caps` typography. The focus state should be a 2px stroke of the secondary color. Use specific input types for numeric data entry to prevent errors.

### Data Tables
Tables are the heart of the toolkit.
- **Headers:** Light grey background (#EDF2F7) with bold text.
- **Rows:** Alternate row striping (zebra striping) for better readability of wide datasets.
- **Alignment:** Numbers should be right-aligned; text should be left-aligned.

### Cards
All analytical modules (e.g., "Descriptive Statistics", "Visualization") must be contained in a card. Cards should include a header area with the title of the module and any context-specific actions (like a "Download CSV" icon).

### Status Chips
Use chips for data types (e.g., "Integer", "String", "Float") or analysis status ("Complete", "Processing"). Use the success/error colors with a 10% opacity background for high legibility and low visual noise.