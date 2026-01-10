# Best Models for Medium-Scale Datasets
This repository provides a comparative study and practical guide to selecting the best machine learning models for medium-scale datasets, covering both Regression and Classification problems.

Medium-scale datasets typically range from 10,000 to 1,000,000 rows, where model performance, training time, and overfitting control all become critical.
# 📊 Dataset Scale Definition
| Dataset Size | Description                 |
| ------------ | --------------------------- |
| Small        | < 10,000 rows               |
| **Medium**   | **10,000 – 1,000,000 rows** |
| Large        | > 1,000,000 rows            |
# 🏆 Best Model Summary (Medium-Scale)
| Task                   | Best Overall Model           |
| ---------------------- | ---------------------------- |
| Regression             | **LightGBM Regressor**       |
| Classification         | **LightGBM Classifier**      |
| Categorical-heavy data | **CatBoost**                 |
| Baseline               | Linear / Logistic Regression |
# 🚀 How to Run

Open Kaggle / Google Colab / Jupyter Notebook

Activate GPU (recommended for XGBoost & LightGBM)

Load dataset

Train models

Compare validation scores

Select best-performing model

# 📌 Key Takeaways

Ensemble models outperform single models on medium datasets

LightGBM offers the best balance of speed, accuracy, and scalability

CatBoost excels with categorical data

Always validate to avoid overfitting

# 📜 License

This project is released under the MIT License.
You are free to use, modify, and distribute with attribution.
