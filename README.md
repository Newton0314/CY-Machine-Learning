# Machine Learning for Degeneration Families of Calabi–Yau Manifolds in CP^n

This repository contains the code from my master's thesis: "Machine Learning for Degeneration Families of Calabi-Yau Manifolds in CP^n"

## Goal
- Goal: numerically approximate the Calabi–Yau metric of K3 surfaces, via solving the Monge-Ampere PDE.
- Approach: Train a neural-network based PDE solver (TensorFlow, with the Adam optimiser), minimising the Monge-Ampere (or Kahler) loss.


## Key Results
- Trained 128k sample points for 500 epochs, achieved RMSE < 0.0001.
- Proposed two research-level conjectures, based on numerical evidence, relating dimension-collapsing of the degeneration family and the eigenvalues of the CY metric tensor.
