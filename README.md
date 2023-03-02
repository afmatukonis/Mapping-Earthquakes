# Mapping-Earthquakes
Module-14

**Overview**

The purpose of this challenge is to use HTML, JavaScript, and CSS to create earthquake maps and overlay them on top of eachother. Ideally we are creating three different maps that can have three different overalays. The overlays will be earthquakes, tectonic plates and then earthquakes with a magnitude greater than 4.5.

**Process**

First thing we did was added two different views to the map; streets and satelites. For each of the layers, all earthquakes, tectonic plates, and earthquakes with a magnitude of 4.5 or greater we followed the same strucutre on adding the information. We added the data using d3.json(), geoJSON(), and then added that to the allEarthquakes, tectonicPlates, and majorEarthquakes layers and then added that layer group to the map. 

To add an aditional map I added a dark style, using the same style of code as when adding the street and satelite view. 

**Analysis** 

As we can see from the Map that most earthquakes are concentrated around tectonic plates which is reanable to assume is correct based on teh basic knowledge of how earthquakes happen. 