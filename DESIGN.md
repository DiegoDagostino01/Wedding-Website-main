---
name: Diego & Bethany Wedding
description: A warm botanical wedding site for invited guests planning the day at Southdowns Manor.
colors:
  cream: "#FBF6EE"
  cream-deep: "#F3EBDC"
  ink: "#33361F"
  sage: "#8FA07C"
  sage-deep: "#5C6B44"
  olive: "#6E7A45"
  peach: "#E7B98D"
  terracotta: "#C77F52"
  mustard: "#CFA044"
  dusty-blue: "#A9C1CE"
typography:
  display:
    fontFamily: "Cormorant Garamond, Georgia, serif"
    fontSize: "clamp(3rem, 9vw, 6rem)"
    fontWeight: 500
    lineHeight: 0.98
    letterSpacing: "-0.03em"
  headline:
    fontFamily: "Cormorant Garamond, Georgia, serif"
    fontSize: "clamp(2.2rem, 4.5vw, 3.2rem)"
    fontWeight: 500
    lineHeight: 1.1
    letterSpacing: "-0.02em"
  title:
    fontFamily: "Cormorant Garamond, Georgia, serif"
    fontSize: "1.4rem"
    fontWeight: 600
    lineHeight: 1.2
    letterSpacing: "-0.02em"
  body:
    fontFamily: "Jost, Arial, sans-serif"
    fontSize: "1rem"
    fontWeight: 400
    lineHeight: 1.6
  label:
    fontFamily: "Jost, Arial, sans-serif"
    fontSize: "0.78rem"
    fontWeight: 400
    lineHeight: 1.2
    letterSpacing: "0.2em"
rounded:
  xs: "3px"
  sm: "4px"
  md: "6px"
spacing:
  xs: "8px"
  sm: "14px"
  md: "22px"
  lg: "32px"
  xl: "44px"
  section: "110px"
components:
  button-primary:
    backgroundColor: "{colors.peach}"
    textColor: "{colors.ink}"
    rounded: "{rounded.xs}"
    padding: "15px 38px"
    typography: "{typography.label}"
  button-primary-hover:
    backgroundColor: "{colors.terracotta}"
    textColor: "{colors.cream}"
    rounded: "{rounded.xs}"
    padding: "15px 38px"
  card-soft:
    backgroundColor: "{colors.cream-deep}"
    textColor: "{colors.ink}"
    rounded: "{rounded.md}"
    padding: "44px"
  input-dark:
    backgroundColor: "#FBF6EE14"
    textColor: "{colors.cream}"
    rounded: "{rounded.xs}"
    padding: "13px 16px"
---

# Design System: Diego & Bethany Wedding

## 1. Overview

**Creative North Star: "The Manor Garden Letter"**

The system should feel like a personal invitation carried through a countryside garden: soft enough for a wedding, clear enough for guests who need practical details, and specific enough to belong to Diego and Bethany rather than to a generic wedding template. It uses botanical accents, restrained page rhythm, and a warm guest-first tone to make the site feel celebratory without losing utility.

The visual language is already established in the static HTML: cream and deeper cream surfaces, sage structure, peach and terracotta warmth, Cormorant Garamond display type, Jost body copy, small botanical dividers, soft reveal motion, and ambient shadows. Preserve those choices unless a future task explicitly asks for a departure. The system rejects gray, flat, static interfaces and placeholder-heavy layouts that feel lifeless.

**Key Characteristics:**
- Warm practical pages for invited guests.
- Botanical detail used as a signature, not filler.
- Soft contrast between cream surfaces and garden-toned accents.
- Ambient depth and light motion rather than heavy decoration.
- Clear form, schedule, and travel information above pure ornament.

## 2. Colors

The palette is a countryside botanical range: cream grounds, olive-green structure, and peach-to-terracotta warmth for invitation moments.

### Primary
- **Garden Ink** (#33361F): Primary text, focus contrast, and the grounding color for body copy.
- **Pressed Terracotta** (#C77F52): Main emphasis color for names, hover accents, botanical marks, and warm section details.

### Secondary
- **Southdowns Sage** (#8FA07C): Soft botanical color used in hero atmospherics, gradients, and supporting detail.
- **Deep Sage** (#5C6B44): Darker green for readable secondary text, schedule structure, and the RSVP section background.
- **Olive Stem** (#6E7A45): Botanical SVG strokes and quiet garden-line accents.

### Tertiary
- **Petal Peach** (#E7B98D): Primary button background, RSVP labels, selection highlights, and warm floral details.
- **Late-April Mustard** (#CFA044): Occasional gallery warmth only; use sparingly so it does not overpower the wedding palette.
- **Fjord Blue** (#A9C1CE): Cool counterpoint in gradients and future proposal/gallery imagery.

### Neutral
- **Invitation Cream** (#FBF6EE): Main page background and light text on dark sections.
- **Pressed Paper** (#F3EBDC): Alternating section background and soft card surface.

### Named Rules
**The Guest-First Contrast Rule.** Body text stays close to Garden Ink or Invitation Cream; decorative pale text is not allowed to carry essential information.

**The Warmth-with-Restraint Rule.** Petal Peach and Pressed Terracotta should feel earned. They mark action, romance, and botanical detail; they should not flood every component.

## 3. Typography

**Display Font:** Cormorant Garamond (with Georgia, serif fallback)
**Body Font:** Jost (with Arial, sans-serif fallback)

**Character:** Cormorant Garamond gives the page its invitation quality, especially in names, dates, and section titles. Jost keeps guest logistics practical, legible, and contemporary without turning the site into a formal stationery piece.

### Hierarchy
- **Display** (500, `clamp(3rem, 9vw, 6rem)`, 0.98): Hero names and the primary emotional introduction.
- **Headline** (500, `clamp(2.2rem, 4.5vw, 3.2rem)`, about 1.1): Section titles such as story, day, travel, gallery, and RSVP.
- **Title** (600, 1.15-1.8rem, about 1.2): Schedule names, card headings, venue title, and footer signature.
- **Body** (400, 1rem-1.05rem, 1.6): Guest-facing explanatory copy, capped around 62ch in the current page.
- **Label** (400, 0.7-0.85rem, 0.1-0.2em, uppercase): Navigation, form labels, tags, countdown labels, and occasional section identifiers.

### Named Rules
**The Invitation-Not-Broadsheet Rule.** Use the serif for warmth and names, but do not turn every section into editorial magazine styling. Guest clarity wins over typographic display.

## 4. Elevation

This system uses ambient softness: most surfaces are flat or tonally separated, with a single warm shadow reserved for lifted cards, mobile navigation, and hover states. Depth should feel like paper and garden light, not glass, chrome, or app panels.

### Shadow Vocabulary
- **Ambient Paper Lift** (`0 20px 60px rgba(94,84,45,0.12)`): Use for the venue card, photo placeholders, mobile menu, and interactive card hover states.

### Named Rules
**The Soft-Lift Rule.** Shadows appear when a surface needs tactile emphasis or hierarchy; do not add shadows to every repeated item.

## 5. Components

Components should feel warm, practical, and guest-first: ceremonial enough for the occasion, but never so precious that guests have to work to find details.

### Buttons
- **Shape:** Small radius, exact current value 3px.
- **Primary:** Petal Peach background, Garden Ink text, uppercase Jost label, `15px 38px` padding.
- **Hover / Focus:** Hover shifts to Pressed Terracotta with Invitation Cream text and a small upward translate. Focus uses a visible 2px outline with 3px offset.
- **Secondary / Ghost / Tertiary:** Not currently defined. Future secondary buttons should use a full border or quiet text treatment, not side-stripe accents.

### Chips
- **Style:** Small uppercase tags use Pressed Terracotta text on the surrounding surface, with no filled pill by default.
- **State:** Use for "Coming soon" and similar status labels; avoid making them compete with calls to action.

### Cards / Containers
- **Corner Style:** 4px for image placeholders and gallery items, 6px for cards and venue containers.
- **Background:** Pressed Paper for large content containers; Invitation Cream for smaller cards on Pressed Paper sections.
- **Shadow Strategy:** Ambient Paper Lift only on prominent cards or hover states.
- **Border:** Use the existing `rgba(51,54,31,0.14)` line for schedule rows and travel cards.
- **Internal Padding:** 32px for small cards, 44px for the venue card.

### Inputs / Fields
- **Style:** Dark-section form fields use translucent cream fill, translucent cream border, 3px radius, and Jost body type.
- **Focus:** Border shifts to Petal Peach and the fill becomes slightly stronger.
- **Error / Disabled:** Not yet defined. Future states should retain readable contrast and avoid gray-only meaning.

### Navigation
- **Style:** Fixed top nav with translucent cream background, blur, botanical-warm hover underline, and compact uppercase Jost links.
- **Mobile:** Links slide in as a right-side cream panel with Ambient Paper Lift. The menu toggle must keep its accessible label and visible focus state.

### Botanical Divider
The sprig SVG is the signature motif. Use it sparingly as a ceremonial divider or visual pause; do not repeat it above every small block of text.

## 6. Do's and Don'ts

### Do:
- **Do** preserve the existing color tokens from `diego-bethany-wedding.html` when extending the page.
- **Do** keep guest logistics easy to scan: schedule rows, travel cards, RSVP fields, and venue details should read quickly.
- **Do** use Cormorant Garamond for names, emotional headlines, dates, and ceremonial accents.
- **Do** use Jost for navigation, forms, labels, and practical body copy.
- **Do** support reduced motion and keep reveal content visible by default or safely recoverable.

### Don't:
- **Don't** make the interface gray, flat, or static; that is an explicit anti-reference for this project.
- **Don't** use generic wedding-template styling that could belong to any couple.
- **Don't** let placeholders dominate the page once real imagery is available.
- **Don't** use side-stripe accent borders, gradient text, glassmorphism, or repeated tiny uppercase labels as default scaffolding.
- **Don't** reduce essential form, schedule, travel, or RSVP text to low-contrast decorative color.