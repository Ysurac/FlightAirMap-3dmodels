# FlightAirMap-3dmodels
3D models used by FlightAirMap

Models are opened in Blender, saved to dae then collada2gltf is used to convert them to gltf and gltf-pipeline to convert the gltf to glb.


    collada2gltf -f xxx.dae -o xxx.gltf -e
    
    
    gltf-pipeline.js -i xxx.gltf -o xxx.glb -b