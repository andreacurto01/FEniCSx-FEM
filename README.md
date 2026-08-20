![Logo FEniCSx](./logo_FEniCSx.png)

# 3D Tapered Beam Structural Analysis using FEniCSx

This repository contains a 3D Finite Element Method (FEM) simulation for the structural analysis of a tapered beam (non-constant cross-section) subjected to aerodynamic/structural loads. The project is implemented in Python using the FEniCSx computing platform and visualized via PyVista.

Full Academic Report

The complete theoretical derivation, variational formulation, and comprehensive material studies are fully documented in the academic report:

[Read the Full Report (PDF)](./Report_FEniCSx_FEM.pdf)

Project Overview

The objective of this project is to model a 3D tapered beam clamped at its widest end (x=0) and subjected to loads at its free tip, analyzing displacement fields and Von Mises stress distributions.

The study explores:

1. Geometric Optimization: Comparing Linear, Quadratic, and Exponential tapering profiles.

2. Material Performance: Conducting a trade-off study across various engineering and aerospace materials to evaluate stiffness-to-weight efficiency.

- Constitutive Equations: Linear elasticity modeled via generalized Hooke's Law using Lamé parameters (μ, λ).

- Variational Formulation: Solved numerically using a preconditioned LU linear solver (LinearProblem in FEniCSx).

- Discretization: 3D Hexahedral mesh domain consisting of 720 cells optimized for structural mechanics.

Visualizing Results

Below are the visualization outputs obtained through PyVista post-processing:

1. Displacement Distribution (Deflection)

2. Von Mises Stress Distribution
