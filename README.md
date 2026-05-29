# Monasterium

A paged reader for markdown documents — an installable web app.

Choose a folder on your device, tap a document, and read it as paged
spreads you swipe through (left/right), rather than a continuous scroll.
Dark violet theme, white text with a black outline.

## Install on Android

1. Open the hosted URL in Chrome.
2. Chrome menu → **Install app** (or "Add to Home screen").
3. Launch **Monasterium** from your home screen. It runs standalone and
   works offline.

Your markdown files are read locally on the device through the folder
picker; nothing is uploaded.

## Font

The app requests **MS Gothic**, falling back to Noto Sans JP. To use the
real MS Gothic, place `msgothic.ttf` (or `.ttc`) beside `index.html`.

## Reading gestures

- Swipe left / tap right half → next page
- Swipe right / tap left half → previous page
- `‹` (top-left) → back to the library
