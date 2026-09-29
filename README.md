<div align="center">

<img src="https://i.imgur.com/hHI2NFW.png" width="96"/>

# Elite Level ScreenCap
### Professional Screenshot & Image Annotation Tool
**by Elite Level Software**

[![Platform](https://img.shields.io/badge/Platform-Windows-blue?style=flat-square&logo=windows)](https://github.com/EliteLevelSoftware/Elite-Level-ScreenCap/releases)
[![Electron](https://img.shields.io/badge/Built%20With-Electron-47848F?style=flat-square&logo=electron)](https://www.electronjs.org/)
[![License](https://img.shields.io/badge/License-Proprietary-red?style=flat-square)](https://github.com/EliteLevelSoftware/Elite-Level-ScreenCap)
[![Release](https://img.shields.io/github/v/release/EliteLevelSoftware/Elite-Level-ScreenCap?style=flat-square&color=gold)](https://github.com/EliteLevelSoftware/Elite-Level-ScreenCap/releases)
[![Downloads](https://img.shields.io/github/downloads/EliteLevelSoftware/Elite-Level-ScreenCap/total?style=flat-square&color=gold&label=Downloads)](https://github.com/EliteLevelSoftware/Elite-Level-ScreenCap/releases)
[![Downloads (latest)](https://img.shields.io/github/downloads/EliteLevelSoftware/Elite-Level-ScreenCap/latest/total?style=flat-square&color=gold&label=Latest%20Release)](https://github.com/EliteLevelSoftware/Elite-Level-ScreenCap/releases/latest)

**[⬇️ Download the latest version](https://github.com/EliteLevelSoftware/Elite-Level-ScreenCap/releases/latest)**

</div>

---

## Overview

**Elite Level ScreenCap** is a professional-grade screenshot and image annotation tool built for power users. Capture any region of your screen, annotate it with a full set of drawing tools, apply effects, and export, all from a sleek, dark-themed interface.

The app ships as two tools in one:
- 🎯 **Elite Level ScreenCap**: the capture launcher. It lives in your system tray, always ready.
- 🖼️ **Elite Image Editor**: a full annotation editor that opens on its own or from the capture tool.

---

## 🆕 What's New in v1.1.0

- **PrintScreen takeover:** ScreenCap detects when another app or the Windows 11 Snipping Tool setting has taken the PrintScreen key, and can take it back automatically.
- **Captures always reach the editor**, even if you closed it.
- **Pixel-accurate region capture at any Windows scaling** (125%, 150% and mixed-DPI multi-monitor setups), at full native resolution.
- **Export and Copy keep your annotations editable.**
- **Undo/redo rewritten.** It now covers crop, rotate, erase, fill, typing and style changes.
- **Stronger redaction:** Blur/Redact now pixelates and blurs right to the edge.
- **Faster:** instant Recent/Library tabs and smoother drawing and dragging.
- **The tray popup no longer appears in screenshots.**

See the [v1.1.0 release notes](https://github.com/EliteLevelSoftware/Elite-Level-ScreenCap/releases/tag/v1.1.0) for the full list.

---

## Features

### 📸 Capture
- **Region Capture:** drag to select any area on one monitor or across several, with pixel-accurate results at any Windows display scaling.
- **Fullscreen Capture:** capture any display instantly.
- **Window Snapping:** hover over a window to snap the selection to its bounds. The visible, top-most window always wins.
- **Global Hotkeys:** `PrintScreen` for region, `Ctrl+PrintScreen` for fullscreen.
- **PrintScreen Takeover:** detects conflicts with the Windows Snipping Tool setting, ShareX, Greenshot, Lightshot, Snagit and others, and fixes them with one click or automatically.
- **Clipboard & Preview** toggles: copy straight to the clipboard or open in the editor.
- **Capture Delay** support.
- ScreenCap's own windows and popups hide before the capture fires, so they never appear in your screenshot.

### ✏️ Annotation Tools
| Tool | Description |
|------|-------------|
| Arrow | Directional arrows with adjustable width |
| Line | Straight lines |
| Rectangle | Filled or outlined rectangles |
| Rounded Rect | Rectangles with rounded corners |
| Ellipse | Circles and ovals |
| Triangle | Directional triangles |
| Diamond | Diamond shapes |
| Star | 5-point stars |
| Hexagon | Hexagonal shapes |
| Parallelogram | Slanted shapes |
| Callout | Speech bubble with pointer tail and inline text |
| Text | Free-form rich text with gradient, shadow and outline support |
| Step | Numbered circle step markers |
| Pen | Freehand drawing |
| Highlight | Semi-transparent highlighter |
| Blur / Redact | Pixelate + blur to hide sensitive info, right to the edge |
| Magnify | Zoom-lens annotations |
| Eraser | Pixel eraser |
| Crop | Region crop with a rule-of-thirds guide. Annotations move with the image. |
| Fill | Flood-fill colour regions |

### 🎨 Styling
- Solid, gradient (linear/radial) and per-annotation colour modes
- Fill colours, transparent by default
- Adjustable stroke width and opacity
- Drop shadows with colour, blur and a joystick control for direction
- Border/outline with separate colour and width controls, included in exports
- Bold, italic and underline text styles
- Custom font and font size selection
- Text alignment (left, centre, right)

### 🖼️ Image Adjustments & Effects
- Brightness, Contrast, Saturation, Hue, Blur, Sharpen and Temperature
- Vignette, Black & White and Colour Tint
- Image border, rounded corners, drop shadow, padding and watermark
- Non-destructive adjustments with live preview
- Rotate, flip and resize, with annotations transformed to match

### 📦 Editor
- Full undo/redo history for image edits and annotation changes
- Select, move and resize any annotation after placing it, including pen and highlighter strokes
- Double-click text annotations to edit them inline
- Shape Adjust Toolbar (SAT): per-annotation property controls
- Inline Text Toolbar (ITT): text-specific controls on selection
- Project library with thumbnails, plus session autosave and restore
- Non-destructive export: Copy, Save As PNG/JPG and drag-to-export never flatten your annotations

---

## Installation

Download **`Elite Level ScreenCap Setup x.x.x.exe`** from the [latest release](https://github.com/EliteLevelSoftware/Elite-Level-ScreenCap/releases/latest) and run it.

**Requirements:** Windows 10 or later (x64)

The installer creates two shortcuts:
- **Elite Level ScreenCap** launches the full app with the tray icon and capture tool.
- **Elite Image Editor** launches straight into the editor. It's single-instance, so it reuses ScreenCap if it's already running.

**Upgrading:** quit ScreenCap from the tray icon (right-click → *Quit Elite Level ScreenCap*), then run the new installer. Your captures, projects and settings are kept.

---

## Troubleshooting

**PrintScreen doesn't open ScreenCap**
Another app has probably taken the key. Right-click the tray icon and choose **Fix PrintScreen Hotkey…**. ScreenCap shows which app is using the key and can fix it for you. If the culprit was the Windows *"Use the Print screen key to open screen capture"* setting and the key still doesn't work, sign out and back in once.

**OneDrive or Dropbox screenshot saving**
These can't be closed safely, so turn off their screenshot feature instead:
- OneDrive → Settings → Backup → *Save screenshots I capture to OneDrive*
- Dropbox → Preferences → Backups → *Share screenshots using Dropbox*

---

## Keyboard Shortcuts

| Shortcut | Action |
|----------|--------|
| `PrintScreen` | Capture region |
| `Ctrl+PrintScreen` | Capture fullscreen |
| `Enter` | Confirm the region selection |
| `Escape` | Cancel/reset current operation |
| `Ctrl+Z` | Undo |
| `Ctrl+Y` | Redo |
| `Ctrl+C` | Copy image to clipboard |
| `Ctrl+S` | Save As |
| `F12` | Toggle DevTools |

---

## License

© 2025–2026 Elite Level Software. All rights reserved.

This software is proprietary. Redistribution or modification without written permission from Elite Level Software is prohibited.

---

<div align="center">
  Made with ❤️ by <strong>Elite Level Software</strong>
</div>
