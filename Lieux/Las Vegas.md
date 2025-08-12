---
mapCalc1: 0.011428571428571429
map_height_y: 1500
map_width_x: 1500
scale_pixels: 70
scale_pixels_range: 0.8
---
# Lieux de Las Vegas
* 
# Carte Las Vegas

```leaflet  
id: MapCalcExample ### Must be unique with no spaces  
image: [[Las-Vegas-Road-Map.jpg]] ### Link to the map image file. Do not add a ! in front of the image  
bounds: [[0,0], [1500, 1500]] ### Size of the map in px Height_y, Width_x. Ignore 0,0  
height: 850px ### Size of the leaflet embed in px on your screen  
width: 95% ### Size of the leaflet embed in your note  
lat: 750 ### To center the map, make this half of the map height.  
long: 750 ### To center the map, make this half of the map width.  
minZoom: -1.5 ### Controls how far away from the map you can zoom out. Hover over the target icon to see the current level.  
maxZoom: 1 ### Controls how far towards the map you can zoom in. Hover over the target icon to see the current level.  
defaultZoom: -1 ### Sets the default zoom level when the map loads. Hover over the target icon to see the current level.  
zoomDelta: 0.5 ### Adjust how much the zoom changes when you zoom in or out.  
unit: km ### The value displayed when measuring so you know what type of unit is being measure.  
scale: 0.011428571428571429 ### Real units/px (resolution) of your map  
recenter: false  
darkmode: false ### marker
marker: Appartement,290,745.5,Appartement de la vampire,,,
marker: fealand,416.34375,309.25,Cours royale de l'automne,,,
marker: Appartement,512.5,749,Appartement Wild Seven,,,

```