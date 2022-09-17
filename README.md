# Mapping_Earthquakes
In this project our aim was to build insightful data visualizations with interactive features on earthquakes from around the world.
For this goal we are using the latest earthquake GeoJSON data form the U.S. Geological Survey websit.
We traverse and retrieve the earthquake data using JavaScript and the D3 and leaflet libraries and plot the data on a Mapbox map through an API request.
On our map, the magnitude and location of each earthquake are shown in a popup marker.
The diameter of the markers for each eathquake reflet the magnitude of the earthquake in their size and color. Earthquakes with higher magnitudes appear
larger and darker in color with a legend providing the context for our map data.
To illustrate the relationship between the location and frequeny of seismic activity and tectonic plates we added foult lines on the map. There are all the earthquakes with a magnitude greater than 4.5 represented on the map.
