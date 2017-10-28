# Workshop Info on Mapillary, OSM, and QGIS

Hi Folks in this crash course we'll be learning the following tools

1. Using Mapillary to capture photos with our phones, uploading them onto the internet to share with others.
2. With our photos online, we can access them on OpenStreetMap where we can use the images to add points of interest onto OpenStreetMap, where anyone can access them for their own research or explorations.
3. We'll end our workshop by using QGIS. We'll be able to access the data from OpenStreetMap and use it to build a simple map.

# What you will need for the workshop

* [Sign up for and OpenStreetMap Account](https://www.openstreetmap.org/user/new)
* Install Mapillary on your phone, you should be able to sign-up with your OpenStreetMap account
   * [iOS](https://itunes.apple.com/us/app/mapillary/id757286802?mt=8&ign-mpt=uo%3D4)
   * [Android](https://play.google.com/store/apps/details?id=app.mapillary)
   * If you are having issues signing up through your phone with your OpenStreetMap account, you may need to sign-up with your email either on the phone or through the [Mapillary website](https://www.mapillary.com/).
* Install QGIS
    * [Windows and Mac](http://www.qgis.org/en/site/forusers/download.html)
    * Note: Windows users have one file to download and install. Mac users have a package to download and need to install additional modules (files) for QGIS to run.
    
# What we'll do

1. Let's go outside with and do a demonstration with Mapillary
    1. [Intro to Mapillary] (https://help.mapillary.com/hc/en-us/categories/115000363489-Getting-started)
    2. We'll form groups and walk the area.
    3. Come back inside and upload our photos online.
    4. Explore our photos and others on the Mapillary website.
2. So we have our street-level photos, we can tag them on OpenStreetMap
    1. [Intro to OpenStreetMap](http://learnosm.org/en/beginner/)
    2. [Intro to the iD editor](http://learnosm.org/en/beginner/id-editor/)
    3. Here's a comprehensive [list of OSM tags](http://wiki.openstreetmap.org/wiki/Map_Features).
    4. Let's do some quick edits on [OpenStreetMap](http://www.openstreetmap.org/)!
    5. Did you know you can load Mapillary photos to iD and improve the map! [Let's try](http://blog.mapillary.com/update/2016/06/26/tools-edit-OSM.html)
    6. [Training AI to improve automated tagging](http://blog.mapillary.com/product/2017/10/18/mapillary-verifier-tool.html)
3. Now let's make a map with some OSM data!
    1. You can get OSM data from the [Overpass API](http://wiki.openstreetmap.org/wiki/Overpass_API).
        1. You can perform custom searches by tags and download them as a geojson, kml, and others for use in other mapping tools.
    2. You can also download them directly to QGIS!
    3. [Intro to QGIS](http://www.qgistutorials.com/en/)
    4. Let's prep up our QGIS working area with some nifty plugins
        1. From the plugins folder install the following plugins
        2. QuickOSM
        3. QuickMapServices
        4. OpenLayers Plugin
