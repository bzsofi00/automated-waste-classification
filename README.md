# Automated Image-Based Waste Classification Using Machine Learning

## Overview

This project explores automated waste classification using image recognition and machine learning techniques to support more efficient waste sorting and recycling. The task involved classifying images into **30 distinct waste categories** using a balanced dataset of 15,000 images, combining studio-quality and real-world photographs.

Four different modelling approaches were implemented and evaluated, ranging from traditional machine learning to deep learning and transfer learning.

## Objectives

- Develop models capable of classifying waste images into 30 categories.
- Compare traditional machine learning and deep learning approaches.
- Evaluate model performance using accuracy, precision, recall and F1-score.
- Investigate the effectiveness of transfer learning for waste classification.

## Models and Approaches

The project evaluated the following approaches:

1. **Support Vector Machine (SVM)** – A traditional machine learning baseline using PCA for dimensionality reduction.
2. **Custom Convolutional Neural Network (CNN)** – A CNN architecture developed for image classification.
3. **CNN with Residual Connections** – An enhanced CNN incorporating residual connections to improve feature learning.
4. **EfficientNetB0** – A pre-trained convolutional neural network fine-tuned using transfer learning.

## Results

The models were evaluated on their classification performance using accuracy, precision, recall and F1-score.

| Model | Test Accuracy | F1-score |
|---|---:|---:|
| SVM with PCA | 55.00% | 0.5600 |
| Baseline CNN | 60.84% | 0.6116 |
| CNN with Residual Connections | 66.11% | 0.6606 |
| Fine-tuned EfficientNetB0 | **87.39%** | **0.8734** |

## Key Findings

- Fine-tuned EfficientNetB0 achieved the best overall performance, with a test accuracy of 87.39% and an F1-score of 0.8734.
- The CNN with residual connections outperformed the baseline CNN, demonstrating the benefit of incorporating residual connections.
- Both CNN approaches outperformed the traditional SVM baseline.
- The results highlight the effectiveness of deep learning, particularly transfer learning, for image-based classification across diverse waste categories.

## Technologies

- Python
- Machine Learning
- Deep Learning
- Scikit-learn
- TensorFlow / Keras
- Convolutional Neural Networks (CNN)
- Support Vector Machines (SVM)
- PCA
- EfficientNetB0
- Transfer Learning

## Dataset

The project used a balanced dataset of 15,000 images across 30 waste categories, including both studio-quality and real-world images.

The full dataset is not included in this repository due to its size. Please refer to the project report for further information about the dataset.

## Academic Context

Developed as part of the **Machine Learning and Deep Learning** course (CDSCO2004E) at Copenhagen Business School (CBS).
