# Day 01: Hex-to-RGB Extractor — Task Tracker

## Plan
Build a single-page tool that accepts a hex color code and returns its RGB components, styled with the Golden Dark design system.

## Tasks
- [x] Create folder structure (`Day_One/tasks/`)
- [x] Write `todo.md` and `lessons.md`
- [x] Build `index.html` with HTML, CSS, and JS
  - [x] Golden Dark CSS variables and base styles
  - [x] Input + button layout
  - [x] Color preview swatch
  - [x] Hex → RGB conversion logic
  - [x] Validation and error state

## Verification
- [x] `#d4af37` → `rgb(212, 175, 55)`
- [x] `#fff` → `rgb(255, 255, 255)` (3-char shorthand)
- [x] `xyz` → error message displayed

## Review
- Single self-contained file, no dependencies beyond Google Fonts
- Fully styled per STYLE.md Golden Dark palette
- Handles 3-char and 6-char hex, with and without leading `#`
