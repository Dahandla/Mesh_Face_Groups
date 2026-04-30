# Mesh Face Groups Free

Mesh Face Groups Free is the no-cost preview edition of the Mesh Face Groups Blender add-on. It creates Meshmixer-style colored face groups on a selected mesh and includes basic cleanup tools.

This Free edition does **not** contain the Pro implementation for separated objects, watertight parts, shell thickness, exploded views, or batch/output workflows.


![image](https://github.com/Dahandla/Mesh_Face_Groups/blob/298a3ba7669853890e407ce577ed128fbdb31cfd/Images/Screenshot%202026-04-30%20133058.png)

## Included In Free

- Colored face-group preview.
- Refresh Face Groups operator.
- Angle threshold control.
- Size threshold filtering.
- Small island cleanup.
- Floating island filtering.
- Delete Floating Islands operator.
- Basic status display.

## Warranty Disclaimer

Mesh Face Groups Free is provided as is. Read `AS_IS_DISCLAIMER.md` before installing or distributing the add-on.

## Pro Features Not Included

![image](https://github.com/Dahandla/Mesh_Face_Groups/blob/ca2d819fbeb1507ba0553eade68e2f2b4607cfd6/Images/Screenshot%202026-04-29%20112717.png)

- Separate groups into new objects.
- Make separated parts watertight.
- Apply shell thickness.
- Auto-hide source mesh.
- Explode separated parts.
- Batch/output workflow.

## Install

1. Open Blender.
2. Go to `Edit > Preferences > Add-ons`.
3. Click `Install...`.
4. Select `dist/mesh_face_groups_free_v1.3.0.zip`.
5. Enable `Mesh Face Groups Free`.
6. Open `3D Viewport > Sidebar (N) > Face Groups > Face Group Tools Free`.

Install zips are structured for direct Blender installation with `blender_manifest.toml` and `__init__.py` at the archive root.



## Basic Usage

1. Select a mesh object.
2. Switch to Object Mode.
3. Open the `Face Groups` sidebar tab.
4. Enable `Live Preview`.
5. Tune `Angle Threshold`.
6. Click `Refresh Face Groups`.
7. Use `Delete Floating Islands` if the mesh contains small disconnected debris.

## Upgrade Path

Upgrade to Mesh Face Groups Pro when you need to convert colored groups into actual part objects, fill part holes, apply thickness, or create exploded part views.

## Distribution Note

The Free edition is a separate source package. Pro feature code is not included in this package.

## Videos
https://www.youtube.com/playlist?list=PLNkqxVhFvsiR06ETzBniApZv5p_eY1ENm
