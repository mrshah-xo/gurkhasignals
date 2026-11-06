---
version: "1.0"
name: "Crop Compass — Blue Horizon Design System"
description: "A premium, minimal agricultural-technology interface inspired by the Crop Compass identity. It combines a confident blue navigation system, restrained green growth accents, crisp white compass geometry, calm data surfaces, and Apple's disciplined typography and spacing—adapted for a practical application rather than a marketing website."

colors:
  # Brand blues — derived from the logo's cyan-to-electric-blue field
  brand-blue: "#087BFA"
  brand-blue-deep: "#0755E8"
  brand-cyan: "#16C9E8"
  brand-blue-soft: "#EAF4FF"
  brand-blue-pale: "#F4F9FF"
  brand-blue-focus: "#3B91FF"
  brand-blue-on-dark: "#69B8FF"

  # Agriculture greens — derived from the compass arrow
  growth-green: "#39D80B"
  growth-green-deep: "#079447"
  growth-green-soft: "#EAF9E8"
  growth-green-pale: "#F4FCF1"
  growth-green-on-dark: "#83E86A"

  # Neutral surfaces
  canvas: "#F7F9FC"
  canvas-white: "#FFFFFF"
  surface-soft: "#F1F5FA"
  surface-blue: "#EDF5FF"
  surface-green: "#F0F9ED"
  surface-elevated: "#FFFFFF"
  surface-dark: "#101B2D"
  surface-dark-raised: "#17263B"
  surface-map: "#EAF1F5"

  # Text
  ink: "#142033"
  body: "#344256"
  body-muted: "#718096"
  body-subtle: "#94A0B2"
  body-on-dark: "#F7FAFF"
  body-muted-on-dark: "#AAB8CA"
  on-brand: "#FFFFFF"
  on-growth: "#102A18"

  # Borders and feedback
  border: "#E3EAF2"
  border-strong: "#CBD7E5"
  divider: "#EAF0F6"
  focus-ring: "#8CC4FF"
  success: "#168A45"
  success-soft: "#EAF8EF"
  warning: "#C98212"
  warning-soft: "#FFF6E5"
  danger: "#D64545"
  danger-soft: "#FFF0F0"
  info: "#1479D5"
  info-soft: "#EAF4FF"
  disabled: "#AAB5C3"
  disabled-surface: "#EEF2F6"

  # Gradients — use only for brand moments and selected emphasis
  gradient-brand: "linear-gradient(135deg, #16C9E8 0%, #087BFA 52%, #0755E8 100%)"
  gradient-brand-deep: "linear-gradient(145deg, #087BFA 0%, #0755E8 100%)"
  gradient-growth: "linear-gradient(135deg, #A7F51A 0%, #39D80B 48%, #079447 100%)"
  gradient-compass-arrow: "linear-gradient(145deg, #A7F51A 0%, #39D80B 45%, #079447 100%)"

typography:
  font-family:
    display: "Inter, SF Pro Display, system-ui, -apple-system, sans-serif"
    body: "Inter, SF Pro Text, system-ui, -apple-system, sans-serif"
    data: "Inter, ui-sans-serif, system-ui, sans-serif"

  hero:
    fontFamily: "Inter, system-ui, sans-serif"
    fontSize: 48px
    fontWeight: 650
    lineHeight: 1.08
    letterSpacing: "-0.04em"
  display-lg:
    fontFamily: "Inter, system-ui, sans-serif"
    fontSize: 36px
    fontWeight: 650
    lineHeight: 1.14
    letterSpacing: "-0.035em"
  display-md:
    fontFamily: "Inter, system-ui, sans-serif"
    fontSize: 28px
    fontWeight: 620
    lineHeight: 1.2
    letterSpacing: "-0.025em"
  heading:
    fontFamily: "Inter, system-ui, sans-serif"
    fontSize: 22px
    fontWeight: 620
    lineHeight: 1.3
    letterSpacing: "-0.02em"
  subheading:
    fontFamily: "Inter, system-ui, sans-serif"
    fontSize: 18px
    fontWeight: 600
    lineHeight: 1.35
    letterSpacing: "-0.01em"
  body-strong:
    fontFamily: "Inter, system-ui, sans-serif"
    fontSize: 15px
    fontWeight: 600
    lineHeight: 1.5
    letterSpacing: "-0.01em"
  body:
    fontFamily: "Inter, system-ui, sans-serif"
    fontSize: 15px
    fontWeight: 400
    lineHeight: 1.55
    letterSpacing: "0"
  body-compact:
    fontFamily: "Inter, system-ui, sans-serif"
    fontSize: 14px
    fontWeight: 400
    lineHeight: 1.45
    letterSpacing: "0"
  label:
    fontFamily: "Inter, system-ui, sans-serif"
    fontSize: 13px
    fontWeight: 550
    lineHeight: 1.35
    letterSpacing: "0.005em"
  caption:
    fontFamily: "Inter, system-ui, sans-serif"
    fontSize: 12px
    fontWeight: 400
    lineHeight: 1.45
    letterSpacing: "0.005em"
  caption-strong:
    fontFamily: "Inter, system-ui, sans-serif"
    fontSize: 12px
    fontWeight: 650
    lineHeight: 1.35
    letterSpacing: "0.01em"
  metric:
    fontFamily: "Inter, system-ui, sans-serif"
    fontSize: 30px
    fontWeight: 650
    lineHeight: 1.1
    letterSpacing: "-0.035em"
    fontVariantNumeric: "tabular-nums"
  metric-sm:
    fontFamily: "Inter, system-ui, sans-serif"
    fontSize: 22px
    fontWeight: 650
    lineHeight: 1.15
    letterSpacing: "-0.025em"
    fontVariantNumeric: "tabular-nums"
  button:
    fontFamily: "Inter, system-ui, sans-serif"
    fontSize: 14px
    fontWeight: 600
    lineHeight: 1.2
    letterSpacing: "0"
  navigation:
    fontFamily: "Inter, system-ui, sans-serif"
    fontSize: 13px
    fontWeight: 550
    lineHeight: 1.2
    letterSpacing: "0"
  fine-print:
    fontFamily: "Inter, system-ui, sans-serif"
    fontSize: 11px
    fontWeight: 400
    lineHeight: 1.4
    letterSpacing: "0"

rounded:
  xs: "6px"
  sm: "9px"
  md: "12px"
  lg: "16px"
  xl: "20px"
  xxl: "26px"
  pill: "9999px"
  full: "50%"

spacing:
  xxs: "4px"
  xs: "8px"
  sm: "12px"
  md: "16px"
  lg: "20px"
  xl: "24px"
  xxl: "32px"
  section: "40px"
  page: "48px"

elevation:
  none: "none"
  subtle: "0 1px 2px rgba(20, 32, 51, 0.04)"
  card: "0 4px 14px rgba(20, 45, 80, 0.06)"
  floating: "0 10px 30px rgba(20, 45, 80, 0.12)"
  popover: "0 16px 40px rgba(20, 32, 51, 0.16)"

motion:
  fast: "120ms"
  normal: "180ms"
  deliberate: "260ms"
  easing: "cubic-bezier(0.2, 0.8, 0.2, 1)"
  press-scale: "0.98"

layout:
  content-max: "1440px"
  reading-max: "760px"
  sidebar-width: "248px"
  sidebar-collapsed: "76px"
  topbar-height: "64px"
  mobile-nav-height: "68px"
  minimum-touch-target: "44px"

components:
  app-shell:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
  sidebar:
    backgroundColor: "{colors.canvas-white}"
    textColor: "{colors.body}"
    width: "{layout.sidebar-width}"
    borderRight: "1px solid {colors.border}"
  topbar:
    backgroundColor: "rgba(255, 255, 255, 0.88)"
    textColor: "{colors.ink}"
    height: "{layout.topbar-height}"
    borderBottom: "1px solid {colors.border}"
    backdropFilter: "saturate(160%) blur(16px)"
  bottom-navigation:
    backgroundColor: "rgba(255, 255, 255, 0.94)"
    textColor: "{colors.body-muted}"
    height: "{layout.mobile-nav-height}"
    backdropFilter: "saturate(160%) blur(16px)"
  button-primary:
    background: "{colors.gradient-brand-deep}"
    textColor: "{colors.on-brand}"
    typography: "{typography.button}"
    rounded: "{rounded.md}"
    padding: "12px 18px"
    minHeight: "44px"
  button-primary-pressed:
    backgroundColor: "{colors.brand-blue-deep}"
    textColor: "{colors.on-brand}"
    transform: "scale(0.98)"
  button-secondary:
    backgroundColor: "{colors.canvas-white}"
    textColor: "{colors.brand-blue-deep}"
    border: "1px solid {colors.border-strong}"
    typography: "{typography.button}"
    rounded: "{rounded.md}"
    padding: "11px 17px"
    minHeight: "44px"
  button-growth:
    background: "{colors.gradient-growth}"
    textColor: "{colors.on-growth}"
    typography: "{typography.button}"
    rounded: "{rounded.md}"
    padding: "12px 18px"
    minHeight: "44px"
  button-quiet:
    backgroundColor: "transparent"
    textColor: "{colors.body}"
    typography: "{typography.button}"
    rounded: "{rounded.md}"
    padding: "10px 12px"
    minHeight: "44px"
  button-icon:
    backgroundColor: "{colors.surface-soft}"
    textColor: "{colors.body}"
    rounded: "{rounded.md}"
    size: "44px"
  card:
    backgroundColor: "{colors.surface-elevated}"
    textColor: "{colors.ink}"
    border: "1px solid {colors.border}"
    rounded: "{rounded.lg}"
    padding: "20px"
    shadow: "{elevation.subtle}"
  card-highlight:
    backgroundColor: "{colors.surface-blue}"
    textColor: "{colors.ink}"
    border: "1px solid #D7E9FF"
    rounded: "{rounded.lg}"
    padding: "20px"
  card-growth:
    backgroundColor: "{colors.surface-green}"
    textColor: "{colors.ink}"
    border: "1px solid #D9EFD4"
    rounded: "{rounded.lg}"
    padding: "20px"
  metric-card:
    backgroundColor: "{colors.canvas-white}"
    textColor: "{colors.ink}"
    border: "1px solid {colors.border}"
    rounded: "{rounded.lg}"
    padding: "18px"
  search-input:
    backgroundColor: "{colors.canvas-white}"
    textColor: "{colors.ink}"
    border: "1px solid {colors.border-strong}"
    typography: "{typography.body}"
    rounded: "{rounded.md}"
    padding: "11px 14px"
    height: "46px"
  filter-chip:
    backgroundColor: "{colors.surface-soft}"
    textColor: "{colors.body}"
    typography: "{typography.label}"
    rounded: "{rounded.pill}"
    padding: "8px 13px"
    minHeight: "36px"
  filter-chip-selected:
    backgroundColor: "{colors.brand-blue-soft}"
    textColor: "{colors.brand-blue-deep}"
    border: "1px solid #C7E0FF"
    typography: "{typography.label}"
    rounded: "{rounded.pill}"
    padding: "8px 13px"
  status-success:
    backgroundColor: "{colors.success-soft}"
    textColor: "{colors.success}"
    rounded: "{rounded.pill}"
    typography: "{typography.caption-strong}"
    padding: "5px 9px"
  status-warning:
    backgroundColor: "{colors.warning-soft}"
    textColor: "{colors.warning}"
    rounded: "{rounded.pill}"
    typography: "{typography.caption-strong}"
    padding: "5px 9px"
  status-danger:
    backgroundColor: "{colors.danger-soft}"
    textColor: "{colors.danger}"
    rounded: "{rounded.pill}"
    typography: "{typography.caption-strong}"
    padding: "5px 9px"
  status-info:
    backgroundColor: "{colors.info-soft}"
    textColor: "{colors.info}"
    rounded: "{rounded.pill}"
    typography: "{typography.caption-strong}"
    padding: "5px 9px"
  map-panel:
    backgroundColor: "{colors.surface-map}"
    textColor: "{colors.ink}"
    border: "1px solid {colors.border}"
    rounded: "{rounded.xl}"
    overflow: "hidden"
  map-control:
    backgroundColor: "{colors.canvas-white}"
    textColor: "{colors.body}"
    rounded: "{rounded.md}"
    shadow: "{elevation.card}"
    size: "44px"
  data-panel:
    backgroundColor: "{colors.canvas-white}"
    textColor: "{colors.ink}"
    border: "1px solid {colors.border}"
    rounded: "{rounded.lg}"
    padding: "20px"
  chart-tooltip:
    backgroundColor: "{colors.surface-dark}"
    textColor: "{colors.body-on-dark}"
    rounded: "{rounded.sm}"
    padding: "8px 11px"
    shadow: "{elevation.floating}"
  modal:
    backgroundColor: "{colors.canvas-white}"
    textColor: "{colors.ink}"
    rounded: "{rounded.xl}"
    padding: "24px"
    shadow: "{elevation.popover}"
  toast:
    backgroundColor: "{colors.surface-dark}"
    textColor: "{colors.body-on-dark}"
    rounded: "{rounded.md}"
    padding: "12px 16px"
    shadow: "{elevation.floating}"
  empty-state:
    backgroundColor: "{colors.surface-blue}"
    textColor: "{colors.body}"
    rounded: "{rounded.xl}"
    padding: "32px"
  table:
    backgroundColor: "{colors.canvas-white}"
    textColor: "{colors.body}"
    border: "1px solid {colors.border}"
    rounded: "{rounded.lg}"
  footer:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.body-muted}"
    typography: "{typography.caption}"
---

# Crop Compass — Frontend Design System

## 1. Design Direction

### Blue Horizon × Living Green

Crop Compass should feel like a **premium agricultural intelligence and navigation application**. The interface takes its visual cues from the app icon:

- The blue field communicates trust, clarity, technology, and navigation.
- The green arrow communicates agriculture, growth, and forward movement.
- The white compass ring communicates precision, orientation, and dependable guidance.
- The geometric mark communicates a modern, engineered product rather than a traditional farm-management tool.

The design should preserve Apple's strongest principles—restraint, hierarchy, whitespace, legibility, and consistency—without reproducing Apple's monochrome palette or marketing-page composition.

**The product is an application, not a product landing page.** Prioritize usable navigation, clear information architecture, maps or location-oriented content where relevant, readable data, and efficient task completion.

### Design keywords

`Premium` · `Clear` · `Trustworthy` · `Agricultural` · `Geospatial` · `Modern` · `Calm` · `Precise` · `Approachable`

### Core visual balance

- 65–75% neutral surfaces and whitespace.
- 15–25% blue brand surfaces and interactive elements.
- 5–10% green accents and growth-related emphasis.

These are visual guidelines, not rigid pixel ratios. Green should not compete with blue for primary navigation or become the default color of every button.

## 2. Logo-to-Interface Translation

| Logo element | Interface expression |
|---|---|
| Cyan-to-electric-blue background | Primary actions, selected navigation, key brand moments, restrained hero gradients |
| White compass ring | Circular progress indicators, location markers, orientation cues, icon geometry |
| Lime-to-deep-green arrow | Growth indicators, agriculture-related highlights, positive recommendations |
| White arrow facet | Light surfaces, clear contrast, crisp iconography |
| Rounded-square app icon | Softly rounded application containers, not excessively rounded every element |

### Brand gradient

The logo's gradient is an important part of the identity and should not be removed entirely. Use it selectively:

- Primary CTA backgrounds, when a stronger brand moment is appropriate.
- Welcome or onboarding panels.
- Selected dashboard highlights.
- Small decorative brand illustrations or empty states.

Do not apply the gradient to every card, page background, navigation bar, or chart. Most of the application should use flat surfaces so the interface remains calm and data remains readable.

## 3. Color System

### Primary blue

- **Brand Blue** (`{colors.brand-blue}` — #087BFA): Main brand and interactive color. Use for primary actions, active navigation, links, selected controls, and important map interactions.
- **Deep Brand Blue** (`{colors.brand-blue-deep}` — #0755E8): Stronger blue for primary button fills, active states, and high-contrast emphasis.
- **Brand Cyan** (`{colors.brand-cyan}` — #16C9E8): A supporting highlight drawn from the brighter left side of the logo gradient. Use sparingly in illustrations and gradient transitions.
- **Soft Blue** (`{colors.brand-blue-soft}` — #EAF4FF): Selected navigation backgrounds, informational panels, and low-emphasis highlights.
- **Pale Blue** (`{colors.brand-blue-pale}` — #F4F9FF): Subtle page or card backgrounds.

### Agriculture green

- **Growth Green** (`{colors.growth-green}` — #39D80B): Bright logo-derived accent. Reserve for small visual highlights, positive growth indicators, and selected agricultural emphasis. Avoid using it for long text because its brightness reduces readability.
- **Deep Growth Green** (`{colors.growth-green-deep}` — #079447): Readable green for text, icons, and meaningful positive states.
- **Soft Growth** (`{colors.growth-green-soft}` — #EAF9E8): Background for growth-related insights, positive status panels, or crop-related emphasis.
- **Pale Growth** (`{colors.growth-green-pale}` — #F4FCF1): Very subtle green-tinted surface.
- **Growth on Dark** (`{colors.growth-green-on-dark}` — #83E86A): Green foreground on dark surfaces.

Green is a brand-supporting color, not a replacement for semantic status colors. Do not imply that every green value means success if the content is simply agricultural.

### Neutral surfaces

- **Canvas** (`{colors.canvas}` — #F7F9FC): Default application background. A cool, slightly blue-tinted white rather than a warm gray.
- **White** (`{colors.canvas-white}` — #FFFFFF): Cards, dialogs, input surfaces, and content panels.
- **Soft Surface** (`{colors.surface-soft}` — #F1F5FA): Secondary controls, inactive chips, and grouped utility areas.
- **Dark Surface** (`{colors.surface-dark}` — #101B2D): Dark-mode foundation, map overlays, and high-contrast panels.
- **Raised Dark** (`{colors.surface-dark-raised}` — #17263B): Elevated dark-mode cards and navigation surfaces.

### Text

- **Ink** (`{colors.ink}` — #142033): Primary headings, values, and high-priority text.
- **Body** (`{colors.body}` — #344256): Standard paragraph and interface text.
- **Muted** (`{colors.body-muted}` — #718096): Supporting labels, metadata, timestamps, and secondary descriptions.
- **Subtle** (`{colors.body-subtle}` — #94A0B2): Placeholder and low-priority text. Do not use for essential information.
- **On Dark** (`{colors.body-on-dark}` — #F7FAFF): Primary text on dark surfaces.

### Semantic colors

Use semantic colors consistently and independently of the brand palette:

- Success: `{colors.success}` with `{colors.success-soft}`.
- Warning: `{colors.warning}` with `{colors.warning-soft}`.
- Danger: `{colors.danger}` with `{colors.danger-soft}`.
- Information: `{colors.info}` with `{colors.info-soft}`.

Never communicate a status using color alone. Pair it with a label or icon.

### Gradient rules

- Use `{colors.gradient-brand}` for selected brand moments, not as a universal background.
- Use `{colors.gradient-brand-deep}` for primary actions where a gradient is appropriate.
- Use `{colors.gradient-growth}` only for selected growth-oriented emphasis.
- Avoid rainbow gradients, purple/pink additions, and unrelated accent colors.
- Keep text and controls on gradients high-contrast and easy to read.

## 4. Typography

### Font family

- **Display and headings:** `Inter, SF Pro Display, system-ui, -apple-system, sans-serif`.
- **Body and UI:** `Inter, SF Pro Text, system-ui, -apple-system, sans-serif`.
- **Data:** `Inter, ui-sans-serif, system-ui, sans-serif` with tabular numerals for aligned values.

Inter is the default cross-platform choice. SF Pro may render on Apple platforms through the system stack. Do not depend on a proprietary font being installed.

### Hierarchy

| Token | Size | Weight | Line height | Use |
|---|---:|---:|---:|---|
| `{typography.hero}` | 48px | 650 | 1.08 | Welcome or onboarding headline |
| `{typography.display-lg}` | 36px | 650 | 1.14 | Main page title |
| `{typography.display-md}` | 28px | 620 | 1.20 | Major section title |
| `{typography.heading}` | 22px | 620 | 1.30 | Card and panel title |
| `{typography.subheading}` | 18px | 600 | 1.35 | Subsection heading |
| `{typography.body-strong}` | 15px | 600 | 1.50 | Emphasis and important labels |
| `{typography.body}` | 15px | 400 | 1.55 | Standard interface copy |
| `{typography.body-compact}` | 14px | 400 | 1.45 | Dense supporting copy |
| `{typography.label}` | 13px | 550 | 1.35 | Form labels and navigation |
| `{typography.caption}` | 12px | 400 | 1.45 | Metadata and helper text |
| `{typography.metric}` | 30px | 650 | 1.10 | Primary dashboard metrics |
| `{typography.metric-sm}` | 22px | 650 | 1.15 | Compact metric values |

### Typography principles

- Use confident, compact headings with modest negative tracking.
- Keep body copy at 15px or larger for comfortable application use.
- Use 12–13px only for secondary labels and metadata.
- Use weight 600–650 for hierarchy; avoid making every label bold.
- Use tabular numerals for measurements, dates, counts, and dashboard metrics.
- Keep paragraphs at a comfortable 1.45–1.6 line height.
- Do not use oversized editorial typography in ordinary dashboard cards.

## 5. Layout and Information Density

### Application shell

The interface should use a practical application layout rather than Apple's full-bleed product-tile layout.

**Desktop:**
- Persistent left sidebar for primary navigation.
- Top bar for page context, search or utility actions, and account controls.
- Main content area with a clear page title and structured sections.
- Optional contextual panel for map details, filters, or selected records.

**Mobile:**
- Compact top bar with page title and essential actions.
- Bottom navigation for the most important destinations.
- Content arranged in a single column.
- Filters and secondary actions may move into sheets or expandable panels.

### Content width

- Maximum application content width: `{layout.content-max}`.
- Reading-oriented content: `{layout.reading-max}`.
- Desktop sidebar: `{layout.sidebar-width}`.
- Collapsed sidebar: `{layout.sidebar-collapsed}`.
- Avoid stretching dense tables and forms across very wide screens without a reason.

### Spacing

Use an 8px-based rhythm:

- 4px: icon-to-label micro spacing.
- 8px: compact control spacing.
- 12px: related elements.
- 16px: standard internal spacing.
- 20–24px: card padding and section grouping.
- 32px: separation between major content groups.
- 40–48px: page-level section spacing.

Whitespace should clarify relationships, not create unnecessarily tall screens. Application screens need a higher information density than Apple's marketing pages while remaining uncluttered.

### Grid

- Desktop dashboard: 12-column conceptual grid.
- Tablet: 6-column or two-column card layout.
- Mobile: single-column stack.
- Metric cards: 2–4 across depending on available width.
- Maintain 16–20px gaps between major cards.

## 6. Shape and Geometry

### Radius scale

| Token | Value | Use |
|---|---:|---|
| `{rounded.xs}` | 6px | Small tags and compact elements |
| `{rounded.sm}` | 9px | Inputs and compact controls |
| `{rounded.md}` | 12px | Buttons and standard controls |
| `{rounded.lg}` | 16px | Main cards and panels |
| `{rounded.xl}` | 20px | Large map panels and dialogs |
| `{rounded.xxl}` | 26px | Special onboarding or feature surfaces |
| `{rounded.pill}` | 9999px | Status badges and filter chips |
| `{rounded.full}` | 50% | Circular icon and map controls |

### Geometry principles

- Use consistent rounded rectangles rather than rounding everything into capsules.
- Keep primary buttons moderately rounded (`12px`), not excessively pill-shaped.
- Reserve pill shapes for compact status labels, filters, and small selectable chips.
- Use circular shapes for compass-related controls, location markers, and icon buttons.
- Do not distort the compass logo or create unrelated compass-like decorative marks.

## 7. Elevation, Borders, and Depth

| Level | Treatment | Use |
|---|---|---|
| Flat | No shadow, no border | Page canvas and broad content regions |
| Hairline | 1px `{colors.border}` | Cards, inputs, separators |
| Subtle | `{elevation.subtle}` | Default cards |
| Card | `{elevation.card}` | Interactive or grouped panels |
| Floating | `{elevation.floating}` | Popovers, floating map controls |
| Modal | `{elevation.popover}` | Dialogs and overlays |

### Shadow philosophy

The original Apple theme used almost no interface elevation. Crop Compass should retain that restraint, but a functional application benefits from subtle separation between cards and the page canvas.

- Prefer borders and surface contrast first.
- Use shadows only to clarify hierarchy or floating behavior.
- Avoid heavy, dark shadows and stacked neumorphic effects.
- Never use shadows as a substitute for spacing or clear grouping.

## 8. Navigation

### Desktop sidebar

The sidebar is the main application navigation surface.

- White background with a subtle right border.
- Crop Compass logo and product name at the top.
- Clear icon-and-label navigation items.
- Active item uses a soft blue background and deep-blue icon/text.
- Avoid filling the entire active row with a saturated gradient.
- Group secondary destinations separately from primary workflows.
- Keep labels short and navigation predictable.

### Top bar

- White translucent surface with a subtle bottom border.
- Page title or breadcrumb on the left.
- Search, notifications, help, or profile actions on the right when those features exist.
- Use 44px minimum icon-button hit areas.
- Do not overload the top bar with every available action.

### Mobile navigation

- Fixed bottom navigation with a white translucent surface.
- Use a small number of primary destinations.
- Active icon and label use `{colors.brand-blue-deep}`.
- Inactive items use `{colors.body-muted}`.
- Keep labels visible where possible; do not rely on icons alone.

## 9. Buttons and Interactive Controls

### Primary button

`button-primary` is the main action style.

- Blue gradient or deep blue fill.
- White label.
- 12px radius.
- Minimum 44px height.
- Use for the most important action in a screen or panel.

### Secondary button

`button-secondary` is for an alternative action.

- White fill.
- Subtle border.
- Blue label.
- Same height and geometry as the primary button.

### Growth button

`button-growth` is a special-purpose accent.

- Green gradient.
- Dark, high-contrast label.
- Use only when the action is explicitly related to a growth-oriented or agriculture-specific workflow.
- Do not use as a second primary button beside every blue CTA.

### Quiet and icon buttons

- Use quiet buttons for low-priority actions.
- Icon buttons use a soft neutral surface and a minimum 44 × 44px target.
- Include accessible labels for icon-only controls.

### Interaction states

- Default: clearly visible and legible.
- Pressed: `transform: scale(0.98)` with a subtle fill shift.
- Focus: 2px visible ring using `{colors.focus-ring}`.
- Disabled: `{colors.disabled}` text and `{colors.disabled-surface}` surface.
- Loading: preserve button width and communicate progress without causing layout shift.

## 10. Cards and Data Surfaces

### Standard card

Use `{component.card}` for general content.

- White surface.
- 1px subtle border.
- 16px radius.
- 20px padding.
- Minimal shadow.

### Highlight card

Use `{component.card-highlight}` for a selected item, important recommendation, or informational highlight. Blue-tinted surfaces should remain light enough for comfortable reading.

### Growth card

Use `{component.card-growth}` for content specifically associated with crop growth, agricultural progress, or positive crop-related insight. Do not use it for unrelated settings or generic actions.

### Metric card

Use `{component.metric-card}` for key values.

- Metric value first.
- Short descriptive label.
- Optional trend or supporting metadata.
- Avoid decorative chart clutter.
- Use tabular numerals for aligned values.

### Data panels

- Use consistent section headings.
- Keep labels close to their values.
- Separate unrelated groups with spacing or a hairline.
- Prefer concise summaries with a path to more detail.
- Always include units for measurements.

## 11. Maps and Compass-Led UI

The logo makes navigation and orientation a distinctive part of the brand. If the application includes maps or location-based workflows, those surfaces should feel like a core product experience rather than an embedded afterthought.

### Map canvas

- Use a quiet, low-saturation map base.
- Keep roads, boundaries, labels, and terrain readable.
- Use blue for the user's current location, selected position, or active navigation state.
- Use green for relevant agricultural areas or crop-related overlays.
- Avoid filling the entire map with saturated blue or green.
- Keep map labels legible above overlays.

### Map controls

- White circular or softly rounded control surfaces.
- Subtle shadow for separation from the map.
- Blue for the active tool or selected state.
- Minimum 44 × 44px touch targets.
- Place controls consistently and avoid covering important map content.

### Compass motif

- Use the compass symbol as a functional orientation cue where appropriate.
- Keep compass graphics simple, flat, and crisp in dense application screens.
- The full logo may appear in onboarding, splash, or brand areas; do not repeat the full logo as decoration on every page.

### Markers and overlays

- Use clear shapes and labels, not color alone.
- Selected markers may use a blue ring or blue surface.
- Agricultural overlays may use restrained green opacity.
- Provide a legend when multiple overlay types appear.
- Ensure map information remains distinguishable for users with color-vision differences.

## 12. Forms, Search, and Filters

### Search input

Use `{component.search-input}`.

- White surface.
- Subtle border.
- 12px radius.
- Search icon at the leading edge.
- Clear button only when a query exists.
- Use helpful placeholder text, not instructions that belong outside the field.

### Form fields

- Labels appear above the field.
- Use persistent labels rather than placeholder-only labels.
- Keep helper text directly below the relevant field.
- Show validation messages near the field that needs attention.
- Use semantic error colors and clear text explanations.
- Maintain consistent field heights and spacing.

### Filter chips

- Neutral inactive state.
- Soft blue selected state.
- Pill radius.
- Clear selected-state contrast.
- Allow horizontal scrolling on narrow screens when necessary.

## 13. Data Visualization

Charts should be informative, calm, and consistent with the brand.

### Color mapping

- Blue: primary data series, selected values, and navigation-related data.
- Green: crop or growth-related series when semantically appropriate.
- Cyan: secondary comparison series.
- Amber: caution or attention.
- Red: critical or negative status.

### Chart principles

- Use a restrained number of series.
- Label axes and units.
- Avoid unnecessary gradients inside charts.
- Keep grid lines faint.
- Highlight selected data points with a clear marker or tooltip.
- Never rely on color alone to distinguish multiple series.
- Use consistent color meaning across the application.

### Metrics

- Use `{typography.metric}` for key dashboard values.
- Pair every metric with a clear label and unit.
- Use `{typography.metric-sm}` for compact secondary values.
- Do not invent precision; display only the precision supported by the underlying data.

## 14. Dark Mode

Dark mode should be a first-class adaptation of the same identity, not a simple inversion.

### Surface mapping

| Light mode | Dark mode direction |
|---|---|
| `{colors.canvas}` | `{colors.surface-dark}` |
| `{colors.canvas-white}` | `{colors.surface-dark-raised}` |
| `{colors.surface-blue}` | Deep blue-tinted surface |
| `{colors.surface-green}` | Deep green-tinted surface |
| `{colors.ink}` | `{colors.body-on-dark}` |
| `{colors.body-muted}` | `{colors.body-muted-on-dark}` |
| `{colors.border}` | Low-contrast blue-gray border |

### Dark-mode rules

- Preserve blue as the primary interaction color.
- Use a softened green for growth accents; avoid neon green over large areas.
- Keep cards distinguishable from the page background.
- Do not use pure black as the default background.
- Reduce gradient intensity and avoid bright gradients behind body text.
- Recheck all charts, maps, badges, and disabled states for contrast.

## 15. Iconography and Illustration

- Use a consistent outline icon family with simple geometry.
- Prefer 1.75–2px stroke weights at standard interface sizes.
- Use filled icons only for active states or clear status indicators.
- Use blue for primary navigation icons and green for selected agricultural meaning.
- Avoid mixing 3D icons, emoji, thin line icons, and filled icon families in the same navigation system.
- Keep illustrations flat, geometric, and low-detail.
- The compass mark should remain the signature symbol; do not turn every icon into a compass.

## 16. Imagery and Asset Direction

- Prefer genuine, relevant agricultural imagery over generic corporate stock photos.
- Crop imagery should support the task or information being shown.
- Use consistent image ratios within the same card group.
- Avoid placing text over busy photographs without a contrast treatment.
- Use the logo's blue gradient as a background for selected brand illustrations, not every image.
- Keep decorative imagery secondary to actual application information.
- Optimize images for responsive display and load important above-the-fold content first.

## 17. Responsive Behavior

### Breakpoints

| Name | Width | Key changes |
|---|---:|---|
| Small phone | ≤ 390px | Single column; compact page padding; bottom navigation |
| Phone | 391–640px | Single-column cards; collapsible filters |
| Large phone | 641–767px | Wider card padding; compact two-column metrics where practical |
| Tablet | 768–1023px | Collapsible sidebar; two-column content |
| Small desktop | 1024–1199px | Narrow sidebar; two- or three-column dashboard |
| Desktop | 1200–1440px | Full sidebar and standard dashboard grid |
| Wide desktop | ≥ 1441px | Content constrained to `{layout.content-max}` |

### Responsive principles

- Do not simply shrink desktop layouts; reorganize them around mobile tasks.
- Keep primary actions visible and reachable.
- Convert dense tables into horizontally scrollable tables or structured mobile rows.
- Move secondary filters into a drawer or sheet on narrow screens.
- Preserve readable type sizes and touch targets.
- Maps should remain usable at mobile sizes; controls must not obscure the main interaction area.

## 18. Accessibility

- Meet WCAG AA contrast for normal text wherever possible.
- Do not use bright `{colors.growth-green}` as small text on white; use `{colors.growth-green-deep}` instead.
- Provide visible keyboard focus states.
- Use semantic headings and labels.
- Ensure all controls are keyboard accessible.
- Provide accessible names for icon-only buttons.
- Pair status colors with text or icons.
- Respect reduced-motion preferences.
- Do not communicate map or chart information through color alone.
- Maintain at least 44 × 44px touch targets for primary interactive controls.

## 19. Motion and Micro-interactions

Motion should make the interface feel responsive, not ornamental.

- Fast feedback: `{motion.fast}`.
- Standard transitions: `{motion.normal}`.
- Larger panel transitions: `{motion.deliberate}`.
- Easing: `{motion.easing}`.
- Press scale: `{motion.press-scale}`.

Use motion for:
- Button press feedback.
- Expanding panels and menus.
- Navigation state changes.
- Loading and progress feedback.
- Map selection and marker focus.

Avoid:
- Constantly moving decorative gradients.
- Unnecessary parallax.
- Large bouncing transitions.
- Motion that delays access to information.

## 20. Do's and Don'ts

### Do

- Use blue as the dominant brand and interaction color.
- Use green as a supporting agricultural accent.
- Keep most application surfaces white or cool-neutral.
- Use gradients selectively to preserve the logo's visual identity.
- Use Inter or a close system sans-serif with a clear hierarchy.
- Prefer structured cards, readable data, and practical navigation.
- Keep map surfaces calm and overlays purposeful.
- Use subtle borders and restrained shadows.
- Make the interface responsive and touch-friendly.
- Keep the full Crop Compass logo intact and proportionally correct.

### Don't

- Do not copy Apple's all-white/black palette or single-accent restriction.
- Do not make every button, card, or page background a gradient.
- Do not turn the entire application green.
- Do not use bright lime green for small body text.
- Do not use heavy shadows, glass effects, or excessive blur everywhere.
- Do not use oversized marketing-style hero sections inside normal application pages.
- Do not make every component pill-shaped.
- Do not introduce unrelated purple, pink, orange, or decorative accent colors.
- Do not use color alone to communicate status or map meaning.
- Do not invent product features or data in the interface; UI content must reflect actual application capabilities.

## 21. Implementation Guidance

1. Treat this file as the visual source of truth for frontend styling.
2. Use the named color, typography, spacing, radius, elevation, and motion tokens rather than repeatedly hardcoding values.
3. Build reusable components for buttons, cards, inputs, navigation, badges, and data panels.
4. Keep light and dark themes mapped to the same semantic tokens.
5. Build responsive behavior into shared components rather than creating unrelated desktop and mobile versions.
6. Use the blue gradient only where the brand needs emphasis; use flat colors for most controls and surfaces.
7. Keep semantic status colors separate from brand colors.
8. Use realistic, source-backed content and values. Do not fabricate crop recommendations, location data, weather, or measurements.
9. When adding a new component, define its default, selected, pressed, focus, disabled, and loading states where applicable.
10. Preserve accessibility, keyboard behavior, and touch target requirements as part of component implementation.

## 22. Product-Specific Decisions Still to Confirm

This design system defines the visual language and reusable interface foundations. The uploaded design reference and logo do not establish the application's complete feature set.

Before designing detailed screens, map the actual Crop Compass workflows and confirm:
- The primary user and their most frequent task.
- Whether the main experience is map-based, crop-information-based, recommendation-based, or a combination.
- Which data sources and live information the application actually provides.
- Which screens are required for the first release.

Do not create dashboard metrics, crop advice, weather panels, or map tools merely because they fit the visual theme. Add them only when they correspond to implemented product functionality.
