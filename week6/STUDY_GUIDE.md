# Week 6 - Regularisation and Model Complexity

## Purpose

Control overfitting by penalising unnecessarily large or complex model parameters.

## Prerequisites

Weeks 1, 2, and 5: loss, generalisation, coefficients, and optimisation.

## Core Ideas

- Regularisation adds a penalty to the training objective.
- Ridge uses an L2 penalty and tends to shrink coefficients smoothly.
- Lasso uses an L1 penalty and can set some coefficients exactly to zero.
- Elastic Net combines L1 and L2 behaviour.
- The regularisation strength is a hyperparameter selected through validation.
- Scaling matters because penalties compare coefficient magnitudes.

## Study Sequence

1. Fit an unregularised baseline.
2. Add ridge and lasso models.
3. Scale features before comparing coefficients.
4. Tune regularisation strength with cross-validation.
5. Compare training and validation performance.
6. Interpret coefficient shrinkage carefully.

## Practice Tasks

- Create correlated features and compare ridge with lasso.
- Plot coefficient values as regularisation strength changes.
- Use a pipeline containing scaling, model fitting, and cross-validation.
- Explain why a zero coefficient does not prove a feature is useless in every model.
- Compare model simplicity with predictive performance.

## Mastery Checklist

- [ ] I can explain why regularisation may improve test performance.
- [ ] I know the difference between L1 and L2 penalties.
- [ ] I can tune regularisation without leaking test information.
- [ ] I can explain why feature scale affects the penalty.
- [ ] I can distinguish feature selection from general coefficient shrinkage.

## Connection to Week 7

Regularisation controls a linear model's complexity. SVMs control classification complexity through margins and support vectors, giving a geometric view of a similar generalisation problem.
