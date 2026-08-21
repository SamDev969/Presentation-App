# SAMDEV Studio — Worship Presentation Engine

![SAMDEV Studio Logo](logo.png)

An ultra-fast, modern, client-side web application built for church worship presentation, song lyrics projection, KJV Scripture lookups, presentation schedules, and PowerPoint (.pptx) slide extraction. Designed to look and feel like professional broadcast software.

---

## ✨ Features

- 🎵 **Worship Song Library**: Create, organize, and present worship song lyrics with automatic text fitting and live slide switching.
- 📖 **KJV Bible Search**: Built-in KJV Bible search engine with book autocompletion and passage fetching powered by `bible-api.com`.
- 📊 **PowerPoint (.pptx) Extraction**: Import `.pptx` presentation files directly on the client side using pure JavaScript.
- 🖥️ **Dual Monitor & Stage Display**: Open an extended broadcast window (`F8`) that syncs live output onto projectors or secondary screens.
- 🔴 **Live Stream Control**: One-key live stream control (`F5`) with visual status indicators, pulsing ON AIR badges, and telemetry.
- 🎨 **Theme & Layer Management**: Toggle between Pitch Black, Ocean Gradient, or custom uploaded image and video media layers.
- 📐 **Resizable Professional Workspace**: Custom column width adjustment with draggable handles between panels.
- ⏱️ **Live Clock & Telemetry Footer**: Fixed bottom footer displaying real-time system clock, active deck slide count, and stage display status.
- 💾 **Offline Persistence**: Automatically saves your database, custom themes, and service schedule locally in `localStorage`.

---

## ⌨️ Keyboard Shortcuts

| Shortcut | Description |
|---|---|
| `<kbd>F5</kbd>` | Toggle Live Output Stream (Go Live / Cut) |
| `<kbd>F8</kbd>` | Toggle Stage / Broadcast Output Window |
| `<kbd>Esc</kbd>` | Instantly Clear Live Presentation Output (Black Screen) |
| `<kbd>↓</kbd>` / `<kbd>PageDown</kbd>` | Next Slide (when Live) |
| `<kbd>↑</kbd>` / `<kbd>PageUp</kbd>` | Previous Slide (when Live) |

---

## 🚀 Getting Started

No installation or build step is required!

1. Clone or download this repository.
2. Open `index.html` in any modern web browser (Chrome, Edge, Firefox, Brave, Safari).
3. Select or add song lyrics / Bible passages to your library, add them to your **Service Order**, and hit **Go Live (F5)**!

---

## 🛠️ Technology Stack

- **Frontend**: Pure HTML5, CSS3 (Glassmorphism, CSS Grid, CSS Variables), Modern JavaScript (ES6+).
- **Presentation Parser**: [JSZip](https://cdnjs.cloudflare.com/ajax/libs/jszip/3.10.1/jszip.min.js) for parsing PowerPoint `.pptx` XML archives.
- **Scripture API**: [bible-api.com](https://bible-api.com/) for KJV Scripture passages.

---

## 📄 License

This project is licensed under the MIT License. Created by **Adebayo Samuel Oluwaseun (SAMDEV)**.
