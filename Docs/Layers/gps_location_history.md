gps_location_history
======================





Meta layer which contains the previous locations of the user as single points. This is mainly for technical reasons,
e.g. to keep match the distance to the modified object

## Table of contents

1. [gps_location_history](#gps_location_history)

- [Basic tags for this layer](#basic-tags-for-this-layer)
- [Supported attributes](#supported-attributes)


- This layer cannot be toggled in the filter view. If you import this layer in your theme, override `title` to make this
  toggleable.
- Not visible in the layer selection by default. If you want to make this layer toggable, override `name`
- Not rendered on the map by default. If you want to rendering this on the map, override `mapRenderings`

[Go to the source code](../assets/layers/gps_location_history/gps_location_history.json)



Basic tags for this layer
---------------------------



Elements must have the all of following tags to be shown on this layer:

- <a href='https://wiki.openstreetmap.org/wiki/Key:user:location' target='_blank'>user:location</a>
  =<a href='https://wiki.openstreetmap.org/wiki/Tag:user:location%3Dyes' target='_blank'>yes</a>

Supported attributes
----------------------



This document is autogenerated from assets/layers/gps_location_history/gps_location_history.json