[vtp3-pavement web map app](http://vtrans.maps.arcgis.com/apps/webappviewer/index.html?id=c4e33f213ee84cb4b69ab44cf73445d8)
=============

[latest services](http://vtransmap01.aot.state.vt.us/arcgis/rest/services/vtp3/PavementCondition2013/FeatureServer)

"My road is in terrible condition. When was the last time it was paved? When will it be paved next?"

##dtims procedure
1. add fields (project year name number)to current condition tables
2. create and run table transformations using most length and max value

##10212014
1. various errors encountered on imports and transformations
2. project year addition ready for gdb creation tomorrow

##10222014
1. gdb's and symbology created for ago publish
2. ago map, app, and feature service created
3. made ago thumbnails

##10232014
1. add route and town to pop up enhancement task identified
2. adding attributes and populating in dtims
3. fixing tables for service publish

##10242014
1. regenerate pavement condition web app
2. pretty up for monday presentation

##10272014
1. see timebox1 readme in roadmap for meeting notes
2. pulling historic condition data from 2008-2013 for charting of comp index
3. fixed bridge closure link for missing links

##10282014
1. Added States/Provinces Boundary backgorund layer for popping VT look.
2. Set filter on States/Provinces Boundary to ("postal" is not "VT") and Fill Transperency to 70%.
3. created expressions and transformations in dtims to create historic condition data

##10292014
1. created and published historic condition data service, remade map, remade app with new template format
2. added historic chart popup and projects to map
