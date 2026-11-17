# Chromatik // Elite Edition

**Chromatik** is an advanced, self-contained web-based color palette laboratory and Procreate command engine. Designed for digital artists, UI/UX designers, and developers, it provides a comprehensive suite of tools for color curation, accessibility auditing, and multi-format asset generation—all within a single responsive file.

---

## ✨ Key Features

- **Palette Workbench (Max 30 Slots):** Drag-and-drop vector sorting, slot locking, history tracking (Undo/Redo), and preset generators.
- **Color Lab Matrix:** Fine-tune vectors using HSB, RGB, HEX, and OKLCH color spaces. Features real-time WCAG contrast ratio calculation and color psychology profiles.
- **AI Prompt Palette Synthesizer:** Generate custom palettes dynamically based on descriptive text prompts and thematic vibes.
- **Vision Extraction Engine:** Upload reference images or input URLs to auto-extract balanced, high-contrast, or deep-shadow color matrices.
- **Advanced Generators:** 
  - Tailwind CSS 10-step scales
  - 10-spectrum hue steps
  - 30-gradation tones and shades matrices
  - Gradient and tonal ramps (Black/White interpolations via OKLab)
  - Dedicated pastels (30 spectra) and portrait skin tone grades (30 grades)
- **Harmonies & Accessibility Audit:** Interactive color wheel for harmony generation (Analogous, Complementary, Triadic, Tetradic, etc.) and color blindness simulation filters (Protanopia, Deuteranopia, Tritanopia, Achromatopsia) with automated palette conflict detection.
- **Developer & Creative Exports:** 
  - Procreate `.swatches` (via JSZip) and Adobe `.ASE` swatch exchange files
  - Copy/Export formats including HEX, RGB, HSL, OKLCH, CSS variables, SCSS variables, Tailwind config snippets, SVG swatch strips, and JSON objects
  - PNG swatch card render engine

---

## 🚀 Getting Started

Since Chromatik is built entirely into a single-file architecture, you don't need any complex build steps or node modules to run it locally.

1. Clone or download this repository.
2. Ensure your main HTML file is named **`index.html`** (if hosted via GitHub Pages).
3. Open `index.html` in any modern web browser.

---

## 🌐 Live Demo

You can host this project instantly using **GitHub Pages**:
1. Go to your repository **Settings** on GitHub.
2. Select **Pages** from the left sidebar.
3. Under **Build and deployment**, set the branch to `main` and folder to `/ (root)`, then click **Save**.
4. Access your live web app via the provided GitHub Pages URL.

---

## 🛠️ Built With

- **HTML5 / CSS3** (Custom design tokens, CSS variables, responsive grid systems)
- **Vanilla JavaScript (ES6+)**
- **JSZip** (For handling Procreate `.swatches` archive parsing and export)
- **Google Fonts** (*Plus Jakarta Sans* & *Outfit*)
