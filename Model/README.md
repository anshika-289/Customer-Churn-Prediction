# 🔍 Customer Churn Prediction — Step-by-Step Workflow

This README outlines the detailed steps implemented in the Jupyter/Colab notebook for predicting customer churn using machine learning.

---

## 📌 Objective

To build and evaluate multiple machine learning models to predict customer churn based on service usage patterns and customer demographics.

---

## 🧪 Step-by-Step Workflow

### 1. 📥 Data Loading
- Load the Telco Customer Churn dataset (`customer_churn.csv`) using `pandas`.

### 2. 🧹 Data Cleaning
- Convert `TotalCharges` to numeric (coerce errors).
- Drop rows with missing values.
- Drop customer ID column as it’s not useful for modeling.

### 3. 🧮 Exploratory Data Analysis (EDA)
- Use `seaborn` and `matplotlib` to:
  - Check churn distribution.
  - Visualize relationships between categorical/numerical features and churn.

### 4. 🏷️ Label Encoding
- Convert categorical columns into numerical using `LabelEncoder`.

### 5. ⚖️ Feature Scaling
- Apply `StandardScaler` to normalize numerical columns (`tenure`, `MonthlyCharges`, `TotalCharges`).

### 6. 🔀 Data Splitting
- Split the dataset into training and testing sets (80-20 split).

### 7. 🤖 Model Building & Evaluation
Train and evaluate the following models using accuracy, classification report, and ROC AUC:

#### a. Logistic Regression
- Basic linear model for binary classification.

#### b. Decision Tree Classifier
- Tree-based model to learn decision rules.

#### c. Random Forest Classifier
- Ensemble model using multiple decision trees for improved accuracy.

#### d. XGBoost Classifier
- Gradient boosting framework optimized for speed and performance.

### 8. 📈 Performance Comparison
- Plot confusion matrix.
- Generate classification report (Precision, Recall, F1-score).
- Compute ROC AUC scores for all models.

### 9. ✅ Final Outcome
- Compare and conclude with the best-performing model for churn prediction.

---
