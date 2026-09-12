# Week 11 - Transfer Learning

## Purpose

Use a pretrained image model as a starting point for a new classification problem.

## Prerequisites

Week 10 CNNs, Week 2 validation, Week 6 regularisation, and Week 8 training workflows.

## Core Ideas

- A pretrained model contains representations learned from another dataset.
- Feature extraction freezes the base model and trains a new classification head.
- Fine-tuning unfreezes selected deeper layers after the new head has stabilised.
- The new data must be preprocessed as expected by the base model.
- Fine-tuning requires a small learning rate to avoid damaging useful features.
- The source and target tasks need not be identical, but similarity affects usefulness.

## Study Sequence

1. Inspect the target dataset and split it correctly.
2. Select a suitable pretrained base.
3. Freeze the base and train a new head.
4. Measure validation performance and inspect errors.
5. Unfreeze a limited number of upper layers.
6. Fine-tune with a low learning rate.
7. Compare against a scratch-trained baseline when feasible.

## Practice Tasks

- Compare frozen-feature extraction with fine-tuning.
- Check preprocessing requirements and input shape.
- Plot validation curves after each training phase.
- Investigate whether the model relies on background or other shortcuts.
- Report compute, data limitations, and uncertainty.

## Mastery Checklist

- [ ] I can explain feature extraction versus fine-tuning.
- [ ] I can justify freezing and unfreezing decisions.
- [ ] I can identify preprocessing incompatibilities.
- [ ] I can use validation data to decide whether fine-tuning helped.
- [ ] I can describe limitations caused by domain shift.

## Connection to the Project

Transfer learning is one possible project technique, not a required answer for every dataset. The project should begin with the problem and data, then select a baseline and justify any advanced model.
