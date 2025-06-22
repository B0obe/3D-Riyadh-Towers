# Technical Specifications for Riyadh Towers 3D Models

## Model Details

### Kingdom Tower (Burj Al-Mamlaka)
- **Polygon Count:** ~150,000 polygons (high-resolution version)
- **Reduced Version:** ~50,000 polygons (optimized for real-time)
- **Texture Maps:**
  - Diffuse/Albedo (4K)
  - Normal Maps (4K)
  - Roughness Maps (2K)
  - Metallic Maps (2K)
  - Ambient Occlusion (2K)
- **Scale:** 1:100 accurate to real-world dimensions
- **Dimensions:** Accurately scaled to 302 meters (992 ft)

### Al-Faisaliah Tower
- **Polygon Count:** ~130,000 polygons (high-resolution version)
- **Reduced Version:** ~40,000 polygons (optimized for real-time)
- **Texture Maps:**
  - Diffuse/Albedo (4K)
  - Normal Maps (4K)
  - Roughness Maps (2K)
  - Metallic Maps (2K)
  - Ambient Occlusion (2K)
- **Scale:** 1:100 accurate to real-world dimensions
- **Dimensions:** Accurately scaled to 267 meters (876 ft)

### Flip Tower
- **Polygon Count:** ~120,000 polygons (high-resolution version)
- **Reduced Version:** ~35,000 polygons (optimized for real-time)
- **Texture Maps:**
  - Diffuse/Albedo (4K)
  - Normal Maps (4K)
  - Roughness Maps (2K)
  - Metallic Maps (2K)
  - Ambient Occlusion (2K)
- **Scale:** 1:100 accurate to real-world dimensions
- **Dimensions:** Accurately scaled to match real-world reference

## Software Compatibility

### 3D Software
- Blender 2.8+
- Maya 2020+
- 3ds Max 2020+
- Cinema 4D R20+
- Houdini 18+
- ZBrush 2021+

### Game Engines
- Unity 2019.4+
- Unreal Engine 4.25+
- Unreal Engine 5
- Godot 3.2+

### AR/VR Platforms
- Snapchat Lens Studio
- Meta Spark AR Studio
- Google ARCore
- Apple ARKit
- Unity XR
- SteamVR

## File Formats Included

### Kingdom Tower
- FBX (Binary)
- OBJ with MTL
- GLTF/GLB
- Blender (.blend)

### Al-Faisaliah Tower
- FBX (Binary)
- OBJ with MTL
- GLTF/GLB
- Blender (.blend)

### Flip Tower
- FBX (Binary)
- OBJ with MTL
- GLTF/GLB
- Blender (.blend)

## Material Setup

All models include:
- PBR materials setup for Physically Based Rendering
- Material assignments for architectural elements
- Ready-to-use shader networks for popular engines
- Material IDs for custom texture application

## Technical Considerations for AR Use

### Snapchat Lens Compatibility
- Low-poly versions optimized to meet Snapchat's performance guidelines
- Texture sizes reduced to 1K for mobile optimization
- Material complexity reduced for real-time performance
- Triangle count optimized for mobile rendering

### Size Optimization
- LOD (Level of Detail) configurations included
- Texture atlasing for reduced draw calls
- Optimized UV layouts for texture efficiency
- Normal map baking from high-poly to low-poly versions

## Creation Process
Each model was created following this workflow:
1. Reference gathering and architectural research
2. Blockout modeling of major structures
3. Detailed modeling of architectural features
4. UV unwrapping and texture coordinate optimization
5. High-resolution texture creation and PBR material setup
6. Optimization and LOD generation for real-time use
7. Testing in target platforms and performance benchmarking

## Rendering Information
Example renders were created with:
- HDRI environment lighting
- Area lights for architectural highlighting
- Glass material simulation with reflections and refractions
- Post-processing for color grading and atmospheric effects 