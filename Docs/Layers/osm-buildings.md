osm-buildings
===============

## Table of contents

1. [osm-buildings](#osm-buildings)

- [Basic tags for this layer](#basic-tags-for-this-layer)
- [Supported attributes](#supported-attributes)
    + [apply_streetname](#apply_streetname)


- Not rendered on the map by default. If you want to rendering this on the map, override `mapRenderings`
- This layer will automatically load  [crab_address](./crab_address.md)  into the layout as it depends on it:  A
  calculated tag loads features from this layer (calculatedTag[0] which calculates the value for _
  embedded_crab_addresses)
- This layer will automatically load  [named_streets](./named_streets.md)  into the layout as it depends on it:  A
  calculated tag loads features from this layer (calculatedTag[3] which calculates the value for _nearby_street_names)
- This layer is needed as dependency for layer [grb](#grb)
- This layer is needed as dependency for layer [grb](#grb)

[Go to the source code](../assets/layers/osm-buildings/osm-buildings.json)



Basic tags for this layer
---------------------------



Elements must have the all of following tags to be shown on this layer:

- building~^..*$
- addr:housenumber~^..*$
-

Supported attributes
----------------------

### apply_streetname

_This tagrendering has no question and is thus read-only_

- **No nearby street has the same name. The CRAB-name is {_name_to_apply}** corresponds
  with <a href='https://wiki.openstreetmap.org/wiki/Key:_spelling_is_correct' target='_blank'>_spelling_is_correct</a>
  =<a href='https://wiki.openstreetmap.org/wiki/Tag:_spelling_is_correct%3Dfalse' target='_blank'>false</a>
- **There are multiple streetnames applicable here** corresponds
  with <a href='https://wiki.openstreetmap.org/wiki/Key:_singular_import' target='_blank'>_singular_import</a>
  =<a href='https://wiki.openstreetmap.org/wiki/Tag:_singular_import%3Dfalse' target='_blank'>false</a>

This document is autogenerated from assets/layers/osm-buildings/osm-buildings.json