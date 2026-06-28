# FotoText

Extract text from images using OCR directly in your browser.

## Features

- **Image Upload** — Click, drag-and-drop, or paste (Ctrl+V) images
- **Crop & Extract** — Select a region of the image before running OCR
- **OCR Language Selection** — 24 language options including English + Chinese, Japanese, Arabic, Hindi, and more
- **AI-Powered Polish** — Uses DeepSeek V4 Pro to correct OCR errors and improve formatting (optional API key)
- **Symbol Detection** — Toggle to better recognize special characters and symbols
- **Handwriting Mode** — Pre-processes images with contrast enhancement and binarization for handwritten text
- **Translation** — Translate extracted text into 20+ languages using MyMemory API
- **Copy to Clipboard** — One-click copy for both extracted and translated text
- **Save & Load** — Save extracted texts to your account and load them later

## Usage

Open `index.html` or visit [fototext.leokontakt.de](https://fototext.leokontakt.de). Register an account to save texts. Optionally add a [DeepSeek API key](https://platform.deepseek.com/api_keys) in Settings for AI-powered OCR correction.

## Tech

- [Tesseract.js v5](https://github.com/naptha/tesseract.js) — OCR engine
- [Cropper.js](https://github.com/fengyuanchen/cropperjs) — Image cropping
- [DeepSeek API](https://api-docs.deepseek.com/) — AI text correction (DeepSeek V4 Pro)
- [MyMemory API](https://mymemory.translated.net/) — Translation
- Flask + JSON storage — Backend for auth and saved texts

## License

MIT