# Teleprompter

A single-page, browser-based teleprompter. Uses your device camera as a live
background and scrolls your script over it, so you can record with a phone
or webcam without extra hardware.

## Features

- Live camera preview with front/back camera switching
- In-app video recording (records the camera feed, saved as a downloadable file)
- Countdown before the first start, so you have time to get in position
- Scrolling script overlay with adjustable speed and text size (tap or hold
  the − / + buttons, or type a value)
- Mirror mode (for use with physical teleprompter rigs/beam splitters)
- Center guide line for eye-level reading
- Fullscreen mode
- Tap-to-edit script sheet; controls auto-hide while playing
- Load script from a `.txt`, `.md`, or `.docx` file
- Double-tap to reset scroll to the top
- Keyboard shortcuts: Space to play/pause, R to restart

## Usage

Open `index.html` in a browser (camera access requires either `localhost`
or HTTPS). Grant camera permission when prompted, tap the pencil icon to
paste in your script, then tap **Start** to begin scrolling. Use the record
button to capture video while you read.

No build step or dependencies — it's a single static HTML file.

## Design

Styled with the Picaloid Studios web UI kit (`brand-identity/brand/web`).
The design tokens used here are copied inline at the top of the `<style>`
block in `index.html`; keep them in sync with `tokens.css` when the brand kit
changes. Fonts (Inter, Inter Tight) load from Google Fonts and fall back to
the system font offline.
