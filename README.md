# PDF Editor

A fully local, browser-based PDF editor with signature support. No server required — runs entirely in your browser.

![PDF Editor](https://img.shields.io/badge/PDF-Editor-blue) ![License](https://img.shields.io/badge/license-MIT-green) ![No Backend](https://img.shields.io/badge/backend-none-orange)

## ✨ Features

- **📂 Open PDFs** — File picker or drag-and-drop
- **✍️ Signatures** — Draw, type (cursive), upload, or reuse saved signatures
- **T Text Annotations** — Click to place, drag to move, editable font size & color
- **🖊️ Pen & Highlighter** — Freehand drawing with configurable color & thickness
- **⬜ Eraser** — Remove drawn strokes
- **💾 Save PDF** — Exports a new PDF with all edits embedded
- **🌙 Dark Mode** — Toggle light/dark theme
- **↩️ Undo** — Full undo support for all actions
- **⌨️ Keyboard Shortcuts** — Fast workflow with hotkeys

## 🚀 Getting Started

Just open `index.html` in your browser. That's it — no install, no build, no server.

Or visit the **[live demo →](https://pdf-editor.vercel.app)**

## ⌨️ Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `Ctrl+O` | Open PDF |
| `Ctrl+S` | Save PDF |
| `Ctrl+Z` | Undo |
| `V` | Select tool |
| `T` | Text tool |
| `S` | Signature |
| `P` | Pen tool |
| `H` | Highlight tool |
| `E` | Eraser tool |
| `←` `→` | Previous/Next page |
| `Ctrl+=` / `Ctrl+-` | Zoom in/out |
| `Delete` | Remove selected annotation |

## 🛠️ Tech Stack

| Library | Purpose |
|---------|---------|
| [PDF.js](https://mozilla.github.io/pdf.js/) | Render PDF pages |
| [pdf-lib](https://pdf-lib.js.org/) | Modify & export PDFs |
| [Dancing Script](https://fonts.google.com/specimen/Dancing+Script) | Cursive font for typed signatures |
| Canvas API | Freehand drawing & signature pad |
| localStorage | Persist saved signatures |

## 📦 Deployment

This is a single static HTML file — deploy anywhere:

- **Vercel**: Just connect this repo
- **Netlify**: Drag and drop
- **GitHub Pages**: Enable in repo settings

## 📄 License

MIT — free to use, modify, and distribute.
