---
name: Tsubaki
description: Serene anime-inspired Discord community guardian with gentle pastel aesthetics and paper-soft minimal craft inspired by MIMI
colors:
  primary: "#f48c9f"
  primary-hover: "#eb7389"
  primary-subtle: "#fdf0f2"
  secondary: "#93b5e1"
  secondary-subtle: "#eef4fb"
  tertiary: "#f6cf7d"
  tertiary-subtle: "#fdf8ee"
  neutral-bg: "#fbf8f3"
  neutral-surface: "#ffffff"
  neutral-card: "#f6f2ea"
  neutral-text: "#2b2f38"
  neutral-muted: "#7c8290"
  neutral-border: "#e7e2d8"
typography:
  display:
    fontFamily: "Plus Jakarta Sans, 'Zen Maru Gothic', 'M PLUS Rounded 1c', sans-serif"
    fontSize: "clamp(2.25rem, 5vw, 3.75rem)"
    fontWeight: 700
    lineHeight: 1.15
    letterSpacing: "-0.02em"
  headline:
    fontFamily: "Plus Jakarta Sans, 'Zen Maru Gothic', sans-serif"
    fontSize: "clamp(1.75rem, 3.5vw, 2.5rem)"
    fontWeight: 600
    lineHeight: 1.25
    letterSpacing: "-0.01em"
  title:
    fontFamily: "Plus Jakarta Sans, sans-serif"
    fontSize: "1.25rem"
    fontWeight: 600
    lineHeight: 1.4
    letterSpacing: "normal"
  body:
    fontFamily: "Plus Jakarta Sans, system-ui, sans-serif"
    fontSize: "1rem"
    fontWeight: 400
    lineHeight: 1.65
    letterSpacing: "normal"
  label:
    fontFamily: "JetBrains Mono, 'Space Mono', monospace"
    fontSize: "0.8125rem"
    fontWeight: 500
    lineHeight: 1.4
    letterSpacing: "0.03em"
rounded:
  sm: "6px"
  md: "12px"
  lg: "18px"
  full: "9999px"
spacing:
  xs: "4px"
  sm: "8px"
  md: "16px"
  lg: "24px"
  xl: "40px"
  "2xl": "64px"
components:
  button-primary:
    backgroundColor: "{colors.primary}"
    textColor: "#ffffff"
    rounded: "{rounded.md}"
    padding: "12px 24px"
  button-primary-hover:
    backgroundColor: "{colors.primary-hover}"
  button-secondary:
    backgroundColor: "{colors.neutral-surface}"
    textColor: "{colors.neutral-text}"
    rounded: "{rounded.md}"
    padding: "12px 24px"
  badge-pill:
    backgroundColor: "{colors.primary-subtle}"
    textColor: "{colors.primary}"
    rounded: "{rounded.full}"
    padding: "4px 12px"
  card-surface:
    backgroundColor: "{colors.neutral-surface}"
    rounded: "{rounded.lg}"
    padding: "24px"
---

# Design System: Tsubaki

## Overview

**Creative North Star: "The Nostalgic Piano Garden (MIMI Soundscape)"**

Tsubaki's visual identity draws inspiration from the gentle, melancholic yet comforting musical universe of vocaloid producer MIMI. Rather than framing server security as a high-alert military war-room or an aggressive neon cyberpunk firewall, Tsubaki embodies a quiet, caring sanctuary. Security is reimagined as an unobtrusive guardian watching over a sunlit afternoon tea room—alert, precise, but radiating quiet reassurance.

The visual atmosphere trades harsh obsidian darkness and high-contrast alert strobes for tactile paper-soft minimalism, watercolor-tinted pastels, and generous negative space. Every surface evokes the stillness of sheet music laid beside an open window: cream-toned canvas, delicate hairline borders, soft ink typography, and organic camellia blossom petals that punctuate key interactive moments with warmth.

**Key Characteristics:**
- **Paper Canvas Warmth:** Uncoated, tactile ivory background (`#fbf8f3`) replacing cold terminal black.
- **Watercolor Pastel Accents:** Muted camellia rose (`#f48c9f`), sky periwinkle (`#93b5e1`), and warm piano honey (`#f6cf7d`).
- **Quiet Minimal Stacking:** Flat tonal layering and 1px hairline dividers in place of heavy drop shadows or harsh neon glows.
- **Gentle Anime Soul:** Softly rounded geometry, Japanese kaomoji touches, and comforting micro-interactions that feel like handwritten notes.

## Colors

The palette feels like a sun-faded watercolor illustration: warm paper canvas, deep soft charcoal ink for high readability, and delicate pastel washes that bring life and clarity without digital fatigue.

### Primary
- **Soft Camellia Blossom** (`#f48c9f`): The signature heart of Tsubaki. Used for primary CTAs, active status indicators, and focal hero typography. Represents gentle vigilance.
- **Camellia Hover Blush** (`#eb7389`): Deepened rose tone for interactive button hover and focused click states.
- **Blossom Wash** (`#fdf0f2`): Ultra-soft pastel tint used for pill tag backgrounds, active menu item highlights, and alert containers.

### Secondary
- **Nostalgic Sky Blue** (`#93b5e1`): Secondary accent representing cloud connectivity (Turso libSQL synchronization, safe URLs, technical telemetry).
- **Sky Wash** (`#eef4fb`): Gentle periwinkle background wash for database sync badges and external resource pills.

### Tertiary
- **Warm Piano Honey** (`#f6cf7d`): Whimsical gold accent representing the Groq-powered anime companion dialogue, mascot tips, and warm community highlights.
- **Honey Wash** (`#fdf8ee`): Soft warm background for companion quotes, mascot tips, and gentle advisory notices.

### Neutral
- **Paper Canvas** (`#fbf8f3`): The warm off-white foundational canvas for pages and background layouts. Soft on the eyes, tactile, and calm.
- **Pure Soft Surface** (`#ffffff`): Elevated card and modal surface providing crisp contrast against the paper canvas.
- **Muted Paper Layer** (`#f6f2ea`): Secondary container background for code blocks, terminal mockups, and nested list items.
- **Gentle Ink Charcoal** (`#2b2f38`): Primary text color. Soft on the eyes while exceeding WCAG AAA contrast against paper surfaces.
- **Soft Pencil Dust** (`#7c8290`): Secondary descriptive text, metadata captions, and inactive tab labels.
- **Faint Paper Fold** (`#e7e2d8`): Hairline boundary lines, card borders, and subtle table rules.

### Named Rules
**The Watercolor Restraint Rule.** Pastel accents are applied as light washes and deliberate punctuation, never exceeding 15% of the viewport. The paper canvas must always dominate so the reading experience remains peaceful.

**The Ink Harmony Rule.** Never use pure digital black (`#000000`). Deep charcoal ink (`#2b2f38`) preserves the printed illustrated feel and prevents optical harshness.

## Typography

Typography pairs modern geometric clarity with the friendly cadence of Japanese rounded editorial fonts.

**Display Font:** Plus Jakarta Sans (with 'Zen Maru Gothic', 'M PLUS Rounded 1c', sans-serif fallbacks)  
**Body Font:** Plus Jakarta Sans (with system-ui, -apple-system, sans-serif fallbacks)  
**Label/Mono Font:** JetBrains Mono (with 'Space Mono', ui-monospace, monospace fallbacks)

**Character:** Calm, lyrical, and legible. Headlines feel like book chapter titles; code snippets feel like neatly handwritten margin notes.

### Hierarchy
- **Display** (Bold 700, `clamp(2.25rem, 5vw, 3.75rem)`, line-height 1.15, letter-spacing -0.02em): Hero headlines and emotional narrative declarations.
- **Headline** (SemiBold 600, `clamp(1.75rem, 3.5vw, 2.5rem)`, line-height 1.25, letter-spacing -0.01em): Section titles, bento grid major headers.
- **Title** (SemiBold 600, `1.25rem` / 20px, line-height 1.4): Card titles, feature headlines, modal titles.
- **Body** (Regular 400, `1rem` / 16px, line-height 1.65, max line length 68ch): Explanatory paragraphs, feature descriptions, and documentation prose.
- **Label** (Medium 500, `0.8125rem` / 13px, letter-spacing 0.03em, mono): Command syntax, technical latency values, badge pills, and tab headers.

### Named Rules
**The Melodic Rhythm Rule.** Headlines prioritize soft letter-spacing, generous line heights, and comfortable reading pacing. Never squeeze or uppercase entire sentences; let the type breathe like musical phrasing.

## Layout

The spatial model uses an airy, human-scale grid structured around standard 8px increments.

- **Container Model:** Max content width of 1200px (`max-w-7xl` with generous padding), centered with dynamic gutter spacing (16px mobile, 32px tablet, 48px desktop).
- **Rhythm & Density:** Generous section spacing (`py-20` to `py-28`), giving each concept room to settle before the next section begins.
- **Asymmetric Bento Grids:** Feature showcases use varied proportions (2:1 and 1:2 card splits) mimicking editorial magazine spreads.

### Named Rules
**The Paper Margin Rule.** Content must never touch card borders or screen edges. Generous internal padding (24px to 32px on cards, 64px+ between sections) preserves the serene, unhurried reading atmosphere.

## Elevation & Depth

This system is flat-by-default, relying on tonal layering and crisp paper borders rather than dramatic drop shadows.

- **Primary Depth Strategy:** Visual hierarchy is achieved through tone-on-tone paper stepping (`#fbf8f3` canvas → `#ffffff` card surface → `#f6f2ea` inset well) bordered by a 1px hairline stroke (`#e7e2d8`).
- **Ambient Paper Glow:** For focal hover states, a barely perceptible warm diffuse ambient haze (`0 4px 20px rgba(244, 140, 159, 0.12)`) suggests light reflecting off watercolor paper.

### Named Rules
**The Flat-by-Paper Rule.** Surfaces rest flush on the page canvas. Shadows never exceed 20px blur or 15% opacity, and black directional drop shadows are strictly forbidden.

## Shapes

Shapes reflect organic, friendly geometry with soft curves that feel approachable and hand-crafted.

- **Corner Radius Strategy:**
  - Micro elements & buttons: 12px (`rounded-xl` / `rounded.md`).
  - Cards & container frames: 18px (`rounded-2xl` / `rounded.lg`).
  - Tags, badges & pill buttons: 9999px (`rounded-full`).
- **Border Treatment:** Hairline 1px solid borders in `#e7e2d8` on cards and containers. Never thick 2px+ borders unless used as a gentle pastel accent badge.

## Components

### Buttons
- **Shape:** Gentle rounded rectangle (12px radius).
- **Primary:** Soft Camellia Blossom background (`#f48c9f`), crisp white text (`#ffffff`), padding `12px 24px`, subtle 1px border (`#eb7389`). Hover shifts to `#eb7389` with a subtle 1px upward translation.
- **Secondary:** Pure soft surface (`#ffffff`), charcoal ink text (`#2b2f38`), hairline border (`#e7e2d8`), padding `12px 24px`. Hover deepens border to `#d5cfc3` with subtle background tint `#f6f2ea`.
- **Ghost:** Transparent background, charcoal text (`#2b2f38`), padding `8px 16px`. Hover introduces a light `#fdf0f2` blush.

### Chips & Badges
- **Shape:** Full pill shape (9999px radius).
- **Style:** Light pastel wash background (`#fdf0f2` for rose, `#eef4fb` for sky, `#fdf8ee` for honey), matched tinted border, font-mono label (`12px`), padding `4px 12px`.
- **State:** Active pills feature a solid 6px pastel dot before the text label.

### Cards & Containers
- **Corner Style:** Soft 18px radius (`rounded-2xl`).
- **Background:** Pure soft surface (`#ffffff`) resting over the `#fbf8f3` paper canvas.
- **Border:** 1px hairline rule in `#e7e2d8`.
- **Internal Padding:** 24px on mobile, 32px on desktop.
- **Hover:** Hairline border subtly warms to `#f48c9f` with a soft diffuse watercolor blush.

### Inputs & Textareas
- **Style:** Inset paper well background (`#f6f2ea`), 1px border (`#e7e2d8`), 12px corner radius, charcoal text (`#2b2f38`), placeholder in `#7c8290`.
- **Focus:** Border transitions to Soft Camellia Blossom (`#f48c9f`) with a soft 2px outer aura (`rgba(244, 140, 159, 0.2)`).

### Navigation
- **Style:** Sticky header with frosted paper backdrop blur (`rgba(251, 248, 243, 0.85)` + `backdrop-filter: blur(12px)`), hairline bottom border (`#e7e2d8`).
- **Brand Item:** Subtle camellia icon mark paired with quiet charcoal branding and a gentle "椿" pastel badge.
- **Links:** Charcoal ink (`#2b2f38`), hovering to Camellia Blossom (`#f48c9f`) with a light blush pill hover state.

### Discord Forensic Preview Card
- **Style:** Reimagined Discord embed styled as an archival index card: soft white container (`#ffffff`), pastel rose left accent ribbon (4px wide `#f48c9f`), gentle typography, unclickable safe code block in `#f6f2ea` with ink syntax.

## Do's and Don'ts

### Do:
- **Do** use the warm paper canvas (`#fbf8f3`) as the global foundation for page layouts.
- **Do** frame security and auto-moderation as a serene, caring guardian protecting community peace.
- **Do** pair pastel washes (`#fdf0f2`, `#eef4fb`, `#fdf8ee`) with rich ink charcoal (`#2b2f38`) to ensure effortless readability.
- **Do** keep cards and elevation flat, separating surfaces with hairline borders (`#e7e2d8`) and subtle background stepping.
- **Do** use generous white space and comfortable line heights to let visitors breathe.

### Don't:
- **Don't** use pure digital black (`#000000`) or heavy dark obsidian backgrounds.
- **Don't** use neon laser glow effects, pulsing high-intensity drop shadows, or aggressive cyberpunk grids.
- **Don't** use harsh saturated red warning banners; use gentle rose pastel washes (`#fdf0f2` with `#f48c9f` borders) for security alerts.
- **Don't** crowd components together; claustrophobic density breaks the MIMI-inspired calm pacing.
