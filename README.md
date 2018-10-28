# Acoustic Vibration of a Fluid in a Three-Dimensional Cavity: Finite Element Method Simulation using CUDA and MATLAB

An implementation of a FEM acoustic model on a GPU using C/C++ and CUDA libraries.

## Quick steps
Just do `make`:

  cd CUDA
  make
  ./fem-solver A B C
 
 A: Number of nodes n in grid 'n x n x n'
 B: Method `0` for Conquer and Divide, `1` for Jacobi. 
 C: Precision `0` for Single, `1` for Double. 

## Notes
CUDA 9.2 is needed(also cuSolver)
NVIDIA Tesla Titan X, P100 and V100 were tested.


## For more information
Please see the wiki: [[Link Text|WikiLink]]

