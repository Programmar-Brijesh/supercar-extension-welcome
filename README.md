<div align="center">
  <h1>Supercar Live Wallpaper 4K</h1>
  <p><strong>RACING NEW TAB WITH VOICE & CURSOR EFFECTS</strong></p>

  <a href="https://chrome.google.com/webstore/detail/EXTENSION_ID" target="_blank">
    <img src="https://img.shields.io/badge/Chrome%20Web%20Store-Available%20Soon-00e5ff?style=for-the-badge&logo=google-chrome&logoColor=white&labelColor=0a0e14" alt="Chrome Web Store">
  </a>
  <br>
  <img src="https://img.shields.io/badge/version-1.0-00e5ff?style=flat-square" alt="Version">
  <img src="https://img.shields.io/badge/manifest-v3-blue?style=flat-square" alt="Manifest">
  <img src="https://img.shields.io/badge/license-MIT-00e5ff?style=flat-square" alt="License">
  <img src="https://img.shields.io/badge/privacy-policy-0a0e14?style=flat-square&logo=shieldsdotio&logoColor=white" alt="Privacy">
</div>

<br>

> Transform every new tab into a high‑octane cockpit. Live 4K wallpapers, HUD stats, voice commands, and futuristic cursor effects – all stored locally, no sign‑up required.

---

## Table of Contents

- [Features](#features)
- [Demo](#demo)
- [Installation](#installation)
- [How It Works](#how-it-works)
- [Voice Commands](#voice-commands)
- [Customization](#customization)
- [Privacy & Permissions](#privacy--permissions)
- [Tech Stack](#tech-stack)
- [Changelog](#changelog)
- [Roadmap](#roadmap)
- [Support](#support)
- [License](#license)

---

## Features

| Category | Details |
|----------|---------|
| **Live Wallpapers** | 4K Formula Racing and Digital Matrix video loops. Seamless playback with no stutter. |
| **Smart Clock Widget** | Personalised greeting ("Good Morning, Driver"), live time and date. Name is stored locally. |
| **Intelligent Search** | Dual‑mode search bar: detects URLs and opens directly, otherwise searches Google. |
| **HUD Gauges** | Animated RPM (7000‑9800) and Speed (280‑360 km/h). Purely aesthetic but immersive. |
| **Magnetic Quick‑Dock** | Add up to 12 favourite sites. Icons auto‑fetch via Google Favicons. Hover lift effect. |
| **Voice Commander** | Jarvis‑style voice recognition. Activate by clicking the AI orb. Supports 20+ commands. |
| **Cursor Effects** | 5 futuristic cursor trails: Cyber Trail, Neon Particles, Matrix Code, HUD Ring, Lightning Flow. |
| **Customize Mode** | Drag, resize, show/hide every widget. Layout is auto‑saved per device. |
| **Offline Ready** | All assets (videos, scripts) are bundled. Works perfectly without internet (except voice). |
| **Incognito Support** | Optional incognito mode via Chrome settings. Spanning mode for seamless experience. |

---

## Demo

*Add a GIF or video link showing the extension in action.*

![Dashboard Screenshot](images/dashboard-preview.png)

---

## Installation

1. Install from the [Chrome Web Store](#) (link coming soon).
2. Open a **New Tab** – the dashboard loads immediately.
3. (Optional) Enter your name in the welcome popup.
4. To use in Incognito: go to `chrome://extensions`, find the extension, and enable **Allow in Incognito**.

---

## How It Works

The extension overrides Chrome's new tab page (`chrome_url_overrides`) with a self‑contained HTML dashboard. All personalization data is stored in `localStorage` and never leaves your device. Voice commands are processed by the browser's built‑in **Web Speech API**, which streams audio to Google's cloud for transcription. The extension does **not** record or store any audio.

---

## Voice Commands

| Command | Action |
|---------|--------|
| `"Open YouTube"` | Opens YouTube in a new tab |
| `"Open GitHub"` | Opens GitHub |
| `"Open ChatGPT"` | Opens ChatGPT |
| `"Open Gmail"` | Opens Gmail |
| `"Formula wallpaper"` | Switches to Formula Racing background |
| `"Matrix wallpaper"` | Switches to Matrix background |
| `"Cyber trail"` | Enables cursor effect |
| `"Neon particles"` | Enables cursor effect |
| `"Matrix code"` | Enables cursor effect |
| `"HUD ring"` | Enables cursor effect |
| `"Lightning flow"` | Enables cursor effect |
| `"Show clock"` / `"Hide clock"` | Toggles clock widget |
| `"Show stats"` / `"Hide stats"` | Toggles HUD stats |
| `"Show search"` / `"Hide search"` | Toggles search bar |
| `"Show dock"` / `"Hide dock"` | Toggles quick‑dock |
| `"Customize mode"` | Enables drag‑and‑drop layout editing |
| `"Open settings"` / `"Close settings"` | Opens/closes settings panel |

> **Privacy:** Voice input is processed by Google's Speech‑to‑Text API. No audio is recorded or stored by the extension.

---

## Customization

- **Drag widgets** using the handle to reposition.
- **Resize** by pulling the right edge (scales content).
- **Toggle visibility** of clock, stats, search, dock, and customize mode.
- **Reset layout** from settings to restore default positions.
- All preferences persist across sessions automatically.

---

## Privacy & Permissions

| Permission | Why it's needed |
|------------|-----------------|
| `audioCapture` | Optional voice assistant. Only active after user clicks the AI orb. |

**Data Storage:**
- Display name, layout positions, wallpaper choice, dock shortcuts, cursor mode.
- All stored **exclusively** in `localStorage`. No external servers.
- Clear data anytime by resetting the dashboard or uninstalling the extension.

[Full Privacy Policy](https://supercar-extension-welcome.netlify.app/privacy)

---

## Tech Stack

- **Manifest V3** – latest Chrome extension standard
- **Vanilla JavaScript** – zero dependencies (except Interact.js for dragging)
- **Interact.js** – lightweight drag/resize library
- **HTML5 Video** – hardware‑accelerated background playback
- **CSS Custom Properties** – all colours and effects are CSS variables
- **Web Speech API** – native browser speech recognition

---


---

## Changelog

### v1.0 (Initial Release)
- 4K live wallpapers (Formula Racing, Matrix)
- Clock & greeting widget
- Google search bar
- HUD RPM & speed
- Magnetic quick‑dock (add/remove)
- Voice assistant with 20+ commands
- 5 cursor trail effects
- Draggable, resizable widgets
- Customize mode
- Incognito support
- Full offline capability
- Local storage, no tracking

---

## Roadmap

- [ ] Additional wallpapers (Cyberpunk City, Neon Lamborghini)
- [ ] Weather widget integration
- [ ] To‑do / notes panel
- [ ] Custom search engine selection
- [ ] Sync settings across devices (optional)
- [ ] Dark/Light theme toggle
- [ ] Animated icon shortcuts
- [ ] Multi‑language support



## Support

- [Landing Page](https://supercar-extension-welcome.netlify.app)
- [Privacy Policy](https://supercar-extension-welcome.netlify.app/privacy)
- [Report an Issue](https://github.com/yourusername/supercar-extension/issues)

---

## License

Distributed under the MIT License. See `LICENSE` for more information.

---

<div align="center">
  <sub>Built with precision by <strong>Developer Brijesh</strong></sub>
</div>
