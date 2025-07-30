# INTERNSHIPTASK-1-BANK-
---

## ✅ `README.md` for Task 2: Classification (Bank Marketing)

```markdown
# 📊 Classification – Bank Marketing Term Deposit Prediction

This project uses classification models to predict whether a customer will subscribe to a term deposit, based on personal and campaign-related features.

---

## 📁 Dataset

- **File:** `bank-additional-full.csv`
- **Description:** Contains customer information and marketing campaign outcomes.
- **Target Column:** `y` (yes/no)

---

## 🧠 Task Objectives

- Load and explore the dataset
- Encode categorical features
- Train classification models:
  - Logistic Regression
  - Random Forest
- Evaluate performance:
  - Confusion Matrix
  - F1-Score
  - ROC Curve
- Explain 5 predictions using SHAP or LIME

---

## 🧾 Steps Performed

1. **Import Required Libraries**
2. **Load and Explore Dataset**
3. **Encode All Categorical Features**
   - Label encoding for all string columns
4. **Train Classifiers**
   - Logistic Regression
   - Random Forest
5. **Evaluate Models**
   - Confusion Matrix
   - F1-Score
   - ROC Curve Plot
6. **Explainability**
   - SHAP used to explain 5 random predictions from Random Forest

---

## 📊 Evaluation Results

| Metric        | Logistic Regression | Random Forest |
|---------------|---------------------|----------------|
| Confusion Matrix | ✅                | ✅              |
| F1-Score         | ✅                | ✅              |
| ROC Curve        | ✅                | ✅              |

---

## 📈 Model Explanation

SHAP plots were generated to interpret how features influenced predictions for 5 test cases.

---

## 🛠️ Libraries Used

- `pandas`, `numpy`
- `matplotlib`, `seaborn`
- `scikit-learn`
- `xgboost`
- `shap`

---

## 📥 How to Run

```bash
pip install -r requirements.txt
