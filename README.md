# model-animation
Resources and examples for animating assemblies.

In animation this process is often called [rigging](https://www.adobe.com/uk/creativecloud/animation/discover/rigging.html). Rigging controls the movement of a "skeleton" made of "bones" that has a "skin" on it.

Checkout the [Blender docs](https://docs.blender.org/manual/en/latest/animation/introduction.html) for more of an explanation.

## Uses
+ Make explosion videos
+ Make video of assembly process of an assembly ensuring correct order


## Making Assembly
Make an assembly in your CAD program of choice and export as a glTF file either directly or export a step file, import into FreeCAD and export there.

It is important to use glTF when importing as that maintains the name of the subobjects allowing the blender scripting to reference via the assembly name.

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
Seems the best place to ask questions is the [Discord](https://discord.com/invite/blender)

### Videos
+ https://www.youtube.com/watch?v=n27rgkp5UmQ
+ Good YouTube Channel: https://www.youtube.com/watch?v=KFb4r8UVO0A&list=PLscNcVn_eHIdD3ZIbUKd946KX8VFIJXsJ&index=1
+ https://www.youtube.com/watch?v=gAYdVjvSeew
+ RigaCar: There's a series of videos that give a good outline of the rigging process. Although not the same problem as the general assembly it is solid background info. https://digicreatures.net/articles/rigacar.html
+ Assembly Explosion: https://www.youtube.com/watch?v=IC0-9b0Rv2g
+ Lego Assembly Geo Nodes: https://www.youtube.com/watch?v=UzocW9RtOOQ

### Repos
+ https://github.com/funwithtriangles/blender-to-threejs-export-guide
+ https://github.com/MinaPecheux
+ https://github.com/CommonWealthRobotics/BowlerStudio

### Examples
+ Blender Script Animation Example, excellent blog post: https://demando.io/blog/dev-generating-a-procedural-solar-system-with-blenders-python-api
+ Blender Assembly Explosion Tool: https://blendermarket.com/products/blender-exploder-tool

### Manuals
+ Blender API: https://docs.blender.org/api/current/index.html
+ List of useful Blender tools: https://github.com/agmmnn/awesome-blender
