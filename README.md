# Blender-CNC Gcode-Importer for Blendercam
G-code importer with some extra functionalities to convert from G-code to Blender curve.  
Having access to the toolspaths directly let's you do some interesting things conventional slicers can't do.  

This version was stripped of extruder information to allow mesh generation for CNC machine.

G0 and G00 are now interchangeable
G1 and G01 are now interchangeable

For some Blender operations it helps if the paths are evenly segmentized to give some modifiers the necessary resolution.  
Use the 'subdivide' option in the importer for that.


<img src=https://raw.githubusercontent.com/Heinz-Loepmeier/wiki-sources/main/gcode-importer-docs/import.gif>

### Compatibility
Add-On works with Blender 2.8. I tested on 2.92 with G-code from f-engrave andd carbide create.  
All G1 and G0 commands get drawn as an edge. (Travel lines get omitted)




