# Ovarian Cancer Subtype Classification Using Deep Learning, Attention Mechanisms, and Explainable AI

![Python](https://img.shields.io/badge/Python-3.10-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange)
![Keras](https://img.shields.io/badge/Keras-DeepLearning-red)
![SHAP](https://img.shields.io/badge/XAI-SHAP-green)
![License](https://img.shields.io/badge/License-MIT-brightgreen)

## Overview

Ovarian cancer is one of the most lethal gynecological malignancies worldwide. Accurate subtype classification is essential for effective diagnosis, prognosis, and treatment planning.

This project presents a Deep Learning-based framework for automated ovarian cancer subtype classification using medical imaging data. The proposed approach combines Convolutional Neural Networks (CNNs), transfer learning architectures, attention mechanisms, and Explainable AI (XAI) techniques to improve classification performance and model interpretability.

---

## Key Features

* Multi-class ovarian cancer subtype classification
* Transfer learning with VGG16 and MobileNetV2
* Attention mechanism using Squeeze-and-Excitation (SE) Blocks
* Explainable AI using SHAP
* Medical image preprocessing and augmentation
* Deep learning model comparison
* Healthcare AI application

---

## Dataset

The dataset consists of ovarian cancer medical images categorized into multiple diagnostic classes.

### Classification Categories

* Serous Carcinoma
* Mucinous Carcinoma
* Endometrioid Carcinoma
* Clear Cell Carcinoma
* Normal Tissue Samples

### Dataset Characteristics

* Histopathological Medical Images
* Multi-Class Classification Problem
* Healthcare AI Research Dataset
* Suitable for Deep Learning Applications

---

## Methodology

### Data Preprocessing

The following preprocessing techniques were applied:

* Image Resizing
* Normalization
* Data Cleaning
* Dataset Organization

### Data Augmentation

To improve model robustness:

* Rotation
* Flipping
* Zooming
* Translation
* Scaling

---

## Model Architecture

### Baseline CNN

A custom Convolutional Neural Network (CNN) was implemented as a baseline classification model.

### Transfer Learning Models

#### VGG16

Pre-trained convolutional architecture used for feature extraction and classification.

#### MobileNetV2

Lightweight transfer learning model optimized for efficient feature learning.

---

## Attention Mechanism

### Squeeze-and-Excitation (SE) Block

The attention mechanism enables the model to focus on the most informative image features.

Benefits:

* Improved feature representation
* Better channel-wise attention
* Enhanced classification accuracy
* Improved model generalization

---

## Explainable AI (XAI)

### SHAP (SHapley Additive Explanations)

To improve transparency and trustworthiness, SHAP was incorporated to explain model predictions.

### Advantages

* Interpretable predictions
* Feature attribution analysis
* Improved model transparency
* Trustworthy healthcare AI

---

## Technologies Used

### Programming Language

* Python

### Deep Learning

* TensorFlow
* Keras

### Computer Vision

* OpenCV
* Pillow

### Explainable AI

* SHAP

### Data Science

* NumPy
* Pandas
* Matplotlib
* Seaborn

---

## Experimental Workflow

```text
Medical Images
      │
      ▼
Data Preprocessing
      │
      ▼
Data Augmentation
      │
      ▼
CNN / VGG16 / MobileNetV2
      │
      ▼
SE Attention Block
      │
      ▼
Classification Layer
      │
      ▼
Subtype Prediction
      │
      ▼
SHAP Explainability
```

---

## Evaluation Metrics

The models were evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Specificity
* Confusion Matrix
* ROC Curve
* AUC Score

---

## Results

The proposed framework demonstrates the effectiveness of combining:

* Deep Learning
* Transfer Learning
* Attention Mechanisms
* Explainable AI

for automated ovarian cancer subtype classification.

### Sample Results

Add your screenshots below after uploading them to the repository.

#### Confusion Matrix

```markdown
![Confusion Matrix](images/confusion_matrix.png)
```

#### ROC Curve

```markdown
![ROC Curve](images/roc_curve.png)
```

#### SHAP Analysis

```markdown
![SHAP Analysis](images/shap_analysis.png)
```

---

## Repository Structure

```text
ovarian-cancer-subtype-classification/

├── Ovarian_Cancer_Classification.ipynb
├── README.md
├── requirements.txt
│
├── images/
│   ├── confusion_matrix.png
│   ├── roc_curve.png
│   ├── shap_analysis.png
│   └── training_curves.png
│
└── dataset/
```

---


## Applications

### Healthcare AI

* Ovarian Cancer Diagnosis
* Clinical Decision Support Systems
* Medical Image Analysis
* Computer-Aided Diagnosis (CAD)

### Research

* Medical Imaging Research
* Explainable AI Research
* Deep Learning Research
* Precision Healthcare

---

## Future Work

* Vision Transformer (ViT) Models
* Advanced Attention Architectures
* Federated Learning in Healthcare
* Real-Time Clinical Deployment
* Multi-Modal Cancer Diagnosis
* Explainable Healthcare AI Systems

---

## Author

**Ankur Ray Chayan**

Machine Learning Researcher | Embedded Systems Researcher

GitHub: https://github.com/AnkurRay25

Research Interests:

* Artificial Intelligence
* Deep Learning
* Computer Vision
* Healthcare AI
* Explainable AI
* Medical Image Analysis

---

## License

This project is licensed under the MIT License.

