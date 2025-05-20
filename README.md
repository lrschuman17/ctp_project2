# ctp_project2
# PlantVillage Disease Classification using CatBoost, SVM, Decision Trees, and KNN

This project uses the PlantVillage dataset to classify plant diseases from leaf images. The focus is on the **segmented version** of the dataset, which isolates the leaf from the background to improve classification accuracy.

## 🌱 Dataset

The dataset is sourced from the open-access [PlantVillage Dataset](https://github.com/spMohanty/PlantVillage-Dataset), specifically using:

- `raw/segmented` images
- Binary classification: Healthy vs. Diseased

## 🧠 Models Used

- **CatBoost Classifier**: Gradient boosting on decision trees, robust on small tabular datasets.
- **Support Vector Machine (SVM)**: A linear classifier used as a baseline model.
- **Decision Tree Classifier**: A simple interpretable model for visualizing decision boundaries.
- **K-Nearest Neighbors (KNN)**: A distance-based classifier for intuitive class separation.

## 🧰 Features

- Image preprocessing and label extraction
- Feature extraction using image statistics (e.g., texture, color variance)
- Training and evaluation using four classifiers: CatBoost, SVM, Decision Tree, and KNN
- Accuracy, confusion matrix, and feature importance visualizations

## 📦 Requirements

Install the following packages before running the notebook:

```bash
pip install catboost
pip install scikit-learn
pip install pandas
pip install matplotlib
pip install opencv-python
