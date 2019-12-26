# GMap.NET - Maps For Windows

![GMap.Net](https://raw.githubusercontent.com/judero01col/GMap.NET/master/GMap.ico "this is the result")

GMap.NET Windows Forms & Presentation is an excellent open source, powerful, free and cross-platform .NET control.
Allows the use of routing, geocoding, directions and maps from Google, Yahoo!, Bing, OpenStreetMap, ArcGIS, Pergo, SigPac, Yendux, Mapy.cz, Maps.lt, iKarte.lv, NearMap, HereMap, CloudMade, WikiMapia, MapQuest and many more.

# Installing
This customized version is not available via nugget; refer to the upstream package https://github.com/judero01col/GMap.NET

If you wish to use this build, clone or download the sources and build the library. Should be simple enough. 

# Documentation
https://github.com/judero01col/GMap.NET/wiki

# Release Notes
We will follow upstream versioning; so refer to https://github.com/judero01col/GMap.NET for changes.
Changes listed here are additional changes applied on top of the base library.

## GMap.NET.Core
- None

## GMap.NET.WinForms

### Fixed tracking of multiple mouse cursor states
Fixed a problem tracking the previous mouse cursor when doing multiple actions at the same time.

### Support for more complex marker shapes.
- GMapMarker provides 3 new virtual Contains() methods to determine whether a point is within a marker. Used for mouse over. 
- GMapPolygon IsInside() and IsInsideLocal() are marked public virtual.
- GMapRoute IsInside () is marked public virtual.

### Marker provides a PositionChanged event.

### Monospace tooltips

### .Net 4.6.2 as the primary target framework
