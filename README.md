# RushID

**ID & Passport Photo Layout Maker** — one square photo, cropped, sized, and laid out with cut marks on your paper of choice. Runs entirely in your browser. Nothing is uploaded anywhere.

## Features

- **Multi-photo upload** — drag & drop or click to select one or more JPG/PNGs. Automatically center-crops each to a square canvas. Assign different photos to different sizes to mix several people/photos on one sheet.
- **Manual crop & zoom** — reposition and zoom any uploaded photo in a dedicated crop editor before it's laid out.
- **ID presets** — one-click common passport/visa/ID photo specs by country or document type (US, UK/EU, India, China, Canada, Japan, Australia, South Korea).
- **Paper sizes** — Letter, Legal, A4, A5, 4R (4×6 in), 5R (5×7 in), 8R (8×10 in). Choose portrait or landscape orientation.
- **Standard photo sizes** — 1×1, 2×2, 2×3, 2.5×3.5 (wallet), 3×4, 3.5×4.5, 4×6, 5×7 inches. Each is centre-cropped from your source to fill its frame.
- **Custom sizes** — add any width/height/quantity combination.
- **Smart packing** — items are sorted largest-first and packed onto sheets row by row, with optional margins and cut gaps. Sheets that overflow wrap to additional pages.
- **Live preview** — see the layout build in real time with SVG cut marks at every corner.
- **PDF export** — generates a print-ready PDF (correct paper dimensions, orientation, images, cut marks) for direct printing.
- **Remembers your settings** — paper size, orientation, margins, sizes, and custom sizes are saved locally between visits.

## Usage

1. Click **Upload** (or drag one or more photos onto the drop zone). Use **adjust crop** to reposition/zoom any photo.
2. Optionally pick an **ID preset** for a specific country/document size, or enable/add sizes manually.
3. If you uploaded multiple photos, assign which photo each size should use from its dropdown.
4. Pick a **paper size** and **orientation**, and adjust **margin** and **cut gap** as needed.
5. Review the layout in the preview.
6. Click **Generate PDF** to download.

## Requirements

None — everything runs in a modern browser. The only external dependency is [jsPDF](https://github.com/parallax/jsPDF) loaded from a CDN.

## Files

- `index.html` — single-file app containing all HTML, CSS, and JavaScript.
