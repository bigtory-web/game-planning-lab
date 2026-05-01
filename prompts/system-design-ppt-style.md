# System Design PPT Style Rules

This document defines **visual rules** for turning a system design document into a **document-style PowerPoint deck**.

It is intentionally separate from
[system-design-writing.md](C:/Users/Home/OneDrive/110.카카오톡/New%20project/game-planning-lab/prompts/system-design-writing.md),
which defines **what to write**.

This file defines **how the document should look**.

## 1. Purpose

Use this rule set when the output format is **PowerPoint**, but the desired result is **not a presentation-style slide deck**.

The target is a deck that reads like a **practical work document**:

- readable at close range
- structured for review
- table- and flow-oriented
- restrained in decoration
- consistent from page to page

The deck should feel like a **system planning document in PPT form**, not a pitch deck, promo deck, or presentation-first slide set.

## 2. Applies To

Use this style when all of the following are true:

- the topic is a game system or feature
- the output is `.pptx`
- the audience is reviewing, evaluating, or implementing the system
- the document is meant to be read, not performed

Do not use this style for:

- marketing decks
- announcement decks
- investor decks
- visual moodboards
- presentation-first summary slides

## 3. Background And Overall Tone

- Use a **white or near-white document background**
  - Preferred: `#F7F7F4`
  - Acceptable: pure white or a very light warm gray
- Do **not** use dark presentation backgrounds
- The overall tone should be:
  - calm
  - practical
  - structured
  - review-friendly

The deck should read like a **work document**, not like a dramatic or cinematic showcase.

## 4. Typography Rules

- Slide title: `22–24pt`
- Section subtitle or key label: `12pt`
- Body text: `10–11pt`
- Table body text: `9.5–10pt`
- Large cover-style title is allowed only on the first page
  - If used, keep it restrained and document-like

### Font behavior

- Prefer neutral, readable fonts
- Keep one consistent font family through the whole deck unless there is a strong reason not to
- Avoid decorative display fonts

### Emphasis behavior

- Use bold sparingly
- Use bold only for:
  - slide titles
  - table headers
  - short key terms
- Do **not** bold entire bullet lists or long explanatory sentences

## 5. Color Rules

### Base colors

- Primary text: `#202020`
- Secondary dark line or frame: `#444444`
- Light divider or grid line: `#CCCCCC`
- Background: `#F7F7F4`

### Accent colors

- Primary accent: `#1E2D4A`
- Add only `1–2` additional state colors when needed
  - examples:
    - warning
    - success
    - selected state

Do not create a colorful deck. Accent colors should exist only to communicate structure or state.

## 6. Table And Diagram Rules

Tables and flow diagrams are allowed and encouraged, but they should look like part of the document, not like default PowerPoint furniture.

### Table rules

- Prefer **document-style tables**
- If the default PowerPoint table looks too generic, rebuild it with shapes and text blocks
- One slide should usually contain **one main table**
- Keep tables aligned and easy to scan

### Table visual behavior

- Header row should be clearly separated
- Body rows should remain calm and low-contrast
- Borders and lines should help reading, not dominate the page

Recommended treatment:

- Header background: light neutral or muted accent tint
- Body background: white or very light neutral
- Lines: `#CCCCCC` or `#444444` depending on hierarchy

### Diagram rules

- Use simple arrows, boxes, and grouped blocks for system flow
- Avoid decorative shapes with no structural meaning
- Diagrams should explain state or sequence, not act as visual decoration

## 7. Page Composition Rules

- Slide titles should follow `number + section name`
  - example: `4. 핵심 구조`
- Each page should have **one primary job**
- It is acceptable for a page to be information-dense
  - but it must still read like a document page, not a cluttered canvas
- Prefer stable alignment and consistent spacing over visual novelty

### Layout rhythm

- top: title
- middle: explanation, table, flow, or comparison
- bottom: short notes only if needed

Do not make every page look different. Consistency matters more than surprise.

## 8. Image And Screenshot Rules

- Do not force images into the deck if they are not needed
- A screenshot or image should appear only when it has a clear documentary role

Allowed roles:

- UI evidence
- state comparison
- flow support
- prototype proof

Not allowed:

- decorative screenshots
- filler images
- images inserted only to make the page look less empty

If an image is used, the document should make clear:

- why it is there
- what the reader should inspect

## 9. Emphasis Rules

Use emphasis only when it has a clear job.

Allowed emphasis targets:

- key rule difference
- selected state
- warning or limitation
- before/after comparison

Avoid:

- repeated bolding
- multiple accent colors on one page
- decorative highlight boxes
- large attention-grabbing banners

## 10. Banned Patterns

The following should be avoided in this document style:

- dark presentation backgrounds
- large decorative hero sections after page 1
- card-heavy marketing layouts
- pitch-deck style center slogans
- oversized promo visuals
- multiple unrelated tables on one page
- filler icons or decorative shapes without meaning
- excessive bolding
- loud color palettes
- “slides first, document second” layouts

## 11. Style Traits Derived From The Reference PPT

The reference
[고대승_SpinMiner_브레이크시스템_기획서_v2.pptx](C:/Users/Home/Desktop/고대승_SpinMiner_브레이크시스템_기획서_v2.pptx)
shows these useful traits:

- bright document-style background
- small but readable text allowed
- strong consistency across slides
- one master-like visual rhythm
- title + structured body pattern
- text, table, and flow are more important than imagery
- practical review tone over presentation tone

These traits should be preserved as **direction**, not copied mechanically.

Do not copy the exact page count, exact color accents, or exact slide order from the reference.

## 12. Summary Rule

When in doubt, choose the option that makes the deck feel more like:

- a practical system document
- a readable internal review file
- a structured planning artifact

and less like:

- a stage presentation
- a summary-only deck
- a visual marketing file
