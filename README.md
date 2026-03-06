![Challenge Logo](./challenge_logo.png)

# March 2026 Code Challenge

One small, self-contained project per day throughout March 2026. Each day lives in its own folder as a single `index.html` — no build tools, no frameworks, just HTML, CSS, and vanilla JS.

All projects share the **Golden Dark** design system: deep charcoal backgrounds, Outfit typeface, and gold (`#d4af37`) accents.

---

## Progress

**6 of 31 days complete** · Week 1 in progress

```
Week 1 ███████████████░░░░░  6 / 7
Total  ████░░░░░░░░░░░░░░░░  6 / 31
```

---

## Completed Projects

| Day | Title | What it does |
|-----|-------|-------------|
| [01](./Day_One/index.html) | **Hex-to-RGB Extractor** | Enter a hex color and extract its RGB and HSL values with a live color swatch and one-click copy for each format. |
| [02](./Day_Two/index.html) | **Fluid Scale Generator** | Pick a base font size and a ratio (Golden Ratio, Perfect Fourth, Major Third, Minor Second) to generate a 7-step typographic scale with live preview and one-click CSS variable export. |
| [03](./Day_Three/index.html) | **Accessible Palette Generator** | Enter a hex color to generate a 5-shade tonal palette (100–900) with WCAG AA/AAA contrast scores and one-click CSS variable export. |
| [04](./Day_Four/index.html) | **CSS Variable Injector** | Edit the Golden Dark design tokens live with synchronized color pickers and hex inputs — the preview card updates in real time. Copy the full `:root { }` block for your own project. |
| [05](./Day_Five/index.html) | **Google Fonts Pairer** | Search and select two Google Fonts (heading + body). Adjust weight and size with live controls, see them rendered side-by-side, then copy the ready-to-use `@import` CSS. Supports the Google Fonts API key to unlock all 1,500+ fonts. |
| [06](./Day_Six/index.html) | **Glassmorphism UI Maker** | Dial in blur, tint color, opacity, border, radius, and shadow with live sliders. See the glass card update in real time over a vivid gradient background, then copy the ready-to-use CSS. Three presets: Frosted, Dark Glass, and Colored. |

---

## 📅 Roadmap

### 🎨 Week 1: Color & Type Foundation
- [x] Day 01: Hex-to-RGB & Contrast Extractor
- [x] Day 02: Fluid Type & Golden Ratio Generator
- [x] Day 03: Accessible Palette Generator
- [x] Day 04: CSS Variable Injector
- [x] Day 05: Google Fonts Pairer
- [x] Day 06: Glassmorphism UI Maker
- [ ] Day 07: SVG Wave/Blob Generator (For section dividers)

### ✍️ Week 2: Content & Formatting
- [ ] Day 08: Markdown-to-HTML Live Preview (Side-by-side editor)
- [ ] Day 09: JSON Formatter & Validator (Prettify messy data strings)
- [ ] Day 10: Lorem Ipsum "Dev Edition" (Generates tech-themed filler text)
- [ ] Day 11: Case Converter (camelCase, snake_case, PascalCase, kebab-case)
- [ ] Day 12: RegEx Playground (Test patterns against sample strings)
- [ ] Day 13: Base64 Image Encoder (Convert small icons to strings)
- [ ] Day 14: Word & Character Counter (With "Reading Time" estimator)

### 🚀 Week 3: Developer Productivity
- [ ] Day 15: Unit Converter (px to rem / em / vh / vw)
- [ ] Day 16: Meta Tag Generator (SEO, OpenGraph, and Twitter cards)
- [ ] Day 17: Cron Job Visualizer (Human-readable schedule generator)
- [ ] Day 18: JWT Debugger — client-side only (Decode tokens securely)
- [ ] Day 19: Git Command Helper (Interactive builder for complex git flows)
- [ ] Day 20: Flexbox/Grid Visualizer (Interactive layout sandbox)
- [ ] Day 21: HTTP Status Code Reference (Searchable modal of codes/meanings)

### 🔗 Week 4: Integration & Polish
- [ ] Day 22: URL Parser/Encoder (Breaks down UTM params and queries)
- [ ] Day 23: CSS Animation Keyframe Maker (Visual easing curves)
- [ ] Day 24: Favicon Generator — Canvas-based (Create simple icons)
- [ ] Day 25: Code Snippet "Card" Generator (Export code as an image)
- [ ] Day 26: CORS Header Tester (Mock request builder)
- [ ] Day 27: Password/Secret Generator (Entropy-based secure strings)
- [ ] Day 28: Performance Checklist (Interactive dev checklist)

### 🏁 Final Stretch: Suite Integration
- [ ] Day 29: Navigation Sidebar (The "glue" that connects all folders)
- [ ] Day 30: Master Dashboard (Searchable index of all 29 tools)
- [ ] Day 31: Build & Deploy Utility (Final optimization and manifest generation)

---

## Design System

**Golden Dark** — a dark-mode aesthetic built around deep charcoal surfaces, the [Outfit](https://fonts.google.com/specimen/Outfit) typeface, and gold accents.

### Color Tokens
| Token | Value | Role |
|-------|-------|------|
| `--bg-color` | `#1e2122` | Page background |
| `--modal-bg` | `#2d3436` | Card / modal surface |
| `--secondary-bg` | `#3b4244` | Input fields, inner surfaces |
| `--accent-gold` | `#d4af37` | Borders, buttons, active states |
| `--text-main` | `#ffffff` | Primary text |
| `--text-muted` | `#dfe6e9` | Secondary text, labels |

### Typography
- **Family:** Outfit (Google Fonts) · weights 300, 400, 600
- **Headings:** 1.4rem / 600 / `var(--accent-gold)`
- **Body:** 0.875rem / 300 / `var(--text-muted)`

### Layout
- Centered modal card, `border-top: 4px solid var(--accent-gold)`, `border-radius: 16px`
- Single-panel tools: `max-width: 500–640px`
- Two-panel tools: `max-width: 860–900px`, stacks to single column at ≤ 640px
- All tools are fully self-contained single `index.html` files — open directly in a browser, no server required
