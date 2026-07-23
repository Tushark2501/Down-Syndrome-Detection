# Down Syndrome Detection using ResNet50 Transfer Learning

## Overview

This project uses ResNet50 Transfer Learning to classify facial images into two categories:

- Healthy
- Down Syndrome

The model was developed using TensorFlow and Keras in Google Colab.

---

## Features

- ResNet50 Transfer Learning
- Data Augmentation
- Fine-Tuning
- Early Stopping
- Model Checkpointing
- Accuracy, Precision, Recall, F1-Score
- ROC-AUC
- Confusion Matrix
- Grad-CAM Visualization
- Single Image Prediction

---

## Dataset Structure

dataset/
├── train/
│   ├── down_syndrome/
│   └── healthy/
├── val/
│   ├── down_syndrome/
│   └── healthy/
└── test/
    ├── down_syndrome/
    └── healthy/

---

## Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- OpenCV
- Matplotlib
- Scikit-learn
- Google Colab

---

## Performance

| Metric | Score |
|---------|--------|
| Accuracy | 93.85% |
| Precision | 94.39% |
| Recall | 93.26% |
| F1 Score | 93.82% |
| ROC-AUC | 98.81% |

---

## Workflow

1. Load Dataset
2. Data Augmentation
3. Train ResNet50
4. Fine-Tuning
5. Evaluate Model
6. Grad-CAM Visualization
7. Predict Down Syndrome or Healthy

---

## Repository Contents

- Down_Syndrome_Detection.ipynb
- README.md

---

## Disclaimer

This project is developed for educational and research purposes only. It is not intended to replace professional medical diagnosis.
