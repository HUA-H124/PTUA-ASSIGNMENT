# PTUA-ASSIGNMENT
## Project overview

This project examines the driving accessibility of currently operating Scotch whisky distilleries from Glasgow. It combines distillery data from the Scotch Whisky Association (SWA) with road network data from OpenStreetMap (OSM) to analyse travel time, travel distance, and spatial clustering patterns across Scotland.

## Data sources
Scotch Whisky Association (SWA): list of currently operating distilleries
OpenStreetMap (OSM): road network data and geocoding support

## Main methods
PDF text extraction and geocoding
Coordinate transformation to British National Grid (EPSG:27700)
Road network construction using networkx
Shortest-path calculation of driving distance and driving time
Spatial autocorrelation analysis using Moran’s I and LISA
Proximity analysis using a 50 km buffer around Glasgow

## Main findings
Most distilleries are not located close to Glasgow
The largest share of distilleries falls within the 2–4 hour driving range
Accessibility shows a clear spatial clustering pattern
Less accessible distilleries are mainly concentrated in northern Scotland, especially Highland and Speyside
