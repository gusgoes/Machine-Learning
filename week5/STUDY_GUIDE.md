# Week 5 - Gradient Descent

## Purpose

Understand the optimisation process used to find parameters that reduce model error.

## Prerequisites

Week 1 loss functions, linear models, basic algebra, graphs, and an introduction to derivatives.

## Core Ideas

- A loss function measures how bad current predictions are.
- A parameter is learned from data; a hyperparameter is selected by the practitioner.
- The gradient gives the direction of steepest increase.
- Gradient descent moves parameters in the opposite direction.
- The learning rate controls step size.
- Batch, stochastic, and mini-batch methods use different amounts of data per update.
- Poor scaling or a poor learning rate can slow or prevent convergence.

## Study Sequence

1. Draw a simple one-variable loss curve.
2. Calculate a derivative for a basic function.
3. Implement one gradient-descent update by hand.
4. Track parameters and loss over iterations.
5. Plot the loss curve.
6. Compare learning rates and stopping conditions.

## Practice Tasks

- Implement gradient descent for a straight line.
- Test a learning rate that is too small and one that is too large.
- Standardise features and compare convergence.
- Verify the implementation against a library model.
- Explain why a decreasing training loss does not guarantee good generalisation.

## Mastery Checklist

- [ ] I can explain the role of the gradient.
- [ ] I can distinguish parameters from hyperparameters.
- [ ] I can interpret a learning-rate experiment.
- [ ] I can recognise divergence in a loss plot.
- [ ] I can connect optimisation to the model-fitting workflow.

## Connection to Week 6

Gradient descent minimises a chosen loss, but a model can still become too complex. Week 6 adds regularisation terms that discourage overly flexible solutions.
