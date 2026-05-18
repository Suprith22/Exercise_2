# Brain Tumor Classification using Transfer Learning

## Overview

This project implements transfer learning using MobileNet for brain tumor MRI classification.

Pipeline:
Image → MobileNet Feature Extraction → Dense Classification Layer

## Methodology

* A pretrained MobileNet model was used.
* Earlier pretrained layers were frozen initially.
* Later layers were fine-tuned for brain tumor classification.
* Transfer learning reduced training complexity and improved performance.

## Important Concepts

* Transfer Learning
* MobileNet
* Fine Tuning
* Deep Feature Extraction
* Medical Image Classification

## Evaluation Metrics

* Accuracy
* F1-score
* Sensitivity
* Specificity

## Observations

* Transfer learning achieved strong performance due to pretrained visual features.
* Fine tuning improved dataset-specific feature learning.
* CNN-based transfer learning outperformed traditional machine learning methods.

