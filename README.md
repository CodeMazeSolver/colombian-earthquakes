# Colombian Earthquakes Timeline

A multilingual static website about historically significant earthquakes in and around Colombia. The project presents one earthquake card at a time, combines event-level facts with an interactive map, and adds a reference center with scientific context, glossary material, preparedness guidance, and source lists.

**Live repo:** https://github.com/CodeMazeSolver/colombian-earthquakes

## What this project includes

- **Single-page static site** in `colombian_earthquakes.index.html`
- **Three languages:** Spanish, English, and German
- **19 historical earthquake entries** with coordinates and at least two sources per event
- **Interactive event map** with Colombia-wide reset control
- **Reference center tabs** for:
  - seismic measurement basics
  - Colombia tectonics
  - secondary hazards
  - emergency / preparedness information
  - glossary
  - full sources and further reading
- **Mobile-oriented UI work**, including:
  - compact mobile header
  - drawer-based controls
  - horizontal scroll hints
  - tap-to-enlarge EMS resource image
- **ETH Zurich resource integration**, including:
  - EMS-98 visual resources by language
  - AI-generated Spanish EMS variant clearly labeled as AI-generated
  - behavioral instruction imagery in the assets folder

## Repository structure

```text
.
├── assets/
│   ├── ems-scale-ethz.png
│   ├── ems-scale-ethz-de.jpg
│   ├── ems-scale-ethz_es_gemini.png
│   └── ethz-behaviour-*.png
├── colombian_earthquakes.index.html
├── Impactful Earthquakes in Colombia History.md
└── README.md
```

## Running locally

Because this is a static site, you can open the HTML file directly or serve the folder locally.

### Option 1: open the file directly

Open:

```text
colombian_earthquakes.index.html
```

### Option 2: run a local server

Using Python:

```bash
python -m http.server 8123
```

Then visit:

```text
http://127.0.0.1:8123/colombian_earthquakes.index.html
```

## Main data and content sources

The site content is assembled from public reference material, including:

- Servicio Geológico Colombiano (SGC)
- USGS
- Earthquakes Canada
- Ready.gov / NOAA / tsunami safety references
- ETH Zurich / Swiss Seismological Service visual education material
- historical earthquake reference pages used in the in-page bibliography

The site itself includes the full numbered source list and further-reading list in the **Sources & reading / Fuentes y lectura / Quellen & Lesen** tab.

## Notes on visual attribution

- The **English** and **German** EMS visuals are adapted from ETH / Swiss Seismological Service source material.
- The **Spanish EMS visual** in `assets/ems-scale-ethz_es_gemini.png` is an **AI-generated localized variant** and is explicitly labeled as such in the UI.

## Project goals

This repository is aimed at a static, readable, reference-style earthquake history site that balances:

- historical event browsing
- scientific background
- risk communication
- multilingual accessibility
- mobile usability

## License / reuse

No explicit open-source license has been added yet. Reuse of third-party visual assets may depend on their original source terms, especially for ETH Zurich reference graphics and adapted derivatives.
