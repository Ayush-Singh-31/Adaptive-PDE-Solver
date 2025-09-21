# Numerical PDE Solver with Adaptive Mesh

This project aims to develop a Python-based numerical solver for partial differential equations (PDEs) using finite difference methods. We first implement the solver on a fixed uniform mesh, addressing key components such as spatial and temporal discretization, stability analysis, and scheme selection for representative equations like the advection-diffusion PDE. After validating the baseline solver, we extend it to incorporate an adaptive moving mesh framework. This adaptive method employs monitor functions and the equidistribution principle to dynamically redistribute grid points, focusing resolution in regions with steep gradients or localized features while maintaining efficiency in smooth regions. Our solver achieves improved accuracy and computational efficiency, with applications spanning fluid dynamics, reaction-diffusion systems, and financial modeling such as option pricing. Through this work, we integrate classical numerical analysis with adaptive meshing techniques to create a flexible and efficient PDE solver for complex, real-world problems.

## Objectives

1. Implement a finite difference solver on a uniform mesh (explicit and implicit schemes).
2. Validate the solver on the advection–diffusion equation.
3. Incorporate an adaptive moving mesh using monitor functions and the equidistribution principle.
4. Demonstrate the approach on financial models such as the Black–Scholes equation.

## Current Status

The project is in the planning stage. Implementation has not yet started.

## References

- W. Huang and R. D. Russell, _Adaptive Moving Mesh Methods_. Springer, 2011.
- Standard references on finite difference methods and numerical stability.
