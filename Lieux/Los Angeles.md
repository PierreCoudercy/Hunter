---
mapCalc1: NaN
map_height_y: 2200
map_width_x: 1700
---
# Lieux de Los Angeles
* [[Centre de congrès]]
* [[Villa Vampire]]
# Carte Los Angeles

```leaflet  
id: MapCalcExample ### Must be unique with no spaces  
image: [[Los-Angeles-Neighborhood-Map.jpg]] ### Link to the map image file. Do not add a ! in front of the image  
bounds: [[0,0], [2200, 1700]] ### Size of the map in px Height_y, Width_x. Ignore 0,0  
height: 850px ### Size of the leaflet embed in px on your screen  
width: 95% ### Size of the leaflet embed in your note  
lat: 1100 ### To center the map, make this half of the map height.  
long: 850 ### To center the map, make this half of the map width.  
minZoom: -1.5 ### Controls how far away from the map you can zoom out. Hover over the target icon to see the current level.  
maxZoom: 1 ### Controls how far towards the map you can zoom in. Hover over the target icon to see the current level.  
defaultZoom: -1 ### Sets the default zoom level when the map loads. Hover over the target icon to see the current level.  
zoomDelta: 0.5 ### Adjust how much the zoom changes when you zoom in or out.  
unit: km ### The value displayed when measuring so you know what type of unit is being measure.  
scale: 0.03 ### Real units/px (resolution) of your map  
recenter: false  
darkmode: false ### marker
marker: Maison,293,769.5,Villa Vampire,,,
marker: Appartement,1182.53125,1207.75,Centre de congrès,,,

```