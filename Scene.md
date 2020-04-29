# Room

💡Pivot Point on bottom, to allow scaling on floor By.

Put 3D Cursor on floor SHIFT + Right
Create plain object
Move in object mode, to keep origin at center of object
Move cursor to selected
Walls

Plane scale x4.0 Wall Extrude 0.15 Windows Inset — Loop cut — Individual Insets (i) .15

# LIGHT

1. Sun
2. Object Data Properties — Use Nodes — Strength 3.0
3. Render Properties — Cycles + Color Management — Exposure

2. Area Light
3. Object Data Properties:
    1. Orange
    2. Power 2000W

1. World Properties
    1. Surface, Color (e.g. Blue)

## For better preview…
* Render Properties
    * 📷 Ambient Occlusion
    * 📷 Bloom
    * 📷 Screen Space Reflections

Sampling
+ Path Tracing — Render 512

Light Paths (to avoid fireflies)
+ Clamping
+ Direct 5.0
Indirect 2.0

## Add Glow

Add Filter — Glare

## EVEE
📷 Render Properties —  Ambient Occlusion
📷 Render Properties — Bloom for Emitting lights

## Add Objects
+ Light Probe — Reflection Cube map
+ Light Probe — Irradiance Volume
📷 Render Properties — Screen Space Reflections

+ Shadow — High Bitdepth
+ Render — Bake Indirect Light!!

## Fog
using Volume Shader

+ Cube
+ Add material 
+ Remove default material
+ Add “Volume”
+ Volume — Volume Scatter
+ Density 0.025