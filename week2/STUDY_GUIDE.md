# Week 2 - Generalisation and Validation

## Purpose

Learn how to estimate performance on unseen data and recognise overfitting.

## Prerequisites

Week 1 regression workflow, train/test splitting, loss, and basic pandas operations.

## Core Ideas

- Generalisation means performing well on data not used during fitting.
- Underfitting means the model is too simple to capture the pattern.
- Overfitting means the model learns noise or accidental details.
- A validation set helps choose between models or hyperparameters.
- A test set should remain untouched until final evaluation.
- Cross-validation averages performance across several training/validation splits.
- Data leakage occurs when information from evaluation data influences training.

## Study Sequence

1. Train a baseline model.
2. Compare training and validation performance.
3. Increase model complexity and observe the error pattern.
4. Use cross-validation to obtain a more stable estimate.
5. Select a model using validation information.
6. Evaluate the selected model once on the test set.

## Important Discipline

Fit scalers, imputers, feature selectors, and other preprocessing steps only on training data. A pipeline is useful because it keeps preprocessing and modelling together and reduces leakage risk.

## Practice Tasks

- Compare a simple linear model with a higher-complexity alternative.
- Plot training and validation error against model complexity.
- Perform k-fold cross-validation.
- Explain why repeatedly checking the test set makes it less trustworthy.
- Create an example of leakage and then remove it.

## Mastery Checklist

- [ ] I can define overfitting and underfitting.
- [ ] I know the roles of training, validation, and test data.
- [ ] I can explain why cross-validation is useful.
- [ ] I can identify a leakage risk.
- [ ] I can choose a model without using the final test result.

## Connection to Week 3

Validation principles apply to every classifier. Week 3 changes the target from a continuous number to a category, but the train/validation/test discipline remains the same.
