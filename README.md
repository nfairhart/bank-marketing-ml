# 🏦 Optimizing Direct Marketing Campaign Using Machine Learning

This analysis presents a complete modeling workflow for improving the targeting of a direct marketing campaign. The dataset is based on marketing calls made by a Portuguese banking institution. The goal is to predict whether a customer will subscribe to a term deposit based on features like call duration, previous contact outcome, job type, and more.

📂 **Dataset**: [UCI Bank Marketing Dataset](https://archive.ics.uci.edu/dataset/222/bank+marketing)

---

## 📌 Objective

Maximize marketing efficiency by building machine learning models that identify likely responders. The business goal is to increase ROI by targeting the smallest group of customers needed to achieve nearly all campaign conversions.

---

## 🛠 Tools & Techniques

- **Python**: `pandas`, `scikit-learn`, `xgboost`, `matplotlib`
- **Model Types**: Random Forest, XGBoost, Logistic Regression
- **Imbalanced Data Strategies**:
  - `scale_pos_weight` in XGBoost
  - Downsampling of majority class
- **Evaluation Metrics**:
  - Precision, Recall, F1
  - Precision/Recall vs Threshold curve
  - Decile analysis

---

## 📈 Key Results

- Reduced outreach list by **72%** while still capturing **96% of positive responses**
- Precision-recall tradeoffs analyzed across model thresholds
- Delivered data-backed marketing segmentation for operational use

---

## 🔍 Sections Overview

| Section | Description |
|--------|-------------|
| `1. Assumptions` | Defines the objective function as recall to maximize campaign yield |
| `2. Data Exploration` | Visual and statistical analysis, class imbalance handling |
| `3. Weighted Model Training` | Implements XGBoost with adjusted class weights |
| `4. Downsampling Strategy` | Evaluates alternative to weighting by reducing non-responder volume |
| `5. Parameter Refinement` | Fine-tunes model hyperparameters |
| `6. Final Evaluation` | Threshold tuning and gains chart |
| `7. Conclusion` | Summarizes marketing and modeling impact |

---

## 📊 Visual Outputs

> _(You can add screenshots of key visualizations here in your GitHub repo after exporting them as images from the notebook)_

---

## 📂 Files in This Repo

- `BankOfHawaiiExampleWork.ipynb` – Full Jupyter Notebook
- `README.md` – This file
- `assets/` – (Optional) Visuals and supporting charts

---

## 📬 Contact

Want to know more? Connect with me on [LinkedIn](#) or view other projects on [GitHub](#).
