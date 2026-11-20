================================================================================

CHROMATIK

Palette Lab & Procreate Command Engine

https://chromatik.neocities.org/

================================================================================



OVERVIEW

--------------------------------------------------------------------------------

Chromatik is a single-file, browser-based color palette studio, accessibility

auditor, and Procreate swatch engine. Built with zero build-step dependencies,

it provides digital artists, illustrators, and UI/UX designers with a complete

30-slot palette workspace, perceptual OKLCH/OKLab color math, vision extraction,

and multi-format exports.





KEY FEATURES

--------------------------------------------------------------------------------

1. 30-Slot Palette Grid & Quick 5-Swatch Bar

   - Drag-and-drop swatch reordering, Shift+Click range selection, and

     Ctrl/Cmd+Click multi-selection.

   - Individual slot locking to protect key colors during randomization,

     sorting, inversion, or global shifts.

   - Synced Quick 5-Swatch Bar (Slots 1-5) with curated trending palettes.

   - Real-time Harmony & Balance Analyzer tracking average saturation,

     brightness, warm/cool ratios, and lowest-contrast swatch pairs.



2. Color Lab Matrix & Perceptual Scales

   - Precision editing across HEX, RGB, and HSB sliders/inputs.

   - Automated human color naming and color psychology notes.

   - Instant generation of 10-step Tailwind Scales, 10-step Hue shifts, and

     30-step OKLab Tones & Shades matrices.

   - Interactive Harmony Wheel supporting Analogous, Complementary, Split

     Complementary, Triadic, Tetradic, and Monochrome harmonies.

   - 10-slot Pin Matrix for temporary color staging.



3. Accessibility & Color Vision Simulator

   - Live viewport simulation for Protanopia, Deuteranopia, Tritanopia, and

     Achromatopsia.

   - Real-time WCAG contrast ratio checks (AA / AAA) against light (#F8FAFC)

     and dark (#090D16) backgrounds.

   - Automated Delta-E palette conflict scanner to flag indistinguishable

     color pairs under color vision deficiencies.



4. Advanced Studio Tools

   - Multi-Stop Gradient Builder: Linear, radial, and conic CSS gradients with

     OKLab color sampling into 10, 20, or 30 grid slots.

   - Tonal Ramp Generator: Black-to-Color-to-White, Dark-to-Light, Tints, and

     Shades ramps in OKLab space.

   - Hue Step Matrix (H000-H350 & B&W): Structured 19-step saturation/brightness

     matrices every 25 degrees plus a 5% grayscale ramp.

   - AI Prompt Palette Synthesizer: Generates mood- and keyword-driven palettes

     across Vibrant, Pastel, Darkmode, Earthy, and Luxury profiles.

   - Vision Extraction Engine: Upload local images or fetch URLs with an

     interactive zoom/pan loupe and perceptual mood-weighted auto-extraction.

   - Master Color Themes Catalog: Over 12 categorized collections (Seasonal,

     Metals, Nature, Neon, Painting Mediums, and organized Skin Tones by

     Undertone, Monk 01-10 Scale, Fitzpatrick Types I-VI, and Complexion)

     with a live Warm-to-Cool temperature slider.

   - Live HTML Preview Mode: Full-screen preview stage displaying active

     swatches alongside organized skin tone matrices.



5. Import, Export & Persistence

   - Procreate (.swatches): Direct import and export of native Procreate

     swatch archives (powered by JSZip).

   - Adobe Swatch Exchange (.ASE): Binary .ase export for Photoshop,

     Illustrator, and InDesign.

   - Developer & Asset Formats: HEX, RGB, HSL, OKLCH, CSS Variables, SCSS

     Variables, Tailwind Config, SVG Swatch Strip, JSON, and high-res PNG

     swatch cards.

   - Project Archive & URL Sharing: LocalStorage folder archive and hash-based

     shareable palette URLs.





GETTING STARTED

--------------------------------------------------------------------------------

No installation, package manager, or local server is required.



1. Download or clone this repository.

2. Open `Chromatik Computer.html` in any modern web browser (Chrome, Edge,

   Firefox, Safari).

3. Start building palettes immediately—or click "Load" to import an existing

   Procreate `.swatches` file.



Note: Exporting/importing Procreate `.swatches` files uses JSZip loaded via

CDN. All other features work 100% offline.





KEYBOARD SHORTCUTS

--------------------------------------------------------------------------------

SPACE               Randomize all unlocked swatches

?                   Open / close Keyboard Shortcuts modal

1 - 9               Jump directly to Palette Slots 1 through 9

Ctrl / Cmd + Z      Undo last action

Ctrl / Cmd + Y      Redo action

Ctrl / Cmd + Shift + Z  Redo action (alternative)

Shift + Click       Select a range of swatches

Ctrl / Cmd + Click  Toggle individual swatches in multi-selection

Right-Click         Clear an unlocked slot or pin

ESC                 Close modal, exit Live Preview, or clear multi-selection





UI THEMES

--------------------------------------------------------------------------------

Chromatik includes 5 warm-to-cool workspace themes accessible via the header

temperature scroller:

- Ember   (Warm Dark)

- Sand    (Warm Light)

- Neutral (Balanced Dark)

- Cobalt  (Cool Dark - Default)

- Glacier (Arctic Dark)





DEPENDENCIES

--------------------------------------------------------------------------------

- JSZip v3.10.1 (CDN) - Used for packing and unpacking `.swatches` archives.

- Google Fonts (Plus Jakarta Sans & Outfit) - UI typography.





LICENSE

--------------------------------------------------------------------------------

MIT License

================================================================================
