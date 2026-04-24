# FotoText

Extract text from images using OCR directly in your browser. No server required.

## Features

- **Image Upload** — Click, drag-and-drop, or paste (Ctrl+V) images
- **Crop & Extract** — Select a region of the image before running OCR
- **OCR Language Selection** — 24 language options including English + Chinese, Japanese, Arabic, Hindi, and more
- **Symbol Detection** — Toggle to better recognize special characters and symbols
- **Handwriting Mode** — Pre-processes images with contrast enhancement and binarization for handwritten text
- **Translation** — Translate extracted text into 20+ languages using MyMemory API
- **Copy to Clipboard** — One-click copy for both extracted and translated text

## Usage

Open `index.html` in any modern browser. No build step or server needed.

## Tech

- [Tesseract.js v5](https://github.com/naptha/tesseract.js) — OCR engine
- [Cropper.js](https://github.com/fengyuanchen/cropperjs) — Image cropping
- [MyMemory API](https://mymemory.translated.net/) — Translation

## License

MIT