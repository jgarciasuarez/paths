# Universal Path Decomposition of Multilayer Transfer and Scattering Matrices

This repository contains companion Jupyter notebooks for the paper:

**"Universal Path Decomposition of Multilayer Transfer and Scattering Matrices"**  
by Joaquin Garcia-Suarez (2025)

This repository contains a reference implementation of the path decomposition method for wave propagation in one-dimensional layered media. The method provides an efficient alternative to classical transfer matrix formulations and supports both full and truncated path summation.

The contents support four classes of applications: computational benchmarking, optics, geophysical site response analysis, and quantum superlattice optimization.

## Contents

### Notebooks

- `Numerical_Performance_Paths_Garcia-Suarez_2025.ipynb`  
  Benchmarks runtime scaling of the path decomposition method versus classical transfer matrix chaining. Includes speed-up plots.

- `Soil_Stratigraphy_Inversion_Paths_Garcia-Suarez_2025.ipynb`  
  Applies the method to a 1D site-response model using shear-wave velocity data from a Kik-Net station. Demonstrates inversion.

- `Lattice_Optimization_Paths_Garcia-Suarez_2025.ipynb`  
  Optimizes a seven-layer GaAs/AlAs quantum superlattice to match a target transmission at a prescribed energy. Compares global search (TMM) and local gradient-based search (paths).

- `Quantum_Verification_Paths_Garcia-Suarez_2025.ipynb`  
  Verifies unitarity of the scattering matrix and validates convergence of the path sum against TMM.

- `Random_Layering_Paths_Garcia-Suarez_2025.ipynb`  
  Performs tests over ensembles of random dielectric stacks.

- `Paths_Garcia-Suarez_2025.ipynb`  
  Core notebook implementing key routines: transfer matrix propagation, path generation, amplitude/delay evaluation, and scattering conversion.

## Requirements

- Python 3.8 or higher  
