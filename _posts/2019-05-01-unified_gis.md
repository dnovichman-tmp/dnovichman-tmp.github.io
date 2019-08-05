---
author: someone
featimg: unified_gis.png
title: Unified GIS
layout: post-full
---
With our mobile and desktop applications, our software framework is a unification of the majority of the commonly used geographic information system (GIS) file formats which follow the standard "Points, LineString, MultiLines/LinearRings" types.
<br/>
<br/>
<figure>
<a href="/media/compressed/unified_gis.png
" target="_blank"><img src="/media/compressed/unified_gis.png" 
alt="IMAGE ALT TEXT HERE" width="340" height="280" border="10" /><figcaption>Some of the input/output file formats supported by PaM.
 </figcaption></a>
 </figure>
<br/>
<br/>
##### Desktop Application
Our desktop applications are developed to support a wide variety of formats for use as input and output GIS files. The current file formats supported are
* Comma separated value (csv). We have specific formats for land, address (pin) and roads. 
* Keyhole Markup Language (KML). Linestring (path), point (pin/address) and LinearRing for 3D structures
* Environmental Systems Research Institute ESRI shapefile. Both .shp (.shx) and .dbf are supported, Point for pin/address Polyline and PolylineM for road and Polygon for land
* SQL database (custom format)
* PostGRE support (to be added)
* GeoJSON
* RASTER GeoTIFF
* Windows bitmap 
* Joint Photographic Experts Group JPEG
* Shuttle Radar Topography Mission (SRTM) HGT
* XYZ
* United States Geological Survey's ArcGrid ADF

<br/>
##### Mobile Applications
Our mobile applications support loading and writing of KML files. The files can be used to support emergency response to hard to reach places. The applications can also take high resolution screenshots of the current display.
<br/>
<br/>

##### Future Plans
To support all the RASTER file formats. If there is is a format you would like us to add, please [contact us](/contact_us).






