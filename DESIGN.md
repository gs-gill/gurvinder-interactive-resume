---
name: Gurvinder Gill Portfolio
description: An engineering journal in warm paper, serif display type, and cobalt rules.
colors:
  paper: "#f5f0e7"
  paper-light: "#faf7f0"
  charcoal-ink: "#242422"
  muted-ink: "#5d5b57"
  journal-blue: "#263fa0"
  journal-blue-deep: "#1d317d"
  strong-rule: "#aaa59b"
  soft-rule: "#cdc8be"
  selection-blue: "#c4cffb"
  contact-copy: "#f0f1ff"
  contact-rule: "#aeb9e2"
  contact-label: "#d8dff9"
typography:
  display:
    fontFamily: "DM Serif Display, Georgia, serif"
    fontSize: "clamp(53px, 6vw, 90px)"
    fontWeight: 400
    lineHeight: 1.02
    letterSpacing: "-0.025em"
  headline:
    fontFamily: "DM Serif Display, Georgia, serif"
    fontSize: "clamp(42px, 4.5vw, 68px)"
    fontWeight: 400
    lineHeight: 1.08
    letterSpacing: "-0.025em"
  title:
    fontFamily: "DM Serif Display, Georgia, serif"
    fontSize: "clamp(24px, 2.4vw, 33px)"
    fontWeight: 400
    lineHeight: 1.1
  body:
    fontFamily: "DM Sans, Segoe UI, sans-serif"
    fontSize: "16px"
    fontWeight: 400
    lineHeight: 1.55
  label:
    fontFamily: "DM Sans, Segoe UI, sans-serif"
    fontSize: "14px"
    fontWeight: 700
  annotation:
    fontFamily: "Caveat, cursive"
    fontSize: "23px"
    fontWeight: 500
    lineHeight: 1.05
spacing:
  small-gutter: "18px"
  mobile-gutter: "22px"
  desktop-gutter: "42px"
  chapter-gap: "44px"
components:
  button-primary:
    backgroundColor: "{colors.journal-blue}"
    textColor: "#ffffff"
    typography: "{typography.body}"
    rounded: "0px"
    padding: "10px 17px"
    height: "48px"
  button-outline:
    backgroundColor: "transparent"
    textColor: "{colors.journal-blue}"
    typography: "{typography.body}"
    rounded: "0px"
    padding: "8px 16px"
    height: "44px"
  technology-ribbon:
    backgroundColor: "{colors.paper}"
    textColor: "{colors.charcoal-ink}"
    padding: "14px 42px"
  chapter-row:
    backgroundColor: "{colors.paper}"
    textColor: "{colors.charcoal-ink}"
    padding: "22px 0"
---

# Design System: Gurvinder Gill Portfolio

## Overview

**Creative North Star: "The Engineering Journal"**

The portfolio reads like an edited record of production work: numbered chapters, generous serif headlines, precise sans-serif details, and blue rules that organize the page. The warm paper field keeps a long work history approachable. Emphasis comes from type, lines, and proportion.

The professional account is direct and evidence-led. `park.html` is an optional interactive companion with its own visual language; its styling does not set the main portfolio system.

**Key Characteristics:**

- A subtle locally generated paper texture, near-black ink, and cobalt blue rules.
- A full-width masthead and technology ribbon followed by asymmetric editorial chapters.
- Local DM Serif Display for statements, DM Sans for detail, and Caveat for handwritten annotations.
- Flat sections separated by thin rules, with a solid blue contact close.

## Colors

The palette resembles printed paper marked with blue editorial ink. The frontmatter values are normative.

### Primary

- **Journal Blue** (`journal-blue`): Chapter numbers, links, key dividers, the solid action, and the contact field.
- **Deep Journal Blue** (`journal-blue-deep`): Primary action hover.

### Neutral

- **Paper** (`paper`): Default page background.
- **Light Paper** (`paper-light`): Skip-link text and lighter surface reference.
- **Charcoal Ink** (`charcoal-ink`): Main text and strong borders.
- **Muted Ink** (`muted-ink`): Dates and secondary context.
- **Strong Rule** (`strong-rule`): Structural dividers.
- **Soft Rule** (`soft-rule`): Repeated row dividers.
- **Selection Blue** (`selection-blue`): Selected text background.
- **Contact Copy**, **Contact Rule**, and **Contact Label**: Light values used on the blue contact field.

**The Blue Rule.** Use cobalt for navigation, chapter indexing, key rules, and actions. Let paper and charcoal carry the long-form reading experience.

## Typography

**Display Font:** Local DM Serif Display, with Georgia and serif fallbacks.

**Body Font:** Local DM Sans, with Segoe UI and sans-serif fallbacks.

**Annotation Font:** Local Caveat for marginalia and the technology ribbon introduction. These notes are supporting explanation, never the sole source of a fact or action.

**Character:** Serif gives chapters a human editorial voice. Sans-serif keeps technologies, dates, actions, and detailed explanations crisp. Sparse handwritten marks add the annotated journal feel of the selected reference.

### Hierarchy

- **Display:** Regular serif, `clamp(53px, 6vw, 90px)`, 1.02 line-height for the featured Tesco statement.
- **Headline:** Regular serif, responsive sizes around `clamp(42px, 4.5vw, 68px)` for section headings; the introduction uses its own smaller clamp.
- **Title:** Regular serif, `clamp(24px, 2.4vw, 33px)` for chapter points.
- **Body:** DM Sans, 16px/1.55 by default, with larger lead paragraphs and controlled reading widths.
- **Label:** Bold DM Sans, generally 14px; contact labels use uppercase, 13px, and wider tracking.

**The Two-Voice Rule.** Use serif for identity and editorial statements, and sans-serif for navigation, metadata, tools, and detail.

## Layout

The site uses a 1600px maximum-width page field. The masthead spans three columns for identity, navigation, and résumé download. A ruled technology ribbon introduces the stack. The opening and later career chapters use a roughly 30/70 split: a narrow introduction or chapter margin and a broad work area. Tesco has three work points; later roles use ruled story rows. Toolkit and contact details use two-column grids.

Desktop gutters are 42px. The reference opening uses a 29/71 split, with the Tesco feature's three ruled work points on the right. Below 1280px, annotation space tightens and the intro links stack when needed. At 900px and below, chapter columns stack, masthead navigation moves to a horizontal second row, work points and toolkit collapse to single columns, and gutters become 22px. At 460px, gutters become 18px and story rows and contact links stack further.

## Elevation & Depth

The page is flat and uses no box shadows. Depth comes from the low contrast paper texture, column proportion, type scale, 1px keylines, stronger blue separators, and the solid blue contact region. The background asset is `assets/plates/paper-texture.webp`.

**The Ruled Page Rule.** Organize work with lines and whitespace instead of raised containers.

## Shapes

The system is rectilinear. Buttons have square corners; sections and rows use straight edges and one-pixel rules. Short blue strokes beneath select serif headings act as editorial marks. The featured chapter's three columns remain open rather than becoming cards.

## Components

### Actions

- **Solid link:** Blue fill, white bold sans-serif text, 48px minimum height, and `10px 17px` padding. Hover darkens to deep blue.
- **Outline résumé link:** Square blue outline, blue text, 44px minimum height, and `8px 16px` padding. Hover fills blue and turns text white.
- **Text link:** Underlined blue text with a 44px minimum target for supporting paths.
- **Focus:** Links use a 3px blue outline offset by 4px; the skip link appears when focused.

### Navigation and ribbon

Masthead links are unboxed, bold sans-serif text with a two-pixel underline on hover. The technology ribbon uses a handwritten blue introduction, local colorful technology marks, and compact labels divided by thin vertical rules. On narrow screens, navigation moves below identity and scrolls horizontally.

### Chapters and rows

Chapter indexes and major statements use serif type. Employer wordmarks and metadata use bold sans-serif text and tabular numerals. Featured work has three ruled points with blue Caveat margin notes and hand-drawn arrows. Later work uses labeled story rows separated by light keylines.

### Contact

The full blue closing section pairs a large serif invitation with two columns of labeled contact details. Fine light-blue rules divide links; labels use uppercase and wider tracking.

## Do's and Don'ts

### Do:

- **Do** maintain the warm paper, charcoal, and cobalt hierarchy.
- **Do** keep chapter numbers, employer, dates, technology, and outcomes scannable.
- **Do** use serif statements and sans-serif detail as distinct voices.
- **Do** use ruled, open rows for work and skills.

### Don't:

- **Don't** replace the journal structure with a card grid.
- **Don't** use rounded pills or shadows as the default component language.
- **Don't** carry the optional park's illustration style into the main professional page.
