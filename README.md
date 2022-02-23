# Mapping Earthquakes
# Overview
This analysis traverses the latest GeoJson data from US Geological Survey website to create insightful data visualizations with interactive features on earthquakes from around the world.

To view the code for the analysis discussed below please view the **"Earthquake_Analysis"** folder in this repository.

# Resources 
Data Sources
* Map Styles: https://docs.mapbox.com/api/maps/styles/
* Earthquake Data: https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_week.geojson
* Tectonic Plate Data: https://raw.githubusercontent.com/fraxen/tectonicplates/master/GeoJSON/PB2002_boundaries.json
* Major Earthquakes (Past 7 Days) Data: https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/4.5_week.geojson

Programming Languages & Framework
* Javascript, HTML, CSS 

Tools
* Leaflet, Mapbox, d3.json, geoJson, APIs 

# Results

The earthquake data is visualized using the webpage shown below. The data can be filtered using the control on the top right corner for "Earthquakes," "Tectonic Plates," and "Major Earthquakes." The map style can also be chosen using the control for "Streets," "Satellite," and "Dark." 

<img width="154" alt="Screen Shot 2022-02-23 at 11 25 34 AM" src="https://user-images.githubusercontent.com/94571150/155362338-43818a4c-dccc-4dcc-b007-04a57d72aa2d.png">


The color of each marker is relative to the legend on the bottom left corner, color-coating the magnitudes of each earthquake.

<img width="82" alt="Screen Shot 2022-02-23 at 11 25 47 AM" src="https://user-images.githubusercontent.com/94571150/155362437-6bcdcee9-5a40-48b1-840e-e13eeeae64b4.png">

Each circle marker can be clicked on, showing the magnitude and location of the earthquake that took place. 

<img width="1439" alt="Screen Shot 2022-02-23 at 11 22 29 AM" src="https://user-images.githubusercontent.com/94571150/155361999-dfb1ad09-dd19-4503-a837-e173d08660f7.png">


