# Marble Surface Defect Classification (CNN)

## 📌 Overview
This project implements a multiclass image classification model to detect defects in marble surfaces using a Convolutional Neural Network (CNN) built from scratch in PyTorch.

## 📂 Dataset
Downloaded from:- https://www.kaggle.com/datasets/wardaddy24/marble-surface-anomaly-detection-2
- Classes: crack, dot, good, joint
- Predefined train/test split
- Validation split created from training data

## ⚙️ Methodology
- Image preprocessing (resize, normalization)
- Custom Dataset and DataLoader
- CNN built from scratch
- Training with CrossEntropyLoss and Adam optimizer

## 📊 Results
- Validation Accuracy: ~82%
- Test Accuracy: ~84%

## 📈 Visualizations
- Training Loss vs Validation Accuracy
- Confusion Matrix

## 🔍 Insights
- Strong performance on 'good' class
- Confusion observed between 'crack' and 'joint'
- 'dot' class is hardest to classify

## 🚀 Future Improvements
- Data augmentation
- Deeper architectures
- Transfer learning

## 🛠️ Tech Stack
- Python
- PyTorch
- NumPy
- Matplotlib
- Scikit-learn
