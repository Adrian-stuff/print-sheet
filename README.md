# RushID

**ID & Passport Photo Layout Maker** — one square photo, cropped, sized, and laid out with cut marks on your paper of choice. Runs entirely in your browser. Nothing is uploaded anywhere.

## Features

- **Drop-in upload** — drag & drop or click to select a JPG/PNG. Automatically center-crops to a square canvas.
- **Paper sizes** — Letter, Legal, A4, A5, 4R (4×6 in), 5R (5×7 in), 8R (8×10 in). Choose portrait or landscape orientation.
- **Standard photo sizes** — 1×1, 2×2, 2×3, 2.5×3.5 (wallet), 3×4, 3.5×4.5, 4×6, 5×7 inches. Each is centre-cropped from your source to fill its frame.
- **Custom sizes** — add any width/height/quantity combination.
- **Smart packing** — items are sorted largest-first and packed onto sheets row by row, with optional margins and cut gaps. Sheets that overflow wrap to additional pages.
- **Live preview** — see the layout build in real time with SVG cut marks at every corner.
- **PDF export** — generates a print-ready PDF (correct paper dimensions, orientation, images, cut marks) for direct printing.

## Usage

1. Click **Upload** (or drag a photo onto the drop zone).
2. Pick a **paper size** and **orientation**.
3. Adjust **margin** and **cut gap** as needed.
4. Enable the sizes you want and set quantities. Add custom sizes if needed.
5. Review the layout in the preview.
6. Click **Generate PDF** to download.

## Requirements

None — everything runs in a modern browser. The only external dependency is [jsPDF](https://github.com/parallax/jsPDF) loaded from a CDN.

## Files

- `index.html` — single-file app containing all HTML, CSS, and JavaScript.
