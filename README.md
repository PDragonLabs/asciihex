# asciihex  site is live at https://pdragonlabs.github.io/asciihex/

A simple, self-contained HTML page that converts ASCII text to and from multiple encodings — inspired by [asciitohex.com](https://www.asciitohex.com/).

## Features

- **Bidirectional conversion** between plain text and:
  - Binary (space-separated 8-bit bytes)
  - Hexadecimal (space-separated bytes)
  - Base64
  - Decimal (space-separated character codes)
  - ROT13
  - URL Encoded (spaces as `+`)
  - HTML Entities
- One-click **Copy to clipboard** on every field
- Light / dark theme toggle (persists via `localStorage`)
- Pre-filled sample text
- Fully client-side — no backend required

## Usage

1. Open `ascii-to-hex.html` in any modern browser.
2. Edit the text in any field.
3. Click the corresponding **Convert from …** button to update all other fields.
4. Use the **Copy** buttons to copy results.

## File

- `ascii-to-hex.html` — the complete single-file converter

## License

Free to use and modify.
