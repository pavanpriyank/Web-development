# Assignment 3: The Big Styled Table

## Overview
This project displays a structured, 20-row by 10-column product inventory size and stock chart table for a Campus Store. It utilizes advanced HTML table tags (`caption`, `thead`, `tbody`, `tfoot`, `th` with `scope`) along with CSS variables for custom styling.

## Features Implemented
* **HTML Table Structure:** Built using proper semantic tags (`table`, `caption`, `thead`, `tbody`, `tfoot`).
* **Scoped Headers:** Uses `scope="col"`, `scope="colgroup"`, and `scope="rowgroup"` for accessibility.
* **Rowspan & Colspan Usage:**
  - `colspan="4"` for grouping measurement headers.
  - `colspan="8"` in footer for total summary label.
  - `rowspan="10"` for grouping brand names (`Campus` and `Everyday`).
  - `rowspan="2"` for main table headers.
* **CSS Variables (`:root`):** Manages theme colors, cell padding, font size, and hover states cleanly.
* **Visual Enhancements:** `border-collapse`, alternating striped rows (`tr:nth-child(even)`), and interactive hover highlight (`tr:hover`).

## Directory Structure
```text
web-development/
    └── assignment-3/
        ├── index.html
        ├── style.css
        └── README.md