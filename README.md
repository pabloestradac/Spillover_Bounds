# Spillover Effects with Nonrandom Sample Selection

[Pablo Estrada](https://www.pabloestrada.io/)<sup>1</sup>
<br>
<sup>1</sup>Emory University

[Paper](https://www.pabloestrada.io/publication/spillover_bounds/) | [Five-minute Summary](https://www.pabloestrada.io/publication/spillover_bounds/)


## Abstract

This paper proposes a method to estimate spillover effects of a random treatment using a nonrandom sample of individuals for whom the analyst can observe their outcomes, i.e., nonrandom sample selection. The proposed method employs an exposure monotonicity assumption that extends the conventional Lee bounds to general exposures to treatment. Under this assumption, we show how to compute the bounds for a spillover estimand that allows for the inclusion of covariate adjustments and network dependence, where statistical inference follows a design-based approach. The framework is extended with a conditional exposure monotonicity assumption that allows for the inclusion of high dimensional covariates via regularization and machine learning methods. The empirical application presents the new method to analyze spillover effects of a randomized experiment on computer utilization in students from public schools. The results suggest positive spillover effects for laptop lottery winners and non-winners. Including covariates can substantially tighten the bounds in this context.


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
