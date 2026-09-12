# Week 10 - Convolutional Neural Networks

## Purpose

Understand how CNNs learn visual features from image data.

## Prerequisites

Weeks 8 and 9 neural networks, multiclass classification, tensors, training curves, and validation.

## Core Ideas

- An image is represented as a tensor of height, width, and channels.
- A convolution applies learnable filters to local regions.
- Early filters can learn edges and textures; later layers combine them into higher-level patterns.
- Pooling or strided operations reduce spatial dimensions.
- The receptive field describes the input region influencing a feature.
- Data augmentation creates realistic variations to improve robustness.
- CNNs require careful attention to image shape, scaling, labels, and class balance.

## Study Sequence

1. Inspect image dimensions, channels, labels, and sample examples.
2. Create a correct input pipeline and normalise pixel values.
3. Build a small CNN baseline.
4. Monitor training and validation behaviour.
5. Add augmentation or regularisation only when justified.
6. Inspect confusion matrices and incorrect predictions.
7. Save the best validation model and evaluate on test data.

## Practice Tasks

- Visualise several samples from every class.
- Compare a dense network with a CNN.
- Test the effect of one convolutional or pooling layer.
- Display incorrectly classified images and explain possible causes.
- Check that augmentation does not change the label semantics.

## Mastery Checklist

- [ ] I can describe the shape of an image tensor.
- [ ] I can explain convolution and pooling conceptually.
- [ ] I can identify image-data leakage risks.
- [ ] I can interpret CNN training curves.
- [ ] I can investigate errors visually and quantitatively.

## Connection to Week 11

CNNs learn useful visual representations, but training a large network from scratch may require substantial data and compute. Transfer learning reuses representations learned from a larger dataset.
