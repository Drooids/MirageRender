Mirage Render
======

Mirage Render is a 3d renderer that aims for photorealistic results. Currently the software is in very early stage.

Usage
-----

```
mirage --help
LOG | Main: MirageRender, version 0.0.28
LOG | Usage: mirage.exe --script scriptfilename.lua, folder for scripts is ./res/scripts/
      Available launch parameters:
      Show this help message: --help, -h
      Load a scene file: --script, -s
LOG | Main: atexit(dispose) Hook called.
```

Example images
--------------

![Cornell Box, caustics test](img/mirage_water3.png "Cornell Box, caustics test")

_a Cornell box scene rendered using monte carlo path tracing, caustics caused by water, indirect illumination._

![Cornell Box, gi test](img/mirage_cornellbox_plight.png "Cornell Box, gi test")

_a Cornell box scene rendered using monte carlo path tracing, direct & indirect illumination._

![Cornell Box, Golden Dragon](img/golden_dragon.png "Cornell Box, glossy material test")

_a Cornell box scene with a glossy metallic floor, a golden dragon and two room surfaces acting as light sources._

![Mitsuba, Texture Mapping](img/texturemapping.png "Mitsuba, texture mapping test")

_a Mitsuba sphere, spot light source and a diffuse texture applied on the floor mesh._