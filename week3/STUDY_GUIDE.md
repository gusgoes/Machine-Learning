# Week 3 - Logistic Regression and Classification

## Purpose

Use a linear model to estimate class probabilities and make binary classification decisions.

## Prerequisites

Weeks 1 and 2: supervised learning, splitting, generalisation, functions, and basic probability.

## Core Ideas

- Classification predicts a discrete class rather than a continuous value.
- Logistic regression maps a linear score through the sigmoid function.
- The sigmoid output is between 0 and 1 and can be interpreted as a probability when the model is appropriate.
- A threshold converts probability into a class label.
- Log loss penalises confident incorrect predictions strongly.
- A confusion matrix separates true positives, true negatives, false positives, and false negatives.

## Study Sequence

1. Encode the target consistently.
2. Inspect class balance before training.
3. Split the data with stratification when appropriate.
4. Scale features when the algorithm is sensitive to feature magnitude.
5. Train logistic regression.
6. Inspect probabilities, labels, and the confusion matrix.
7. Change the threshold and observe precision/recall trade-offs.

## Practice Tasks

- Plot the sigmoid function.
- Use a simple feature to draw an approximate decision boundary.
- Compare accuracy with a majority-class baseline.
- Construct a confusion matrix by hand for a small example.
- Explain a false positive and false negative in the dataset's domain.

## Mastery Checklist

- [ ] I can distinguish regression from classification.
- [ ] I can explain what the sigmoid function does.
- [ ] I can interpret a confusion matrix.
- [ ] I know why accuracy can be misleading with imbalanced classes.
- [ ] I can explain how changing a threshold changes decisions.

## Connection to Week 4

Week 3 introduces the classification problem. Week 4 broadens the tools used to judge classifiers and adds k-NN and feature-engineering decisions that affect model performance.
