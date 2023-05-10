# UExplore
![homepage](https://github.com/xchkcode0803/UExplore/assets/109048196/a638ffeb-bd11-4ee2-bf1b-33eb3e521e3f)

## Overview
UExplore is a geographical information software (GIS) that aims to help university students explore different cities around the world. Written using C++, retrieves data using the OpenStreetMap Database API, and draws graphics using GTK.

## Functionalities 
This software provides the following functionalities: 
- Layered display of geographical features based on zoom levels
- Searching for specific places of interest
- Displaying transportation networks (subway, bus, biking)
- Short-cut buttons highlighting common types of places 
- Path-finding and driving instruction between two intersections

### Display of geographical features 
The following information of a city is displayed on the map without any user manipulation: 
- highways (yellow)
- Water bodies including lakes, streams, ocean, river (blue)
- Green Spaces (green)
- Parks (green)
- Island (green)
- Golf course (green)

To avoid visual clutter, more detailed information will only be displayed once zoom in. These include: 
- Street: major streets will be displayed at a moderate zoom level, whereas street names and minor streets will only be displayed at a close zoom level 
- Buildings 

### Places of Interest search bar 
As shown below, there's a search bar with autocomplete that allows user to look for specific places of interest. All places with a matching name will be highlighted on the map once a place name is entered. 

### Transportation networks 
User can choose to display a specific transportation network on the map by selecting one of the options from the drop down menu. For subway and bus networks, the station names will only be displayed once zoomed in to avoid visual clutters. 

### Short-cut display buttons 
On the top of the home window, user can click on any of the four buttons to display types of places on the map. User can click on "Clear POI" to clear out the places being displayed on the map. The place's name will be displayed on a pop up window once clicking on the icon. 

### Path-finding
UExplore can find the fastest driving path between any two intersections on the map considering the speed limit of each street segment and a 15 seconds penalty spent on each turn of the streets. User can perform the path-finding by following these steps: 

1. Click on "Direction" located on the bottom left of the home page. This will take the user to a seperate interface 
2. Enter two intersections by entering the corresponding street names (two street names for one intersection) or by clicking on any two intersections on a map (This auto fills the intersection entry boxes)
3. Click on "Search directions". A path will be displayed along with a detailed driving instruction. Arrows showing the driving direction will be displayed once zoomed in. User can also follow along the path by clicking on "next", which will take the user through each of the turning point along the path. 















