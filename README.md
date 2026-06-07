# Forest Fire Smoke Detection System

## Project Overview

This project develops a Deep Learning-based Forest Fire Smoke Detection System capable of classifying forest images into:

- Smoke Present
- No Smoke Present

The project compares a Custom CNN with Transfer Learning models including MobileNetV2 and ResNet50.

---

## Objectives

- Detect smoke in forest environments automatically.
- Compare CNN and transfer learning approaches.
- Improve wildfire monitoring and early warning systems.
- Analyze model performance using multiple evaluation metrics.

---

## Dataset

Forest Fire Smoke Dataset

Sources:
- Kaggle
- Roboflow

Images are resized to 224×224 pixels and normalized before training.

---

## Models Implemented

### Custom CNN
- Conv2D (32)
- Conv2D (64)
- Conv2D (128)
- Dense (128)
- Dropout (0.5)

### MobileNetV2
Pretrained on ImageNet and fine-tuned for binary classification.

### ResNet50
Pretrained on ImageNet and fine-tuned for binary classification.

---

## Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC
- Confusion Matrix

---

## Repository Structure

- Proposal/ – Project proposal
- notebooks/ – Kaggle notebooks
- src/ – Python source code
- figures/ – Generated plots and visualizations
- models/ – Saved trained models

---

## Author

Karthik Kanmanthreddy

Master's in Data Science

Machine Learning Project
