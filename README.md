<div align="center">
  <img src="logo.png" width="96" height="96" alt="Lively Logo" />
  <h1>Lively</h1>
  <p><strong>A hardware-accelerated live wallpaper engine built natively for macOS.</strong></p>

  <p>
    <a href="https://github.com/vikas-6/lively-releases/releases/latest"><strong>Download for macOS</strong></a>
  </p>
</div>

---

### Overview

Lively brings animated video loops, high-resolution imagery, and dynamic photo slideshows directly behind your macOS desktop icons. Written entirely in native Objective-C using AppKit, Metal, and AVFoundation, it operates with zero runtime dependencies and minimal CPU and memory overhead.

### Key Capabilities

- **GPU-Accelerated Playback** — Native AVFoundation pipeline supports MP4, MOV, HEIC, PNG, JPG, WebP, TIFF, and animated GIF at high refresh rates (up to 120 Hz ProMotion).
- **Intelligent Resource Throttling** — Playback automatically suspends when active windows fully occlude the desktop, when applications enter fullscreen, or when running on battery power.
- **Multi-Display Architecture** — Independently renders and scales across all connected monitors with dynamic hotplug detection.
- **Folder Slideshow Engine** — Point to any local folder to cycle through background collections at configurable intervals with random shuffling.
- **Stealth Background Agent** — Operates entirely from the macOS menu bar with no Dock icon and negligible idle power draw.
- **Over-the-Air Updates** — Built-in cryptographic updater powered by Sparkle for seamless background version updates.

---

### Installation

1. Download the latest **[Lively.dmg](https://github.com/vikas-6/lively-releases/releases/latest)**.
2. Open the disk image and drag **Lively.app** to your **Applications** folder.
3. Launch Lively. Access controls and configuration from the menu bar icon.

---

### Requirements

| Specification | Details |
|---|---|
| Operating System | macOS 11.0 (Big Sur) or later |
| Architecture | Universal binary (Apple Silicon & Intel 64-bit) |
| Binary Size | Under 2 MB |

---

### Support

If you find Lively useful and would like to support ongoing development:

<br />

<a href="https://buymeacoffee.com/otterbtw_" target="_blank">
  <img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" height="46" />
</a>

<br /><br />

---

<div align="center">
  <sub>© 2026 Vikas. All rights reserved.</sub>
</div>
