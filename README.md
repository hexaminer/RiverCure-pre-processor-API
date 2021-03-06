# RiverCure-pre-processor-API
Flask python script to run the rivercure pre processor


It is necessary to create a folder with the name simulation and the tree of histav
mesh and gmsh 4.0.7 executables should be added in the respective places

```
.
├── bed
│   ├── activeLayers
│   │   ├── bedLayers.sed
│   │   └── nodesFrictionCoef.sed
│   ├── bed.cnt
│   ├── fractionData
│   │   ├── fineSand.sed
│   │   ├── gravel.sed
│   │   └── silt.sed
│   └── gradCurves
│       ├── curve-1.sed
│       ├── curve-2.sed
│       └── curve-3.sed
├── boundary
│   ├── boundary.cnt
│   └── meshData
│       ├── boundaryDim.bnd
│       ├── boundaryIdx-0.bnd
│       ├── boundaryIdx-1.bnd
│       ├── boundaryIdx-2.bnd
│       ├── boundaryIdx-3.bnd
│       └── boundaryIdx-4.bnd
├── control
│   ├── hpc.cnt
│   ├── numerics.cnt
│   ├── physics.cnt
│   └── time.cnt
├── forcing
│   ├── forcing.cnt
│   └── gauges
│       ├── rainGauge-1.env
│       ├── rainGauge-2.env
│       └── rainGauge-3.env
├── gis
│   ├── PreProcessingSTAV.log
│   ├── gmsh
│   │   ├── generatedSTAVMesh.geo
│   │   ├── generatedSTAVMesh.mesh
│   │   └── gmsh                    <--------- gmsh 4.0.7 executable
│   ├── mesh                        <--------- executable to run the program
│   ├── rasters
│   ├── context_files
│   │   ├── alignments.geojson
│   │   ├── boundaries_points.geojson
│   │   ├── boundaries.geojson
│   │   ├── domain.geojson
│   │   ├── refinements.geojson
│   └── test.qgz
├── initial
│   └── initial.cnt
├── mesh
│   ├── elements.mesh
│   ├── info.mesh
│   ├── nodes.mesh
│   └── vtk
│       └── meshQuality.vtk
└── output
    ├── bed
    ├── forcing
    ├── hydrodynamics
    ├── lagrangian
    ├── maxima
    ├── numerics
    ├── output.cnt
    └── scalars
```