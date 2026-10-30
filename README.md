# FotoLoco

Make a print-ready photobook in your browser. Drop in photos or whole folders and FotoLoco lays them out page by page, without cropping or stretching. You then export a 300 DPI PDF with bleed, ready for a print service.

**Live site:** https://ahmadhadi.github.io/fotoloco/

Everything runs in the browser. Photos are never uploaded anywhere.

## What it does

- Automatic layout: a book solver splits photos into pages and keeps folders together; a page solver arranges each page with even gaps and exact aspect ratios.
- Resize any photo by dragging a corner; the rest of the page refits and overflow moves to a new page.
- Rotate photos, crop them into shapes (square, circle, oval, arch, hexagon and more), and freely move, scale and straighten them inside the mask.
- Text boxes, a cover title and a subtitle, each with its own English and Arabic font, size, colour, bold, italic, underline, strikethrough, case, alignment, lists and spacing. Arabic is laid out right to left.
- Upload your own fonts (TTF, OTF, WOFF, WOFF2). They are used only in your browser.
- Folder tree, right-click menu, Spreads / Page / Grid views, page thumbnails, zoom and fullscreen.
- PDF export at 300, 200 or 150 DPI with bleed, plus warnings for low-resolution photos.

## Fonts

The site uses free fonts from Google Fonts. To use your own fonts, use **Upload your own font** in the app.

## Credits

The layout approach is inspired by [fotobuch](https://github.com/EddyXorb/fotobuch). PDFs are written with [jsPDF](https://github.com/parallax/jsPDF) (MIT), which is bundled in `index.html`.
