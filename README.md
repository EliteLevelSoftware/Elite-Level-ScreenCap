<div align="center">

<img src="https://i.imgur.com/hHI2NFW.png" width="96"/>

# Elite Level ScreenCap
### Professional Screenshot, Screen Recording & Image Annotation Tool
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

**Elite Level ScreenCap** is a professional-grade screenshot, screen-recording and image annotation tool built for power users. Capture or record any region of your screen, annotate screenshots with a full set of drawing tools, crop and trim recordings, and share, all from a sleek, dark-themed interface.

The app ships as two tools in one:
- 🎯 **Elite Level ScreenCap**: the capture launcher. It lives in your system tray, always ready.
- 🖼️ **Elite Image Editor**: a full annotation editor that opens on its own or from the capture tool.

---

## 🆕 What's New in v1.2.0

- **Screen recording:** press `Shift+PrintScreen`, drag to select an area just like a screenshot, and record it to MP4 with system audio, your microphone, or both.
- **Preview before you share:** crop out anything you didn't mean to record, trim the start and end, or remove the audio, then Save or Copy the video straight into Discord.
- **Settings window:** rebind every hotkey, choose where screenshots and recordings are saved, and set recording and startup options.
- **Electron 44 (Chromium 152)**, bringing native MP4 recording and current security fixes.

**v1.2.1** fixes copying images to the clipboard.

See the [v1.2.0 release notes](https://github.com/EliteLevelSoftware/Elite-Level-ScreenCap/releases/tag/v1.2.0) for everything, or [all releases](https://github.com/EliteLevelSoftware/Elite-Level-ScreenCap/releases) for earlier changes.

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

### 🎬 Screen Recording
- **Record a region:** same drag-to-select overlay as screenshots, including window snapping, handles and Enter.
- **MP4 (H.264 + AAC)** that plays everywhere, using your GPU's hardware encoder where available.
- **System sound and/or microphone,** each with its own switch.
- **3-2-1 countdown, recording border and a floating control bar** (pause, stop, discard). None of them appear in the video.
- **Preview window:**
  - Drag-to-crop with ratio presets.
  - Trim the start and end.
  - Remove the audio.
  - Save, Save As, Copy (the video file itself, for pasting into Discord or Explorer), Show in Folder and Delete.
- Recordings are saved to `Videos\Elite Level ScreenCap` by default. You can change this in Settings.

### ⚙️ Settings
- **Hotkeys:** rebind Capture Region, Capture Full Screen and Record/Stop. Click a hotkey and press the new combination. ScreenCap warns about duplicates and combinations another app already uses.
- **Save locations:** choose the folders for screenshots and recordings.
- **Recording:** frame rate (15 / 24 / 30 / 60), countdown, and default audio sources.
- **PrintScreen conflicts:** ask, fix automatically, or do nothing.
- **Start with Windows.**

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

**Requirements:** Windows 10 (version 2004 or later) or Windows 11, x64

The installer creates two shortcuts:
- **Elite Level ScreenCap** launches the full app with the tray icon and capture tool.
- **Elite Image Editor** launches straight into the editor. It's single-instance, so it reuses ScreenCap if it's already running.

**Upgrading:** quit ScreenCap from the tray icon (right-click → *Quit Elite Level ScreenCap*), then run the new installer. Your captures, projects and settings are kept.

---

## Troubleshooting

**PrintScreen doesn't open ScreenCap**
Another app has probably taken the key. Right-click the tray icon and choose **Fix PrintScreen Hotkey…**, or open **Settings** and use **Check** under *PrintScreen conflicts*. You can also move the capture hotkey to a different combination in **Settings → Hotkeys**. ScreenCap shows which app is using the key and can fix it for you. If the culprit was the Windows *"Use the Print screen key to open screen capture"* setting and the key still doesn't work, sign out and back in once.

**The microphone isn't recorded**
Turn on Windows **Settings → Privacy & security → Microphone → Let desktop apps access your microphone**. The recording bar shows a warning icon when the mic couldn't be opened.

**I recorded sound I didn't want**
In the preview window, switch **Audio** off (or press `M`) and click **Save**.

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
| `Shift+PrintScreen` | Record region, or stop recording |
| `Enter` | Confirm the region selection |
| `Escape` | Cancel/reset current operation |
| `Ctrl+Z` | Undo |
| `Ctrl+Y` | Redo |
| `Ctrl+C` | Copy image to clipboard |
| `Ctrl+S` | Save As |
| `F12` | Toggle DevTools |

The three capture hotkeys can be changed in **Settings → Hotkeys**.

**Recording preview**

| Shortcut | Action |
|----------|--------|
| `Space` | Play / pause |
| `I` / `O` | Set trim start / end at the playhead |
| `M` | Keep or remove audio |
| `←` / `→` | Step one frame (hold `Shift` for 1 second) |
| `Ctrl+S` | Save edits |
| `Ctrl+C` | Copy the video file |

---

## License

© 2025–2026 Elite Level Software. All rights reserved.

This software is proprietary. Redistribution or modification without written permission from Elite Level Software is prohibited.

---

<div align="center">
  Made with ❤️ by <strong>Elite Level Software</strong>
</div>
