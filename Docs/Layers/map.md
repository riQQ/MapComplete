

 map 
=====



<img src='https://mapcomplete.osm.be/./assets/layers/map/map.svg' height="100px"> 

A map, meant for tourists which is permanently installed in the public space




## Table of contents

1. [map](#map)
      * [Themes using this layer](#themes-using-this-layer)
  - [Basic tags for this layer](#basic-tags-for-this-layer)
  - [Supported attributes](#supported-attributes)
    + [images](#images)
    + [map-map_source](#map-map_source)
    + [map-attribution](#map-attribution)










#### Themes using this layer 





  - [maps](https://mapcomplete.osm.be/maps)
  - [nature](https://mapcomplete.osm.be/nature)
  - [personal](https://mapcomplete.osm.be/personal)


[Go to the source code](https://github.com/pietervdvn/MapComplete/blob/develop/assets/layers/map/map.json)



 Basic tags for this layer 
---------------------------



Elements must have the all of following tags to be shown on this layer:



  - <a href='https://wiki.openstreetmap.org/wiki/Key:tourism' target='_blank'>tourism</a>=<a href='https://wiki.openstreetmap.org/wiki/Tag:tourism%3Dmap' target='_blank'>map</a>|<a href='https://wiki.openstreetmap.org/wiki/Key:information' target='_blank'>information</a>=<a href='https://wiki.openstreetmap.org/wiki/Tag:information%3Dmap' target='_blank'>map</a>


[Execute on overpass](http://overpass-turbo.eu/?Q=%5Bout%3Ajson%5D%5Btimeout%3A90%5D%3B(%20%20%20%20nwr%5B%22information%22%3D%22map%22%5D(%7B%7Bbbox%7D%7D)%3B%0A%20%20%20%20nwr%5B%22tourism%22%3D%22map%22%5D(%7B%7Bbbox%7D%7D)%3B%0A)%3Bout%20body%3B%3E%3Bout%20skel%20qt%3B)



 Supported attributes 
----------------------



**Warning** This quick overview is incomplete



attribute | type | values which are supported by this layer
----------- | ------ | ------------------------------------------
[<img src='https://mapcomplete.osm.be/assets/svg/statistics.svg' height='18px'>](https://taginfo.openstreetmap.org/keys/map_source#values) [map_source](https://wiki.openstreetmap.org/wiki/Key:map_source) | [string](../SpecialInputElements.md#string) | [OpenStreetMap](https://wiki.openstreetmap.org/wiki/Tag:map_source%3DOpenStreetMap)
[<img src='https://mapcomplete.osm.be/assets/svg/statistics.svg' height='18px'>](https://taginfo.openstreetmap.org/keys/map_source:attribution#values) [map_source:attribution](https://wiki.openstreetmap.org/wiki/Key:map_source:attribution) | Multiple choice | [yes](https://wiki.openstreetmap.org/wiki/Tag:map_source:attribution%3Dyes) [incomplete](https://wiki.openstreetmap.org/wiki/Tag:map_source:attribution%3Dincomplete) [sticker](https://wiki.openstreetmap.org/wiki/Tag:map_source:attribution%3Dsticker) [none](https://wiki.openstreetmap.org/wiki/Tag:map_source:attribution%3Dnone)




### images 



_This tagrendering has no question and is thus read-only_





### map-map_source 



The question is **On which data is this map based?**

This rendering asks information about the property  [map_source](https://wiki.openstreetmap.org/wiki/Key:map_source) 
This is rendered with `This map is based on {map_source}`



  - **This map is based on OpenStreetMap** corresponds with <a href='https://wiki.openstreetmap.org/wiki/Key:map_source' target='_blank'>map_source</a>=<a href='https://wiki.openstreetmap.org/wiki/Tag:map_source%3DOpenStreetMap' target='_blank'>OpenStreetMap</a>




### map-attribution 



The question is **Is the OpenStreetMap-attribution given?**





  - **OpenStreetMap is clearly attributed, including the ODBL-license** corresponds with <a href='https://wiki.openstreetmap.org/wiki/Key:map_source:attribution' target='_blank'>map_source:attribution</a>=<a href='https://wiki.openstreetmap.org/wiki/Tag:map_source:attribution%3Dyes' target='_blank'>yes</a>
  - **OpenStreetMap is clearly attributed, but the license is not mentioned** corresponds with <a href='https://wiki.openstreetmap.org/wiki/Key:map_source:attribution' target='_blank'>map_source:attribution</a>=<a href='https://wiki.openstreetmap.org/wiki/Tag:map_source:attribution%3Dincomplete' target='_blank'>incomplete</a>
  - **OpenStreetMap wasn't mentioned, but someone put an OpenStreetMap-sticker on it** corresponds with <a href='https://wiki.openstreetmap.org/wiki/Key:map_source:attribution' target='_blank'>map_source:attribution</a>=<a href='https://wiki.openstreetmap.org/wiki/Tag:map_source:attribution%3Dsticker' target='_blank'>sticker</a>
  - **There is no attribution at all** corresponds with <a href='https://wiki.openstreetmap.org/wiki/Key:map_source:attribution' target='_blank'>map_source:attribution</a>=<a href='https://wiki.openstreetmap.org/wiki/Tag:map_source:attribution%3Dnone' target='_blank'>none</a>
  - **There is no attribution at all** corresponds with <a href='https://wiki.openstreetmap.org/wiki/Key:map_source:attribution' target='_blank'>map_source:attribution</a>=<a href='https://wiki.openstreetmap.org/wiki/Tag:map_source:attribution%3Dno' target='_blank'>no</a>_This option cannot be chosen as answer_
 

This document is autogenerated from [assets/layers/map/map.json](https://github.com/pietervdvn/MapComplete/blob/develop/assets/layers/map/map.json)