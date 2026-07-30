# Catenary Cable Arch Suspension Canvas - Physics Simulator 2026

> **Explore suspended cables and arch-shaped curves in a browser with live views of geometry, support tension, and the curve's lowest point.**

[![Platform](https://img.shields.io/badge/Platform-Web%20browser-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-Unversioned-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/jordan-reedxn1132/cable-suspension-physics-canvas?style=flat-square)](https://github.com/jordan-reedxn1132/cable-suspension-physics-canvas)

---

<p align="center">
  <a href="https://jordan-reedxn1132.github.io/cable-suspension-physics-canvas/">
    <img src="https://img.shields.io/badge/Download-Catenary%20Cable%20Arch%20Suspension%20Canvas%20Latest-brightgreen?style=for-the-badge" alt="Download Catenary Cable Arch Suspension Canvas">
  </a>
</p>

> **[Download Catenary Cable Arch Suspension Canvas](https://jordan-reedxn1132.github.io/cable-suspension-physics-canvas/)**

---

[Download Latest Build](https://jordan-reedxn1132.github.io/cable-suspension-physics-canvas/)

---

## Explore the Simulator

Catenary Cable Arch Suspension Canvas is a static browser application for studying how suspended cables and arch-like curves are shaped. The simulation is drawn on an HTML canvas, so it can be used for demonstrations, visual learning, and parameter experiments without installing a desktop program.

Interactive controls let you vary the sag and the separation of the supports while the display marks the lowest point and illustrates the tension vectors at the supports. Catenary and inverted catenary arch views are both available, allowing the two related curve orientations to be examined in the same interface.

---

## Included Capabilities

- Continuously rendered catenary curve
- Visual support tension vectors
- Highlighted lowest point on the curve
- User-controlled sag
- User-controlled support spacing
- Catenary and inverted catenary arch views
- Keyboard interaction support
- Static single-page application for modern web browsers

---

## Getting Started

Download the source and enter the project directory:

```bash
git clone https://github.com/jordan-reedxn1132/cable-suspension-physics-canvas.git
cd REPO
```

No dependencies need to be installed, and a build command is not needed for ordinary use. Since the project is a static SPA, you can open its main HTML file in a modern browser or host the directory with a simple static HTTP server.

To serve it locally with Python, run:

```bash
python3 -m http.server
```

Visit the local URL reported by the server.

---

## Using the Application

1. Open the simulator in a web browser.
2. Change the sag setting to alter the cable profile.
3. Set a different support distance to test other spans.
4. Watch the catenary update while the values change.
5. Read the displayed vectors to examine the direction of support tension.
6. Identify the highlighted lowest point.
7. Select either the catenary or inverted catenary arch mode.
8. Apply the available keyboard controls for further adjustments.

---

## Available Controls

All settings are managed within the browser interface or through keyboard input. The static application has no backend service and does not use a separate configuration file.

The adjustable values and modes are:

- Sag
- Support distance
- Curve or arch mode

---

## System Requirements

- Modern web browser with HTML canvas support
- JavaScript enabled
- Enough local storage for the repository files
- Optional static HTTP server for local development and serving

The application is distributed as static web content, so it does not need a database or runtime service.

---

## Frequently Asked Questions

### Do I need to install the simulator?

No. Clone or download the static files and open the application in a compatible browser.

### Will it work offline?

Yes. After the project files have been downloaded, the application can be run locally, depending on how the browser handles local file access.

### How can I reshape the cable?

Use the sag and support-distance controls. The displayed curve is recalculated as those parameters are modified.

### What does the lowest-point indicator represent?

The marker points to the lowest position on the catenary curve currently shown.

### Why are there two arch modes?

The simulator provides both catenary and inverted catenary shapes so their opposing orientations can be viewed side by side conceptually and compared.

### What can I try if the controls are not responding?

Make sure JavaScript is active and serve the files through a local HTTP server rather than opening the HTML file directly. Using a current web browser is also recommended.

### Where do new versions appear?

Project updates are released through the repository and its web deployment at [https://jordan-reedxn1132.github.io/cable-suspension-physics-canvas/](https://jordan-reedxn1132.github.io/cable-suspension-physics-canvas/).

---

## License

This project is available under the GNU GPL v3.0. Refer to [LICENSE](LICENSE) for the complete license text.
