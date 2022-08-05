# Amazon_Vine_Analysis

## Overview

The purpose of this analysis is to see the earthquake data in relation to the tectonic plates’ location on the earth, the earthquakes with a magnitude greater than 4.5 on the map, and the data on a third map. The following tasks are to be completed: 

1. Add Tectonic Plate Data.
2. Add Major Earthquake Data.
3. Add an Additional Map.

## Results

***Deliverable 1: Add Tectonic Plate Data***
Using knowledge of JavaScript, Leaflet.js, and geoJSON data, add tectonic plate data using d3.json(), add the data using the geoJSON() layer, set the tectonic plate LineString data to stand out on the map, and add the tectonic plate data to the overlay object with the earthquake data:

Figure 1:

![Webpage](https://raw.githubusercontent.com/krismbah/Mapping_Earthquakes/main/Earthquake_Challenge/D1.png)


***Deliverable 2: Add Major Earthquake Data***
Using knowledge of JavaScript, Leaflet.js, and geoJSON data, add major earthquake data to the map using d3.json(). Also add color and set the radius of the circle markers based on the magnitude of earthquake, and add a popup marker for each earthquake that displays the magnitude and location of the earthquake using the GeoJSON layer, geoJSON():

Figure 2:

![Webpage](https://raw.githubusercontent.com/krismbah/Mapping_Earthquakes/main/Earthquake_Challenge/D2.png)


***Deliverable 3: Create a Gauge Chart***
Using knowledge of JavaScript and Leaflet.js add a third map style to the earthquake map:

Figure 3:

![Webpage](https://raw.githubusercontent.com/krismbah/Mapping_Earthquakes/main/Earthquake_Challenge/D3.png)



## Summary

To summarize, the Leaflet.js Application Programming Interface (API) was used to populate a geographical map with GeoJSON earthquake data from a URL. Each earthquake is visually represented by a circle and color, where a higher magnitude will have a larger diameter and will be darker in color. In addition, each earthquake displays a popup marker that, when clicked, shows the magnitude of the earthquake and the location of the earthquake. In futher development of the webpage, the following customizations were implemented:

1. The tectonic plate data is added as a second layer group.
2. The tectonic plate data is added to the overlay object.
3. Add more information about the project as a paragraph on the page.
4. The tectonic plate data is passed to the geoJSON() layer.
5. The geoJSON() layer adds color and width to the tectonic plate lines.
6. The tectonic layer group variable is 




Structure, Organization, and Formatting (6 points)
The written analysis has the following structure, organization, and formatting:

There is a title, and there are multiple sections (2 pt)
Each section has a heading and subheading (2 pt)
Links to images are working, and code is formatted and displayed correctly (2 pt).
Analysis (14 points)
The written analysis has the following:

Overview of the analysis of the Vine program:

The purpose of this analysis is well defined (3 pt)
Results:

There is a bulleted list that addresses the three questions for unpaid and paid program reviews (7 pt)
Summary:

The summary states whether or not there is bias, and the results support this statement (2 pt)
An additional analysis is recommended to support the statement (2 pt)
