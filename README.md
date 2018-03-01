# Quick Pie Blender Addon
Version 0.1.1 compatible with Blender 2.72+

This addon provides shortcuts to the most common and important actions in blender. 

- SPACEBAR - the most important tasks
- Q - Secondary tasks
- X - Delete options


## Installation
Install like every other addon through the addon menu. Click "Install from File.." at the bottom and select quick_pie.py. Don't forget to check the Quick Pie addon if it is unchecked.

To have the full spectrum of options in the quick pie menus add the following addons:
- BSurfaces (integrated in blender)
- LoopTools (integrated in blender)
- BoolTool 0.2 (https://github.com/vitorbalbio/code/tree/master/BoolTool)

If you have enabled the Official Pie addon you will have to uncheck the Q hotkey at the Input section.


## Usage
### Object Mode
#### Spacebar
- Flyout Settings
- Boolean Union
- Boolean Difference
- Radial Clone
- Origin to Geometry
- Join Objects
- Apply all Transformations
- Auto Smooth (30degree angle)

#### Q Key
- Flyout Settings
- Add Cube
- Add Plane
- Add Circle
- Add Monkey
- Add Camera
- Add Point
- Add Sun

#### X Key
- Remove from Group
- Delete Object
- Clear Parent
- Clear Transformations


### Edit Mode
#### Spacebar
- Flyout Settings
- Select Edge
- Select Vertex
- Select Face
- Merge at Center
- Subdivide
- Bevel Vertex
- Bevel Edge

#### Q Key
- Flyout Settings
- Circle Vertces
- Relax Vertices
- Space Vertices
- Flatten Vertices
- Inverse Selection
- Add BSurface
- Solidify

#### X Key
- Clean Up
- Delete Edges
- Delete Vertices
- Delete Faces
- Delete EdgeLoops
- Dissolve Faces
- Dissolve Vertices
- Dissolve Edges


### Sculpt Mode
#### Spacebar
- Pinch Brush
- Crease Brush
- Strips Brush
- Fill Mask
- Mask
- Invert Mask
- Grab
- Scrape

#### Q Key
- Sharp
- Line
- Max
- Mirror (DynoTopo)
- Optimize (DynoTopo)
- Enable/Disable DynoTopo
- Smooth
- Round

### X Key
- Hide Mask
- Clear Mask
- Show Masked


## Customizing
The Python file is well documented and a great template to remove and add your own operators.
