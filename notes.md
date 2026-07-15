# Ongoing notes

This is the working notebook for the STL → VTT workflow. Keep observations tied to a model, scene scale, Blender version, and output size whenever possible.

## Known good starting points

- Freestyle thickness `1` has been the best starting point so far.
- Sun + Area Light gives a useful balance of broad visibility and directional portrait light.
- Ambient Occlusion is easiest to judge through the final orthographic camera.
- Linked Flat Faces + Circle Select is the core face-selection workflow for fused STL meshes.
- Large miniatures may need much larger AO distance values than smaller characters.

## Version-specific notes

Record the following whenever a menu path changes:

| Date | Blender version | Feature / panel | What changed or worked | Model / scale |
| --- | --- | --- | --- | --- |
|  |  |  |  |  |

Useful feature names to search for when a path differs:

- Ambient Occlusion
- Fast GI Approximation
- Raytracing
- Freestyle
- Film → Transparent
- Orthographic camera

## Experiments to run

- Compare a warm key light with a cool key light.
- Test silhouette-only Freestyle for very small tokens.
- Compare flat-color materials with slightly varied roughness.
- Record AO distance for small, medium, and giant-sized models.
- Test portrait and square-token crops from the same transparent master render.

## Screenshot backlog

The most useful screenshots to add to `assets/` later are:

- Material Properties with material slots and Assign visible
- Linked Flat Faces menu and angle setting
- Camera Properties showing Orthographic and Orthographic Scale
- Eevee / AO controls in the current Blender version
- Freestyle enablement and line thickness
- Output Properties showing PNG and RGBA
