# 2.5.0:

### Major updates
    
### Updates
- Added `camera.isInFrustum` and `camera.isCompletelyInFrustum`. Can be used with meshes, submeshes and boundingInfo ([deltakosh](https://github.com/deltakosh)) 
- Several memory allocation reduction ([benaadams](https://github.com/benaadams)) 
- Several GPU state change reduction ([benaadams](https://github.com/benaadams)) 
- MapTexture: add `supersample` mode to double font quality. ([nockawa](https://github.com/nockawa))
- new `invertUV` parameter an all ribbon based shapes : ribbon, tube, lathe, basic and custom extrusion
- Text2D: new `fontSuperSample` setting to use high quality font.

### Exporters
    
### API doc

### Bug fixes
- MapTexture: Font Characters are now correctly aligned on Chrome ([nockawa](https://github.com/nockawa))
-  Fixed some missing parameter default values in `MeshBuilder.CreateGroundFromHeightMap()` and `MeshBuilder.CreateTiledGround()` ([jerome](https://github.com/jbousquie))
- Fixed model shape initial red vertex color set to zero not formerly being taken in account in the `SolidParticleSystem` ([jerome](https://github.com/jbousquie))
- Canvas2D:
 - `Sprite2D`: texture size is now set by default as expected
 - `Sprite2D`: can have no `id` set
 - `ZOrder` fixed in Primitives created inline
### Breaking changes

