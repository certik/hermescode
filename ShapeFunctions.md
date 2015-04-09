## Introduction ##

The table below summarizes all shapesets in hermes2d. It's always in the from `shapeset (generator of the shapeset)`:

| | **Triangles** | **Quads** |
|:|:--------------|:----------|
| **H1** | shapeset\_h1\_beuchler.cpp, shapeset\_h1\_ortho.cpp | shapeset\_h1\_quad.cpp (gen\_h1\_simple\_quad.cpp), shapeset\_h1\_eigen.cpp |
| **Hcurl** | shapeset\_hc\_legendre.cpp (gen\_hc\_leg.cpp), shapeset\_hc\_gradleg.cpp (gen\_hc\_gradleg\_triang.cpp) | shapeset\_hc\_eigen2.cpp, shapeset\_hc\_gradeigen.cpp (gen\_hc\_gradeigen.cpp) |
| **Hdiv** |  | shapeset\_hd\_legendre.cpp (gen\_hdiv\_leg.cpp) |
| **L2** |  |  |

## Missing Generators ##

The following shapesets in hermes2d don't have a generator in the `src/gen` directory:

shapeset\_h1\_beuchler.cpp, shapeset\_h1\_ortho.cpp, shapeset\_h1\_eigen.cpp, shapeset\_hc\_eigen2.cpp

## Missing Shapeses ##

The following shapesets have a generator, but are not generated in hermes2d:

gen\_hc\_gradleg.cpp