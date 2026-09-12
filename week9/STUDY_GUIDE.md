# Week 9 - Neural Networks II

## Purpose

Handle more difficult neural-network tasks, especially multiclass prediction and model tuning.

## Prerequisites

Week 8 neural-network structure, TensorFlow/Keras training, loss curves, and Week 4 metrics.

## Core Ideas

- Multiclass classification predicts one class from several possibilities.
- One-hot targets and integer targets require different loss configurations.
- Softmax outputs form a probability distribution across classes.
- Deeper models can represent richer functions but are harder to regularise.
- Dropout, early stopping, weight decay, and data augmentation can improve generalisation.
- Hyperparameter searches must use validation information correctly.

## Study Sequence

1. Inspect class labels and class frequencies.
2. Decide how targets will be encoded.
3. Build a small multiclass baseline.
4. Select output activation and loss consistently.
5. Monitor per-class performance, not only overall accuracy.
6. Compare model changes using a fixed validation procedure.
7. Evaluate once on the untouched test set.

## Practice Tasks

- Train a classifier on three or more classes.
- Display a confusion matrix and inspect difficult class pairs.
- Compare a shallow and deeper network.
- Add early stopping or dropout and observe the curves.
- Explain why a high accuracy can hide poor performance on a minority class.

## Mastery Checklist

- [ ] I can distinguish binary and multiclass output layers.
- [ ] I can match target encoding to the loss function.
- [ ] I can interpret softmax output.
- [ ] I can diagnose class-specific errors.
- [ ] I can tune a network without contaminating the test result.

## Connection to Week 10

The same neural-network training principles apply to images. CNNs add an architecture that preserves local spatial structure instead of treating every pixel as unrelated input.
