# Flood Risk Mapping of Kota District using DEM and GIS Techniques

## Project Overview

This project demonstrates the application of Geographic Information Systems (GIS) and Digital Elevation Model (DEM)-based hydrological analysis for identifying potential flood-prone areas in Kota District, Rajasthan, India.

Using SRTM DEM data and QGIS 3.40, terrain characteristics such as elevation, slope, drainage network, flow direction, and flow accumulation were derived and analyzed. Areas exhibiting low slope values and high flow accumulation were classified as potential flood-risk zones.

The project highlights how DEM-based spatial analysis can support flood management, disaster preparedness, infrastructure planning, and sustainable regional development.

---

## Study Area

**Kota District, Rajasthan, India**

Kota District is located in southeastern Rajasthan and is characterized by a combination of plateau terrain, river valleys, and drainage networks associated with the Chambal River system. Variations in elevation and terrain slope influence surface runoff and flood susceptibility across the district.

---

## Objectives

* Generate an elevation map of Kota District.
* Derive slope information from DEM data.
* Extract and analyze the drainage network.
* Identify potential flood-prone areas using hydrological parameters.
* Prepare thematic maps for flood risk assessment and planning.

---

## Data Sources

* **SRTM Digital Elevation Model (DEM)**
* **OpenStreetMap (OSM) Basemap**
* **Administrative Boundary Data**

---

## Software Used

* QGIS 3.40
* GDAL Processing Tools
* Raster Terrain Analysis Tools
* Hydrological Analysis Tools

---

## Methodology

1. Acquisition of SRTM DEM data.
2. Clipping DEM to Kota District boundary.
3. Generation of elevation and slope maps.
4. Flow direction analysis.
5. Flow accumulation analysis.
6. Extraction of drainage network.
7. Identification of flood-prone areas using:

   * High Flow Accumulation
   * Low Slope Conditions
8. Preparation of final thematic maps.

---

## Project Outputs

### 1. Elevation Analysis Map

The elevation map illustrates terrain variation across Kota District, ranging from low-lying regions to elevated plateau areas. Elevation plays a significant role in controlling runoff movement and water accumulation patterns.

### 2. Slope Analysis Map

The slope map classifies terrain into different slope categories. Low-slope regions exhibit greater flood susceptibility due to slower runoff movement and increased water retention.

### 3. Drainage Network Analysis Map

The drainage network was extracted from DEM-derived hydrological analysis. The resulting stream channels reveal the natural flow pathways through which runoff is transported across the district.

### 4. Flood Risk Analysis Map

Flood-prone zones were identified by integrating flow accumulation and slope characteristics. Areas located near drainage channels and low-gradient terrain were classified as potentially vulnerable to flooding.

---

## Key Findings

* Elevation values range from approximately **177 m to 511 m**.
* Large portions of the district exhibit **flat to gently sloping terrain**.
* The extracted drainage system displays a **dendritic drainage pattern**.
* Potential flood-risk zones are concentrated near drainage pathways and low-slope regions.
* DEM-based GIS analysis provides an efficient approach for preliminary flood hazard assessment.

---

## Repository Structure

```text
flood-risk-mapping-kota-gis
│
├── Report
│   └── Flood Risk Mapping Kota District.pdf
│
├── Maps
│   ├── Elevation Map kota District.png
│   ├── Slope Map kota District.png
│   ├── Drainage Network Analysis Map kota.png
│   └── Flood Risk Analysis of Kota District.png
│
├── LICENSE
└── README.md
```

---

## Applications

* Flood Hazard Assessment
* Disaster Management Planning
* Watershed and Hydrological Studies
* Land Use Planning
* Infrastructure Development
* Environmental Management

---

## Author

**Pranav Mathur**

GIS & Spatial Analytics Portfolio Project

---

## License

This project is distributed under the MIT License.
