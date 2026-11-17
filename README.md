# Rakshi Kanwar — Portfolio & Resume

Personal portfolio and curriculum vitae website for Rakshi Kanwar (English Literature & Digital Humanities at Christ University, Digital Business & Entrepreneurship at IIM Bangalore).

Inspired by modern editorial web craft and publication-style layouts.

## Project Structure

```text
├── index.html       # Semantic HTML5 markup, OpenGraph metadata, JSON-LD schema
├── styles.css       # Design tokens, fluid clamp typography, dark mode, print stylesheet
├── script.js        # Theme toggle, mobile drawer, scroll spy, clipboard actions, IST clock
├── .gitignore       # System and editor ignore rules
└── README.md        # Documentation
```

## Features

- **Typography & Grid**: Typeset in *Instrument Serif*, *Inter*, and *IBM Plex Mono* across a responsive 12-column editorial grid.
- **Color Themes**: Light and dark themes with system preference detection and persistent state via `localStorage`.
- **Print / PDF Generation**: Custom `@media print` rules format the Curriculum Vitae section into a clean A4 resume when clicking "Save as PDF" or running `window.print()`.
- **Accessibility & Semantics**: WCAG compliant markup, skip links, ARIA attributes, and reduced motion respect (`prefers-reduced-motion`).
- **Interactive UI**: One-click email copy with toast feedback, live Bangalore time display, active navigation scroll spy, and smooth reveals.
- **Zero Dependencies**: Pure vanilla HTML, CSS, and modern JavaScript.

## Local Development

Run with any local static HTTP server:

```bash
# Using Python
python3 -m http.server 8000

# Using Node / npx
npx serve .
```

Open `http://localhost:8000` in your browser.

## Deployment

### GitHub Pages
1. Push this repository to GitHub.
2. In your repository, navigate to **Settings** > **Pages**.
3. Under **Build and deployment** > **Source**, choose `Deploy from a branch`.
4. Select `main` branch and `/ (root)` folder, then save.
5. Your site will be live at `https://<username>.github.io/<repo-name>/`.

### Vercel
1. Push this repository to GitHub.
2. Go to [vercel.com](https://vercel.com) and click **Add New Project**.
3. Import the repository.
4. Keep the default settings (Framework Preset: *Other*) and click **Deploy**.
