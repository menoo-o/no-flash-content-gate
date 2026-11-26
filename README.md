# Content Gating Architecture Demo

A front-end and system-design sandbox exploring how client-side "flash-and-lock" paywalls leak content in the DOM, why teams make that trade-off, and how to architect a zero-flash, SEO-safe split gate.

## Project Structure


- **`01-seo-server-gated-split/`**: Demonstrates the production-grade pattern—keeping `<title>`, meta tags, `<h1>`, and opening teaser paragraphs public for search crawlers while withholding restricted body paragraphs until access is verified.

## How to Run Locally

No build step or dependencies required:
1. Open any `index.html` file directly in your browser, or run a local static server (e.g., VS Code Live Server or `npx serve .`).
2. Open DevTools (`F12`) to inspect DOM states and test `console-unlock.js` on Demo 01.