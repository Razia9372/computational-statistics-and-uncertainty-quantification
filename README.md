# Computational Statistics & Uncertainty Quantification

A collection of computational statistics projects exploring **Monte Carlo methods, variance reduction, statistical inference, neural-network surrogate modeling, and uncertainty quantification** in physical and biological systems.

Developed as part of the Computational Statistics course at Politecnico di Milano.

## Projects

### 1. Monte Carlo Methods for Semiconductor Electron Dynamics

**[View project](monte-carlo-semiconductor/)**

This project investigates the momentum distribution of an electron trapped near an impurity in an idealized one-dimensional semiconductor.

The study applies statistical simulation and variance-reduction methods to estimate quantities associated with the electron's momentum distribution.

**Methods and techniques:**
- Acceptance-rejection sampling
- Analytical and empirical distribution comparisons
- Kolmogorov–Smirnov goodness-of-fit testing
- Monte Carlo estimation and confidence intervals
- Importance sampling
- Antithetic variables

**Implementation:** [Jupyter Notebook](monte-carlo-semiconductor/Assignment1.ipynb)

### 2. Uncertainty Quantification for Cellular Metabolism

**[View project](cellular-metabolism-uncertainty/)**

This project studies uncertainty in a mathematical model of cellular glucose metabolism, describing glucose uptake, intracellular substrate concentration, and ATP production.

It combines statistical estimation with neural-network surrogate modeling and multifidelity methods.

**Methods and techniques:**
- Monte Carlo estimation
- Statistical confidence intervals
- Singular Value Decomposition (SVD)
- Neural-network surrogate modeling
- Multifidelity estimation
- Discussion of Gaussian-process modeling

The analysis considers three quantities of interest: average extracellular glucose concentration, maximum ATP concentration, and the time at which glucose and substrate concentrations become equal.

**Implementation:** [Jupyter Notebook](cellular-metabolism-uncertainty/Assignment_2.ipynb)

## Repository Structure

```text
computational-statistics-and-uncertainty-quantification/
├── README.md
├── monte-carlo-semiconductor/
│   ├── README.md
│   └── Assignment1.ipynb
└── cellular-metabolism-uncertainty/
    ├── README.md
    └── Assignment_2.ipynb
```

## Technical Skills Demonstrated

| Area | Methods and tools |
|---|---|
| Statistical computing | Monte Carlo simulation, confidence intervals |
| Variance reduction | Importance sampling, antithetic variables |
| Statistical inference | Goodness-of-fit testing |
| Machine learning | Neural-network surrogate modeling |
| Numerical methods | Singular Value Decomposition |
| Uncertainty quantification | Multifidelity estimation |
| Programming | Python, NumPy, SciPy, Jupyter Notebook |

## Reproducibility

The notebooks preserve their original coursework implementations and saved numerical results.

Some computations depend on course-provided datasets or additional Python packages. Reproducing the results may require access to those resources and compatible software versions.

The notebooks are shared as academic project implementations; their numerical results have not been independently revalidated for this repository.

## Academic Context

**Institution:** Politecnico di Milano

**Course:** Computational Statistics

**Academic Year:** 2025–2026

## Author

**Razia Jafari**

M.Sc. Telecommunication Engineering — Politecnico di Milano

**Research interests:** Wireless Networks · Networked Embedded Systems · Distributed Computing · Computational Modeling · Optimization
