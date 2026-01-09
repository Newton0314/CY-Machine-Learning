# Machine Learning for Degeneration Families of Calabi–Yau Manifolds in CP<sup>n</sup>

This repository contains the code from my master's thesis: "Machine Learning for Degeneration Families of Calabi-Yau Manifolds in CP<sup>n</sup>".

## Goals
- Goal 1: numerically approximate the Calabi–Yau metric of K3 surfaces, via solving the Monge-Ampère PDE.
- Approach: Train a neural-network based PDE solver (TensorFlow, with the Adam optimiser), minimising the Monge-Ampère (or Kähler) loss.
- Goal 2: numerically classify the complex structure limits of a family of CY manifolds, via considering the growth rate of the holomorphic volume.
- Approach: numerically compute the holomorphic volume growth rate, by using Monte-Carlo integration with respect to the Fubini-Study measure on CP<sup>n</sup>.


## Key Results (Section 4.3 - 4.5)
- Section 4.3: numerically computed of the growth rate of the holomorphic volume of degeneration families of K3 surfaces. Numerically classified the complex structure limits.
- Section 4.4: trained 128k sample points for 500 epochs for approximation of the CY metric of K3 surfaces, achieved RMSE < 0.0001.
- Section 4.5: proposed two research-level conjectures, based on numerical evidence, relating dimension-collapsing of the degeneration family and the eigenvalues of the CY metric tensor.
