Remove light object while keeping the emitted light
+ Select
+ Object properties
+ 
camera
ray visibilllllllllllll

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