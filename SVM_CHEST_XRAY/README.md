# Chest X-ray Classification using PCA + SVM

## Overview

This project implements Support Vector Machine (SVM) classification on chest X-ray images for pneumonia detection.

Pipeline:
Image → Resize → Flatten → PCA → SVM

## Methodology

* Images were resized and converted into feature vectors.
* PCA was used for dimensionality reduction.
* SVM was used for classification.
* Both linear and RBF kernels were tested.

## Important Concepts

* PCA Dimensionality Reduction
* Support Vector Machines
* Linear vs RBF Kernel
* Medical Image Classification

## Evaluation Metrics

* Accuracy
* F1-score
* Sensitivity
* Specificity

## Observations

* RBF kernel performed better due to nonlinear image patterns.
* PCA reduced dimensionality and computation cost.
* Increasing training data improved model performance.
