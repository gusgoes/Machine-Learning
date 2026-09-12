# Week 4 - Metrics, k-NN, and Feature Engineering

## Purpose

Choose meaningful classification metrics, understand nearest-neighbour classification, and prepare useful input features.

## Prerequisites

Week 3 classification, confusion matrices, probabilities, and Week 2 validation principles.

## Core Ideas

- Precision answers: of predicted positives, how many were correct?
- Recall answers: of actual positives, how many were found?
- F1-score balances precision and recall.
- ROC-AUC evaluates ranking across thresholds, but must be interpreted with class balance and context.
- k-NN predicts using nearby training examples.
- Distance-based methods are affected by feature scale.
- Feature engineering transforms raw information into a form a model can use.

## Study Sequence

1. Define which error matters most in the application.
2. Calculate several metrics, not accuracy alone.
3. Scale numeric features before k-NN.
4. Compare several values of `k` using validation or cross-validation.
5. Encode categorical variables and handle missing values.
6. Refit preprocessing only within the training workflow.

## Practice Tasks

- Compute precision, recall, and F1 from a confusion matrix.
- Compare k-NN with logistic regression.
- Plot validation score against `k`.
- Test the effect of scaling on neighbour selection.
- Create a preprocessing pipeline for mixed numeric and categorical data.

## Mastery Checklist

- [ ] I can select a metric based on the cost of errors.
- [ ] I can explain why k-NN needs a meaningful distance.
- [ ] I can identify when a feature should be scaled or encoded.
- [ ] I can spot preprocessing leakage.
- [ ] I can compare models using the same validation procedure.

## Connection to Week 5

Feature preparation and evaluation tell us whether a model is useful. Week 5 explains how model parameters are found by minimising a loss function with gradient descent.
