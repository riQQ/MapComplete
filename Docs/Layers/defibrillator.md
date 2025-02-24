

 defibrillator 
===============



<img src='https://mapcomplete.osm.be/./assets/themes/aed/aed.svg' height="100px"> 

A layer showing defibrillators which can be used in case of emergency. This contains public defibrillators, but also defibrillators which might need staff to fetch the actual device




## Table of contents

1. [defibrillator](#defibrillator)
      * [Themes using this layer](#themes-using-this-layer)
  - [Basic tags for this layer](#basic-tags-for-this-layer)
  - [Supported attributes](#supported-attributes)
    + [images](#images)
    + [defibrillator-indoors](#defibrillator-indoors)
    + [defibrillator-access](#defibrillator-access)
    + [defibrillator-defibrillator](#defibrillator-defibrillator)
    + [defibrillator-level](#defibrillator-level)
    + [defibrillator-defibrillator:location](#defibrillator-defibrillatorlocation)
    + [defibrillator-defibrillator:location:en](#defibrillator-defibrillatorlocation:en)
    + [defibrillator-defibrillator:location:fr](#defibrillator-defibrillatorlocation:fr)
    + [wheelchair-access](#wheelchair-access)
    + [defibrillator-ref](#defibrillator-ref)
    + [defibrillator-email](#defibrillator-email)
    + [defibrillator-phone](#defibrillator-phone)
    + [defibrillator-opening_hours](#defibrillator-opening_hours)
    + [defibrillator-description](#defibrillator-description)
    + [defibrillator-survey:date](#defibrillator-surveydate)
    + [defibrillator-fixme](#defibrillator-fixme)





  - This layer will automatically load  [walls_and_buildings](./walls_and_buildings.md)  into the layout as it depends on it:  a preset snaps to this layer (presets[1])




#### Themes using this layer 





  - [aed](https://mapcomplete.osm.be/aed)
  - [personal](https://mapcomplete.osm.be/personal)


[Go to the source code](https://github.com/pietervdvn/MapComplete/blob/develop/assets/layers/defibrillator/defibrillator.json)



 Basic tags for this layer 
---------------------------



Elements must have the all of following tags to be shown on this layer:



  - <a href='https://wiki.openstreetmap.org/wiki/Key:emergency' target='_blank'>emergency</a>=<a href='https://wiki.openstreetmap.org/wiki/Tag:emergency%3Ddefibrillator' target='_blank'>defibrillator</a>


[Execute on overpass](http://overpass-turbo.eu/?Q=%5Bout%3Ajson%5D%5Btimeout%3A90%5D%3B(%20%20%20%20nwr%5B%22emergency%22%3D%22defibrillator%22%5D(%7B%7Bbbox%7D%7D)%3B%0A)%3Bout%20body%3B%3E%3Bout%20skel%20qt%3B)



 Supported attributes 
----------------------



**Warning** This quick overview is incomplete



attribute | type | values which are supported by this layer
----------- | ------ | ------------------------------------------
[<img src='https://mapcomplete.osm.be/assets/svg/statistics.svg' height='18px'>](https://taginfo.openstreetmap.org/keys/indoor#values) [indoor](https://wiki.openstreetmap.org/wiki/Key:indoor) | Multiple choice | [yes](https://wiki.openstreetmap.org/wiki/Tag:indoor%3Dyes) [no](https://wiki.openstreetmap.org/wiki/Tag:indoor%3Dno)
[<img src='https://mapcomplete.osm.be/assets/svg/statistics.svg' height='18px'>](https://taginfo.openstreetmap.org/keys/access#values) [access](https://wiki.openstreetmap.org/wiki/Key:access) | [string](../SpecialInputElements.md#string) | [yes](https://wiki.openstreetmap.org/wiki/Tag:access%3Dyes) [customers](https://wiki.openstreetmap.org/wiki/Tag:access%3Dcustomers) [private](https://wiki.openstreetmap.org/wiki/Tag:access%3Dprivate) [no](https://wiki.openstreetmap.org/wiki/Tag:access%3Dno)
[<img src='https://mapcomplete.osm.be/assets/svg/statistics.svg' height='18px'>](https://taginfo.openstreetmap.org/keys/defibrillator#values) [defibrillator](https://wiki.openstreetmap.org/wiki/Key:defibrillator) | Multiple choice | [manual](https://wiki.openstreetmap.org/wiki/Tag:defibrillator%3Dmanual) [automatic](https://wiki.openstreetmap.org/wiki/Tag:defibrillator%3Dautomatic)
[<img src='https://mapcomplete.osm.be/assets/svg/statistics.svg' height='18px'>](https://taginfo.openstreetmap.org/keys/level#values) [level](https://wiki.openstreetmap.org/wiki/Key:level) | [int](../SpecialInputElements.md#int) | [0](https://wiki.openstreetmap.org/wiki/Tag:level%3D0) [1](https://wiki.openstreetmap.org/wiki/Tag:level%3D1)
[<img src='https://mapcomplete.osm.be/assets/svg/statistics.svg' height='18px'>](https://taginfo.openstreetmap.org/keys/defibrillator:location#values) [defibrillator:location](https://wiki.openstreetmap.org/wiki/Key:defibrillator:location) | [text](../SpecialInputElements.md#text) | 
[<img src='https://mapcomplete.osm.be/assets/svg/statistics.svg' height='18px'>](https://taginfo.openstreetmap.org/keys/defibrillator:location:en#values) [defibrillator:location:en](https://wiki.openstreetmap.org/wiki/Key:defibrillator:location:en) | [text](../SpecialInputElements.md#text) | 
[<img src='https://mapcomplete.osm.be/assets/svg/statistics.svg' height='18px'>](https://taginfo.openstreetmap.org/keys/defibrillator:location:fr#values) [defibrillator:location:fr](https://wiki.openstreetmap.org/wiki/Key:defibrillator:location:fr) | [text](../SpecialInputElements.md#text) | 
[<img src='https://mapcomplete.osm.be/assets/svg/statistics.svg' height='18px'>](https://taginfo.openstreetmap.org/keys/wheelchair#values) [wheelchair](https://wiki.openstreetmap.org/wiki/Key:wheelchair) | Multiple choice | [designated](https://wiki.openstreetmap.org/wiki/Tag:wheelchair%3Ddesignated) [yes](https://wiki.openstreetmap.org/wiki/Tag:wheelchair%3Dyes) [limited](https://wiki.openstreetmap.org/wiki/Tag:wheelchair%3Dlimited) [no](https://wiki.openstreetmap.org/wiki/Tag:wheelchair%3Dno)
[<img src='https://mapcomplete.osm.be/assets/svg/statistics.svg' height='18px'>](https://taginfo.openstreetmap.org/keys/ref#values) [ref](https://wiki.openstreetmap.org/wiki/Key:ref) | [text](../SpecialInputElements.md#text) | 
[<img src='https://mapcomplete.osm.be/assets/svg/statistics.svg' height='18px'>](https://taginfo.openstreetmap.org/keys/email#values) [email](https://wiki.openstreetmap.org/wiki/Key:email) | [email](../SpecialInputElements.md#email) | 
[<img src='https://mapcomplete.osm.be/assets/svg/statistics.svg' height='18px'>](https://taginfo.openstreetmap.org/keys/phone#values) [phone](https://wiki.openstreetmap.org/wiki/Key:phone) | [phone](../SpecialInputElements.md#phone) | 
[<img src='https://mapcomplete.osm.be/assets/svg/statistics.svg' height='18px'>](https://taginfo.openstreetmap.org/keys/opening_hours#values) [opening_hours](https://wiki.openstreetmap.org/wiki/Key:opening_hours) | [opening_hours](../SpecialInputElements.md#opening_hours) | [24/7](https://wiki.openstreetmap.org/wiki/Tag:opening_hours%3D24/7)
[<img src='https://mapcomplete.osm.be/assets/svg/statistics.svg' height='18px'>](https://taginfo.openstreetmap.org/keys/description#values) [description](https://wiki.openstreetmap.org/wiki/Key:description) | [text](../SpecialInputElements.md#text) | 
[<img src='https://mapcomplete.osm.be/assets/svg/statistics.svg' height='18px'>](https://taginfo.openstreetmap.org/keys/survey:date#values) [survey:date](https://wiki.openstreetmap.org/wiki/Key:survey:date) | [date](../SpecialInputElements.md#date) | [](https://wiki.openstreetmap.org/wiki/Tag:survey:date%3D)
[<img src='https://mapcomplete.osm.be/assets/svg/statistics.svg' height='18px'>](https://taginfo.openstreetmap.org/keys/fixme#values) [fixme](https://wiki.openstreetmap.org/wiki/Key:fixme) | [text](../SpecialInputElements.md#text) | 




### images 



_This tagrendering has no question and is thus read-only_





### defibrillator-indoors 



The question is **Is this defibrillator located indoors?**





  - **This defibrillator is located indoors** corresponds with <a href='https://wiki.openstreetmap.org/wiki/Key:indoor' target='_blank'>indoor</a>=<a href='https://wiki.openstreetmap.org/wiki/Tag:indoor%3Dyes' target='_blank'>yes</a>
  - **This defibrillator is located outdoors** corresponds with <a href='https://wiki.openstreetmap.org/wiki/Key:indoor' target='_blank'>indoor</a>=<a href='https://wiki.openstreetmap.org/wiki/Tag:indoor%3Dno' target='_blank'>no</a>




### defibrillator-access 



The question is **Is this defibrillator freely accessible?**

This rendering asks information about the property  [access](https://wiki.openstreetmap.org/wiki/Key:access) 
This is rendered with `Access is {access}`



  - **Publicly accessible** corresponds with <a href='https://wiki.openstreetmap.org/wiki/Key:access' target='_blank'>access</a>=<a href='https://wiki.openstreetmap.org/wiki/Tag:access%3Dyes' target='_blank'>yes</a>
  - **Publicly accessible** corresponds with <a href='https://wiki.openstreetmap.org/wiki/Key:access' target='_blank'>access</a>=<a href='https://wiki.openstreetmap.org/wiki/Tag:access%3Dpublic' target='_blank'>public</a>_This option cannot be chosen as answer_
  - **Only accessible to customers** corresponds with <a href='https://wiki.openstreetmap.org/wiki/Key:access' target='_blank'>access</a>=<a href='https://wiki.openstreetmap.org/wiki/Tag:access%3Dcustomers' target='_blank'>customers</a>
  - **Not accessible to the general public (e.g. only accesible to staff, the owners, ...)** corresponds with <a href='https://wiki.openstreetmap.org/wiki/Key:access' target='_blank'>access</a>=<a href='https://wiki.openstreetmap.org/wiki/Tag:access%3Dprivate' target='_blank'>private</a>
  - **Not accessible, possibly only for professional use** corresponds with <a href='https://wiki.openstreetmap.org/wiki/Key:access' target='_blank'>access</a>=<a href='https://wiki.openstreetmap.org/wiki/Tag:access%3Dno' target='_blank'>no</a>




### defibrillator-defibrillator 



The question is **Is this a a regular automatic defibrillator or a manual defibrillator for professionals only?**





  - **There is no info about the type of device** corresponds with _This option cannot be chosen as answer_
  - **This is a manual defibrillator for professionals** corresponds with <a href='https://wiki.openstreetmap.org/wiki/Key:defibrillator' target='_blank'>defibrillator</a>=<a href='https://wiki.openstreetmap.org/wiki/Tag:defibrillator%3Dmanual' target='_blank'>manual</a>
  - **This is a normal automatic defibrillator** corresponds with <a href='https://wiki.openstreetmap.org/wiki/Key:defibrillator' target='_blank'>defibrillator</a>=<a href='https://wiki.openstreetmap.org/wiki/Tag:defibrillator%3Dautomatic' target='_blank'>automatic</a>
  - **This is a special type of defibrillator: {defibrillator}** corresponds with defibrillator~^..*$_This option cannot be chosen as answer_




### defibrillator-level 



The question is **On which floor is this defibrillator located?**

This rendering asks information about the property  [level](https://wiki.openstreetmap.org/wiki/Key:level) 
This is rendered with `This defibrillator is on floor {level}`



  - **This defibrillator is on the <b>ground floor</b>** corresponds with <a href='https://wiki.openstreetmap.org/wiki/Key:level' target='_blank'>level</a>=<a href='https://wiki.openstreetmap.org/wiki/Tag:level%3D0' target='_blank'>0</a>
  - **This defibrillator is on the <b>first floor</b>** corresponds with <a href='https://wiki.openstreetmap.org/wiki/Key:level' target='_blank'>level</a>=<a href='https://wiki.openstreetmap.org/wiki/Tag:level%3D1' target='_blank'>1</a>




### defibrillator-defibrillator:location 



The question is **Please give some explanation on where the defibrillator can be found (in the local language)**

This rendering asks information about the property  [defibrillator:location](https://wiki.openstreetmap.org/wiki/Key:defibrillator:location) 
This is rendered with `<i>Extra information about the location (in the local languagel):</i><br/>{defibrillator:location}`



### defibrillator-defibrillator:location:en 



The question is **Please give some explanation on where the defibrillator can be found (in English)**

This rendering asks information about the property  [defibrillator:location:en](https://wiki.openstreetmap.org/wiki/Key:defibrillator:location:en) 
This is rendered with `<i>Extra information about the location (in English):</i><br/>{defibrillator:location:en}`



### defibrillator-defibrillator:location:fr 



The question is **Please give some explanation on where the defibrillator can be found (in French)**

This rendering asks information about the property  [defibrillator:location:fr](https://wiki.openstreetmap.org/wiki/Key:defibrillator:location:fr) 
This is rendered with `<i>Extra information about the location (in French):</i><br/>{defibrillator:location:fr}`



### wheelchair-access 



The question is **Is this place accessible with a wheelchair?**





  - **This place is specially adapted for wheelchair users** corresponds with <a href='https://wiki.openstreetmap.org/wiki/Key:wheelchair' target='_blank'>wheelchair</a>=<a href='https://wiki.openstreetmap.org/wiki/Tag:wheelchair%3Ddesignated' target='_blank'>designated</a>
  - **This place is easily reachable with a wheelchair** corresponds with <a href='https://wiki.openstreetmap.org/wiki/Key:wheelchair' target='_blank'>wheelchair</a>=<a href='https://wiki.openstreetmap.org/wiki/Tag:wheelchair%3Dyes' target='_blank'>yes</a>
  - **It is possible to reach this place in a wheelchair, but it is not easy** corresponds with <a href='https://wiki.openstreetmap.org/wiki/Key:wheelchair' target='_blank'>wheelchair</a>=<a href='https://wiki.openstreetmap.org/wiki/Tag:wheelchair%3Dlimited' target='_blank'>limited</a>
  - **This place is not reachable with a wheelchair** corresponds with <a href='https://wiki.openstreetmap.org/wiki/Key:wheelchair' target='_blank'>wheelchair</a>=<a href='https://wiki.openstreetmap.org/wiki/Tag:wheelchair%3Dno' target='_blank'>no</a>




### defibrillator-ref 



The question is **What is the official identification number of the device? (if visible on device)**

This rendering asks information about the property  [ref](https://wiki.openstreetmap.org/wiki/Key:ref) 
This is rendered with `Official identification number of the device: <i>{ref}</i>`



### defibrillator-email 



The question is **What is the email for questions about this defibrillator?**

This rendering asks information about the property  [email](https://wiki.openstreetmap.org/wiki/Key:email) 
This is rendered with `Email for questions about this defibrillator: <a href='mailto:{email}'>{email}</a>`



### defibrillator-phone 



The question is **What is the phone number for questions about this defibrillator?**

This rendering asks information about the property  [phone](https://wiki.openstreetmap.org/wiki/Key:phone) 
This is rendered with `Telephone for questions about this defibrillator: <a href='tel:{phone}'>{phone}</a>`



### defibrillator-opening_hours 



The question is **At what times is this defibrillator available?**

This rendering asks information about the property  [opening_hours](https://wiki.openstreetmap.org/wiki/Key:opening_hours) 
This is rendered with `{opening_hours_table(opening_hours)}`



  - **24/7 opened (including holidays)** corresponds with <a href='https://wiki.openstreetmap.org/wiki/Key:opening_hours' target='_blank'>opening_hours</a>=<a href='https://wiki.openstreetmap.org/wiki/Tag:opening_hours%3D24/7' target='_blank'>24/7</a>




### defibrillator-description 



The question is **Is there any useful information for users that you haven't been able to describe above? (leave blank if no)**

This rendering asks information about the property  [description](https://wiki.openstreetmap.org/wiki/Key:description) 
This is rendered with `Additional information: {description}`



### defibrillator-survey:date 



The question is **When was this defibrillator last surveyed?**

This rendering asks information about the property  [survey:date](https://wiki.openstreetmap.org/wiki/Key:survey:date) 
This is rendered with `This defibrillator was last surveyed on {survey:date}`



  - **Checked today!** corresponds with survey:date=




### defibrillator-fixme 



The question is **Is there something wrong with how this is mapped, that you weren't able to fix here? (leave a note to OpenStreetMap experts)**

This rendering asks information about the property  [fixme](https://wiki.openstreetmap.org/wiki/Key:fixme) 
This is rendered with `Extra information for OpenStreetMap experts: {fixme}` 

This document is autogenerated from [assets/layers/defibrillator/defibrillator.json](https://github.com/pietervdvn/MapComplete/blob/develop/assets/layers/defibrillator/defibrillator.json)