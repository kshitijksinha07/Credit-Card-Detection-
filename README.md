# Credit Card Fraud Detection Pipeline

This project implements a high-performance predictive model to detect fraudulent transactions using the ULB Credit Card Fraud dataset.

## 🚀 Key Features
- **Exploratory Data Analysis:** Visualizing transaction density over time and feature correlations.
- **Advanced Engineering:** Converting raw timestamps into cyclical hourly features.
- **Model:** LightGBM (Gradient Boosting Machine) with custom hyperparameter tuning.
- **Validation Strategy:** 5-Fold Stratified Cross-Validation to handle extreme class imbalance (0.17% fraud).

## 📊 Results
- **Metric:** ROC-AUC Score ~0.97+
- **Recall:** Optimized to minimize false negatives (missed fraud).

## 🛠️ How to Run
1. Open the notebook in [Google Colab](YOUR_GITHUB_LINK_HERE).
2. Run all cells; the dataset will be automatically downloaded via `kagglehub`.
