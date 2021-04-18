# Mapping Earthquakes with Leaflet and Mapbox

## Project Overview
The purpose of this project is to create visualizations of earthquake data using Leaflet.js and Mapbox API. These earthquakes are visually represented by circles and colors, where a higher magnitude will have a larger diameter and will be darker in color.

## Software and APIs

- A code editor, such as [VS Code](https://code.visualstudio.com/), that supports the following:
  - JavaScript
  - HTML
  - D3.js
  - CSS
- [Leaflet.js](https://leafletjs.com/)
- [Mapbox API](https://www.mapbox.com/) 

## How To Run and Use This Map

![completed_project](https://github.com/Mishkanian/Mapping_Earthquakes/blob/main/README_images/completed_mapbox.png)  

1. Download the [Earthquakes_Challenge](https://github.com/Mishkanian/Mapping_Earthquakes/tree/main/Earthquakes_Challenge) folder found in this repository.

2. After obtaining an API key from [Mapbox](https://www.mapbox.com/), create a file called "config.js" and place it inside of the js folder, which is found inside of the static folder. Use the template below for your config.js file. **DO NOT UPLOAD OR SHARE YOUR API KEY WITH ANYONE.**
 ```javascript
// API key
const API_KEY = 'paste-your-mapbox-api-key-here';
 ```
3. Open a new terminal at the Earthquake_Challenge folder and run the following code to start a live server:
```terminal
python -m http.server
```
4. The command above will usually return port 8000, if it's a different port that will not be a problem. Copy the address that is returned by the terminal ( Example: http://[::]:8000/ ) and paste this into your browser. The map should now be visible.

### Layer Controls and Legend

This map allows users to change layers by using the layer control panel found in the top right of the map. In the example below, the user has selected the "Dark Mode" map style and has enabled all earthquake data layers. Selecting a different map style will quickly reload the map with updated styling. Additionally, a [Map Legend](https://github.com/Mishkanian/Mapping_Earthquakes/blob/main/README_images/map_legend.png) is visible in the bottom right section of the map to explain the meaning of the circle colors found on the map.

![layer_controls](https://github.com/Mishkanian/Mapping_Earthquakes/blob/main/README_images/layer_controls.png)  

**Author: Michael Mishkanian**  
For all questions and inquiries, please contact me on [LinkedIn](https://www.linkedin.com/in/michaelmishkanian/).
