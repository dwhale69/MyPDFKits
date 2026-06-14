# MyPDFkits

A free, premium, **100% browser-based** PDF toolkit. Nine tools, zero servers — your files never leave your device.

> Edit · Merge · Split · Compress · Convert · Annotate · Sign · Protect · Watermark

## Why

Editing PDFs on the web usually means uploading sensitive documents to someone else's server. MyPDFkits runs entirely client-side using [pdf-lib](https://pdf-lib.js.org/) and [PDF.js](https://mozilla.github.io/pdf.js/), so nothing is ever uploaded.

## Tools

| Tool | What it does |
|------|--------------|
| **Edit** | Add text, images, and shapes directly onto pages |
| **Merge** | Combine multiple PDFs, drag to reorder |
| **Split** | Extract pages or ranges into new files |
| **Compress** | Reduce file size, strip metadata |
| **Convert** | PDF ↔ images (PNG / JPG) |
| **Annotate** | Highlight, draw, add notes and arrows |
| **Sign** | Draw or type a signature and place it |
| **Protect** | Password + permission restrictions |
| **Watermark** | Text or image watermark across all pages |

## Design

Premium monochrome (black & white), fully responsive on mobile and desktop, no frameworks, no build step.

## Deploy

This is a static site — deploy it anywhere.

**Netlify (drag-and-drop):** drag this folder onto <https://app.netlify.com/drop>.

**Netlify (Git):** connect the repo; no build command needed (`publish = "."`).

**GitHub Pages:** Settings → Pages → deploy from branch root.

## Local preview

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

## Stack

Vanilla HTML / CSS / JS · pdf-lib · PDF.js · zero dependencies, zero tracking.

## License

MIT
