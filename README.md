# AHC Event Stimulus (phase-jump indicator)

**ID:** `eq-ahc-event-stimulus`  
**Tier:** derived  
**Score:** 69  
**Units:** OK  
**Theory:** PASS  

## Equation

$$
S_k=\mathbf{1}\{|r_k|>\pi_{a,k-1}\}
$$

## Description

Binary indicator: 1 when a residual exceeds the current πₐ bound, 0 otherwise. Alternative: curvature-based S_k ∝ |Δ²θ_R|. Triggers πₐ widening.

## Repository Structure

```
images/       # Visualizations, plots, diagrams
derivations/  # Step-by-step derivations and proofs
simulations/  # Computational models and code
data/         # Numerical data, experimental results
notes/        # Research notes and references
```

## Links

- [TopEquations Leaderboard](https://rdm3dc.github.io/TopEquations/leaderboard.html)
- [TopEquations Main Repo](https://github.com/RDM3DC/TopEquations)
- [Certificates](https://rdm3dc.github.io/TopEquations/certificates.html)

---
*Part of the [TopEquations](https://github.com/RDM3DC/TopEquations) project.*
