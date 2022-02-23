# Mapping Earthquakes
# Overview
This analysis traverses the latest GeoJson data from US Geological Survey website to create insightful data visualizations with interactive features on earthquakes from around the world.

# Resources 
Data Sources
* Map Styles: https://api.mapbox.com/styles/v1/mapbox/streets-v11/tiles/{z}/{x}/{y}?access_token={accessToken}
* Earthquake Data: https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_week.geojson
* Tectonic Plate Data: https://raw.githubusercontent.com/fraxen/tectonicplates/master/GeoJSON/PB2002_boundaries.json
* Major Earthquakes (Past 7 Days) Data: https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/4.5_week.geojson

Programming Languages & Framework
* Javascript, HTML, CSS 

Tools
* Leaflet, Mapbox, d3.json, geoJson, APIs 

# Results

The earthquake data is visualized using the webpage shown below. The data can be filtered using the control on the top right corner for "Earthquakes," "Tectonic Plates," and "Major Earthquakes." The map style can also be chosen using the control for "Streets," "Satellite," and "Dark." 
Each circle marker can be clicked on, showing the magnitude and location of the earthquake that took place. 
The color of each marker is relative to the legend on the bottom left corner, color-coating the magnitudes of each earthquake.
