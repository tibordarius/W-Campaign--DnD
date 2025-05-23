



```leaflet
id: toril_map
tileServer: https://forgotten-map.github.io/ForgottenMaps-Tiles/tiles/toril/{z}/{x}/{y}.png ### Tile server URL pattern
osmLayer: false ### Disable default OpenStreetMap layer
minZoom: 3 ### Minimum zoom level based on available tiles
maxZoom: 8 ### Maximum zoom level
defaultZoom: 3 ### Default zoom level when the map loads
height: 600px ### Height of the map container
width: 100% ### Width of the map container
lat: 0 ### Latitude center of the map (adjust if necessary)
long: 0 ### Longitude center of the map (adjust if necessary)
zoomDelta: 0.5 ### Control the zoom sensitivity
preserveAspect: true ### Maintain aspect ratio when resizing the pane



##```


```leaflet
id: toril_map
tileServer: http://localhost:8000/toril_files/{z}/{z}_{x}_{y}.png ### Local file path for your tiles
osmLayer: false ### Disable OpenStreetMap layer since you are using local tiles
minZoom: 3 ### Minimum zoom level based on your available tiles
maxZoom: 8 ### Maximum zoom level
defaultZoom: 3 ### Default zoom level when the map loads
height: 600px ### Height of the map container
width: 100% ### Width of the map container
lat: 0 ### Latitude center of the map (adjust if necessary)
long: 0 ### Longitude center of the map (adjust if necessary)
zoomDelta: 0.5 ### Control the zoom sensitivity
preserveAspect: true ### Maintain aspect ratio when resizing the pane
333```




