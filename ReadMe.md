# Geospatial Data & Software Resources for Hackathons

Below you'll find some of the basic building blocks for creating interactive mapping applications for the web of Mobile. About the only thing you need, that you won't find below, is a web server for your html code. 

## The Basics
[http://mapschool.io/](http://mapschool.io/)  

An excellent introduction to mapping with computers, particularly for the web. Mapschool is a collaborative, simple guide to understanding the concepts of cartography, gis, and maps. You can read it at [mapschool.io](mapschool.io) and contribute to it at [https://github.com/mapschool/mapschool](https://github.com/mapschool/mapschool). Mapschool is licensed CC0: it is free.

## Software

#### QGIS
[http://www.qgis.org/en/site/forusers/download.html](http://www.qgis.org/en/site/forusers/download.html)  
QGIS is the best Open Source Desktop GIS package around. A good place to start for learning to use it is: [http://www.qgistutorials.com/en/](http://www.qgistutorials.com/en/)  

#### GDAL  
[http://www.gdal.org/](http://www.gdal.org/)  
GDAL is the Geospatial Data Abstraction Library, a command-line set of tools for transforming and converting geospatial datasets.

#### OpenRefine  
[http://openrefine.org/](http://openrefine.org/)  

OpenRefine (formerly Google Refine) is a powerful tool for working with messy data: cleaning it; transforming it from one format into another; and extending it with web services and external data.  You can also use it in conjunction with geonames.org and other web-based geospatial APIs to geocode and route. See [https://github.com/StanfordGeospatialCenter/Tutorial-Geocoding-APIs](https://github.com/StanfordGeospatialCenter/Tutorial-Geocoding-APIs) for a tutorial on using OpenRefine for geocoding. 

## Online Services  

#### Planet.com
[https://www.planet.com/](https://www.planet.com/)  
The Earth, imaged with 4 spectral bands, at 5m resolution or better, every day. *.edu emails have the opportunity to obtain research and teaching accounts. 

#### Mapbox  
[https://www.mapbox.com/mapbox-studio/](https://www.mapbox.com/mapbox-studio/)  
Mapbox Studio provides a free tier of subscription which will allow you to create performant web mapping applications. You can customize the symbology of OpenStreetMap data to your own purpose, add your own operational data, and create custom behaviors in pop-ups, etc...  

#### CARTO  
[https://carto.com/](https://carto.com/)  
CARTO.com is the newest iteration of CartoDB.com, and provides a great deal of developer-friendly geospatial data analysis and management functionality with the free account level.  You can even use CARTO to store non-geo data and call it through the SQL API or the DATA API, for use in websites using D3.js, etc...  

#### OpenStreetMap  
[http://www.openstreetmap.org/](http://www.openstreetmap.org/)  
OpenStreetMa is the crowdsourced map of the world, and one of the most complete sources of geospatial data, especially for developing parts of the globe. QGIS provides some great plugins for subsetting and downloading from OSM. You can also add your own data to OSM. THat's the whole idea!

#### Humanitarian OpenStreetMap Task Manager  
[tasks.hotosm.org  ](http://tasks.hotosm.org/)  

OSM Tasking Manager is a mapping tool designed and built for the Humanitarian OSM Team collaborative mapping. The purpose of the tool is to divide up a mapping job into smaller tasks that can be completed rapidly. It shows which areas need to be mapped and which areas need the mapping validated.

The application is an integral part of the work that the OpenStreetMap community does to respond to, and prepare for disasters, with geospatial data. 

#### DavidRumsey.com  
[http://www.davidrumsey.com/](http://www.davidrumsey.com/)  
The physical map collection is housed in the David Rumsey Map Center at the Stanford University Library. The historical map collection has over 76,000 maps and images online. The collection includes rare 16th through 21st century maps of America, North America, South America, Europe, Asia, Africa, Pacific and the World. The site also has integrated the ability to **georeference** any of the historical maps you find on the site, and serve them as WMS or Map Tile Services using several OGC Standard mapping service types. 

#### mapshaper
[www.mapshaper.org/](http://www.mapshaper.org/)  
A tool for topologically aware shape simplification. Reads and writes Shapefile, GeoJSON and TopoJSON formats. A quick and efficient way to simplify geospatial datasets for faster performance over the internet. 

####  geojson.io 
[http://geojson.io](http://geojson.io)
geojson.io is a quick, simple tool for creating, viewing, and sharing map data. geojson.io is named after GeoJSON, an open source data format, and it supports GeoJSON in all ways - but also accepts KML, GPX, CSV, GTFS, TopoJSON, and other formats.

#### Geonames.org
[www.geonames.org](http://www.geonames.org)
The GeoNames geographical database covers all countries and contains over eleven million placenames that are available for download free of charge. Also includes a geocoding service/API with very liberal use terms. 

#### Google Earth Engine
[https://earthengine.google.com/#intro](https://earthengine.google.com/#intro)  
Google Earth Engine combines a multi-petabyte catalog of satellite imagery and geospatial datasets with planetary-scale analysis capabilities and makes it available for scientists, researchers, and developers to detect changes, map trends, and quantify differences on the Earth's surface.

Clipping and image viz:
[https://developers.google.com/earth-engine/image_visualization](https://developers.google.com/earth-engine/image_visualization)

## Code Libraries

#### leaflet.js
[http://leafletjs.com/](http://leafletjs.com/)
Leaflet.js is everyone's favorite mapping library, created for mobile, and so very performant in all situations. Super easy to use, and interoperable with mapping services that comply with OGC standards (WMS & WFS).

#### Geostats.jl  
[https://github.com/juliohm/GeoStats.jl](https://github.com/juliohm/GeoStats.jl)
High-performance implementations of geostatistical algorithms for the Julia programming language.

#### turf.js  
[http://turfjs.org/ ](http://turfjs.org/) 
Turf is a JavaScript library for spatial analysis. It includes traditional spatial operations, helper functions for creating GeoJSON data, and data classification and statistics tools. Turf can be added to your website as a client-side plugin, or you can run Turf server-side with Node.js  

#### simple statistics  
[http://simplestatistics.org/](http://simplestatistics.org/)  
Simple Statistics is a JavaScript library that implements statistical methods.

It helps coders harness the power of statistics and statisticians understand code. The library is exhaustively documented, written in a simple and friendly style, and thoroughly tested.  

#### D3.js  
[https://d3js.org/](https://d3js.org/)  

D3.js is a JavaScript library for manipulating documents based on data. D3 helps you bring data to life using HTML, SVG, and CSS. D3’s emphasis on web standards gives you the full capabilities of modern browsers without tying yourself to a proprietary framework, combining powerful visualization components and a data-driven approach to DOM manipulation.

#### DC.js - Dimensional Charting Javascript Library
[https://dc-js.github.io/dc.js/ ](https://dc-js.github.io/dc.js/)  
  
dc.js is a javascript charting library with native crossfilter support, allowing highly efficient exploration on large multi-dimensional datasets (inspired by crossfilter's demo). It leverages d3 to render charts in CSS-friendly SVG format. Charts rendered using dc.js are data driven and reactive and therefore provide instant feedback to user interaction.

dc.js is an easy yet powerful javascript library for data visualization and analysis in the browser and on mobile devices.


# Data Sources
## General Data

#### [Data.gov](https://Data.gov)

#### Skyhook TIDE Mobile Device Data  
[Skyhook OpenTIDE](http://www.skyhook.com/gi_opentide?__hstc=114541272.ba4ed08edd58696dbf995d3a78598b09.1520981230931.1521748065146.1521850347232.3&__hssc=114541272.1.1523652006349&__hsfp=1131349608&hsCtaTracking=4a863f88-239d-40ae-a3a2-2b1f251231bc%7Cea64981c-6e1c-4f04-8f5b-7922a3aff0b4)   
[http://skyhook.carto.com/](http://skyhook.carto.com/)  
Tiled, hourly counts of mobile devices per 100m grid cell, for the globe. 

#### USGS online data search platform, including GIS data  
[https://data.usgs.gov/datacatalog](https://data.usgs.gov/datacatalog)
The USGS Science Data Catalog provides seamless access to USGS research and monitoring data from across the nation. Users have the ability to search, browse, or use a map-based interface to discover data.

#### HDX - Humanitarian Data Exchange  
[https://data.humdata.org/](https://data.humdata.org/)  
The Humanitarian Data Exchange (HDX) is an open platform for sharing data, launched in July 2014. The goal of HDX is to make humanitarian data easy to find and use for analysis. Our growing collection of datasets has been accessed by users in over 200 countries and territories. Watch this video to learn more.

#### Earthworks.stanford.edu  
[https://earthworks.stanford.edu/](https://earthworks.stanford.edu/)  
Earthworks is Stanford's geospatial Data Discovery platform. It provides federated serach across several institutions like Harvard, Columbia, MIT, etc... There are over 25,000 data layers indexed in Earthworks, with nearly 10k publicly available.  

#### GLOVIS  
[http://glovis.usgs.gov/next/](http://glovis.usgs.gov/next/)  
Explore the world’s largest civilian collection of images of the Earth’s surface. Find satellite images and data, aerial photography, elevation and land cover datasets, digitized maps, and our Image Gallery collections.

Our Archive spans from 1937 aerial photographs to millions of satellite images of the Earth’s surface, starting with the original Earth orbits in the 1960’s and first Landsat satellite in 1972, to our current hourly additions of satellite images. Click on any product category to review detailed information on the products, plus how to order or download selected images at no charge.

#### Census.gov  
[https://www.census.gov/developers/](https://www.census.gov/developers/)    
The Census Bureau's mission is to serve as the leading source of quality data about the nation's people and economy. We honor privacy, protect confidentiality, share our expertise globally, and conduct our work openly. The Census Bureau has begun rolling out datasets via APIs.  Check out our Discovery Tool. Sign up for our newsletter to get the latest updates and newest dataset addition. We also invite you to make requests for features / data via our forum.

#### Historic U.S. Census GEOGRAPHIC SUMMARY DATA AND BOUNDARY FILES
[NHGIS.org](http://NHGIS.org)  
The National Historical Geographic Information System (NHGIS) provides population, housing, agricultural, and economic data, along with GIS-compatible boundary files, for geographic units in the United States from 1790 to the present.

#### Mannahatta Project
[https://welikia.org/science/recreating-mannahatta/](https://welikia.org/science/recreating-mannahatta/)  
Reconstruction of Pre-Colombian environment of Manhattan Island. 

The Map Application:
[https://welikia.org/explore/mannahatta-map/](https://welikia.org/explore/mannahatta-map/)

#### Natural Earth Data  
[http://www.naturalearthdata.com/](http://www.naturalearthdata.com/)  

Natural Earth is a public domain map dataset available at 1:10m, 1:50m, and 1:110 million scales. Featuring tightly integrated vector and raster data, with Natural Earth you can make a variety of visually pleasing, well-crafted maps with cartography or GIS software.

Most important for this event, there are great TIFFs of the surface of the earth, with.without acean, etc...

## Bay Area Data

#### SF Open Data Portal  
[https://data.sfgov.org/](https://data.sfgov.org/)

#### SFEI Aquatic Science Center data portal  
[http://www.sfei.org/sfeidata.htm](http://www.sfei.org/sfeidata.htm)  

SFEI is the regional data center for the San Francisco Bay-Delta and northern montane regions. The Institute manages water quality, tissue, wetlands, historical, and ...

#### SF MTC spatial data library  
[http://opendata.mtc.ca.gov/](http://opendata.mtc.ca.gov/)  

Discover, explore, and download open data from Metropolitan Transportation Commission Open Data

## Disaster Data

#### USGS Earthquake data  
[https://earthquake.usgs.gov/data/data.php#geod](USGS Earthquake data)

#### Global Historical Earthquake Browser
[http://ds.iris.edu/ieb/index.html](http://ds.iris.edu/ieb/index.html)

#### Historical hurricane tracks and information  
[https://www.ncdc.noaa.gov/ibtracs/index.php?name=ibtracs-data](https://www.ncdc.noaa.gov/ibtracs/index.php?name=ibtracs-data)  

#### Northern California Earthquake Data Center (for time-series data from seismic stations)  
[http://service.ncedc.org/](http://service.ncedc.org/)

#### ABAG Resilience Program data:  
[http://resilience.abag.ca.gov/open-data/](http://resilience.abag.ca.gov/open-data/)  

ABAG’s Resilience Open Data portal contains 40+ hazard map layers and a growing list of tabular data sets for the nine county Bay Area region.

#### BCDC Sea Level Rise Viewer  
[http://www.bcdc.ca.gov/slr.html](http://www.bcdc.ca.gov/slr.html)  

Areas Vulnerable to Sea Level Rise in San Francisco Bay. Sea level rise is a concern for many Bay Area residents, community leaders, and resource ...  

#### Pacific Institute Sea Level Rise data
[http://www2.pacinst.org/reports/sea_level_rise/data/](http://www2.pacinst.org/reports/sea_level_rise/data/)  

This page contains links to downloadable geographic data created or modified by Pacific Institute researchers for the project Impacts of Sea ...
