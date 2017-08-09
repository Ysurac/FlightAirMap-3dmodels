# FlightAirMap-3dmodels
3D models used by FlightAirMap

Models come from https://github.com/kalmykov/fr24-3d-models and https://github.com/FGMEMBERS/

## glTF 2.0

To convert models: https://github.com/KhronosGroup/glTF-Blender-Exporter

## glTF 1.0

Models are opened in Blender, saved to dae then collada2gltf is used to convert them to gltf and gltf-pipeline to convert the gltf to glb.


    collada2gltf -f xxx.dae -o xxx.gltf -e
    
    
    gltf-pipeline.js -i xxx.gltf -o xxx.glb -b