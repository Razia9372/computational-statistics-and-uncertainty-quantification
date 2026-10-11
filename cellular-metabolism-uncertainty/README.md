# Uncertainty Quantification for Cellular Metabolism

## Overview

This project investigates uncertainty in a mathematical model of cellular glucose metabolism using Monte Carlo simulation, neural-network surrogate modeling, and multifidelity estimation.

The underlying model describes glucose uptake, intracellular substrate concentration, and ATP production through a system of ordinary differential equations.

## Methods

- Monte Carlo estimation and 95% confidence intervals
- Singular Value Decomposition (SVD)
- Neural-network surrogate modeling
- Multifidelity estimation
- Gaussian-process modeling considerations

## Quantities of Interest

The analysis focuses on three quantities:

- **Q1:** Average extracellular glucose concentration during the first four hours.
- **Q2:** Maximum ATP concentration over the simulation period.
- **Q3:** Time at which extracellular glucose and intracellular substrate concentrations become equal.

## Implementation

The Jupyter notebook covers baseline Monte Carlo estimation, training a neural-network surrogate, and evaluating whether multifidelity estimation can improve statistical precision.

## Technologies

Python, NumPy, SciPy, PyTorch, Jupyter Notebook

## Reproducibility

The notebook relies on course-provided simulation data and the `dlroms` package. Additional configuration may be required to reproduce the results.

## Academic Context

Developed as part of the Computational Statistics course at Politecnico di Milano.

The project demonstrates applications of statistical simulation, surrogate modeling, and uncertainty quantification to a dynamical biological system.
