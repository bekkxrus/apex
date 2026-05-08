# Apex Houzz Figma Design Handoff

This folder contains a Figma-ready SVG board based on the provided reference:

- `apex-houzz-figma-board.svg`

## How to use in Figma

1. Open Figma.
2. Create a new design file.
3. Drag `apex-houzz-figma-board.svg` onto the canvas.
4. Select the imported artwork and ungroup as needed to edit individual layers.
5. Replace the vector photo placeholders with final real-estate imagery if desired.

## Frame

- Desktop landing page: 1200 px wide inside a 1440 px canvas
- Sections:
  - Navigation and hero lead-capture form
  - Services grid
  - Property preferences match
  - Free flip calculator
  - Contact form and contact information

## Visual system

### Colors

- Navy: `#111F3A`
- Deep navy gradient: `#0A1530` to `#25395D`
- Red CTA: `#C82A3E`
- Light background: `#F0F3F8`
- Section background: `#F5F8FC`
- Body text: `#5E6676`
- White: `#FFFFFF`

### Typography

Use Inter in Figma if available. Arial/Helvetica are acceptable fallbacks.

- Hero headline: 55 px, Extra Bold/Black
- Section titles: 42-45 px, Extra Bold
- Card titles: 24 px, Extra Bold
- Body copy: 15-28 px, Regular/Medium
- Buttons and nav: 13-16 px, Bold/Extra Bold

### Components to create in Figma

- Primary button: red fill, white bold text, 4-5 px radius
- Secondary button: transparent or gray fill, bold text
- Service card: white fill, 12 px radius, soft drop shadow
- Property card: white fill, 14 px radius, image area, navy label strip
- Form input: white fill, light gray border, 3-5 px radius

## Suggested Figma layer structure

```text
Apex Houzz Landing Page - Desktop
  Navigation
  Hero Section
    Hero copy
    Hero lead form
  Services Grid
    Service card - Subto
    Service card - Financing
    Service card - Lead Generation
  Property Preferences Match
    Property cards
  Free Flip Calculator
    Laptop illustration
    Spreadsheet preview
  Contact Section
    Contact form
    Contact information
```

## Notes

- The SVG uses editable vector shapes and text so the design can be refined directly in Figma.
- Photo areas are intentionally vector placeholders to avoid licensing issues.
- If exact brand assets are available, replace the logo mark and property imagery after import.
