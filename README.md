# 🧠 Machine Learning With Python

## 📌 Overview

This project focuses on comparing multiple Machine Learning models using performance metrics, explainability techniques, and statistical testing.

It includes:

* Model training and evaluation
* LIME explainability
* Statistical comparison using Wilcoxon test
* Organized outputs for analysis

---

## 📁 Project Structure

```
Machine-Learning-With-Python/
│
├── AllResults/        # Stores all model results, evaluation outputs
├── Dataset/           # Contains dataset files used for training/testing
├── LimeHtmlFile/      # LIME explanation HTML files
├── Model/             # Saved trained models
│
└── README.md          # Project documentation
```

---

## 🤖 Models Used

* Logistic Regression
* Decision Tree
* Random Forest
* Gradient Boosting
* XGBoost
* LightGBM
* CatBoost
* K-Nearest Neighbors (KNN)
* Multi-Layer Perceptron (MLP)

---

## 📊 Features

* ✅ Multiple ML model comparison
* ✅ Performance evaluation (accuracy, etc.)
* ✅ LIME-based model explainability
* ✅ Wilcoxon statistical test for model comparison
* ✅ Organized output storage

---

## ⚙️ Requirements

Install dependencies using:

```
pip install numpy pandas scikit-learn matplotlib seaborn xgboost lightgbm catboost lime shap
```

---

## ▶️ How to Run

1. Load dataset from `Dataset/`
2. Train models and save them in `Model/`
3. Generate results → stored in `AllResults/`
4. Generate LIME explanations → saved in `LimeHtmlFile/`

---

## 📈 Outputs

* 📁 Model performance results → `AllResults/`
* 📁 Saved models → `Model/`
* 📁 LIME explanations → `LimeHtmlFile/`

---

## 🔬 Statistical Analysis

Wilcoxon Signed-Rank Test is used to compare model performances and determine statistically significant differences.

---

## 📌 Future Improvements

* Add SHAP explainability
* Improve model tuning
* Add GUI or web interface
* Convert project into production-ready pipeline

---

## 👨‍💻 Author

**Sujit Kar**

---

## ⭐ Support

If you like this project, consider giving it a star ⭐ on GitHub!
