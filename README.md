# model-animation
Resources and examples for animating assemblies

## Making Assembly
Make an assembly in your CAD program of choice and export as a qlTF file either directly or export a step file, import into FreeCAD and export there.

## CADQuery Assembly
CADQuery is an excellent option for making assemblies.
Assign names programmatically as needed.
Assemblies are easier to edit and maintain when the relationships are more literal than
is possible with most CAD systems.

+ CADQuery Assemblies: https://cadquery.readthedocs.io/en/latest/assy.html 

## Steps
1. Export assembly in FreeCAD as a glTF. This will maintain the names in the assembly.
2. Import into blender
3. Write the script describing the part movement or do using the GUI 
4. Run script
5. Setup view port, scene, cameras, etc.
6. Render the video or image export of frames (https://docs.blender.org/manual/en/latest/render/output/animation.html)

## Resources
+ https://github.com/funwithtriangles/blender-to-threejs-export-guide
+ https://github.com/MinaPecheux
+ https://github.com/CommonWealthRobotics/BowlerStudio
+ Blender API: https://docs.blender.org/api/current/index.html
+ Blender Script Animation Example, excellent blog post: https://demando.io/blog/dev-generating-a-procedural-solar-system-with-blenders-python-api
+ Good YouTube Channel: https://www.youtube.com/watch?v=KFb4r8UVO0A&list=PLscNcVn_eHIdD3ZIbUKd946KX8VFIJXsJ&index=1
