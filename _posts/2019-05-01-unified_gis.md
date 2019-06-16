---
author: someone
featimg: unified_gis.png
title: Unified GIS
layout: post-full
---
With our mobile and desktop applications, our software framework is a unification of the majority of the commonly used geographic information system (GIS) file formats which follow "Points, LineString, MultiLines/LinearRings" etc which follow the standard GIS formats.
<br/>
<figure>
<a href="/media/compressed/unified_gis.png
" target="_blank"><img src="/media/compressed/unified_gis.png" 
alt="IMAGE ALT TEXT HERE" width="340" height="280" border="10" /><figcaption>Some of the input output files supported by PAM.
 </figcaption></a>
 </figure>
<br/>
<br/>
##### Desktop Application
Our desktop applications are developed to support a wide variety of formats for use as input and output GIS files. The current file formats supported are
* Comma separated value (csv). We have specific formats for land, address (pin) and roads. Please save a csv file from either our 2D or 3D viewer to see the various csv formats.
* Keyhole Markup Language (KML). Linestring (path), point (pin/address) and LinearRing for 3D structures
* ESRI shapefile. Both .shp (.shx) and .dbf are supported, Point for pin/address Polyline and PolylineM for road and Polygon for land
* SQL database (custom format)
* PostGRE support (to be added)
* GeoJSON
* RASTER GeoTIFF
* Windows bitmap 
* JPEG
* SRTM HGT
* XYZ
* USGS ADF

<br/>
##### Mobile Applications
Our mobile applications support loading and writing of KML files. The applications can also take high resolution screenshots of the application display.
<br/>
<br/>

##### Future Plans
We support all the RASTER file formats. Those not listed above can be easily added by [contacting us](/contact_us). Some future features and file formats to be added include
* Data cropping
* 3D Measurements
* Dae






