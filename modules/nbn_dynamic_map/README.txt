NBN Map taxon formatter output module.

This module allows formatters to be added to the list of taxon formatter presets
which use the NBN WMS web services to return a distribution map for a species, 
overlaid onto an OpenLayers map.

Theme functions
===============

theme_nbn_dynamic_map_output($map, $preset)
--------------------------------------------

Creates the final HTML output for the map.  
$map contains the dynamic map.
$preset['settings'] includes width and height elements.