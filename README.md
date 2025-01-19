# Neural-networks-in-image-processing
Histological Image Patch Classification Model

## Dataset

The dataset consists of color histological image patches, each labeled with one of the nine classes. These patches provide diverse histological patterns and textures critical for robust model training and evaluation.

## Classes:

ADI: Adipose tissue.

BACK: Background (no tissue).

DEB: Debris.

LYM: Lymphocytes.

MUC: Mucin.

MUS: Muscle tissue.

NORM: Normal tissue.

STR: Stroma.

TUM: Tumor tissue.

## Evaluation Result on Full Test Dataset: 0.9825

## Implemented Enhancements:
* `#LBL1` -- Data augmentation
* `#LBL2` -- Validation on a subset of the training dataset
* `#LBL3` -- Displaying various metrics during training (e.g., loss function value at each epoch)
* `#LBL4` -- Automatic model saving during training
* `#LBL5` -- Plotting graphs to visualize the training process
* `#LBL6` -- Confusion matrix construction, evaluation of model sensitivity and specificity
