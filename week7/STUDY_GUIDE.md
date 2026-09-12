# Week 7 - Support Vector Machines

## Purpose

Understand maximum-margin classification and how kernels represent nonlinear decision boundaries.

## Prerequisites

Weeks 2, 3, and 6: classification, generalisation, regularisation, vectors, and basic geometry.

## Core Ideas

- A separating hyperplane divides classes.
- The margin is the distance from the boundary to the closest examples.
- Support vectors are the observations that determine the boundary.
- Soft margins allow some violations when perfect separation is undesirable.
- `C` controls the trade-off between a wide margin and training violations.
- Kernels allow nonlinear relationships without explicitly creating every transformed feature.
- Feature scaling is usually important for SVMs.

## Study Sequence

1. Draw a two-dimensional separating boundary.
2. Identify the margin and support vectors.
3. Compare linear and nonlinear kernels.
4. Scale data before fitting.
5. Tune `C` and kernel parameters through validation.
6. Evaluate with metrics appropriate to the problem.

## Practice Tasks

- Plot a linear SVM on a two-feature dataset.
- Add noise and observe the effect of `C`.
- Compare a linear kernel with an RBF kernel.
- Explain why a kernel model can overfit.
- Record training and validation metrics for each experiment.

## Mastery Checklist

- [ ] I can explain the maximum-margin idea.
- [ ] I can identify support vectors conceptually.
- [ ] I understand the role of `C`.
- [ ] I can explain why kernels help with nonlinear boundaries.
- [ ] I can validate an SVM without using the test set for tuning.

## Connection to Week 8

SVMs build powerful boundaries using geometry and kernels. Neural networks learn their own representations through layers and gradient-based optimisation.
