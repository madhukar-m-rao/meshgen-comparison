# Mesh Generator Comparison

This repository creates meshes of the same domains with multiple mesh generators and
compares the results. The used mesh generators are

  * [Gmsh](https://gmsh.info/) (via [pygmsh](https://github.com/nschloe/pygmsh)),
  * [CGAL](https://www.cgal.org/) (via [pygalmesh](https://github.com/nschloe/pygalmesh)),
  * [MeshPy](https://github.com/inducer/meshpy),
  * [dmsh](https://github.com/nschloe/dmsh),
  * [meshzoo](https://github.com/nschloe/meshzoo), and
  * [SeismicMesh](https://github.com/krober10nd/SeismicMesh).

For each domain and mesh generator (if applicable), the repostory shows the following data:
   * the mesh generation time
   * the average and minimum cell quality
   * the nummber of CG iterations for the FEM-Poisson-problem on the mesh.

### Disk

<img src="https://github.com/nschloe/meshgen-comparison/blob/gh-pages/disk-mesh.png?raw=true" width="50%"> | ![alt text](https://github.com/nschloe/meshgen-comparison/blob/gh-pages/disk-times.svg?raw=true) |
:-------------:|:-----------------:|
| ![alt text](https://github.com/nschloe/meshgen-comparison/blob/gh-pages/disk-quality.svg?raw=true) | ![alt text](https://github.com/nschloe/meshgen-comparison/blob/gh-pages/disk-poisson.svg?raw=true)


### L-shape

<img src="https://github.com/nschloe/meshgen-comparison/blob/gh-pages/l-shape-mesh.png?raw=true" width="50%"> | ![alt text](https://github.com/nschloe/meshgen-comparison/blob/gh-pages/l-shape-times.svg?raw=true) |
:-------------:|:-----------------:|
| ![alt text](https://github.com/nschloe/meshgen-comparison/blob/gh-pages/l-shape-quality.svg?raw=true) | ![alt text](https://github.com/nschloe/meshgen-comparison/blob/gh-pages/l-shape-poisson.svg?raw=true)


### Rectangle with refinement

<img src="https://github.com/nschloe/meshgen-comparison/blob/gh-pages/rect-with-refinement-mesh.png?raw=true" width="50%"> | ![alt text](https://github.com/nschloe/meshgen-comparison/blob/gh-pages/rect-with-refinement-times.svg?raw=true) |
:-------------:|:-----------------:|
| ![alt text](https://github.com/nschloe/meshgen-comparison/blob/gh-pages/rect-with-refinement-quality.svg?raw=true) | ![alt text](https://github.com/nschloe/meshgen-comparison/blob/gh-pages/rect-with-refinement-poisson.svg?raw=true)

### Ball

<img src="https://github.com/nschloe/meshgen-comparison/blob/gh-pages/ball-mesh.png?raw=true" width="50%"> | ![alt text](https://github.com/nschloe/meshgen-comparison/blob/gh-pages/ball-times.svg?raw=true) |
:-------------:|:-----------------:|
| ![alt text](https://github.com/nschloe/meshgen-comparison/blob/gh-pages/ball-quality.svg?raw=true) | ![alt text](https://github.com/nschloe/meshgen-comparison/blob/gh-pages/ball-poisson.svg?raw=true)

### L-shape in 3D

<img src="https://github.com/nschloe/meshgen-comparison/blob/gh-pages/l-shape-3d-mesh.png?raw=true" width="50%"> | ![alt text](https://github.com/nschloe/meshgen-comparison/blob/gh-pages/l-shape-3d-times.svg?raw=true) |
:-------------:|:-----------------:|
| ![alt text](https://github.com/nschloe/meshgen-comparison/blob/gh-pages/l-shape-3d-quality.svg?raw=true) | ![alt text](https://github.com/nschloe/meshgen-comparison/blob/gh-pages/l-shape-3d-poisson.svg?raw=true)

### Box with refinement

<img src="https://github.com/nschloe/meshgen-comparison/blob/gh-pages/box-with-refinement-mesh.png?raw=true" width="50%"> | ![alt text](https://github.com/nschloe/meshgen-comparison/blob/gh-pages/box-with-refinement-times.svg?raw=true) |
:-------------:|:-----------------:|
| ![alt text](https://github.com/nschloe/meshgen-comparison/blob/gh-pages/box-with-refinement-quality.svg?raw=true) | ![alt text](https://github.com/nschloe/meshgen-comparison/blob/gh-pages/box-with-refinement-poisson.svg?raw=true)

### License
This software is published under the [GPLv3 license](https://www.gnu.org/licenses/gpl-3.0.en.html).
