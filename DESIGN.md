---
version: alpha
name: Manu Kaushal Publications
description: Premium academic brand for chemistry textbooks targeting NEET and JEE aspirants. Deep navy authority meets warm gold achievement — trustworthy, clean, and aspirational.
colors:
  primary: "#1a2332"
  secondary: "#475569"
  tertiary: "#f59e0b"
  accent: "#047857"
  neutral: "#f8fafc"
  neutral-light: "#ffffff"
  neutral-mid: "#e2e8f0"
  neutral-dark: "#0f172a"
  success: "#047857"
  success-bg: "#ecfdf5"
  error: "#b91c1c"
  error-bg: "#fef2f2"
  star: "#f59e0b"
  gold-sft: "#fef3c7"
typography:
  h1:
    fontFamily: "Inter, -apple-system, BlinkMacSystemFont, sans-serif"
    fontSize: 28px
    fontWeight: 800
    lineHeight: 1.15
    letterSpacing: "-0.02em"
  h2:
    fontFamily: "Inter, -apple-system, BlinkMacSystemFont, sans-serif"
    fontSize: 22px
    fontWeight: 700
    lineHeight: 1.2
    letterSpacing: "-0.01em"
  h3:
    fontFamily: "Inter, -apple-system, BlinkMacSystemFont, sans-serif"
    fontSize: 18px
    fontWeight: 700
    lineHeight: 1.3
    letterSpacing: "0em"
  h4:
    fontFamily: "Inter, -apple-system, BlinkMacSystemFont, sans-serif"
    fontSize: 15px
    fontWeight: 600
    lineHeight: 1.4
    letterSpacing: "0em"
  body-lg:
    fontFamily: "Inter, -apple-system, BlinkMacSystemFont, sans-serif"
    fontSize: 16px
    fontWeight: 400
    lineHeight: 1.6
    letterSpacing: "0em"
  body:
    fontFamily: "Inter, -apple-system, BlinkMacSystemFont, sans-serif"
    fontSize: 15px
    fontWeight: 400
    lineHeight: 1.55
    letterSpacing: "0em"
  body-sm:
    fontFamily: "Inter, -apple-system, BlinkMacSystemFont, sans-serif"
    fontSize: 13px
    fontWeight: 400
    lineHeight: 1.5
    letterSpacing: "0em"
  overline:
    fontFamily: "Inter, -apple-system, BlinkMacSystemFont, sans-serif"
    fontSize: 11px
    fontWeight: 600
    lineHeight: 1.4
    letterSpacing: "0.08em"
  mono:
    fontFamily: "ui-monospace, SFMono-Regular, Menlo, monospace"
    fontSize: 13px
    fontWeight: 500
    lineHeight: 1.5
    letterSpacing: "0em"
spacing:
  xs: 4px
  sm: 8px
  md: 16px
  lg: 24px
  xl: 32px
  "2xl": 48px
  "3xl": 64px
rounded:
  none: 0px
  sm: 4px
  md: 8px
  lg: 12px
  xl: 16px
  full: 9999px
components:
  button-primary:
    backgroundColor: "{colors.primary}"
    textColor: "#ffffff"
    typography: "{typography.body-sm}"
    rounded: "{rounded.md}"
    padding: 14px
    height: 48px
  button-primary-hover:
    backgroundColor: "{colors.neutral-dark}"
    textColor: "{colors.tertiary}"
  button-secondary:
    backgroundColor: "{colors.neutral-light}"
    textColor: "{colors.primary}"
    typography: "{typography.body-sm}"
    rounded: "{rounded.md}"
    padding: 14px
    height: 48px
  button-secondary-hover:
    backgroundColor: "{colors.neutral}"
  card:
    backgroundColor: "{colors.neutral-light}"
    rounded: "{rounded.lg}"
    padding: "{spacing.lg}"
  badge:
    backgroundColor: "{colors.success-bg}"
    textColor: "{colors.accent}"
    typography: "{typography.overline}"
    rounded: "{rounded.sm}"
    padding: 4px
  badge-discount:
    backgroundColor: "{colors.error}"
    textColor: "{colors.neutral-light}"
    typography: "{typography.overline}"
    rounded: "{rounded.sm}"
    padding: 4px
  chip:
    backgroundColor: "{colors.neutral}"
    textColor: "{colors.secondary}"
    typography: "{typography.body-sm}"
    rounded: "{rounded.full}"
    padding: "6px 14px"
  section-heading:
    textColor: "{colors.primary}"
    typography: "{typography.h2}"
  section-heading-accent:
    textColor: "{colors.tertiary}"
    typography: "{typography.overline}"
  modal:
    backgroundColor: "{colors.neutral-light}"
    rounded: "{rounded.xl}"
    padding: "{spacing.xl}"
  nav-header:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.neutral-light}"
    typography: "{typography.overline}"
  sticky-bar:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.tertiary}"
    typography: "{typography.h3}"
  input:
    backgroundColor: "{colors.neutral-light}"
    textColor: "{colors.neutral-dark}"
    typography: "{typography.body}"
    rounded: "{rounded.md}"
    padding: 12px
  testi-card:
    backgroundColor: "{colors.neutral-light}"
    rounded: "{rounded.lg}"
    padding: "{spacing.lg}"
  feature-chip:
    backgroundColor: "{colors.gold-sft}"
    textColor: "{colors.primary}"
    typography: "{typography.body-sm}"
    rounded: "{rounded.full}"
    padding: "8px 16px"
---

## Overview

Manu Kaushal Publications is a chemistry textbook brand built for NEET and JEE aspirants across India. The visual identity must feel academically authoritative yet approachable, premium but accessible. The target audience is students aged 16–25 who are investing in their future through rigorous competitive exam preparation.

The design system uses **deep navy** as the anchor for trust and academic credibility, **gold/amber** as the accent that signals achievement and premium quality, **green** for positive outcomes and success cues, and **warm neutrals** for clarity and readability. Every token is chosen to reduce cognitive load on students who spend hours reading and studying from these materials.

## Colors

### Core Palette

- **Primary (#1a2332)** — Deep navy, the backbone of the brand. Used for headers, navigation, and primary actions. Conveys institutional trust and academic authority.
- **Secondary (#475569)** — Warm slate gray for supporting text, labels, and secondary UI elements. Provides hierarchy without competing with primary content.
- **Tertiary (#f59e0b)** — Warm amber/gold. Used for CTAs, highlights, star ratings, and achievement badges. Draws attention to the most important actions and signals premium value.
- **Accent (#047857)** — Rich emerald green. Reserved for success states, discount savings, growth indicators, and positive outcome messaging.
- **Neutral (#f8fafc)** — Warm off-white for page backgrounds. Softer than pure white to reduce eye strain during extended reading sessions.
- **Neutral-Light (#ffffff)** — Pure white for cards, hero sections, and elevated surfaces. Creates separation from the neutral page background.
- **Neutral-Mid (#e2e8f0)** — Light warm gray for borders, rules, dividers, and disabled states.
- **Neutral-Dark (#0f172a)** — Near-black for high-emphasis body text and the darkest backgrounds in the navy family.
- **Gold-Soft (#fef3c7)** — Light warm gold for feature-chip backgrounds and subtle highlights. Pairs with primary navy text for gentle emphasis.

### Semantic Colors

- **Success (#047857 / #ecfdf5)** — Positive feedback, saved amounts, enrollment confirmations.
- **Error (#b91c1c / #fef2f2)** — Urgency cues, sold-out warnings, validation errors.
- **Star (#f59e0b)** — Rating indicators, quality badges, achievement marks.

### Contrast & Accessibility

All text-color and background-color combinations used in components meet WCAG AA (4.5:1 minimum for normal text, 3:1 for large text). The gold (#f59e0b) is only used on dark navy (#1a2332) backgrounds for hover states where contrast exceeds 5:1, or as a decorative/accent element never carrying essential text on its own.

Note: `button-secondary` uses a white background (`neutral-light`) with navy text (`primary`) for its component defaults, ensuring 12.6:1 contrast ratio. The hover variant shifts to a soft neutral-gray fill that still maintains > 8:1 contrast with navy text.

## Typography

**Font family: Inter** — a clean, highly legible sans-serif designed for screen readability. Inter performs well at small sizes on mobile devices and maintains clarity across all weights. The system font stack (`-apple-system, BlinkMacSystemFont, sans-serif`) is included as a fallback for faster first paint.

### Scale

| Token | Size | Weight | Use |
|-------|------|--------|-----|
| h1 | 28px / 1.15 lh | 800 | Page hero titles, module section headers |
| h2 | 22px / 1.2 lh | 700 | Section titles, card headings |
| h3 | 18px / 1.3 lh | 700 | Subsection headers, feature titles |
| h4 | 15px / 1.4 lh | 600 | Card titles, list headers |
| body-lg | 16px / 1.6 lh | 400 | Long-form reading, testimonial text |
| body | 15px / 1.55 lh | 400 | Primary body copy, product descriptions |
| body-sm | 13px / 1.5 lh | 400 | Secondary details, helper text |
| overline | 11px / 1.4 lh | 600 | Labels, tags, category markers |
| mono | 13px / 1.5 lh | 500 | Chapter counts, statistics, codes |

### Readability Notes

- Line heights range from 1.4 to 1.6 to accommodate dense academic content on 320px–480px mobile screens.
- Negative letter-spacing on h1 (–0.02em) tightens display type without sacrificing legibility at large sizes.
- Overline text uses 0.08em letter-spacing for visual rhythm — common in editorial and premium education brands. Overline text is always rendered in uppercase (text-transform: uppercase in implementation).

## Layout

### Spacing Scale

The spacing system uses a 4px base unit, doubled progressively:

| Token | Value | Use |
|-------|-------|-----|
| xs | 4px | Icon gaps, tight padding |
| sm | 8px | Between related elements, chip spacing |
| md | 16px | Default section padding, card internal spacing |
| lg | 24px | Between distinct sections, image-to-text gaps |
| xl | 32px | Major section separation, form field groups |
| 2xl | 48px | Page-level breathing room |
| 3xl | 64px | Hero-to-content transitions |

### Mobile-First Structure

- Maximum content width: 480px (phone-first). On screens > 481px, content is centered with a subtle background wash and card-like appearance.
- Touch targets minimum 44px height for all interactive elements.
- Safe-area-inset is respected for the header on notched devices.
- Font size minimum 11px — never go below 13px for body text.

## Elevation & Depth

| Token | Value | Use |
|-------|-------|-----|
| flat | none | Inline elements, subtle cards |
| sm | 0 1px 2px rgba(0,0,0,0.05) | Product thumbnails, small badges |
| md | 0 2px 8px rgba(0,0,0,0.08) | Cards, hero product image, dropdowns |
| lg | 0 4px 16px rgba(0,0,0,0.1) | Sticky header, floating action bars |
| xl | 0 8px 24px rgba(0,0,0,0.12) | Modal overlays, confirmation dialogs |

Elevation shadows use neutral-black with low opacity to stay neutral across all background contexts. Shadow strength increases proportionally with the visual weight of the component.

## Shapes

| Token | Value | Use |
|-------|-------|-----|
| none | 0px | Sharp corners for data-heavy elements |
| sm | 4px | Badges, discount pills |
| md | 8px | Brand mark, buttons, inputs |
| lg | 12px | Product image containers, cards |
| xl | 16px | Modals, desktop page frame |
| full | 9999px | Chips, rounded avatars, pill tags |

The rounding scale moves from practical (sm/md) for functional elements to decorative (xl) for surfaces. Full rounding is reserved for pill-shaped chips and tags that should feel friendly and scannable.

## Components

### button-primary

The highest-emphasis action on any screen — "Buy on Amazon", "Enroll Now", "Download Sample". Uses full navy with white text for maximum contrast (ratio > 8:1). Hover state inverts to near-black background with gold text. Typography is `body-sm` at weight 700 (set in the design system's typography scale). Height is 48px.

```css
background: #1a2332;
color: #ffffff;
font: 700 13px / 1.5 Inter, sans-serif;
padding: 14px 24px;
height: 48px;
border-radius: 8px;
```

### button-primary-hover

Hover variant of button-primary — near-black background with gold text for strong visual feedback.

```css
background: #0f172a;
color: #f59e0b;
```

### button-secondary

Secondary actions — "View Syllabus", "Read More". Outline style with white fill and navy border. Uses `body-sm` typography at weight 600. Height is 48px.

```css
background: #ffffff;
color: #1a2332;
font: 600 13px / 1.5 Inter, sans-serif;
padding: 14px 24px;
height: 48px;
border: 2px solid #e2e8f0;
border-radius: 8px;
```

### button-secondary-hover

Hover state — fills with soft neutral background (#f8fafc) and shifts border to primary navy for clear feedback.

```css
background: #f8fafc;
```

### card

Content containers for testimonials, feature lists, and module summaries. White fill with subtle border and soft shadow. Padding uses the `lg` spacing token (24px). Keeps dense academic content scannable.

```css
background: #ffffff;
border-radius: 12px;
padding: 24px;
border: 1px solid #e2e8f0;
box-shadow: 0 2px 8px rgba(0,0,0,0.08);
```

### badge

Inline status indicators — "Bestseller", "New Edition", "NCERT-based". Uses success-bg background with accent green text. Typography is `overline` (uppercase in implementation). Padding is 4px 8px.

```css
background: #ecfdf5;
color: #047857;
font: 700 11px / 1.4 Inter, sans-serif;
padding: 4px 8px;
border-radius: 4px;
text-transform: uppercase;
letter-spacing: 0.08em;
```

### badge-discount

High-urgency discount display — "53% OFF", "Save ₹2,110". Red background with white text for maximum attention. Used sparingly on product hero only.

```css
background: #b91c1c;
color: #ffffff;
font: 800 11px / 1.4 Inter, sans-serif;
padding: 4px 10px;
border-radius: 4px;
text-transform: uppercase;
```

### chip

Pill-shaped tags for subjects, modules, and quick-filter categories. Rounded-full for a friendly, scannable feel. Uses `body-sm` typography.

```css
background: #f8fafc;
color: #475569;
font: 500 13px / 1.5 Inter, sans-serif;
padding: 6px 14px;
border: 1px solid #e2e8f0;
border-radius: 9999px;
```

### section-heading

Standard H2 for page sections — "Why Students Trust Us", "What's Inside". Uses the `h2` typography token. Margin-bottom is 8px in implementation.

```css
color: #1a2332;
font: 700 22px / 1.2 Inter, sans-serif;
margin-bottom: 8px;
```

### section-heading-accent

Introductory eyebrow text above section headings — "Proven Results", "Trusted by 50,000+ Students". Uses the `overline` typography token (uppercase in implementation). Margin-bottom is 4px.

```css
color: #f59e0b;
font: 700 11px / 1.4 Inter, sans-serif;
margin-bottom: 4px;
text-transform: uppercase;
letter-spacing: 0.08em;
```

### modal

Overlay dialogs for purchase confirmations, sample chapter previews, or enrollment flows. Centered card with backdrop overlay. High elevation ensures focus. Padding uses the `xl` spacing token (32px).

```css
background: #ffffff;
border-radius: 16px;
padding: 32px;
box-shadow: 0 8px 24px rgba(0,0,0,0.12);
overlay: rgba(0,0,0,0.5);
```

### nav-header

Sticky top navigation — brand identity, page title, primary nav links. Navy background with gold brand mark creates immediate recognition. Uses `overline` typography (uppercase). Safe-area-inset padding for notched devices.

```css
background: #1a2332;
color: #ffffff;
font: 600 11px / 1.4 Inter, sans-serif;
padding: calc(14px + env(safe-area-inset-top, 0px)) 18px 14px;
box-shadow: 0 4px 16px rgba(0,0,0,0.1);
z-index: 50;
```

### sticky-bar

Bottom or top sticky CTA bar — persistent purchase link for long-scrolling pages. Navy background with gold text. Uses `h3` typography. Gold top border (2px) creates urgency and permanence.

```css
background: #1a2332;
color: #f59e0b;
font: 800 18px / 1.3 Inter, sans-serif;
padding: 12px 18px;
border-top: 2px solid #f59e0b;
box-shadow: 0 4px 16px rgba(0,0,0,0.1);
```

### input

Form fields for email capture, phone numbers, or search. Uses `body` typography. Focus state adds gold border (2px) with a subtle gold glow ring (3px spread at 15% opacity) for clear keyboard navigation visibility.

```css
background: #ffffff;
color: #0f172a;
font: 400 15px / 1.55 Inter, sans-serif;
padding: 12px 14px;
border: 1px solid #e2e8f0;
border-radius: 8px;
/* focus state: */
border: 2px solid #f59e0b;
box-shadow: 0 0 0 3px rgba(245, 158, 11, 0.15);
```

### testi-card

Testimonial containers for student success stories and reviews. White card with soft shadow and left-border accent in gold to highlight credibility. Padding uses the `lg` spacing token (24px).

```css
background: #ffffff;
border-radius: 12px;
padding: 24px;
box-shadow: 0 1px 2px rgba(0,0,0,0.05);
border: 1px solid #e2e8f0;
border-left: 3px solid #f59e0b;
```

### feature-chip

Highlighted feature callouts within feature lists — "NCERT-based", "Video Lectures", "24/7 Doubt Support". Gold-soft (#fef3c7) background with primary navy text for visual emphasis without overwhelming.

```css
background: #fef3c7;
color: #1a2332;
font: 600 13px / 1.5 Inter, sans-serif;
padding: 8px 16px;
border-radius: 9999px;
```

## Do's and Don'ts

### Do

- Use navy as the dominant background for headers and the dark hero section to establish authority.
- Reserve gold exclusively for CTAs, badges, and emphasis — never scatter it as decoration.
- Keep body text on neutral or white backgrounds — never on navy (reserve navy backgrounds for white text).
- Use the 4px spacing grid consistently — avoid ad-hoc spacing values like 13px or 21px.
- Maintain a clear visual hierarchy: overline → h2 → body → body-sm.
- Use feature chips sparingly — 2–4 per section maximum to avoid visual noise.

### Don't

- Don't place gold text on white backgrounds at small sizes — contrast drops below WCAG AA for body-sm and overline.
- Don't mix rounded values — always pull from the spacing/rounded scale tokens.
- Don't use pure black (#000000) — use neutral-dark (#0f172a) for dark text to maintain warmth.
- Don't stack more than two elevations in a single component group (e.g., card + shadow + border creates visual confusion).
- Don't use accent green for CTAs — reserve for success states and savings messaging.
- Don't deviate from Inter without a performance-critical reason — the font loads fast and is optimized for mobile screens.
- Don't exceed 480px content width on mobile — the single-column layout is intentional for focused reading.
