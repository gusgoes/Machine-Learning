# Final Project - End-to-End Machine Learning Investigation

## Purpose

Demonstrate the complete machine-learning workflow on a meaningful dataset and communicate the results clearly.

## Recommended Project Structure

1. **Question:** Define the real-world question and the prediction target.
2. **Data audit:** Describe observations, features, missing values, duplicates, outliers, and class balance.
3. **Exploration:** Use tables and plots to understand relationships and possible bias.
4. **Split:** Create train, validation, and test data before fitting learned preprocessing.
5. **Baseline:** Build the simplest credible model.
6. **Feature preparation:** Encode, scale, impute, or engineer features using a reproducible pipeline.
7. **Candidate models:** Compare a small number of justified alternatives.
8. **Validation:** Tune hyperparameters without repeatedly adapting to the test set.
9. **Error analysis:** Inspect wrong predictions and performance by class or subgroup.
10. **Final evaluation:** Report metrics and uncertainty on the untouched test data.
11. **Communication:** Explain what the model can and cannot support.

## Model Selection Guide

- Numeric target: begin with a mean baseline and linear regression.
- Binary target: begin with a majority baseline and logistic regression.
- Mixed tabular features: compare a linear model with a tree or distance-based approach if covered by the module.
- Image target: begin with a simple CNN or transfer-learning baseline.
- Use SVMs or neural networks when their assumptions and trade-offs are justified, not merely because they are more advanced.

## Required Checks

- Is the target defined before inspecting outcomes that would not be available at prediction time?
- Is the split representative of the real deployment situation?
- Is preprocessing fitted only on training data?
- Is the baseline included?
- Are metrics appropriate for the cost of errors and class balance?
- Are hyperparameters selected using validation data?
- Are test results reported only after decisions are finished?
- Are limitations, ethical concerns, and possible sources of bias discussed?

## Suggested Report Sections

1. Problem and motivation
2. Dataset and data-quality audit
3. Exploratory analysis
4. Methodology
5. Baseline and candidate models
6. Validation strategy
7. Results and error analysis
8. Limitations and responsible use
9. Conclusion and possible next steps

## Mastery Checklist

- [ ] I can reproduce the complete experiment from a clean start.
- [ ] I can justify the target, split, preprocessing, model, and metrics.
- [ ] I can explain results to a non-specialist.
- [ ] I can distinguish evidence from speculation.
- [ ] I can state what additional data or experiments would improve confidence.

## How the Weeks Feed the Project

Weeks 1-4 provide the basic supervised workflow, validation, classification, metrics, and feature preparation. Weeks 5-7 explain optimisation, complexity control, and SVM alternatives. Weeks 8-11 provide neural-network, CNN, and transfer-learning options. The project is the place to combine these ideas selectively and justify each decision.
