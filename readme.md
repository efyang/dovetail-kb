# custom keyboard

Uses a modified version of ergogen that supports placing arbitrary library parts.

![Top Down](images/topdown.jpg)
![Tilted](images/tilted.jpg)
![Bottom](images/bottom.jpg)
### FreeCAD Pics (some parts don't make it)
![Flat Orthographic](images/flat-orthographic.png)
![Tented Orthographic](images/tent-orthographic.png)
![Tented Perspective](images/tent-perspective.png)

## Features
- underglow
- trackpad (tm035035-2024-003)
- solder-on 90-degree thumb clusters
- choc spacing
- 36 keys

To update using ergogen:
- `node ergogen/src/cli.js ergogen.yaml -o .`
- Open pcb in pcbnew
- Tools -> Update Footprints from Library
- Check all "Update Options"
- Update

## Notes
- Designed for 3.3v power/logic (kb2040)
    - if you want to use 5v then you have to desolder more on the trackpad pcb
