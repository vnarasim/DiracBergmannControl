# Optimal Control via Dirac–Bergmann Algorithm

### Worked Example: The Brachistochrone Problem (Mathematica)

## Overview

This repository contains a fully worked-out example of applying the **Dirac–Bergmann algorithm** for constrained dynamical systems to an **optimal control problem**: the classical **brachistochrone problem**.

The implementation is written in **Wolfram Mathematica** and demonstrates how constrained Hamiltonian methods can be systematically used to derive and solve optimal trajectories.

This repository is a supplement to the scholarly article *"The Dirac--Bergmann approach to optimal control theory"* by the repository’s authors.

## Objectives

* Demonstrate the use of the Dirac–Bergmann algorithm in a control context
* Reformulate the brachistochrone problem as a constrained dynamical system
* Derive equations of motion using Hamiltonian methods with constraints
* Solve and visualize the optimal trajectory

## Background

### Brachistochrone Problem

The brachistochrone problem asks:

> What is the curve along which a particle descends under gravity between two points in the shortest time?

The solution is a **cycloid**, but this repository focuses on deriving it using **constraint dynamics**, rather than classical variational calculus alone.

### Dirac–Bergmann Algorithm

The Dirac–Bergmann procedure is a systematic method for handling:

* Singular Lagrangians
* Constraints in phase space
* Consistency conditions and secondary constraints

This framework is especially useful when:

* Control variables introduce degeneracies
* Standard Euler–Lagrange methods are insufficient

## Contents

* `CB_2.nb` — Mathematica notebook containing:

  * Problem setup
  * Constraint formulation
  * Hamiltonian construction
  * Dirac–Bergmann algorithm steps
  * Analytical derivations
  * Numerical solutions and plots

## Requirements

* Wolfram Mathematica (version 12 or later recommended)

## How to Use

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/dirac-bergmann-brachistochrone.git
   ```
2. Open `CB_2.nb` in Mathematica
3. Execute cells sequentially to follow the derivation

## Key Steps in the Notebook

* Reformulation of the brachistochrone as a control system
* Identification of primary constraints
* Construction of the total Hamiltonian
* Iterative constraint stabilization (Dirac–Bergmann procedure)
* Extraction of equations of motion
* Solution and visualization

## Who would find it useful

* Researchers in quantum science and technology and other areas where **optimal control** problems arise
* Researchers working with **constrained Hamiltonian systems**
* Anyone interested in bridging **physics-based methods and control theory**

## Possible Extensions

* Generalization to other optimal control problems
* Inclusion of inequality/path constraints
* Numerical optimal control comparisons (e.g., direct methods)
* Extension to field-theoretic systems

## License
Creative Commons Zero v1.0 Universal

## Authors

Davit Aghamalyan, Aleek Maity, Varun Narasimhachar, V V Sreedhar

## References

* D. Aghamalyan, A. Maity, V. Narasimhachar, & V. V. Sreedhar (2025). *The Dirac--Bergmann approach to optimal control theory*. arXiv preprint arXiv:2506.17610.
* P. A. M. Dirac — *Lectures on Quantum Mechanics*
* M. Henneaux & C. Teitelboim — *Quantization of Gauge Systems*
* Classical mechanics and optimal control literature on the brachistochrone problem
