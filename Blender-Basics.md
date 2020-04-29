## General

FN + F3 Search for command

## Viewport

Rotate OPT + Drag
Pan SHIFT + OPT + Drag
Zoom CMD + Scroll
Zoom to Selection SHIFT + B

Select all A
Insert I 

Subdivide, right click, “Subdivide”

## Create Object
+ Create flat object (circle, plane instead of box) to start with Pivot at bottom!!
+ Select existing Faces, SHIFT + D Duplicate, P Separate

## Hard Surface Modelling — Bevel
1. Use Bevel Modifier, Width 0.005 m
2. Right click object — Shade smooth

+ Limit Angle

+ Apply modifiers… Select target, SHIFT select source, CMD + L — Modifiers (Creates Linked duplicate of some aspect)

## Select Object

Select object
SHIFT + G

## Hard Surface Modelling — Surface Division, Rounded Objects
1. Right click object — Shade smooth
2. Add Subdivision Modifier
3. Add loop cuts to add rounding constraints

💡Without face, hard edge

## Hard Surface Modelling — Edge Split Modifier

Edge Angle!! Depending on edges

## Resize Planes
+ Edge select
+ g g — relational resize

💡+ Scale in object mode to enter dimenions

## Grease Pencil, 2D Mapped Drawing
1. Add 3D Cursor
2. Create Plane/extrude single verts
3. Add Grease Pencil empty
4. Select Grease pencil object
5. Switch to DRAW Mode
6. Mode Surface OR View (no plane needed)
7. Draw curves
8. Object — Convert to curves
Optional.  Add-on Simplfy Curves
+ Add Object Curves — Simplified Curve
+ Change Error, 0.1…
+ Object Data Properties — Geometry 0.01

## Extrude
Extrude e || Option e for options
E, S extrude angled
OPT + E Extrude along normals (+ S even thickness)

Skin modifier to add volume, CTRL + A change thickness/volume

## Pipes
1. Add single vert (from add-on)
2. Extrude, move…
3. Object — Convert to — Curve from Mesh
4. Object Data Properties — Geometry — Depth/Resolution

Boolean

## Organize cowmposed objects

+ Select many objects
+ SHIFT + Select partent
+ CTRL + P — Object (Keep Transform)

## Kit Bash

+ ALT + D Move
+ ALT+ P — Clear Parent and Keep Transformation

## Mirror vs Spin

Mirror X/Y/Z
Spin, Circular — use duplicate Angle 360 / Steps

## Text

+ Geometry — Extrude
+ Bevel — Depth

## Check Normals

1. Select all, Overlay show normals
2. Mesh – Normals – Recalculate Normals (SHIFT + N)

## Array along curve

1. Add object, add bezier Curve/Bezier
2. Add array modifier
3. Add curve modifier, select bezier curve

## Move Objects

Target Shift S - Cursor to selected
Object to move Shift S Selection to cursor

G Y (Global) Y again (Local)

Inset i

Z View Modes

Add SHIFT + a

## Sub object selection in edit mode
Hover + l Selected Linked Meshes from same object

## View
1, 3, 7 → 9 Shift to Mirror
OPTION + Q Pie Menu
ALT + . (Remapped from NUMPAD .) View Selected
SHIFT + Z, SHIFT + Z Rotate x/y global, local

## Reference Image

SHIFT + A, Image
1. Top View (CTRL + Q, pie)
2. Use alpha, 0.5
3. Side front (only show one side)
4. Uncheck display perspective (only show in top view)

## POLYGON MODELLING

Triangles Right click, “Triangulate” (CTRL T)
Subdivide Right click, “Subdivide”
Subdivide CTRL R, Mousewheel
Close face f
Merge close vertices - Vertex, Merge

K knife cut, click for line, z for cut through

Bevel CTRL + B, v vertex only

## CAMERA
0 Camera View
Add Camera – N Show sidepanel – 30.609 m, -30.609 m, 30.609 m
Camera Properties — Orthographic Scale

## Emitter
1. Create Emitter area, ALT + right click , move 3D Curser
2. Add plane, edit mode, vertices
3. Merge to center
4. E Extrude, left click, repeat, F fill face OR CTRL + Right Click, add points

1. Add Emitter, + setting
2. Render, render as “Object”
3. Select Object to emit
4. Set, Scale Scale Random
5. Uncheck “Show Emitter” hide for render

## SETTINGS

N Show sidepanel

## 3D CURSOR

SHIFT + Right Mousebuggon Move
select cursor to selected SHIFT + S 
!!Reset Cursor to center, SHIFT C
Delete x + delete
Hide/Show h/ALT + h

## MATERIAL

## WATER
Roughness (Reflection) 0.15
Transmission (Transparency) 0.9
IOR (Refraction?! Volume, magnifying, water depth) 

## RENDERING GPU

Render Properties, Render Engine
Settings, System CUDA

## UV MATERIAL
+ UV Editing Mode
+ Select, Smart UV Unwrap

## Room

💡Pivot Point on bottom, to allow scaling on floor
By.
+ Put 3D Cursor on floor SHIFT + Right 
+ Create plain object
+ Move in object mode, to keep origin at center of object
+ Move cursor to selected

## Walls
Plane scale x4.0
Wall Extrude 0.15
Windows Inset — Loop cut — Individual Insets (i) .15

## Windows
+ Array
+ Boolean
+ Display — Wire

## Window Segments
+ Loop Cuts for Segments
+ Bevel, single surface, .05

## Add Image

Image Add-in