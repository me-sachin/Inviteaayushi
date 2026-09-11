# Aayushi & Sachin Ring Ceremony Invitation

A single-file HTML invitation for Aayushi & Sachin's ring ceremony.

## Features
- Original invitation design preserved.
- Flute music embedded directly inside `index.html`.
- Music loops continuously while playing.
- Top-right **🔊 Stop Music** control.
- Click the control to switch to **🔇 Play Music** and resume playback.
- No separate image or MP3 file is required.
- Designed to work on older browsers as far as browser autoplay policies allow.

## Run locally
Open `index.html` in a browser.

## GitHub Pages
1. Create a GitHub repository.
2. Upload `index.html` and this `README.md`.
3. Open **Settings → Pages**.
4. Select **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`.
6. Save and open the generated GitHub Pages URL.

### Music autoplay note
Modern browsers can block audible autoplay until the visitor interacts with the page. The invitation attempts autoplay and also starts the music on the first touch/click/keypress when the browser blocks autoplay. After playback starts, it loops until the visitor presses **Stop Music**.
