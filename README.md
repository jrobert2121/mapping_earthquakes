# Mapping Earthquakes

## Project Overview
A map was created to visually show the differences between the magnitudes of earthquakes all over the world for the past seven days.  With the original map completed, enhancements were requested in order to display more data in relation to the recent earthquakes on a map.

## Purpose
Map the tectonic plates' location on earth so earthquake data can be seen in relation.  In addition, create a map overlay of all earthquakes with a magnitude greater than 4.5 and add an third base map that the data can be viewed on.

## Resources
 - Data Sources:
    - [USGS All Earthquakes, Past Week](https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_week.geojson)
    - [USGS Magnitude 4.5+ Earthquakes, Past Week](https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/4.5_week.geojson)
    - [Github Fraxon Tectonic Plates Boundaries](https://raw.githubusercontent.com/fraxen/tectonicplates/master/GeoJSON/PB2002_boundaries.json)
- Software:
  - Leaflet, JavaScript, Visual Studio Code, D3, and Mapbox API.

## Summary

Tectonic plate data, within a GeoJSON file,  containing the boundaries of the plates around the world was added to the earthquake map.  This additional overlay allows users to view current earthquakes in relation to the fault lines.  Then another overlay was created from USGS.gov's major earthquake data files to allow users to just view recent earthquakes that had a magnitude of 4.5 or greater.  These overlays can viewed on one of three base maps: a street view, a satellite view, and a dark view.


