# Assignment 04: Style Your Portfolio (v2)

## Overview
This project transforms the plain HTML portfolio from Assignment 2 into a styled, professional portfolio using CSS design tokens, custom font pairings, and responsive flex/grid layouts.

## Requirements Implemented
- **4+ Selectors Used:**
  1. *Element:* `body`, `h1`, `h2`, `p`, `a`
  2. *Class:* `.hero-section`, `.btn-primary`, `.project-card`
  3. *ID:* `#home`, `#about`, `#projects`, `#contact`
  4. *Descendant/Child:* `.main-header .logo`, `.hero-text h1`, `.nav-links a`
  5. *Pseudo-class:* `a:hover`, `.btn-primary:hover`, `.project-card:hover`
- **External Stylesheet:** Linked via `<link rel="stylesheet" href="style.css">`.
- **Design Tokens (`:root`):** Centralized CSS variables for palette colours, fonts, font sizes, border radius, and spacing.

---

## Design Choices

### Font Pairing Rationale
- **Heading Font — Plus Jakarta Sans:** Chosen for its geometric, modern structure. Its bold weights (`700`, `800`) give headers a clear visual hierarchy and clean digital look.
- **Body Font — Inter:** Highly readable sans-serif typeface designed for screen readability. Provides neutral, legible reading across paragraph text and lists.

### Colour Palette Rationale
- **Primary (`#173a3a` - Dark Teal):** Provides high contrast for header, footer, and main headings, establishing structure.
- **Secondary (`#d9edd8` - Mint / Sage Green):** Used as a soft background highlight for the hero card to draw immediate visual attention.
- **Accent (`#215c5c` - Deep Green):** Used for interactive elements such as buttons and hover links to guide user navigation.
- **Background (`#f4f7f6` - Light Grey-Green):** Soft, non-glare off-white background that keeps the portfolio clean and approachable.

---

## Folder Location
```text
web-development/
    └── assignment-4/
        ├── index.html
        ├── style.css
        └── README.md