---
layout: post
title: Geocoding
categories: [openrefine, palladio]
---

# Geocoding
## What geocoding is
Geocoding is a process, though which a geographical location, e.g. and address, is transformed into coordinates, which can be used for creating maps. 
It is helpful in visualising a list of geographical locations in relation to each other. For research such a tool can be useful, when the question lies with the location of certain 
categories of places, e.g. religious buildings of a particular denomination, or locations of specific religious communities around the globe.

## What we did
We worked with a set of data on synagogues in Germany. Our aim was to find different synagogues around Germany, identify their address, give that information to the computer so that it can
place the synagogues on a map. The information about addresses was already prepared beforehand. 

## How we did it
We used [Nominatim][1] in order to find each synagogue and transform their addresses to coordinates. The web-site finds a location by its address; and then through API request it is possible to 
look up the specific geographical coordinates. 
That information was organized in OpenRefine (e.g. each synagogue was linked to a set of coordinates), and then uploaded to [Palladio][2]. Palladio analyses the coordinates and places them on a map.
The map can be customized, e.g. to show the sizes of parishes (that information was also in the table provided beforehand. 

Overall, I found the tools very nice and useful.

[1]: https://nominatim.openstreetmap.org/ui/search.html
[2]: https://hdlab.stanford.edu/palladio-app/#/upload 
