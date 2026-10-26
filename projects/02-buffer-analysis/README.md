# Project 02: Road Buffer Analysis — Bekasi, Indonesia

## Overview

This project uses QGIS to conduct a 500-meter buffer analysis around the road network in Bekasi, Indonesia. The objective is to explore the spatial coverage surrounding mapped roads using a fundamental GIS proximity-analysis technique.

## Map Preview

![Bekasi Road Buffer Analysis](bekasi_road_buffer_analysis.png)

*Figure 1. Road network and 500-meter buffer analysis in Bekasi, Indonesia.*

## Objectives

- Prepare road network data for spatial analysis.
- Reproject geographic coordinates into a projected coordinate reference system.
- Generate a 500-meter buffer around mapped roads.
- Dissolve overlapping buffer areas into a single geometry.
- Calculate the area of the dissolved buffer.
- Visualize and communicate the results through a map layout.

## Tools and Data

| Item | Details |
|---|---|
| GIS Software | QGIS |
| Input Data | OpenStreetMap road network |
| Original CRS | EPSG:4326 — WGS 84 |
| Projected CRS | EPSG:32748 — WGS 84 / UTM zone 48S |
| Buffer Distance | 500 meters |
| Buffer Method | Dissolved buffer |
| Output Formats | PNG and PDF |

## Methodology

1. Obtained road network data from OpenStreetMap.
2. Reprojected the road data from EPSG:4326 to EPSG:32748.
3. Generated a 500-meter buffer around the road network.
4. Dissolved overlapping buffer areas into a single geometry.
5. Calculated the buffer area in square kilometers.
6. Designed the final map using QGIS Print Layout.
7. Exported the map in PNG and PDF formats.

## Key Result

The dissolved 500-meter road buffer covers approximately **301.5 km²**, based on the calculated geometry.

This value represents the area of the dissolved buffer around the mapped road network. It does not represent the total administrative area of Bekasi or prove actual travel accessibility.

## Deliverables

- [View the exported map (PNG)](bekasi_road_buffer_analysis.png)
- [View the printable map (PDF)](bekasi_road_buffer_analysis.pdf)

## Skills Demonstrated

- Spatial data preparation
- Coordinate reference systems and reprojection
- Buffer and dissolve analysis
- Area calculation
- GIS cartography and map layout
- Spatial data visualization

## Limitations

The analysis depends on the completeness and accuracy of the mapped OpenStreetMap road network. A geometric buffer represents proximity to mapped roads, not travel time, road conditions, or actual service accessibility.

## Data Source

OpenStreetMap contributors: https://www.openstreetmap.org/

