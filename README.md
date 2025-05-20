# ctp_project2
# PlantVillage Disease Classification using CatBoost and SVM

This project uses the PlantVillage dataset to classify plant diseases from leaf images. The focus is on the **segmented version** of the dataset, which isolates the leaf from the background to improve classification accuracy.

## 🌱 Dataset

The dataset is sourced from the open-access [PlantVillage Dataset](https://github.com/spMohanty/PlantVillage-Dataset), specifically using:

- `raw/segmented` images
- Binary classification: Healthy vs. Diseased

## 🧠 Models Used

- **CatBoost Classifier**: Gradient boosting on decision trees optimized for categorical features and small datasets.
- **Support Vector Machine (SVM)**: A traditional classifier used for baseline comparison.

## 🧰 Features

- Image preprocessing and label extraction
- Feature extraction using basic image statistics (e.g., color, texture)
- Training and evaluation using SVM and CatBoost
- Accuracy, confusion matrix, and feature importance visualizations

## 📦 Requirements

Install the following packages before running the notebook:

```bash
pip install catboost
pip install scikit-learn
pip install pandas
pip install matplotlib
pip install opencv-python
