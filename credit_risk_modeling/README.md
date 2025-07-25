# 💳 Reducing Credit Default Rate at Bank

**Author:** Gaurav Yadav  
**Technologies:** Python · Pandas · Scikit-learn · SMOTE · XGBoost · Matplotlib · Seaborn

---

## 🎯 Goal

The objective of this project is to identify **risky customers** who are likely to default on their loans and recommend proactive actions to reduce the **overall credit default rate** at ABC Bank.

---

## 🏦 Background

ABC Bank has been facing challenges due to high credit default rates.  
To tackle this, the bank aims to:
- Detect customers with high default probability.
- Take **proactive measures** to prevent defaults before they occur.
- Use **data-driven decision-making** to reduce financial risk.

---

## 🧠 Methodology – Solution Approach

The project involves the following major steps:

### 🔹 Step 1: Load the Dataset
- Loaded using Python (Pandas).
- Checked for **missing values** and explored feature details.

### 🔹 Step 2: Preprocessing and Feature Engineering
- Checked class distribution (imbalance found).
- Separated **numerical and categorical features**.
- Performed **EDA** on both types.
- Selected important numerical features using:
  - Extra Trees Regressor  
  - Correlation Matrix  
- Applied **StandardScaler** to numerical features.
- Chose categorical features based on **domain knowledge**.

### 🔹 Step 3: One-Hot Encoding
- One-hot encoded categorical variables.
- Handled **dummy variable trap**.

### 🔹 Step 4: Handling Imbalanced Data
- Used **SMOTE (Synthetic Minority Over-sampling Technique)** to balance the classes.

### 🔹 Step 5: Model Creation
- Combined processed numerical and encoded categorical features.
- Split the data into **train/test sets**.
- Trained multiple models:
  - Logistic Regression  
  - Decision Tree  
  - Random Forest  
  - XGBoost

### 🔹 Step 6: Model Evaluation
- Compared models using:
  - Accuracy  
  - Precision  
  - Recall  
  - F1-Score

---

## 🧪 Modeling Techniques

- **Logistic Regression** – Baseline binary classifier.
- **Decision Tree** – Interpretable model with logical rules.
- **Random Forest** – Ensemble of decision trees for better generalization.
- **XGBoost** – Gradient boosting framework offering high performance.

> More technical details are available in the Jupyter notebook and presentation.

---

## 📁 Files Included

- `data.xlsx` – Dataset used for modeling.  
- `code.ipynb` – Complete code with EDA, preprocessing, modeling, and evaluation.  
- `Analysis_Result.pptx` – Visual analysis and model performance summary.  

---

## ▶️ How to Run the Project

1. Clone the repository or download the files.
2. Install required dependencies (you can use pip or conda):

```bash
pip install pandas scikit-learn xgboost imbalanced-learn matplotlib seaborn
