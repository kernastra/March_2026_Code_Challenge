# STYLE.md | "Golden Dark" Design System (Updated)

## 🎨 Color Palette
- **Background:** `#1e2122` (Deepest Charcoal - for body backdrop)
- **Surface (Modal):** `#2d3436` (Deep Charcoal)
- **Secondary Surface:** `#3b4244` (Muted Charcoal)
- **Text Primary:** `#ffffff` (Pure White)
- **Text Secondary:** `#dfe6e9` (Soft Gray)
- **Accent:** `#d4af37` (Accent Gold)

## 🔡 Typography
- **Font Family:** 'Outfit', sans-serif (Google Fonts)
- **Weights:** 300, 400, 600

## 🏗️ Layout Rules
1. **The Dark Modal:** The container now uses the Deep Charcoal as its base to blend into the dark environment while remaining distinct.
2. **Gold Accents:** Use the Gold (#d4af37) for borders, buttons, and active states to guide the eye.
3. **Glassmorphism (Optional):** Add a subtle border to the modal to define it against the background.

## 🧱 CSS Base Variables
```css
@import url('[https://fonts.googleapis.com/css2?family=Outfit:wght@300;400;600&display=swap](https://fonts.googleapis.com/css2?family=Outfit:wght@300;400;600&display=swap)');

:root {
  --bg-color: #1e2122;
  --modal-bg: #2d3436;
  --secondary-bg: #3b4244;
  --accent-gold: #d4af37;
  --text-main: #ffffff;
  --text-muted: #dfe6e9;
  --modal-shadow: 0 25px 50px -12px rgba(0, 0, 0, 0.5);
}

body {
  background-color: var(--bg-color);
  color: var(--text-main);
  font-family: 'Outfit', sans-serif;
  display: flex;
  justify-content: center;
  align-items: center;
  min-height: 100vh;
  margin: 0;
}

.modal-container {
  background: var(--modal-bg);
  width: 90%;
  max-width: 500px;
  padding: 2.5rem;
  border-radius: 16px;
  box-shadow: var(--modal-shadow);
  border: 1px solid rgba(255, 255, 255, 0.05);
  border-top: 4px solid var(--accent-gold);
}

button {
  background: var(--accent-gold);
  color: var(--bg-color);
  border: none;
  padding: 0.8rem 1.5rem;
  border-radius: 8px;
  font-weight: 600;
  cursor: pointer;
  transition: transform 0.2s ease;
}

button:hover {
  transform: translateY(-2px);
  filter: brightness(1.1);
}