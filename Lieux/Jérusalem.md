---
mapCalc1: 0.01639344262295082
map_height_y: 1200
map_width_x: 1060
scale_pixels: 183
scale_pixels_range: 3
---
# Carte de Jérusalem

```leaflet  
id: MapCalcExample ### Must be unique with no spaces  
image: [[Jerusalem.png]] ### Link to the map image file. Do not add a ! in front of the image  
bounds: [[0,0], [1200, 1060]] ### Size of the map in px Height_y, Width_x. Ignore 0,0  
height: 850px ### Size of the leaflet embed in px on your screen  
width: 95% ### Size of the leaflet embed in your note  
lat: 600 ### To center the map, make this half of the map height.  
long: 530 ### To center the map, make this half of the map width.  
minZoom: -1.5 ### Controls how far away from the map you can zoom out. Hover over the target icon to see the current level.  
maxZoom: 1 ### Controls how far towards the map you can zoom in. Hover over the target icon to see the current level.  
defaultZoom: -0.5 ### Sets the default zoom level when the map loads. Hover over the target icon to see the current level.  
zoomDelta: 0.5 ### Adjust how much the zoom changes when you zoom in or out.  
unit: mi ### The value displayed when measuring so you know what type of unit is being measure.  
scale: 0.01639344262295082 ### Real units/px (resolution) of your map  
recenter: false  
darkmode: false ### marker
marker: People,512.5234375,771.25,Lazarus,,,

```