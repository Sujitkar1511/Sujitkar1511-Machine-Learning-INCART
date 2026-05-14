
# Machine Learning Model Comparison with Explainable AI (LIME)

## Overview

This project compares multiple Machine Learning models using different evaluation metrics and explainability techniques. The project also includes statistical significance testing using Friedman Test and Wilcoxon Test.

---

## Models Used

* Random Forest
* CatBoost
* LightGBM
* KNN

---

## Explainable AI

LIME (Local Interpretable Model-Agnostic Explanations) was used to explain predictions of different models.

---

## Project Structure

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

## Statistical Tests

* Friedman Test
* Wilcoxon Signed-Rank Test

---

## Output Files

* Accuracy comparison results
* Final metric rankings
* LIME explanation HTML files
* Statistical test outputs

---

## Technologies Used

* Python
* Scikit-learn
* CatBoost
* LightGBM
* LIME
* Pandas
* NumPy
* Matplotlib

---

## Author

Sujit Kar
