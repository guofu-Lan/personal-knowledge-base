---
name: Grade 5 Chinese Learning Workbench
description: Original language learning through a bright, hands-on mechanical exhibit.
colors:
  primary: "#2058D6"
  primary-deep: "#173D9D"
  progress-blue: "#E4EDFF"
  signal-red: "#C53B2C"
  citrus-yellow: "#F5C544"
  workshop-mint: "#178363"
  notice-border: "#E1AA48"
  notice-paper: "#FFF3D4"
  notice-ink: "#4A3210"
  paper: "#F5F8FC"
  surface: "#FFFFFF"
  ink: "#17243B"
  muted-ink: "#52657E"
  rule: "#CBD6E3"
  exhibit-blue: "#E6EFFC"
typography:
  micro:
    fontSize: "10px"
  caption:
    fontSize: "11px"
  helper:
    fontSize: "13px"
  body-compact:
    fontSize: "14px"
  display:
    fontFamily: '"Segoe UI", "Microsoft YaHei", "PingFang SC", sans-serif'
    fontSize: "clamp(29px, 3vw, 43px)"
    fontWeight: 700
    lineHeight: 1.1
    letterSpacing: "-0.045em"
  headline:
    fontFamily: '"Segoe UI", "Microsoft YaHei", "PingFang SC", sans-serif'
    fontSize: "clamp(25px, 2.6vw, 34px)"
    fontWeight: 700
    lineHeight: 1.18
    letterSpacing: "-0.04em"
  title:
    fontFamily: '"Segoe UI", "Microsoft YaHei", "PingFang SC", sans-serif'
    fontSize: "22px"
    fontWeight: 700
    lineHeight: 1.3
    letterSpacing: "-0.03em"
  body:
    fontFamily: '"Segoe UI", "Microsoft YaHei", "PingFang SC", sans-serif'
    fontSize: "15px"
    fontWeight: 400
    lineHeight: 1.75
  body-default:
    fontSize: "16px"
    fontWeight: 400
    lineHeight: 1.55
  brand:
    fontSize: "19px"
    fontWeight: 700
    lineHeight: 1.2
  section-mobile:
    fontSize: "20px"
    fontWeight: 700
    lineHeight: 1.3
  section-compact:
    fontSize: "21px"
    fontWeight: 700
    lineHeight: 1.3
  headline-mobile:
    fontSize: "27px"
    fontWeight: 700
    lineHeight: 1.18
    letterSpacing: "-0.04em"
  display-mobile:
    fontSize: "31px"
    fontWeight: 700
    lineHeight: 1.1
    letterSpacing: "-0.045em"
  label:
    fontFamily: '"Segoe UI", "Microsoft YaHei", "PingFang SC", sans-serif'
    fontSize: "12px"
    fontWeight: 750
    lineHeight: 1.35
rounded:
  marker: "3px"
  tag: "7px"
  sm: "11px"
  md: "12px"
  lg: "15px"
  xl: "22px"
  panel: "20px"
  exhibit: "28px"
  pill: "999px"
  circle: "50%"
spacing:
  sm: "8px"
  md: "16px"
  lg: "24px"
  xl: "32px"
components:
  button-primary:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.surface}"
    rounded: "{rounded.md}"
    padding: "10px 15px"
    height: "44px"
  button-primary-hover:
    backgroundColor: "{colors.primary-deep}"
  button-secondary:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.ink}"
    rounded: "{rounded.md}"
    padding: "10px 15px"
    height: "44px"
  unit-button-active:
    backgroundColor: "{colors.progress-blue}"
    textColor: "{colors.ink}"
    rounded: "0"
    padding: "14px 16px"
---

# Design System: Grade 5 Chinese Learning Workbench

## Overview

**Creative North Star: "The Language Machine Workshop"**

This visual system makes learning feel like operating a friendly exhibit: a learner turns a lever, watches a small idea move through observation and thought, and tries a piece of language themselves. Rounded mechanical forms, enamel-like colors, and crisp work surfaces keep that process tangible without borrowing textbook artwork.

The interface stays bright and calm enough for reading in a home or classroom, while the cobalt machine, moving gears, and vermilion controls make interaction easy to spot. Chinese system-font fallbacks keep the lesson text dependable across common devices.

**Key Characteristics:**
- Language learning is shown as a visible, manipulable mechanism.
- Cobalt carries primary actions; warm signal colors mark distinct activity parts.
- Lesson text remains on clear, high-contrast surfaces.
- Responsive layouts preserve the machine and move the lesson beneath it on narrow screens.

## Colors

The palette pairs a dependable blue structure with a few bright enamel signals against cool white work surfaces.

### Primary
- **Workshop Cobalt**: The main action color and the large base of the language machine.
- **Deep Workshop Blue**: The machine frame and high-contrast practice surface; white text stays prominent on it.

### Secondary
- **Progress Blue**: A low-intensity field for the selected unit and completion chip.
- **Signal Vermilion**: A small mechanical accent for the lever and details that deserve attention.
- **Citrus Yellow**: A bright indicator for notice and confirmation states.
- **Notice Amber**: A warm outline and pale surface that distinguish the one-time school reminder; its deep brown text stays legible.

### Tertiary
- **Workshop Mint**: A supporting color for the discovery illustration and positive state accents.

### Neutral
- **Cool Paper**: The page background, chosen to keep the surface bright without making it look like textbook paper.
- **Clean Surface**: Lesson and task panels.
- **Ink Navy**: Primary copy and headings.
- **Muted Blue-Gray**: Secondary copy and supporting labels.
- **Rule Blue-Gray**: Fine dividers and panel boundaries.
- **Exhibit Blue**: The colored field behind the illustrated language machine.

### Named Rules
**The Enamel Signal Rule.** Use vivid red, yellow, and mint as deliberate mechanism cues, not as body-copy colors or blanket decoration.

## Typography

**Display Font:** Segoe UI (with Microsoft YaHei, PingFang SC, and generic sans-serif fallbacks)

**Body Font:** The same system stack, for reliable Chinese text rendering
**Label/Mono Font:** No separate label face; labels use the same sans-serif system stack.

**Character:** Compact, confident headings give the lesson a clear entry point; open body leading makes Chinese copy comfortable to follow. The interface uses weight and size, not decorative typefaces, to create hierarchy.

### Hierarchy
- **Display** (700, `clamp(29px, 3vw, 43px)`, 1.1): The machine's central invitation.
- **Headline** (700, `clamp(25px, 2.6vw, 34px)`, 1.18): Active lesson titles.
- **Title** (700, 22px, 1.3): Section headings for units and tasks.
- **Body** (400, 15px, 1.75): Original explanations and instructions.
- **Label** (750, 12px, 1.35): Step names, unit markers, and status text.
- **Supporting sizes** (10–16px): Small labels (10–12px), helper copy (13px), compact explanations (14px), and the 16px browser-scale body.
- **Shell and mobile headings** (19–31px): Brand title (19px), compact section titles (20–21px), and narrow-screen headings (27px and 31px).

### Named Rules
**The Read-It-First Rule.** Keep Chinese body text on a quiet, high-contrast surface; reserve saturated color for controls and the mechanical illustration.

## Layout

The wide workbench uses a split stage: the machine and its controls take just over half of the width, with the current lesson alongside. The main content is capped at 1440px with generous page margins. Unit navigation uses a four-column ruled drawer; practice and daily tasks sit side by side.

At 980px, the workbench stacks and the unit drawer becomes two columns. At 600px, the page tightens its gutters, stacks lesson and practice content, and lets the weekly plan scroll horizontally rather than squeezing each day into unreadable columns.

## Elevation & Depth

The exhibit uses mostly flat, outlined surfaces. One offset, softly blurred shadow lifts the complete workbench from the page; borders, tonal fields, and the machine's overlapping parts carry the rest of the depth.

### Shadow Vocabulary
- **Workbench lift** (`0 9px 22px rgb(23 36 59 / 12%)`): Use only for the complete interactive stage.

### Named Rules
**The One-Lift Rule.** Keep ordinary lesson, unit, practice, and daily-task surfaces flat; reserve the raised shadow for the principal workbench.

## Shapes

The signature frame is a large, rounded machine bench. Lesson and practice surfaces use progressively smaller rounded corners; unit drawers use crisp separators instead of separate card shells. Controls have a tactile rounded rectangle silhouette and a small offset shadow on the primary action.

## Components

### Buttons
- **Shape:** Tactile rounded rectangles (12px; compact stage controls use 11px).
- **Primary:** Workshop Cobalt with white text, 10px 15px padding, and a 44px minimum height; hover shifts to Deep Workshop Blue.
- **Hover / Focus:** A small upward movement on hover, a clear dark focus outline, and a pressed-down active state.
- **Secondary:** White surface with a blue-gray outline and dark copy; disabled lesson navigation uses a pale fill and muted text.
- **Stage controls:** Three compact controls name the lesson's current stage; the active stage fills with cobalt.

### Chips
- **Style:** Edition/context labels are outlined white pills; progress uses a pale-blue pill with a cobalt marker.
- **State:** The selected unit is distinguished by a pale-blue drawer surface and a filled number marker.

### Cards / Containers
- **Corner Style:** Workbench 28px; unit and practice regions 15–20px; lesson script 15px.
- **Background:** White lesson surfaces and practice/daily panels; cool paper for the page; exhibit blue for the machine side.
- **Shadow Strategy:** Only the principal workbench receives a shadow.
- **Border:** Fine blue-gray outlines define important boundaries and separators.
- **Internal Padding:** 14–32px, reduced at the narrow breakpoint.

### Inputs / Fields
- **Style:** Daily task checkboxes use the browser's native checkbox with the cobalt accent.
- **Focus:** All interactive controls use a visible dark outline with offset.
- **State:** Checked tasks mute and strike through their label; local progress remains in the current browser.

### Navigation
- **Style:** The eight-unit drawer is a ruled, four-column surface on wide screens and a two-column surface below 980px.
- **State:** Active unit has a pale-blue background; each stage and lesson button exposes its current state to assistive technology.
- **Mobile:** Lesson content stacks below the machine; the unit drawer stays two columns and the weekly plan scrolls horizontally.

### Signature Component: Language Machine

An original inline SVG exhibit combines observation and discovery windows with meshing gears and a lever. Stage buttons change the current lesson step and rotate the lever; the explanatory text and quiz remain linked to the active lesson.

## Do's and Don'ts

### Do:
- **Do** keep Chinese explanations on uncluttered light surfaces and use concise, concrete examples.
- **Do** make the current unit, micro-lesson, and learning stage easy to identify.
- **Do** keep the Hunan school context separate from the unified textbook edition label.
- **Do** label temporary school notices with their specific date and one-time status.
- **Do** use original inline artwork and motion for lessons without verified video permissions.

### Don't:
- **Don't** use textbook passages, third-party lesson plans, illustrations, or video in the sample.
- **Don't** present the one-time November 16, 2026 research schedule as a recurring timetable.
- **Don't** assign saturated accent colors to long Chinese paragraphs.
- **Don't** add unrelated shadows or turn every content group into an individual card.
