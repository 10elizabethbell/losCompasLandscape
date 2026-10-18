---
name: Los Compas Landscape LLC
description: A crew's yard, after the leaves come off. Pine ground, cream slab lettering, sunset-gold actions, and a live yard you sweep with a finger.
colors:
  pine: "#133a22"
  pine-deep: "#0e2d1a"
  moss: "#2c5b3b"
  meadow: "#eeeedb"
  field: "#fbfaf1"
  ink: "#16321f"
  ink-soft: "#3e5847"
  cream: "#f7efd9"
  cream-soft: "#cfd8c4"
  sun: "#f3a93c"
  sun-deep: "#e48f1f"
  mark: "#2563a8"
  error: "#a3310f"
  rule: "rgba(22,50,31,.16)"
  placeholder: "#5d6c60"
  on-scene: "#fff"
  lawn-light: "#47873a"
  lawn-dark: "#3a7431"
typography:
  display:
    fontFamily: "Alfa Slab One, Rockwell, Georgia, serif"
    fontSize: "clamp(36px, 10.4vw, 46px)"
    fontWeight: 400
    lineHeight: 1.05
    letterSpacing: "0.005em"
  display-wide:
    fontFamily: "Alfa Slab One, Rockwell, Georgia, serif"
    fontSize: "clamp(54px, 4.8vw, 74px)"
    fontWeight: 400
    lineHeight: 1.05
    letterSpacing: "0.005em"
  headline:
    fontFamily: "Alfa Slab One, Rockwell, Georgia, serif"
    fontSize: "clamp(30px, 8vw, 48px)"
    fontWeight: 400
    lineHeight: 1.05
    letterSpacing: "0.005em"
  title:
    fontFamily: "Alfa Slab One, Rockwell, Georgia, serif"
    fontSize: "22px"
    fontWeight: 400
    lineHeight: 1.1
    letterSpacing: "0.01em"
  body:
    fontFamily: "system-ui, -apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "17px"
    fontWeight: 400
    lineHeight: 1.55
  body-lead:
    fontFamily: "system-ui, -apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(17px, 4.6vw, 20px)"
    fontWeight: 400
    lineHeight: 1.45
  row:
    fontFamily: "system-ui, -apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "20px"
    fontWeight: 600
  label:
    fontFamily: "system-ui, -apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "16px"
    fontWeight: 700
    lineHeight: 1.15
  sub:
    fontFamily: "system-ui, -apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "19px"
    fontWeight: 400
  note:
    fontFamily: "system-ui, -apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "15px"
    fontWeight: 400
  caption:
    fontFamily: "system-ui, -apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "14px"
    fontWeight: 600
  micro:
    fontFamily: "system-ui, -apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "12px"
    fontWeight: 400
    letterSpacing: "0.14em"
  micro-sm:
    fontFamily: "system-ui, -apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "11px"
    fontWeight: 400
    letterSpacing: "0.08em"
rounded:
  tick: "4px"
  focus: "6px"
  field: "12px"
  button: "14px"
  card: "18px"
  scene: "28px"
  arrow: "50%"
spacing:
  gutter-sm: "16px"
  gutter: "20px"
  gutter-wide: "36px"
  fringe: "30px"
  fringe-wide: "38px"
  section-top: "64px"
  section-bottom: "72px"
  section-top-wide: "96px"
  section-bottom-wide: "104px"
components:
  button-primary:
    backgroundColor: "{colors.sun}"
    textColor: "{colors.ink}"
    typography: "{typography.label}"
    rounded: "{rounded.button}"
    padding: "0 14px"
    height: "56px"
  button-primary-hover:
    backgroundColor: "{colors.sun-deep}"
  button-outline:
    backgroundColor: "transparent"
    textColor: "{colors.cream}"
    typography: "{typography.label}"
    rounded: "{rounded.button}"
    padding: "0 14px"
    height: "56px"
  button-outline-hover:
    textColor: "{colors.sun}"
  service-row:
    textColor: "{colors.ink}"
    typography: "{typography.row}"
    padding: "8px 0"
    height: "58px"
  row-arrow:
    backgroundColor: "transparent"
    textColor: "{colors.ink}"
    rounded: "{rounded.arrow}"
    size: "40px"
  row-arrow-hover:
    backgroundColor: "{colors.sun}"
  facebook-card:
    backgroundColor: "{colors.pine}"
    textColor: "{colors.cream}"
    rounded: "{rounded.card}"
    padding: "18px 20px"
    height: "88px"
  facebook-card-hover:
    backgroundColor: "{colors.moss}"
  input-text:
    backgroundColor: "{colors.field}"
    textColor: "{colors.ink}"
    typography: "{typography.body}"
    rounded: "{rounded.field}"
    padding: "13px 15px"
    height: "54px"
  choice-chip:
    backgroundColor: "{colors.field}"
    textColor: "{colors.ink}"
    rounded: "{rounded.field}"
    padding: "0 15px"
    height: "46px"
---

# Design System: Los Compas Landscape LLC

## Overview

**Creative North Star: "The Yard After the Leaves Come Off"**

This is the logo's world laid out as a page: a deep pine ground taken from the badge's ring, cream slab lettering taken from its wordmark, and the badge's sunset gold kept for the things you press. Light sections are a cream tinted toward the lawn. The first screen ends in a real yard, drawn live: a herringbone paver patio with a charcoal soldier border, set in a mowed lawn and covered in fall leaves. The visitor sweeps it clean with a finger. Every section boundary on the page is a strip of swaying grass, so the yard continues the whole way down.

Density is phone-first and plain. One column on phones, big tap targets (56px buttons, 58px rows), short service items, and a single estimate form that writes a text message. The type is loud only in the display face; everything you read or tap is in the system sans. Depth comes from the scene itself (baked leaf shadows, patio edge shadow, airborne leaves casting offset shadows), not from cards floating on the page.

The build rejects the landscaper template its predecessor was: no stock lawn photo, no counters, no icon-card grids.

**Key Characteristics:**
- Two grounds only: pine (dark) and meadow (light), alternating, every boundary a grass edge.
- Alfa Slab One, uppercase, for headings; system sans for all reading and controls.
- Gold is the action color; blue is the form's outline color; red appears only in errors.
- One live signature scene (the yard) plus one recurring living divider (the grass edge), driven by one pointer and one animation loop.
- Nothing moves under `prefers-reduced-motion`: the yard draws once as a still picture and the dividers render a single frame.

## Colors

A two-ground forest-and-cream palette from the company badge, with one warm action color and one cool form color kept strictly apart.

### Primary
- **Sunset Gold** (sun): The badge's sky. Filled primary buttons, the arrow fill on hovered service rows, the phone icon in the header, the global focus ring on dark grounds, text selection, and the hover color of outline buttons and footer links. Never a default fill on anything that is not a primary button.
- **Burnt Gold** (sun-deep): Hover state of filled gold buttons only.

### Secondary
- **Field Blue** (mark): The form's outline color. Hover and focus borders on text inputs, choice chips and the send button, the text caret, the checked-chip box, and the focus ring anywhere on a light ground. Chosen because gold is already the button fill and red is reserved for errors.

### Tertiary
- **Rust Error** (error): Error messages, the border of an invalid input, and the legend of an invalid fieldset. Nothing else in the UI chrome is red.

### Neutral
- **Pine** (pine): The page ground, the hero, the "How it works" section, and the Facebook card. The badge's ring lifted off black. Also `theme-color`.
- **Deep Pine** (pine-deep): Footer ground only, one step below pine so the page settles at the bottom.
- **Moss** (moss): Facebook card hover.
- **Meadow** (meadow): Light section ground (services, estimate).
- **Field** (field): Fill inside text inputs and choice chips on meadow.
- **Forest Ink** (ink): Text and arrow strokes on meadow; text on gold buttons.
- **Soft Ink** (ink-soft): Secondary text on meadow (sub-lines, form notes, "(optional)").
- **Cream** (cream): Headings and primary text on pine; the badge's lettering.
- **Sage Cream** (cream-soft): Secondary text on pine (promise line, step bodies, footer muted lines), outline-button border.
- **Rule** (rule): Hairlines between service rows and the arrow circle's resting stroke.

Scene colors live inside the canvas only and are not UI tokens: lawn stripes `#47873a` / `#3a7431`, paver stones `#c9b089 #bfa37a #d3bd96 #b39a74 #a9a191 #c4b7a0 #9d8f7b` on sand joints `#c8b48d`, soldier border `#7d7466`, leaf pairs (face/edge) `#b8371f/#7e2010`, `#d4621e/#9a3d0f`, `#e89a2c/#b56a12`, `#dfbb45/#a8851d`, `#8c5a2c/#5c3818`, `#a6421c/#6e2810`, light-ground grass tips `#6f9a4c #7aa352 #86a95a #66914a`.

### Named Rules
**The Gold Acts Rule.** Gold marks what you press. It fills the primary button, and appears on other controls only as a response (hover, focus). An arrow, link or icon never sits gold at rest, except the small phone glyph beside the header number.

**The Blue Form Rule.** Every control inside the estimate form outlines in Field Blue on hover and on focus. Blue belongs to the form and to focus on light grounds; it never appears in the hero, rows or cards.

**The Red Means Wrong Rule.** In UI chrome, red is only for errors. The rust and red of the leaves are scene material inside the canvas and are exempt; do not borrow them for buttons, badges or highlights.

## Typography

**Display Font:** Alfa Slab One (self-hosted inline as woff2; fallback Rockwell, Georgia, serif)
**Body Font:** system-ui stack (-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial)

**Character:** A heavy slab that matches the badge lettering, always uppercase, against a quiet system sans that does all the reading and tapping. The slab is the brand's voice; the sans is the crew talking plainly.

### Hierarchy
- **Display** (400, `clamp(36px,10.4vw,46px)` on phones, `clamp(54px,4.8vw,74px)` from 1024px, line-height 1.05, uppercase): The hero headline only. Phrases are held together with no-wrap spans so lines break on meaning.
- **Headline** (400, `clamp(30px,8vw,48px)`, 1.05, uppercase): Section headings (`h2`).
- **Title** (400, 22px group headings / 20px step headings, 1.1, uppercase): Sub-headings inside a section ("Build", "Care", step names). Also the Facebook card line (20px, sentence case) and the footer name (22px).
- **Body** (400, 17px, 1.55): Running text. Lead lines step up to `clamp(17px,4.6vw,20px)` (hero promise) or 19px (estimate sub-line). Measure is capped at 34-40ch.
- **Row** (600, 20px): Service row labels.
- **Label** (700, 16px): Buttons, form labels and legends, the header phone number (tabular numerals).
- **Small** (14-15px): Notes under the send button, error text (600), footer muted lines, copyright.

### Named Rules
**The Slab Speaks Uppercase Rule.** Alfa Slab One is used only at weight 400 and only for headings, the wordmark, the Facebook card line and the step numerals. Section and hero headings are uppercase; body copy, labels and buttons never use the slab.

**The Text-Wrap Balance Rule.** All `h1-h3` use `text-wrap: balance`; no orphaned single word on a heading line.

## Layout

A single 1180px max-width column with a fluid gutter (16px under 400px, 20px on phones, 36px from 700px). Sections alternate pine and meadow and are padded 64px top / 72px bottom on phones, 96px / 104px from 700px.

- **Phones:** header row (badge + two-line wordmark left, phone number right), hero copy, two buttons side by side in a two-column grid (max 460px), then the yard canvas at `clamp(250px,40svh,420px)` filling the rest of the first screen. Service groups stack; form chips sit in a two-column grid below 700px.
- **700px+:** service groups go two-up (gap 48px), steps go three-up, footer becomes logo / name / links columns.
- **1024px+:** the hero becomes a 5fr / 6fr grid at `min(100svh,900px)`: copy left on pine, aligned to the content column, yard right at full hero height with a 28px top-left corner. The estimate section splits 5fr / 7fr with the intro column sticky at 32px.
- **Small phones (≤400px):** the wordmark, number and button labels step down a size so the wordmark never collides with the number.

### Named Rules
**The One Number Up Top Rule.** On the first screen the phone number appears once, as a tap-to-call text link in the top-right of the header. There is never a Call button under the headline. The footer may repeat it.

**The Two Buttons Rule.** The hero carries at most two buttons, side by side: the filled gold primary and one outlined secondary. Nothing goes under them but the yard.

**The Footer Email Rule.** The email address exists only in the footer link list. No email buttons, prompts or "send by email" options anywhere else.

## Elevation & Depth

The page is flat. Depth belongs to the scene: the patio casts a soft edge shadow onto the lawn, every leaf sprite has a blurred contact shadow baked under it, and airborne leaves draw a separate blurred shadow offset down-right by their height (`z * .35`) and fading with altitude. On the page itself, the only lifted surface is the Facebook card.

### Shadow Vocabulary
- **Proof card lift** (`box-shadow: 0 10px 22px -12px rgba(0,0,0,.35)`): The Facebook card on meadow, so it reads as a thing to tap.
- **Hint glow** (`radial-gradient(closest-side, rgba(19,58,34,.82), rgba(19,58,34,0))` plus `text-shadow: 0 1px 2px rgba(0,0,0,.5)`): Behind "Drag to clear the leaves" so the hint stays readable over leaves.

### Named Rules
**The Depth Lives In The Yard Rule.** Shadows are physical: cast by stones and leaves inside the canvas. UI surfaces stay flat, with the single exception of the proof card.

## Shapes

Soft, friendly corners on everything you touch, circles for arrows, and organic curves for anything from nature. Fields and chips 12px, buttons 14px, the Facebook card 18px, the desktop yard's top-left corner 28px, arrow buttons fully round (40px). The patio is a superellipse (exponent 0.4), squarer than an oval, the way a laid patio looks. Grass blades are two quadratic curves meeting at a leaning tip; leaves are maple (18-point curved), oak (lobed) and elm (serrated ovate) silhouettes with veins and a curved stem. No ruler-straight shapes stand in for anything natural.

## Components

### Buttons
Big, warm and plain.
- **Shape:** gently rounded (14px), min-height 56px, 2px border, 16px/700 sans label, optional 20px inline SVG icon.
- **Primary:** gold fill, forest ink label, gold border. Hover deepens to burnt gold.
- **Outline (secondary):** transparent with a sage-cream border and cream label; hover turns border and label gold. Used for the hero's second action (WhatsApp).
- **Press:** `translateY(1px)` on `:active`; color transitions .18s ease.
- **Form send button:** the same gold primary at full width, but inside the form it outlines in Field Blue on hover (3px, offset 2px) and focus (3px, offset 3px).

### Service rows
Quiet lists you can tap.
- **Style:** full-width links, 20px/600 label left, 40px arrow circle right, 1px rule between rows (and above the first). No fill, no card.
- **Hover / focus:** only the arrow changes. The circle fills gold (border gold); the row itself never gets an outline, ring, border change or background tint. Keyboard focus draws the ring around the arrow circle (3px, offset 3px; gold on dark, blue on light), never the row.
- **Behavior:** tapping a row jumps to the estimate form and ticks the matching service chip.

### Proof card (Facebook)
- **Placement:** directly under the services list, where a visitor looks for proof of the work. Also listed in the footer.
- **Style:** pine fill on meadow, 18px corners, min-height 88px, padding 18px 20px, 44px Facebook mark, 20px slab line, trailing arrow circle (cream-tinted stroke). The lift shadow from Elevation.
- **Hover:** fill shifts to moss; the arrow fills gold with ink stroke.

### Inputs / Fields
- **Style:** field-cream fill, 2px border at `rgba(22,50,31,.28)`, 12px corners, min-height 54px (textarea 110px, vertical resize), 17px body text, blue caret. Placeholder `#5d6c60`.
- **Hover:** border turns Field Blue.
- **Focus:** Field Blue border plus a 2px Field Blue outline at 2px offset.
- **Error:** border and legend turn rust; a 15px/600 rust message appears under the field. Errors clear on input.
- **Labels:** 16px/700 above the field; optional parts in 400 soft ink in parentheses.

### Choice chips
Real checkboxes styled as tappable tiles; the only chip in the system is this form control.
- **Style:** field-cream fill, same border as inputs, 12px corners, min-height 46px, 16px/600 label, a 16px rounded-square box before the label.
- **Hover / focus:** Field Blue border; keyboard focus adds a 2px blue outline.
- **Checked:** pale gold fill (`#f6e2bd`), blue border, box filled blue with a white check.
- **Layout:** wrapping row on wide screens, two-column grid under 700px.

### Navigation (header)
- Not a menu: badge (48px, 44px on small phones) and a two-line wordmark (slab 19px uppercase over 12px tracked sage-cream "Landscape LLC") link to top on the left; the tap-to-call number with a gold phone glyph on the right, underlining on hover. Respects the top safe-area inset.

### The Yard (signature component)
A full-bleed canvas at the bottom of the hero: the visitor's job is to clear the leaves.

- **Ground (drawn once per size, cached offscreen):** wide mow stripes (36px phone / 46px desktop) in two greens with thousands of short blade strokes in 5 tones per stripe; a superellipse patio of 45-degree herringbone pavers (unit 12px phone / 15px desktop, 0.9px sand joints) where each stone gets a random tone from the stone palette, a soft lit-to-shaded gradient and three speckles; a charcoal soldier-course border cut into stones; a soft shadow where the patio meets the lawn.
- **Leaves:** 18 sprites (3 species x 6 fall colors) pre-rendered with radial shading, light veins, stem and a baked contact shadow. Each leaf has position, velocity, height `z`, spin, scale (0.72-1.22) and a flip factor that foreshortens it as it tumbles.
- **Blower physics:** inside `BLOW_RADIUS` the pointer pushes leaves outward with a quadratic falloff (`BLOW_FORCE`) and hands them a share of its own velocity (`BLOW_CARRY`); a sideways swipe adds spin. A hard swipe (over 280 px/s touch, 450 mouse) can throw ground leaves into the air (`LIFT`). Blown leaves slide on low friction for 0.25s, then settle on high friction.
- **Airborne leaves:** fall under gravity, drift on a three-sine wind field, sway, spin and flip; they draw on top of ground leaves with a blurred shadow offset by their height and grow slightly with altitude. A few are kept aloft at all times (`AIRBORNE_PHONE/DESK`), lifted off the lawn every half second as needed.
- **Self-sweep with rest/resume:** after `AUTO_IDLE_MS` without input, an invisible crew member works a Lissajous path across the patio, blowing leaves outward toward the lawn (with an outward bias from the patio center). Twice a second the yard counts leaves on the patio; the sweep rests once the patio falls below `AUTO_REST_AT` of its starting count and resumes when drifting leaves bring it back above `AUTO_RESUME_AT`. Any touch takes over immediately and hides the hint for good.
- **Regrowth:** leaves that leave the canvas are removed; new ones drift back in at `REGROW` per second (slowed to 35% while the self-sweep runs), 60% arriving from the upwind edge, the rest landing preferably off the patio.
- **Gusts:** the shared page-wide `Gust(t)` occasionally ruffles leaves resting on the lawn.
- **Phones:** a 30px swaying grass fringe is drawn along the yard's top edge. On desktop the fringe is off and the yard takes a 28px top-left corner.
- **Input:** the canvas sets `touch-action: none` and cancels `pointerdown`, and reads its own bounding box every frame, so vertical drags sweep leaves instead of scrolling. The page sets `overscroll-behavior-y: none`.
- **Fallbacks:** before boot a CSS stripe layer stands in for the lawn. Under reduced motion the hint is removed, the canvas label drops the drag instruction, and one still frame is drawn.

### Grass edges (signature divider)
A canvas sits on the top edge of every section after the hero (and the footer), `--fringe` tall (30px phone / 38px wide), and grows up into the section above.

- **Blade color rule:** blades take the color of the section they grow from. On a dark ground (pine, deep pine) each blade is the host background shaded by -14 to +10 per channel. On a light ground (meadow) blades are one of four greens at the tip, fading to the meadow color at the base, so the edge reads as lawn growing out of cream. A 4px strip of the host color seals the base.
- **Blades:** spaced every `BLADE_GAP` px (x0.7-1.3 jitter), heights 35-100% of the strip, widths 2.4-4.6px, sorted tall-to-short so short ones draw in front.
- **Motion:** each blade sways on three summed sines (scaled by `SWAY` and `SWAY_SPEED`) plus a **rolling gust**: a cubed sine wave that travels along the edge, amplified by the page-wide `Gust(t)`.
- **Pointer:** a nearby pointer (within 70px vertically, moved in the last 400ms) pushes blades within 60px aside on a damped spring (stiffness 38, damping 6.5, max lean 80% of height).
- **Caught leaves:** `EDGE_LEAVES` per edge (60% on phones) sit in the grass using the yard's leaf sprites at 80% size. A passing pointer flicks them up; they bounce inside the strip (never above it, so they stay clear of text) and creep back to where they were caught.

### Motion system
- **One pointer:** a single global `P` record (position, smoothed velocity, down state, pointer type) fed by pointer and touch events, shared by the yard and every grass edge.
- **One loop:** a single `requestAnimationFrame` loop ticks every registered scene with a clamped `dt` (max 50ms). Each scene is observed with an IntersectionObserver (80px margin) and only ticks while on screen; the loop stops when nothing is visible and wakes when something scrolls in.
- **One wind:** `Gust(t) = max(0, sin(.45t) * sin(.17t + 2))` ties the lawn's leaf ruffles to the grass edges' rolling gust, so the whole page shares a breeze.
- **Reduced motion:** no loop at all; each canvas paints one frame and redraws only on resize. Smooth scrolling and control transitions turn off.
- **CFG tunables** (top of the script, the first place to adjust feel):

| Key | Value | Effect |
|---|---|---|
| `LEAVES_PHONE` / `LEAVES_DESK` | 380 / 600 | Leaves resting on the yard at start (scaled to area) |
| `LEAF_PHONE` / `LEAF_DESK` | 22 / 28 | Leaf size, CSS px |
| `REGROW` | 7 | Leaves per second drifting back once cleared |
| `AIRBORNE_PHONE` / `AIRBORNE_DESK` | 3 / 8 | Leaves kept tumbling in the air |
| `EDGE_LEAVES` | 10 | Leaves caught in each grass edge (phones x0.6) |
| `BLOW_RADIUS` | 70 | Pointer reach, CSS px (x1.35 desktop) |
| `BLOW_FORCE` | 2600 | Outward push |
| `BLOW_CARRY` | 0.55 | Share of pointer speed handed to leaves |
| `LIFT` | 70 | How hard a strong push throws leaves up |
| `AUTO_IDLE_MS` | 7000 | Quiet time before the yard sweeps itself |
| `AUTO_SPEED` | 0.5 | Self-sweep speed |
| `AUTO_REST_AT` | 0.75 | Self-sweep rests below this share of starting patio leaves |
| `AUTO_RESUME_AT` | 0.9 | ...and resumes above this share |
| `BLADE_GAP` | 4 | px between grass blades |
| `SWAY` / `SWAY_SPEED` | 1.0 / 1.0 | Grass sway amount and speed |

## Do's and Don'ts

### Do:
- **Do** alternate pine and meadow grounds and put a grass edge on the top of every section after the hero, colored by the rule above.
- **Do** keep the phone number as a text `tel:` link in the top-right of the header, once on the first screen.
- **Do** cap the hero at two side-by-side buttons: filled gold primary, outlined secondary.
- **Do** outline every form control (inputs, chips, the send button) in Field Blue on hover and on focus.
- **Do** let service rows respond only through the arrow circle filling gold; put the focus ring on the arrow.
- **Do** keep the Facebook proof card directly under the services, plus a Facebook link in the footer.
- **Do** keep the email in the footer and nowhere else.
- **Do** route new animation through the shared pointer `P`, the single `Loop` and `Gust(t)`, expose new feel parameters in `CFG`, and paint one still frame under reduced motion.
- **Do** keep anything airborne in a grass edge inside its strip, clear of headings and text.
- **Do** draw natural things with curves and baked shading (leaf sprites, superellipse patio, curved blades).

### Don't:
- **Don't** put a Call button under the hero headline, a sticky bottom contact bar, or a third hero button.
- **Don't** outline, ring, tint or border-shift a whole service row on hover or focus.
- **Don't** use red anywhere in the UI except errors (the leaves' rust and red are scene material, not UI color).
- **Don't** use gold as a resting fill on arrows, links or icons; it appears on hover and focus.
- **Don't** use blue outside the form and light-ground focus.
- **Don't** set body copy, labels or buttons in Alfa Slab One, or set the slab in any weight but 400.
- **Don't** add drop shadows to UI surfaces beyond the proof card; depth belongs to the yard.
- **Don't** add stock photos, counters, or icon-card grids.
- **Don't** let a vertical drag in the yard scroll the page.
