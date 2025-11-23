# Alt-Baltimore-Geospatial Worldbuild

[![GeoJSON](https://img.shields.io/badge/GeoJSON-supported-green?logo=json)](#)
[![KML](https://img.shields.io/badge/KML-converted-blue)](#)
[![GIS](https://img.shields.io/badge/Spatial%20Analysis-Enabled-purple)](#)
[![Leaflet](https://img.shields.io/badge/Web%20Mapping-Leaflet%20Ready-brightgreen)](#)
[![Project Type](https://img.shields.io/badge/Type-Speculative%20Urban%20Planning-lightgrey)](#)
[![Last Updated](https://img.shields.io/badge/Updated-Nov%202025-purple)](#)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

A speculative geospatial planning project imagining an alternate development trajectory for Baltimore.  
This repository converts a custom Google Earth worldbuild (KML) into structured GeoJSON layers, forming the foundation for spatial analysis, mapping, and future visualization of a reimagined Baltimore.

---

## 🧭 Purpose

This project transforms a personal, long-term urban worldbuild into a structured, open geospatial dataset suitable for analysis and visualization.

**Core goals include:**

- Extract and preserve custom districts, campuses, corridors, and conceptual developments  
- Convert raw Google Earth KML into modern, analysis-ready GeoJSON layers  
- Provide a clean geospatial foundation for future notebooks, web maps, and planning scenarios  
- Showcase speculative urban design, district planning, and spatial data engineering skills in a portfolio-ready format  

This project is not intended to reflect real planning policy — it is a creative “what-if” model of Baltimore development through a data-driven lens.

---

## 📁 Repository Structure

```text
alt-baltimore-worldbuild/
    ├── data/
    │   ├── points/                     # Point features (institutions, sites)
    │   │    └── alt_baltimore_points.geojson
    │   ├── lines/                      # Corridors, routes, pathways
    │   │    └── alt_baltimore_lines.geojson
    │   └── polygons/                   # Districts, zones, campuses, redevelopment areas
    │        └── alt_baltimore_polygons.geojson
    │
    ├── notebooks/                      # Jupyter notebooks for spatial EDA & modeling
    ├── webapp/                         # Future interactive map (Leaflet/Mapbox)
    ├── docs/                           # Scenario notes, planning concepts, map exports
    ├── LICENSE
    ├── .gitignore
    └── README.md
```
Note: The original KML file is not tracked here; only cleaned, open GeoJSON layers are included.

---

## 🗺️ GeoSpatial Workflow

- Author the worldbuild: Custom districts, development zones, campuses, mixed-use corridors, etc. designed in Google Earth.
- Export to KML: The full worldbuild stored as a hierarchical KML with points, lines, and polygons.
- Convert to GeoJSON: Extracted into three clean layers - (points – anchors, institutions, landmark sites; lines – corridors, connectors, conceptual routes; polygons – districts, regional zones, redevelopment areas)
- Prepare for Analysis: Ready for use in geopandas, QGIS, PostGIS, AWS Athena spatial queries, or web mapping.
- Visualize: (Planned) Leaflet/Mapbox interactive map and (Planned) Spatial EDA notebooks showing accessibility, clustering, density overlays, etc.

---

## 🆕 Current Focus (Nov 2025)
- Establish foundational repository structure
- Add cleaned GeoJSON layers derived from the original KML
- Begin drafting notebooks for spatial EDA (accessibility, clustering, overlay with real Baltimore data)
- Prepare Leaflet/Mapbox starter template for a future interactive web map
- Document district concepts and planning logic in /docs

---

## 🧰 Tech Stack
GeoJSON, Python 3.10+, geopandas, shapely, QGIS, Leaflet, Mapbox GL, GitHub Pages, VS Code

---
## 📝 Project Status
- ✅ KML successfully parsed and converted
- ✅ GeoJSON layers organized by geometry type
- 🟦 Notebooks for spatial analysis (in development)
- 🟦 Interactive web map (coming soon)
- 📈 District and scenario documentation (planned)
- ❌ No original KML tracked in Git

---
## 👤 Author
Warren Jones
Speculative Urban Planning & Spatial Data Engineering

---
## 📚 References
- GeoJSON Format Specification
- Google Earth KML Reference
- Baltimore Open Data Portal
- Urban planning/land use datasets used for comparison in future analysis

All results are speculative, conceptual, and intended for creative, research, and educational use only.
Last updated: Nov 2025
