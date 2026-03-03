# March 2026 Code Challenge — Task Tracker

## Day 03: Accessible Palette Generator

### Plan
- [x] Read README.md, STYLE.md, Day_One/index.html, Day_Two/index.html to understand patterns
- [x] Create `Day_Three/` folder and `index.html`
- [x] Implement CSS (Golden Dark design system, swatch layout, contrast badges, snippet box)
- [x] Implement HTML structure (dual input row, result area, swatch row, export section)
- [x] Implement color-math functions (hexToRgb, rgbToHsl, hslToHex, computeLuminance, computeContrast)
- [x] Implement shade generation (5 fixed lightness steps: 90/70/50/30/15)
- [x] Implement WCAG badge logic (best contrast vs white/black, AA pass ≥ 4.5:1)
- [x] Implement render functions (renderSwatches, renderSnippet with token spans)
- [x] Implement copy functions (copyHex, copyCssVars) with 1.5s feedback
- [x] Implement sync between text input and color picker
- [x] Wire all events (keydown Enter, input, color picker change, swatch row delegation)
- [x] Update README.md projects table and roadmap checklist

### Review
All tasks complete. The file is self-contained at `Day_Three/index.html` with no external dependencies beyond Google Fonts. Follows Golden Dark design system exactly. WCAG contrast math uses the official WCAG 2.1 luminance formula.

### Verification Checklist
- [ ] `#d4af37` → 5 distinct golden shades with labels 100–900
- [ ] `#fff` (3-char) → accepted and generates palette
- [ ] `#xyz` invalid → error message shown, result hidden
- [ ] Color picker → syncs text field and auto-generates
- [ ] "Copy" per-swatch → shows "Copied!" 1.5s then resets
- [ ] "Copy CSS Variables" → copies valid `:root { }` block
- [ ] Mobile: swatch cards flex-wrap gracefully
- [ ] WCAG pass badges (green) on high-contrast shades, fail (red) on low-contrast
