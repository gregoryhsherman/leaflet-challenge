# leaflet-challenge
Visualizing Data with Leaflet

# United States Geological Survey - Last 30 Day Earthquake Maps

Please add your API key to the config.js file located in static/js file path before opening the index.html file.

This demostrates how Leaflet.js is used to visualize geoJSON data. The javascript uses Leaflet layer control using basemaps and overlay maps using a live API feed provided by the USGS(United States Geological Survey). The data includes all earthquake data for the Past 30 Days. Additional layer of tectonic plates provides the relationship between tectonic plates and seismic activites.

# Sources Used 
queryUrl = "https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_month.geojson"
<br />
faultlinequery = "https://raw.githubusercontent.com/fraxen/tectonicplates/master/GeoJSON/PB2002_plates.json"
<br />
outdoorsmap = https://api.tiles.mapbox.com id: "mapbox.outdoors
<br />
satellitemap = https://api.tiles.mapbox.com id: "mapbox.satellite
<br />
grayscalemap = https://api.tiles.mapbox.com id: "mapbox.light
<br />

Please refer below for the a screenshots of the visualizations. 

![ScreenShots of Earthquake Gray Scale Maps](Images/GreyScaleMap.png)
![ScreenShots of Earthquake Outdoor Maps](Images/OutdoorMap.png)
![ScreenShots of Earthquake Satellite Maps](Images/SatelliteMap.png)


