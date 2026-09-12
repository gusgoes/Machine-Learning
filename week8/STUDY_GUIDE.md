# Week 8 - Artificial Neural Networks

## Purpose

Build and train neural networks with TensorFlow and Keras for supervised prediction.

## Prerequisites

Weeks 1-6, especially loss functions, gradient descent, scaling, classification, and validation.

## Core Ideas

- A neuron computes a weighted sum followed by an activation function.
- Layers compose simple transformations into a nonlinear model.
- Forward propagation produces predictions.
- Backpropagation calculates how parameters contributed to the loss.
- The optimiser updates weights using gradients.
- The output layer and loss must match the task.
- Validation data helps monitor generalisation during training.

## Study Sequence

1. Define the input shape and target representation.
2. Prepare and scale the data.
3. Build a small baseline network.
4. Choose an output activation and loss appropriate to the task.
5. Train while monitoring training and validation curves.
6. Evaluate on held-out data.
7. Diagnose overfitting and adjust architecture, epochs, or regularisation.

## Practice Tasks

- Train a binary classifier with one hidden layer.
- Plot loss and metric curves.
- Compare early stopping with training for a fixed number of epochs.
- Change one architecture choice at a time.
- Compare the neural network with a simpler classical baseline.

## Mastery Checklist

- [ ] I can describe a neuron and a layer.
- [ ] I can choose a suitable output/loss combination.
- [ ] I can read training and validation curves.
- [ ] I can explain an epoch and a batch.
- [ ] I can identify neural-network overfitting.

## Connection to Week 9

Week 8 establishes the neural-network workflow. Week 9 extends it to multiclass predictions, deeper architectures, and more systematic tuning.
