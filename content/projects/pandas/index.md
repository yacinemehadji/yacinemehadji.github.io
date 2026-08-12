---

title: "Medical AI — Chest X-Ray Analysis"
summary: "Development of a Deep Learning platform for medical image analysis and detection of pulmonary abnormalities in chest X-rays."
date: 2026-01-01
tags:

* Deep Learning
* Medical Imaging
* Computer Vision
* TensorFlow
* Python
  featured: true

---

## Overview

Development of a Deep Learning-based platform for the analysis of chest X-ray images and the detection of suspicious pulmonary abnormalities.

The initial objective is to develop artificial intelligence models capable of classifying chest X-ray images and identifying patterns associated with pulmonary conditions such as pneumonia.

The project is designed as a modular platform that can progressively integrate additional medical datasets, pathologies, and image analysis techniques.

<!--more-->

## Methodology

The project follows a complete medical imaging and Deep Learning pipeline:

1. Data collection and organization
2. Image preprocessing and normalization
3. Dataset preparation and augmentation
4. Convolutional Neural Network training
5. Model validation and evaluation
6. Prediction analysis and visualization
7. Development of an interactive interface

The initial classification task focuses on distinguishing between normal and pneumonia-related chest X-ray images.

## Technologies

* **Python**
* **TensorFlow**
* **Keras**
* **OpenCV**
* **Convolutional Neural Networks (CNN)**
* **NumPy**
* **Matplotlib**
* **Streamlit**

## Medical Datasets

The project explores several publicly available medical imaging datasets, including:

* Chest X-Ray Pneumonia Dataset
* COVID-19 Radiography Dataset
* Tuberculosis Chest X-Ray Dataset
* ChestX-ray14
* LIDC-IDRI
* LUNA16

These datasets provide opportunities to progressively extend the project from binary classification toward multi-disease classification and pulmonary nodule analysis.

## Model Evaluation

Model performance is evaluated using several metrics:

* Accuracy
* Precision
* Recall
* F1-score
* Confusion matrix
* Classification report

Particular attention is given to recall and false-negative cases because missing an abnormal medical image can be particularly important in medical image analysis.

## Explainable AI

Explainable AI techniques such as **Grad-CAM** can be integrated to visualize the regions of the X-ray that contribute most strongly to the model's prediction.

This helps investigate whether the model focuses on relevant pulmonary regions and provides a more interpretable representation of its predictions.

## Interactive Application

The project is designed to evolve into an interactive application using **Streamlit**.

The interface can provide:

* Chest X-ray image upload
* Automatic image preprocessing
* Model prediction
* Confidence score
* Visualization of predictions
* Explainability results
* Model performance information

## Future Developments

Future developments include:

* Extension to additional pulmonary diseases
* Transfer learning with architectures such as MobileNetV2 and EfficientNet
* Lung and lesion segmentation
* Pulmonary nodule detection
* Integration of LIDC-IDRI and LUNA16
* Object detection using YOLO
* Improved explainability with Grad-CAM
* Deployment through a professional web interface
* Optimization for accelerated inference

> **Note:** This project is intended for research and educational purposes and is not a clinical diagnostic tool.
