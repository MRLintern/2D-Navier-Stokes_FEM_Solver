# 2D-Navier-Stokes_FEM_Solver

## Introduction
A __Modern C++17 Solver__ which solves the ___2D Navier-Stokes Equations___ for a liquid flowing in a River/Open-Channel.
The __2D Navier-Stokes Equations__ are discretised via the __Finite Element Method__.
This is a work in progress.
## Requirements
* Developed on `Ubuntu 20.04`.
* __Compiler__: `g++ 13.1.0`.
* `Eigen Library`.
* `Catch2` for __Unit Testing__.

## Model Description
* The channel is a __2D Rectangular Region__, with __100 nodes__ in both the x- and y-direction, making a __1000 node domain__. 
## Successive Over Relaxation (SOR) Method
* TODO.
## Getting and Running the Software

# 📊 FEM 2D Fluid Flow Solver (C++17 + Eigen + Catch2)

A modern, object-oriented finite element method (FEM) solver for simulating steady 2D open-channel fluid flow in a rectangular domain.  
Implemented in clean, commented C++17 with Eigen for linear algebra, Catch2 for unit testing, and Python/Matplotlib for postprocessing.

---

## 📦 Project Structure

FEM2DFluidSolver/ ├── CMakeLists.txt ├── include/ │ ├── CGSolver.hpp │ ├── FEMSolver.hpp │ └── Mesh.hpp ├── src/ │ ├── CGSolver.cpp │ ├── FEMSolver.cpp │ ├── Mesh.cpp │ └── main.cpp ├── tests/ │ └── test_solver.cpp ├── results/ │ └── (output .csv files) ├── visualization/ │ └── plot_results.py └── README.md

---

## ⚙️ Build Instructions

### 🛠 Prerequisites:
- C++17 compiler (e.g. `g++-11`, `clang++-14`)
- [Eigen 3](https://eigen.tuxfamily.org/dox/GettingStarted.html)
- [CMake ≥ 3.15](https://cmake.org/download/)
- Python 3 with `numpy`, `matplotlib`, `pandas` for visualization

### 📦 Install Catch2 (if not already)

Clone and build Catch2 (if needed):

```bash
git clone https://github.com/catchorg/Catch2.git
cd Catch2
cmake -B build -S .
sudo cmake --install build





