# 🧠 Machine Learning With Python

## 📌 Overview

This project focuses on comparing multiple Machine Learning models using performance metrics, explainability techniques, and statistical testing.

It includes:

* Model training and evaluation
* LIME explainability
* Statistical comparison using Friedman and Wilcoxon tests
* Organized outputs for analysis

---

## 📁 Project Structure

```text
Project Structure
│
├── AllResults
│   ├── catboost_results (2).xlsx
│   ├── final_metric_ranking (1).xlsx
│   ├── final_results.csv
│   └── model_accuracy_results (1).csv
│
├── FriedmanTest
│   └── friedman_test_result.csv
│
├── LimeHtmlFile
│   ├── lime_catboost (2).html
│   ├── lime_explanation (2).html
│   ├── lime_knn_explanation (2).html
│   ├── lime_lightgbm (2).html
│   └── lime_rf_explanation (2).html
│
├── models
│   └── NewDataSet_Allmodel.ipynb
│
├── wilcoxon
│   └── wilcoxon_final_output (1).xlsx
│
└── README.md
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
* ✅ Performance evaluation
* ✅ LIME-based explainability
* ✅ Friedman statistical test
* ✅ Wilcoxon statistical test
* ✅ Organized result storage

---

## ⚙️ Requirements

Install dependencies using:

```bash
pip install numpy pandas scikit-learn matplotlib seaborn xgboost lightgbm catboost lime shap
```

---

## ▶️ How to Run

1. Open the notebook inside `models/`
2. Load the dataset
3. Train and evaluate models
4. Generate LIME explanations
5. Save outputs automatically

---

## 📈 Outputs

* 📁 Model accuracy and comparison results
* 📁 Statistical analysis outputs
* 📁 LIME explanation HTML files

---

## 🔬 Statistical Analysis

This project uses:

* Friedman Test
* Wilcoxon Signed-Rank Test

to compare model performance statistically.

---

## 📌 Future Improvements

* Add SHAP explainability
* Improve hyperparameter tuning
* Add web dashboard or GUI
* Deploy as production pipeline

---

## 👨‍💻 Author

**Sujit Kar**

---

## ⭐ Support

If you like this project, consider giving it a star ⭐ on GitHub!
