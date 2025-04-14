# 🌌 Computational Physics Repository

<div align="center">
  <img src="https://github.com/user-attachments/assets/3d5ae8fa-b49f-4a09-841a-49d1bf5f8353" alt="Computational Physics Banner" width="1000"/>
</div>

> Exploring physical phenomena through computational methods and numerical simulations

This repository houses a collection of computational physics studies that investigate fundamental physical phenomena through simulation, numerical methods, and statistical analysis. Each study combines rigorous theoretical foundations (PDF) with practical implementations (Jupyter Notebook).

---

## ⚛️ Table of Contents

<div align="center">

| # | Study | Theory | Implementation | Key Methods |
|:-:|:------|:-------|:---------------|:------------|
| 1 | [Fractal Generation](#-introduction-to-fractals) | `Introduction_to_Fractals_and_Fractal_Generation.pdf` | `Fractals_Code.ipynb` | Iterated Function Systems, Julia/Mandelbrot Sets, L-systems, Koch Curves, Sierpinski Triangle, Barnsley Fern, Heighway Dragon, Box-counting Dimension |
| 2 | [Surface Growth](#-surface-growth-in-11-dimensions) | `Discrete_Models_for_Simulating_Surface_Growth_in_1+1_Dimensions.pdf` | `Deposition.ipynb` | Random Deposition (RD), Relaxed Random Deposition (RRD), Ballistic Deposition (BD), Competitive Random Deposition (CRD), Edwards-Wilkinson, Kardar-Parisi-Zhang, Mullins Equations |
| 3 | [Percolation Theory](#-percolation-theory) | `Exploring_Percolation_Theory_Through_Simulation.pdf` | `Percolation.ipynb`, `percolation_growth_p0.55.mp4` | Breadth-First Search (BFS), Coloring Algorithm, Hoshen-Kopelman Algorithm, Real-space Renormalization, Correlation Length Analysis, Finite-size Scaling, Invasion Percolation, Cluster Statistics |
| 4 | [Random Walks](#-random-walks) | `Computational_Studies_of_Random_Walks.pdf` | `Random_Walk.ipynb` | One-dimensional/Two-dimensional Random Walks, Absorbing Boundaries, Diffusion-Limited Aggregation (DLA), Self-Avoiding Walks (SAW), Path Enumeration, Persistent/Conservative Random Walks, Continuous Models, Lévy Flights |
| 5 | [Random Number Generators](#-random-number-generators) | `Computational_Studies_of_Random_Number_Generators.pdf` | `Random_Number_Generator.ipynb` | Linear Congruential Generator (LCG), Statistical Testing, Central Limit Theorem, Box-Muller Transform, Polar (Marsaglia) Method, Inverse CDF Method, Transformation Techniques |
| 6 | [Stochastic Integration](#-stochastic-integral-estimation) | `Stochastic_Integral_Estimation_Methods.pdf` | `Stochastic_Integral_Estimation.ipynb` | Monte Carlo Integration, Sploosh Algorithm, Simple Sampling, Importance Sampling, Non-uniform Density, Error Convergence Analysis, Center of Mass Calculation |

</div>

---

## 🔬 Introduction to Fractals

<div align="center">
  <img src="https://github.com/user-attachments/assets/89a18cbc-517f-4887-bcd0-ba4b8c634526" alt="Fractal Visualization" width="500"/>
</div>

### 📚 Documentation
- `Introduction_to_Fractals_and_Fractal_Generation.pdf` - Comprehensive theoretical foundation

### 💻 Implementation
- `Fractals_Code.ipynb` - Interactive fractal generation algorithms

### 📋 Description
This study explores the fascinating mathematics of fractals and implements multiple generation techniques including:

- **Barnsley Fern** using Iterated Function Systems (IFS)
- **Heighway Dragon Curve** through iterative folding
- **Julia Set** exploration with parametric variation
- **Koch Curve and Snowflake** via recursive subdivision
- **Sierpinski Triangle** using three distinct methods: recursive subdivision, chaos game, and Pascal's triangle

### 🔑 Key Physical Concepts
- Self-similarity across multiple scales
- Non-integer fractal dimensions (Hausdorff dimension)
- Complex dynamics and chaotic attractors
- Geometric transformation techniques
- Recursive pattern formation in nature

---

## 📈 Surface Growth in 1+1 Dimensions

<div align="center">
  <img src="https://github.com/user-attachments/assets/42a7a293-89ae-4fe4-a38a-8e9e5d5943a4" alt="Surface Growth Simulation" width="900"/>
</div>

### 📚 Documentation
- `Discrete_Models_for_Simulating_Surface_Growth_in_1+1_Dimensions.pdf` - Theoretical framework

### 💻 Implementation
- `Deposition.ipynb` - Surface growth simulation models

### 📋 Description
This study investigates discrete models for simulating surface growth processes and interfaces in 1+1 dimensions, examining:

- **Random Deposition (RD)** - Basic stochastic deposition model
- **Relaxed Random Deposition (RRD)** - Adding surface relaxation mechanisms
- **Ballistic Deposition (BD)** - Simulating sticky particle aggregation
- **Competitive Random Deposition (CRD)** - Angle-dependent growth dynamics

The research compares simulation results with analytical predictions from continuum models like Edwards-Wilkinson, Kardar-Parisi-Zhang, and Mullins equations.

### 🔑 Key Physical Concepts
- Interface roughness and scaling laws
- Universality classes in surface growth
- Critical exponents (α, β, z) and scaling relationships
- Self-affine fractal interfaces
- Non-equilibrium statistical physics

---

## 🧩 Percolation Theory

<div align="center">
  <img src="https://github.com/user-attachments/assets/593092bd-21a5-43e4-b483-0c8b34b303f8" width="800"/>
</div>

### 📚 Documentation
- `Exploring_Percolation_Theory_Through_Simulation.pdf` - Theoretical analysis

### 💻 Implementation
- `Percolation.ipynb` - Comprehensive percolation simulations
- `percolation_growth_p0.55.mp4` - Visualization of invasion percolation showing cluster growth at occupation probability p=0.55

### 📋 Description
This study explores the critical behavior of percolation systems through computational methods, implementing:

- **Breadth-First Search (BFS)** algorithm for percolation detection
- **Coloring algorithm** for cluster identification
- **Hoshen-Kopelman algorithm** for efficient cluster labeling
- **Real-space renormalization** group implementation
- **Invasion percolation** with dynamically growing clusters

The research verifies critical percolation thresholds (p<sub>c</sub> = 1 for 1D, p<sub>c</sub> ≈ 0.5927 for 2D square lattices) and measures critical exponents.

### 🔑 Key Physical Concepts
- Phase transitions and critical phenomena
- Percolation thresholds in different lattice geometries
- Cluster statistics and size distribution scaling
- Correlation length divergence near critical points
- Finite-size scaling analysis
- Fractal dimensions of percolation clusters

---

## 🚶 Random Walks

<div align="center">
  <img src="https://github.com/user-attachments/assets/f1f2db79-6478-4aeb-81c2-fa60299885a4" alt="Random Walk Visualization" width="600"/>
</div>

### 📚 Documentation
- `Computational_Studies_of_Random_Walks.pdf` - Mathematical framework

### 💻 Implementation
- `Random_Walk.ipynb` - Diverse random walk models

### 📋 Description
This study examines various stochastic processes through the lens of random walk models, implementing:

- **One-dimensional random walks** and first passage statistics
- **Random walks with absorbing boundaries** using Monte Carlo and enumeration methods
- **Two-dimensional random walks** with diffusion analysis
- **Diffusion-Limited Aggregation (DLA)** with linear and central seeds
- **Self-Avoiding Walks (SAW)** with path enumeration algorithms
- **Persistent (conservative) random walks** with memory effects
- **Continuous random walk models** with variable step distributions

### 🔑 Key Physical Concepts
- Diffusion equations and scaling laws (⟨r²⟩ = 2dDt)
- Brownian motion and stochastic processes
- Self-avoiding polymer configurations
- Fractal dimensions in diffusion-limited growth (D ≈ 1.6)
- Correlation and persistence in random processes
- Lévy flights and anomalous diffusion

---

## 🎲 Random Number Generators

<div align="center">
  <img src="https://github.com/user-attachments/assets/17b6a24e-81fb-4176-8a9d-09b518b2d01c" alt="Random Number Distribution" width="900"/>
</div>

### 📚 Documentation
- `Computational_Studies_of_Random_Number_Generators.pdf` - Statistical analysis

### 💻 Implementation
- `Random_Number_Generator.ipynb` - PRNG implementations and testing

### 📋 Description
This study analyzes pseudorandom number generators (PRNGs) and their applications in computational physics, including:

- **Linear Congruential Generator (LCG)** implementation and analysis
- **Statistical validation** of NumPy and Python's built-in generators
- **Central Limit Theorem** verification with random sums
- **Non-uniform distribution generation** through transformation methods:
  - Inverse CDF method
  - Box-Muller transform
  - Polar (Marsaglia) method

The research examines uniformity, independence, and statistical convergence of various generators.

### 🔑 Key Physical Concepts
- Statistical mechanics and probability distributions
- Monte Carlo method foundations
- Correlation detection in stochastic systems
- Central Limit Theorem and statistical convergence
- Transformation methods for specific distributions
- Error scaling and statistical validity testing

---

## 📊 Stochastic Integral Estimation

<div align="center">
  <img src="https://github.com/user-attachments/assets/9a446ef2-fe70-4aa3-bed4-9cb948b30d54" alt="Monte Carlo Integration" width="900"/>
</div>

### 📚 Documentation
- `Stochastic_Integral_Estimation_Methods.pdf` - Theoretical foundations

### 💻 Implementation
- `Stochastic_Integral_Estimation.ipynb` - Monte Carlo integration algorithms

### 📋 Description
This study investigates numerical integration using stochastic methods, with a focus on Monte Carlo techniques applied to:

- **Definite integral calculation** using the Sploosh algorithm
- **Comparison of sampling strategies** (simple vs. importance sampling)
- **Center of mass calculation** for a sphere with non-uniform density

The implementation demonstrates how stochastic methods can effectively solve deterministic problems with predictable error convergence properties.

### 🔑 Key Physical Concepts
- Monte Carlo integration methodology
- Importance sampling for variance reduction
- Statistical error scaling (1/√N)
- Numerical integration in complex geometries
- Sampling efficiency and optimization
- Non-uniform density distributions

---

## 🔹 Future Studies
Additional computational physics investigations and implementations will be added in future updates. Stay tuned for more advanced simulations and numerical methods.

---

## 🔧 Requirements and Setup

This repository requires the following Python packages:

```python
numpy               # Numerical computing
matplotlib          # Data visualization
scipy               # Scientific computing
numba               # JIT compilation for performance
jupyter             # Interactive notebooks
```

---

## 💻 Getting Started
```bash
# Clone this repository
git clone https://github.com/kiaraGholizad/Computational-Physics.git
# Install required packages
pip install numpy scipy matplotlib numba jupyterlab
