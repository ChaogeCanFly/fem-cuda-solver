# Acoustic Vibration of a Fluid in a Three-Dimensional Cavity: Finite Element Method Simulation using CUDA and MATLAB

An implementation of a FEM acoustic model on a GPU using C/C++ and CUDA libraries.

[![Article](https://img.shields.io/badge/ieee-article-blue.svg)](https://ieeexplore.ieee.org/document/8705226) 

## Quick steps
For CUDA, just do `make`:

```
  cd CUDA
  make
  ./fem_solver A B C
 ```
 
 A: Number of nodes n in grid `n x n x n`
 
 B: Method type. `0` for Conquer and Divide, `1` for Jacobi. 
 
 C: Precision type. `0` for Single, `1` for Double. 

For MATLAB, run: `fem_acoustic_1.h`.


## Output
Arbitrary eigenvectors were used to graph the sound pressure distribution for low and high frequencies in the cavity and they are shown bellow:

![Acoustic FEM Model GPU](https://i.imgur.com/8tDzzqq.png)


## Notes
CUDA 9.2 is needed(also cuSolver).

NVIDIA Titan X, Tesla  P100 and Tesla  V100 were tested.
