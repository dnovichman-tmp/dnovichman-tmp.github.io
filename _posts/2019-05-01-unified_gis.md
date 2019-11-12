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
<br/>
<br/>

###### Vector Formats
* Comma separated value (csv) for generic and specific formats. 
* Keyhole Markup Language (KML). Linestring (path), Point (pin/address) and LinearRing for 3D structures
* Environmental Systems Research Institute ESRI shapefile. .shp (.shx), .dbf and .prj are supported.<!-- Point for pin/address Polyline and PolylineM for road and Polygon for land-->
* GeoJSON

<br/>
<figure>
<a href="/media/compressed/osm_shapen.png
" target="_blank"><img src="/media/compressed/osm_shapen.png" 
alt="IMAGE ALT TEXT HERE" width="600" height="400" border="10" />
 <figcaption>
 OSM loaded shapefile that can be directly converted to csv or KML.
 </figcaption></a>
 </figure>
 <br/>
<br/>
###### Raster Formats
* GeoTIFF
* Windows bitmap (.bmp)
* Joint Photographic Experts Group (.jpeg)
* Portable Network Graphics (png)
* Shuttle Radar Topography Mission - SRTM (.hgt)
* XYZ (to be added)
* United States Geological Survey's ArcGrid binary (.adf)
* United States Digital Elevation Model (.dem)
* Erdas Imagine (.img)
<br/>
<figure>
<a href="/media/compressed/srtm1011n.png
" target="_blank"><img src="/media/compressed/srtm1011n.png" 
alt="IMAGE ALT TEXT HERE" width="600" height="400" border="10" />
 <figcaption>
 SRTM HGT N10W011 terrain file.
 </figcaption></a>
 </figure>
 <br/>
 
 <br/>
<figure>
<a href="/media/compressed/n44_w093_3arc_v1n.png
" target="_blank"><img src="/media/compressed/n44_w093_3arc_v1n.png" 
alt="IMAGE ALT TEXT HERE" width="600" height="400" border="10" />
 <figcaption>
 n44_w093_3arc_v terrain tiff file in edit mode.
 </figcaption></a>
 </figure>
 <br/>
 
 
###### Spatial Database
* MySQL
* PostGIS
* SpatiaLite

 <br/>
<figure>
<a href="/media/compressed/mysql.png
" target="_blank"><img src="/media/compressed/mysql.png" 
alt="IMAGE ALT TEXT HERE" width="600" height="400" border="10" />
 <figcaption>
 MySQL spatial database that can be directly loaded or saved as csv, KML or Shapefile.
 </figcaption></a>
 </figure>
 <br/>

<br/>
##### Mobile Applications
Our mobile applications support loading and writing of KML files. The files can be used to support emergency response to hard to reach places. The applications can also take high resolution screenshots of the current display.
<br/>
<br/>

##### Future Plans
To support all the vector and raster file formats. If there is is a format you would like us to add, please [contact us](/contact_us).






