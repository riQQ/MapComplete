

 crab_address 
==============



<img src='https://mapcomplete.osm.be/./assets/layers/crab_address/housenumber_blank.svg' height="100px"> 

Address data for Flanders by the governement, suited for import into OpenStreetMap. Datadump from 2021-10-26. This layer contains only visualisation logic. Import buttons should be added via an override. Note that HNRLABEL contains the original value, whereas _HNRLABEL contains a slightly cleaned version




## Table of contents

1. [crab_address](#crab_address)
      * [Themes using this layer](#themes-using-this-layer)
  - [Basic tags for this layer](#basic-tags-for-this-layer)
  - [Supported attributes](#supported-attributes)
    + [render_crab](#render_crab)





  - <img src='../warning.svg' height='1rem'/> This layer is loaded from an external source, namely `https://raw.githubusercontent.com/pietervdvn/MapComplete-data/main/CRAB_2021_10_26/tile_{z}_{x}_{y}.geojson`




#### Themes using this layer 





  - [personal](https://mapcomplete.osm.be/personal)


[Go to the source code](https://github.com/pietervdvn/MapComplete/blob/develop/assets/layers/crab_address/crab_address.json)



 Basic tags for this layer 
---------------------------



Elements must have the all of following tags to be shown on this layer:



  - HUISNR~^..*$


[Execute on overpass](http://overpass-turbo.eu/?Q=%5Bout%3Ajson%5D%5Btimeout%3A90%5D%3B(%20%20%20%20nwr%5B%22HUISNR%22%5D(%7B%7Bbbox%7D%7D)%3B%0A)%3Bout%20body%3B%3E%3Bout%20skel%20qt%3B)



 Supported attributes 
----------------------





### render_crab 



_This tagrendering has no question and is thus read-only_

 

This document is autogenerated from [assets/layers/crab_address/crab_address.json](https://github.com/pietervdvn/MapComplete/blob/develop/assets/layers/crab_address/crab_address.json)