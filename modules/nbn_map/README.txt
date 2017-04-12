NBN Map taxon formatter output module.

This module allows formatters to be added to the list of taxon formatter presets
which use the NBN EasyMap web service to return a distribution map for a species.

Theme functions
===============

theme_nbn_map_output($args)
--------------------------------------------

Creates the final HTML output for the map. 
$args['image_path'] is the path to the EasyMap service with all parameters.
The $args['preset']['settings'] includes width, height, and border elements.