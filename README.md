# EPFL Summer 2024 Internship Project: Optimization of the Ising Model

This repository contains the code, research data, and reports from my Summer 2024 internship project conducted at the École Polytechnique Fédérale de Lausanne (EPFL). The project focused on optimizing the Ising model using Monte Carlo sampling techniques, comparing gradient estimation methods, and applying automatic differentiation techniques to enhance computational efficiency.

## Project Overview

### Objective:
The main objective of this research is to optimize the Ising model using Monte Carlo Markov Chain (MCMC) sampling and analyze different methods for estimating gradient expectation values. The Ising model serves as a representation of ferromagnetism in statistical mechanics, with the goal of finding critical points in the phase diagram and performing optimizations based on thermal fluctuations.

### Key Methods:
1. **Monte Carlo Sampling**: Applied to simulate the Ising model under various conditions using the Metropolis-Hastings algorithm.
2. **Score Method**: Analytical differentiation of the expectation values and optimization using Adam.
3. **Pathwise Method**: Coupling proposals to estimate gradients and optimize energy versus temperature relationships.
4. **Automatic Differentiation**: Implementation for discrete random variables to optimize the model with high precision.

## Files and Structure
- `Task1-sampling-from-continuous-distribution.ipynb`: Implements MCMC sampling from continuous distributions.
- `Task2-sampling-from-discrete-distribution.ipynb`: Focuses on sampling from discrete distributions.
- `Task3-gradients.ipynb`: Calculation and comparison of gradient methods (Score and Pathwise).
- `Task4-differentiation.ipynb`: Implements automatic differentiation for the Metropolis-Hastings algorithm.
- **Research Report**: [EPFL Report](EPFL report.pdf)
- **Research Poster**: [Poster](poster final.pdf)

## Research Findings
- Monte Carlo sampling techniques effectively simulate the thermal properties of the Ising model.
- The Score Method yielded reliable gradient estimates for smaller systems, while the Pathwise Method proved more scalable for larger grid sizes.
- The automatic differentiation approach improved the precision and computational efficiency of optimizing the system at critical temperatures.

## Future Work
The future direction of this project will involve:
- Extending the optimization to larger quantum systems.
- Investigating the use of automatic differentiation in more complex probabilistic models with both continuous and discrete components.

## Citations
This project references the following key papers:
- **Arya et al. (2023)**: *Differentiating Metropolis-Hastings to Optimize Intractable Densities*. [Download PDF](Differentiating Metropolis-Hastings to Optimize Intractable Densities.pdf)
- **Sinibaldi et al. (2023)**: *Automatic Differentiation of Programs with Discrete Randomness*. [Download PDF](Automatic Differentiation of Programs with Discrete Randomness.pdf)

