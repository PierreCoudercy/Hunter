---
mapCalc1: 0.002631578947368421
map_height_y: 1968
map_width_x: 1968
scale_pixels: 380
scale_pixels_range: 1
---
# Lieux de San Francisco
* [[Laboratoire de recherche Trustex]]
* [[Maison de Lukas]]
* [[Ferme de Jeffrey]]
* [[Penthouse de Markus (détruit)]]
# Carte de San Francisco


```leaflet  
id: MapCalcExample ### Must be unique with no spaces  
image: [[San-Francisco-Neighborhood-Map-2.jpg]] ### Link to the map image file. Do not add a ! in front of the image  
bounds: [[0,0], [1968, 1968]] ### Size of the map in px Height_y, Width_x. Ignore 0,0  
height: 850px ### Size of the leaflet embed in px on your screen  
width: 95% ### Size of the leaflet embed in your note  
lat: 984 ### To center the map, make this half of the map height.  
long: 984 ### To center the map, make this half of the map width.  
minZoom: -1.5 ### Controls how far away from the map you can zoom out. Hover over the target icon to see the current level.  
maxZoom: 1 ### Controls how far towards the map you can zoom in. Hover over the target icon to see the current level.  
defaultZoom: -1 ### Sets the default zoom level when the map loads. Hover over the target icon to see the current level.  
zoomDelta: 0.5 ### Adjust how much the zoom changes when you zoom in or out.  
unit: km ### The value displayed when measuring so you know what type of unit is being measure.  
scale: 0.002631578947368421 ### Real units/px (resolution) of your map  
recenter: false  
darkmode: false ### markermarker: laboratoire,469.40625,550.75,Laboratoire de recherche Trustex,,,
marker: Bar,254.90625,943.75,Bar de Bob,,,
marker: Maison,50.64652320248647,1127.8353159925434,Ferme de Jeffrey,,,
marker: Appartement,1137.8125,610.5,Penthouse de Markus (détruit),,,
marker: Appartement,1299.90625,1332.75,Ambassade du Costa Rica,,,
marker: Maison,700,1218,Maison de Lukas,,,

```