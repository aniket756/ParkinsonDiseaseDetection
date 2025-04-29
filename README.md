# Parkinson’s Disease Detection using Voice Features

This project explores early detection of Parkinson’s Disease (PD) using voice features and machine learning techniques. A dataset containing biomedical voice measurements is analyzed to classify and predict the presence and progression of PD.

## 🧠 Project Overview

Parkinson's Disease affects motor skills, and one of the early signs can be changes in speech. This notebook applies various machine learning models (e.g., ensemble methods, Isolation Forest) to identify patterns in vocal features that may signal early PD.

## 📁 Contents

- `project.ipynb`: Main Jupyter notebook with data loading, preprocessing, model training, and evaluation.
- `parkinsons_updrs.data`: Dataset containing voice recordings and clinical labels (assumed to be present).
- `README.md`: Project documentation.

## 🔍 Dataset Description

The dataset includes a range of voice measurements such as:
- Jitter and shimmer
- Harmonics-to-noise ratio
- Nonlinear dynamic complexity measures

These are paired with the **motor UPDRS** and **total UPDRS** scores that indicate disease severity.

## 🛠️ Methods Used

- Data preprocessing and feature selection
- Exploratory Data Analysis (EDA)
- Machine Learning models:
  - Random Forest
  - XGBoost
  - Isolation Forest
- Model evaluation (accuracy, precision, recall, ROC curves)

## 📈 Results

The notebook compares model performance to identify the most reliable technique for early-stage Parkinson’s detection. It also includes visualizations and metrics for interpretability.

## 🚀 Getting Started

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/ParkinsonDiseaseDetection.git
   cd ParkinsonDiseaseDetection
