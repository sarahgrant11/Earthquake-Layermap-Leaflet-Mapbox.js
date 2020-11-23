# Mapping Earthqake Data With Leaflet, Mapbox

![1-Logo](Images/1-Logo.png)

## Object 
To create a an interactive world map that shows the correlations between tectonic plates and seismic activity over the last week, by connecting geoJSON API using D3.

## Data Set 
- Seismic activity: United States Geological Survey (updated every five minutes) via USGS GeoJSON Feed [https://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php]
- Tectonic plate data: https://github.com/fraxen/tectonicplates

## Visualization
* Created a world map using Leaflet.js that plots all of the earthquakes from the data set based on longitude and latitude.
* Added additional basemaps that users can choose from (top-right drop-down) as well as two different data sets into overlays that can be turned on and off by the user. 
* Each data marker reflects the location and magnitude of the earthquake in their size and color. Earthquakes with higher magnitudes appear larger and darker in color. 
* Added a tooltip in the scrollover that indicates the location and magnitude of the earthquake. 
* Added a legend for context, as well as layer controls to the map. 

## Tech Environment: 
Mapbox, D3, Leaflet, Javascript, HTML5, GitHub, VSCode
