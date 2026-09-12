# Week 1 - Introduction and Linear Regression

## Purpose

Learn the basic supervised-learning workflow and use linear regression to predict a numeric target.

## Prerequisites

Basic Python variables, functions, lists, NumPy arrays, pandas DataFrames, and simple plots.

## Core Ideas

- A feature is an input used for prediction.
- A target is the value the model tries to predict.
- In supervised learning, examples contain known targets.
- Regression predicts a continuous numeric value.
- A linear model estimates a relationship such as `y = b0 + b1*x`.
- Training chooses parameters that reduce a loss function.
- Evaluation measures how well predictions match observed targets.

## Study Sequence

1. Inspect a dataset and identify rows, columns, features, and target.
2. Plot a possible relationship between an input and the target.
3. Split data into training and test sets.
4. Fit a linear-regression model using the training data.
5. Generate predictions and plot the fitted line.
6. Calculate mean squared error and interpret its units.
7. Compare predictions with actual values instead of trusting a single score.

## Explain in Plain Language

The model does not memorize a correct answer for every future row. It estimates a pattern from the training examples and applies that pattern to new inputs. The test set is useful because it checks whether the pattern generalises.

## Practice Tasks

- Fit a model with one feature.
- Fit a model with several features and compare the coefficient meanings.
- Predict a new value and state why extrapolation can be risky.
- Create a baseline that always predicts the training mean.
- Compare the model with the baseline using the same test set.

## Mastery Checklist

- [ ] I can distinguish features from the target.
- [ ] I can explain training data versus test data.
- [ ] I can interpret a coefficient and an intercept.
- [ ] I can explain MSE and why lower is usually better.
- [ ] I can identify a possible relationship from a plot.

## Connection to Week 2

Week 1 introduces fitting and evaluation. Week 2 asks whether one train/test split is enough and how to detect a model that performs well on training data but poorly on unseen data.
