## Travel Escape (HTML/CSS)

Single-page travel landing built with only HTML and CSS. Destination cards open CSS-only overlays (checkbox toggle) to reveal five places per country with images and short descriptions.

- Responsive grid layout for hero, destination cards, and highlight pills
- CSS-only modal overlays per card (no JavaScript)
- External Unsplash images for hero and place photos

### Files

- `index.html` – markup and inline styles for the page and modals.
- `style.css` – extracted styles if you prefer linking externally (not required by default).

### Run

Open `index.html` in your browser (no build or server needed). Ensure you have an internet connection so the Unsplash images load.

### Customize

- Swap destination imagery and copy by editing the card and overlay sections in `index.html`.
- Adjust theme colors by changing the CSS variables in `index.html` or `style.css` (`--primary`, `--accent`, `--bg`, `--text`).
- Tweak layout or sizing by modifying the grid definitions and spacing in the CSS.

### Notes

- Overlays use the checkbox + label pattern; clicking the backdrop or “Close” label hides the modal.
- All styling is pure CSS; no external dependencies or scripts are required.
