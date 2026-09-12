# Machine Learning Study Map

This document is the outside-the-fold map for the whole module. Study the weeks in order: each stage supplies a concept, mathematical idea, or practical habit used by the next stage.

## Big Picture

```text
Python and data handling
        |
        v
Week 1: regression and the supervised-learning workflow
        |
        v
Week 2: validation and generalisation
        |
        +--> Week 3: classification with logistic regression
        |          |
        |          v
        |      Week 4: metrics, k-NN, and feature engineering
        |
        v
Week 5: optimisation with gradient descent
        |
        v
Week 6: regularisation and model complexity
        |
        v
Week 7: support vector machines
        |
        v
Week 8: neural-network foundations with TensorFlow/Keras
        |
        v
Week 9: deeper and multiclass neural networks
        |
        v
Week 10: convolutional neural networks for images
        |
        v
Week 11: transfer learning
        |
        v
Project: complete end-to-end machine-learning investigation
```

## How Each Week Supports the Next

| Stage | Main question | Contribution to the next stage |
| --- | --- | --- |
| Week 1 | How can a model learn a numeric relationship? | Introduces features, targets, fitting, prediction, loss, and evaluation. |
| Week 2 | Will the model work on new data? | Adds train/validation/test thinking and explains overfitting. |
| Week 3 | How can we predict categories? | Transfers the supervised-learning workflow to probabilities and classification. |
| Week 4 | How do we compare classifiers and prepare data? | Supplies metrics, scaling, nearest-neighbour reasoning, and feature preparation. |
| Week 5 | How are model parameters found? | Explains optimisation behind linear models and prepares the logic used by neural networks. |
| Week 6 | How can we control complexity? | Connects model flexibility, coefficients, loss functions, and generalisation. |
| Week 7 | Can a boundary be chosen using geometry? | Extends classification into margins, support vectors, and kernels. |
| Week 8 | How can several simple units learn nonlinear patterns? | Introduces layers, activations, backpropagation, and practical deep-learning tools. |
| Week 9 | How do neural networks handle harder class problems? | Builds depth, multiclass outputs, tuning, and robust evaluation. |
| Week 10 | How can models use image structure? | Adds convolutions and spatial feature extraction. |
| Week 11 | How can a strong existing model help with a new task? | Reuses learned image representations and leads to practical project modelling. |
| Project | Can the full process answer a real question? | Combines data, validation, modelling, interpretation, and communication. |

## Common Workflow Used Throughout

1. Define the prediction problem and identify the target.
2. Inspect the data before choosing a model.
3. Split data correctly before fitting preprocessing steps.
4. Build a simple baseline.
5. Train the model using an appropriate loss function.
6. Evaluate on data that was not used for fitting.
7. Diagnose errors, bias, variance, and data-quality problems.
8. Improve one decision at a time and record the reason.
9. Communicate limitations, not only the best score.

## Mathematical Dependencies

- Descriptive statistics support data inspection and evaluation.
- Functions and graphs support regression, sigmoid probabilities, and loss curves.
- Derivatives explain gradient descent and backpropagation.
- Vectors and geometry support linear models, SVM margins, and neural-network layers.
- Probability supports classification outputs and metrics.

## Suggested Study Cycle

For every week, complete this cycle:

1. Read the corresponding `STUDY_GUIDE.md`.
2. Review the relevant notebook without copying code blindly.
3. Reproduce the smallest working example.
4. Change one variable, feature, or hyperparameter.
5. Explain the result in plain language.
6. Complete the mastery checklist before moving on.

## Assessment and Project Connection

MCQ preparation should focus on definitions, assumptions, formulas, graphs, and interpreting output. The final project should demonstrate the whole workflow rather than only a sophisticated model. A simple, well-validated model is stronger than a complex model with data leakage or unexplained results.

## Repository Navigation

- [Week 1 guide](week1/STUDY_GUIDE.md)
- [Week 2 guide](week2/STUDY_GUIDE.md)
- [Week 3 guide](week3/STUDY_GUIDE.md)
- [Week 4 guide](week4/STUDY_GUIDE.md)
- [Week 5 guide](week5/STUDY_GUIDE.md)
- [Week 6 guide](week6/STUDY_GUIDE.md)
- [Week 7 guide](week7/STUDY_GUIDE.md)
- [Week 8 guide](week8/STUDY_GUIDE.md)
- [Week 9 guide](week9/STUDY_GUIDE.md)
- [Week 10 guide](week10/STUDY_GUIDE.md)
- [Week 11 guide](week11/STUDY_GUIDE.md)
- [Project guide](Project/STUDY_GUIDE.md)
