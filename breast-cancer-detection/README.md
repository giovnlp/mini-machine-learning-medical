# Breast Cancer Diagnosis - ML Classifier

This project is a machine learning model built to classify whether a tumor is malignant or benign using the Breast Cancer Wisconsin dataset. It uses feature selection based on correlation and applies a Random Forest Classifier to predict diagnoses.

## 📁 Dataset

The dataset used is `data.csv`, based on the **Breast Cancer Wisconsin (Diagnostic) Data Set**. It includes features such as:

- radius, texture, perimeter, area, smoothness, etc.
- Each measured as mean, standard error, and "worst" (largest).

## 🧼 Data Preprocessing

- Dropped irrelevant columns: `id` and `Unnamed: 32`
- Converted diagnosis labels from `'M'` (malignant) and `'B'` (benign) to binary format:
  - `M → 1`
  - `B → 0`

## 🔍 Feature Selection

Used correlation analysis to select 11 most relevant features for prediction:

- `radius_mean`, `perimeter_mean`, `area_mean`
- `compactness_mean`, `concavity_mean`, `concave points_mean`
- `radius_se`, `area_se`
- `radius_worst`, `perimeter_worst`, `area_worst`

## 🤖 Models

Trained several models (MLP, Random Forest, KNN, SVM). The selected model in the final version was:

- **Random Forest Classifier**

## 📊 Evaluation Metrics

Model performance was evaluated using:

- Confusion Matrix
- **Precision**: 0.97
- **Recall**: 0.85
- **Accuracy**: 0.93

These metrics show a good balance between detecting true positives and minimizing false positives.








--> This mini project was made based on an online artifical inteligence medical course.

