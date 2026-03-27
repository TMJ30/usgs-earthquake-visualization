# USGS Earthquake Visualization
## Overview
This project visualizes earthquake data provided by the **United States Geological Survey (USGS)**. The goals is to create an interactive map that allows users to explore global earthquake activity, including magnitude, depth, and location.

The visualization uses **Leaflet.js** to plot earthquake data in real time, providing both scientific insight and a public-facing educational tool.

## Project Features
**Earthquake Map**
* Fetches live earthquake data from USGS GEOJSON feeds
* Plot earthquakes on a Leaflet map using **latitude** and **longitude**
* Marker **size** represents earthquake magnitude
* Marker **color** represents earthquake **dpeth**
* Clickable markers display popups with additional information (magnitude, location, time)
