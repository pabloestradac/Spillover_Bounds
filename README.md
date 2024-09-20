# Spillover Effects with Nonrandom Sample Selection

[Pablo Estrada](https://www.pabloestrada.io/)<sup>1</sup>
<br>
<sup>1</sup>Emory University

[Paper](https://www.pabloestrada.io/publication/spillover_bounds/) | [Five-minute Summary](https://www.pabloestrada.io/publication/spillover_bounds/)


## Summary

This paper presents a method to estimate spillover effects of a random treatment using a nonrandom sample of individuals with observable outcomes. The approach uses an exposure monotonicity assumption to bound spillover effects, accounting for network dependence. It also incorporates high-dimensional covariates through machine learning to tighten the bounds.


## Replication

**[`Data_Laptops.ipynb`](notebooks/Data_Laptops.ipynb)** contains the code to generate the data used in the empirical application.

**[`Spillover_Bounds.ipynb`](notebooks/Spillover_Bounds.ipynb)** contains the code to estimate the spillover bounds.

**[`Simulation.ipynb`](notebooks/Simulation.ipynb)** contains the code to replicate the simulation study.


## Citation

```
@misc{Estrada_2024,
  title={Spillover Effects with Nonrandom Sample Selection},
  author={Estrada, Pablo},
  year={2024}
}
```
