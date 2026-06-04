# INN vs FEM vs MLP — Comparison Notes

> 🚧 **WIP** — Filling this in as I build understanding. Most cells are TODO for now.

---

## Comparison Table

| Property | FEM (Finite Element Method) | MLP (Standard Neural Network) | INN (Interpolating Neural Network) |
|----------|----------------------------|-------------------------------|-------------------------------------|
| **Type of method** | Numerical / mesh-based | Learned / data-driven | <!-- TODO --> |
| **Basis functions** | Piecewise polynomial (e.g., hat functions) | Learned nonlinear activations | <!-- TODO --> |
| **Interpolation vs. approximation** | Interpolates at nodes | Approximates globally | <!-- TODO --> |
| **Training / fitting** | Solve linear system | Gradient-based optimization | <!-- TODO --> |
| **Handles irregular geometry?** | Yes (with mesh) | N/A | <!-- TODO --> |
| **Extrapolation behavior** | Poor outside domain | Poor in general | <!-- TODO --> |
| **Interpretability** | High — basis functions are explicit | Low — black box | <!-- TODO --> |
| **Computational cost** | Depends on mesh size | Depends on network size | <!-- TODO --> |
| **Convergence guarantees** | Yes (under regularity conditions) | No (in general) | <!-- TODO --> |
| **Typical use case** | PDEs, structural mechanics | Classification, regression | <!-- TODO --> |

---

## Key Similarities

<!-- TODO: List the main ways these three methods overlap or share concepts. -->

- ...

---

## Key Differences

<!-- TODO: List the most important distinctions between FEM, MLP, and INN. -->

- ...

---

## Why This Comparison Matters (to me)

<!-- TODO: Write a short note on why understanding the FEM–MLP–INN relationship is useful
     for your learning goals. -->

...

---

## Open Questions

<!-- TODO: Questions that came up while building this comparison. -->

- [ ] ...
- [ ] ...
