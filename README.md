# GGR472 Lab 4: Incorporating GIS analysis into web maps using Turf.js
 
This repository contains code for a website for GGR472 Lab 4, including a visualization of collisions involving pedestrians and cyclists in Toronto between 2006 and 2021 using a hexgrid, a legend, and functionality such as pop-ups, interactivity, and map controls as required. 
All data was retrived from the Toronto Open Data Portal, specifically the Motor Vehicle Collisions involving Killed or Seriously Injured Persons dataset available at: https://open.toronto.ca/dataset/motor-vehicle-collisions-involving-killed-or-seriously-injured-persons/ 
The purpose of this map is to provide a hexgrid visualization of collision data in order to reduce the bias associated with typical choropleth maps by representing each geographic region equally.


## Key repository contents
- `data/pedcyc_collision_06-21.geojson`: Data file containing point locations of road collisions involving pedestrian and cyclists between 2006 and 2021 in Toronto
- `index.html`: HTML file to render the map
- `style.css`: CSS file for positioning the map interface, layout, style, and managing colours, etc.
- `script.js`: JavaScript file that creates and visualizes and hexgrid map based on the collision data

