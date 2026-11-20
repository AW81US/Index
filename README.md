================================================================================

CHROMATIK

Palette Lab & Procreate Command Engine

https://chromatik.neocities.org/

================================================================================



OVERVIEW

Chromatik is a single-file, browser-based color palette studio, accessibility

auditor, and Procreate swatch engine. Built with zero build-step dependencies,

it gives digital artists, illustrators, and UI/UX designers a complete 30-slot

palette workspace, perceptual OKLab/OKLCH and CIEDE2000 color math, vision

extraction, real-time UI mockups, and multi-format exports.



KEY FEATURES



1. 30-Slot Palette Grid & Quick 5-Swatch Bar

   - Drag-and-drop swatch reordering, Shift+Click range selection, and

     Ctrl/Cmd+Click multi-selection.

   - Individual slot locking to protect key colors during randomization,

     sorting, inversion, or global shifts.

   - Synced Quick 5-Swatch Bar (Slots 1-5) with curated trending palettes.

   - Smart palette actions: Invert unlocked swatches, Harmonize to active

     harmony offsets, Fill Empty slots, and Interpolate gap slots in OKLab.

   - Live Harmony & Balance Analyzer tracking average saturation and brightness,

     warm/cool ratios, and lowest-contrast swatch pairs.



2. Color Lab Matrix & Perceptual Scales

   - Precision editing across HEX, RGB, and HSB sliders and numeric inputs, with

     live readouts for HEX, RGB, HSL, CMYK, and OKLCH.

   - Automated human color naming, color psychology notes, and nearest standard

     color matches via CIEDE2000 (Delta-E00).

   - Instant generation and grid deployment of 10-step Tailwind Scales, 10-step

     Hue strips, and 10-step Tones & Shades matrices.

   - Interactive Harmony Wheel supporting Analogous, Complementary, Split-Comp,

     Triadic, and Tetradic harmonies.

   - 10-slot Pin Matrix for temporary color staging.



3. Accessibility, Contrast Matrix & Color Vision Simulator

   - Live viewport simulation for Protanopia, Deuteranopia, Tritanopia, and

     Achromatopsia.

   - Real-time WCAG 2.1 contrast ratio checks and APCA (WCAG 3.0) Lc lightness

     scores against light (#F8FAFC) and dark (#090D16) backgrounds.

   - Full N x N Contrast Matrix with AA/AAA filtering and click-to-inspect

     foreground/background pairing.

   - CVD palette conflict scanner flagging low-difference swatch pairs.



4. Advanced Studio Tools (12 Tabs & Live HTML Preview)

   - Multi-Stop Gradient Builder: Linear, radial, and conic CSS gradients with

     OKLab sampling into 10, 20, or 30 grid slots and copyable CSS output.

   - Tonal Ramp Generator: Black -> Color -> White, Dark -> Light, Tints, and

     Shades ramps in OKLab space.

   - Hue Step Matrix (H000-H350 & BW_NEUTRAL): Structured multi-step hue and

     grayscale matrices.

   - AI Prompt Palette Synthesizer: Deterministic mood- and keyword-driven

     palettes across Vibrant, Pastel, Darkmode, Earthy, and Luxury profiles.

   - Vision Extraction Engine: Upload local images or fetch URLs with zoom,

     pan, pixel loupe sampling, and mood-weighted auto-extraction.

   - Master Color Themes Catalog: Categorized collections (Seasonal, Natural &

     Biological, Materials, Painting Mediums, Atmospheric, Culinary, Eras,

     Interfaces, Metals, Nature, Neon, and Skin Tones) with live search and a

     Warm-to-Cool temperature slider.

   - Project Archive: LocalStorage folder-based palette library.

   - UI Mockup & Live HTML Preview Mode: Real-time brand/UI mockup with role

     mapping (Canvas BG, Card Surface, Primary CTA, Secondary, Typography),

     dark/light polarity toggle, OKLCH contrast snapping, desktop/tablet/mobile

     viewports, skin tone matrix cards, and standalone HTML/CSS theme export.

   - Perceptual Color Mixer & Blender Lab: 2- or 3-color blending across OKLCH,

     OKLab, Linear sRGB, and sRGB with bias and step controls.

   - Nearest Standard Color Matcher: Batch CIEDE2000 matching against 148 CSS

     and studio reference colors with one-click snapping.



5. Import, Export & Sharing

   - Procreate (.swatches): Direct import and export of native Procreate swatch

     archives (powered by JSZip).

   - Adobe Swatch Exchange (.ASE): Binary .ase export for Photoshop,

     Illustrator, and InDesign.

   - Developer & Design Formats: HEX, RGB, HSL, OKLCH, CSS Variables, SCSS

     Variables, Tailwind Config, W3C / Figma Design Tokens (.json), GIMP/

     Inkscape/Krita (.gpl), SVG Swatch Strip, JSON, and high-res PNG swatch

     cards, plus paste-to-import hex support.

   - Shareable URLs: Hash-based palette sharing (#p=...).



GETTING STARTED

No installation, package manager, or local build server is required.



1. Download or clone this repository.

2. Open "Chromatik Computer.html" in any modern web browser (Chrome, Edge,

   Firefox, or Safari).

3. Start building palettes immediately, or click "Load" to import an existing

   Procreate .swatches archive.



Note: Exporting and importing Procreate .swatches files uses JSZip loaded via

CDN. Core palette editing and local tools work offline once cached or opened

locally, though external image URLs and Google Fonts require network access.



KEYBOARD SHORTCUTS

SPACE              Randomize all unlocked swatches

?                  Open or close the Keyboard Shortcuts modal

1 - 9              Jump directly to Palette Slots 1 through 9

Ctrl / Cmd + Z     Undo last action

Ctrl / Cmd + Y     Redo action

Ctrl / Cmd + Shift + Z

                   Redo action (alternative)

Shift + Click      Select a range of swatches

Ctrl / Cmd + Click Toggle individual swatches in multi-selection

Right-Click        Clear an unlocked slot or pin

ESC                Close modal or clear multi-selection



UI THEMES

Chromatik includes 5 warm-to-cool workspace themes accessible via the header

temperature scroller:

- Ember (Warm Dark)

- Sand (Warm Light)

- Neutral (Balanced Dark)

- Cobalt (Cool Dark - Default)

- Glacier (Arctic Dark)



DEPENDENCIES

- JSZip v3.10.1 (CDN) - Packing and unpacking Procreate .swatches archives.

- Google Fonts (Plus Jakarta Sans & Outfit) - UI typography.



LICENSE

MIT License

================================================================================
