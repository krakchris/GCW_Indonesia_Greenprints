# Green City Watch #Greenprints for 26 cities in Indonesia

The code that was used for the analysis of parks in 26 cities in Indonesia. 

By: Jim Groot and Chris van Diemen @ Green City Watch


The work is presented in a jupyter notebook and can is broken apart in the following steps:

* Read city boundaries from OSM, GADM, and shapefile
* Get park polygons within city boundaries for a city of choice by using the overpass API  
* Make a selection of the parks 
* Define initial classification based on known tresholds
* Manually improve classifications using ipywidgets
* save data to csv and shapefiles


![alt text](https://github.com/krakchris/GCW_ID_greenprints/blob/master/images/GCW--PNG_small.png)