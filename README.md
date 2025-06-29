# Qdrant Browser

A simple, single-file, web-based UI for browsing, searching, and managing [Qdrant](https://qdrant.tech/) vector database collections and points.

## Features

- **Single HTML file:** No build step, no dependencies—just open in your browser.
- List all Qdrant collections
- View, search, and filter points (vectors and payloads)
- Create new collections with custom vector size
- Delete collections and individual points
- View collection configuration (with modal dialog)
- Light/Dark mode toggle (remembers your preference)
- Auto-refresh collections panel (customizable interval)
- Settings modal to change Qdrant server URL (persists in local storage)
- Fast client-side search across all fields (ID, vector, payload)
- Expand/collapse collections
- Responsive, accessible UI
- Works with any modern browser

## Usage

1. **Start your Qdrant server** (default: `http://localhost:6333`).
2. Open `qdrant browse.html` in your browser.
3. Use the UI to manage your collections and points.

> **Note:** This tool connects to Qdrant at `http://localhost:6333` by default.  
> To use a different Qdrant server, click the ⚙️ Settings button and enter your Qdrant URL.

## Requirements

- Qdrant server running and accessible from your browser
- Modern web browser (Chrome, Firefox, Edge, Safari)

## Screenshots

![Qdrant Browser Screenshot](https://github.com/johnelder/qdrant-browser/blob/main/Screenshot%202025-06-28%20173833.png)

## License

MIT License

---

**Not affiliated with Qdrant.**  
For more information about Qdrant, visit [qdrant.tech](https://qdrant.tech/).