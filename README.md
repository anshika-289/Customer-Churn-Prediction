# 📉 Customer Churn Prediction

This project focuses on predicting customer churn using machine learning techniques. Churn prediction is vital for businesses to retain customers by identifying those at risk of leaving and taking proactive measures.

## 📁 Project Structure

- `Customer_Churn_Prediction.ipynb`: Main Jupyter Notebook containing the entire end-to-end churn prediction workflow.

## 🚀 Features

- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Feature engineering and scaling
- Model training and evaluation using:
  - Logistic Regression
  - Decision Tree
  - Random Forest
  - XGBoost
- Model comparison using accuracy, classification report, and ROC AUC score
- Final predictions and confusion matrix visualization

## 🧠 Algorithms Used

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- XGBoost Classifier

## 🗃️ Dataset

The dataset contains customer information including demographics, account details, and service usage. Key features include:
- `gender`
- `SeniorCitizen`
- `tenure`
- `MonthlyCharges`
- `TotalCharges`
- `Contract`, `PaymentMethod`, etc.

> **Note:** The dataset appears to be a modified version of the [Telco Customer Churn dataset](https://www.kaggle.com/blastchar/telco-customer-churn).

## 📊 Evaluation Metrics

- Accuracy
- Confusion Matrix
- Precision, Recall, F1-Score
- ROC AUC Score

## 🛠 Requirements

Install dependencies via:

```bash
pip install -r requirements.txt
```

### `requirements.txt` sample:

```txt
pandas
numpy
matplotlib
seaborn
scikit-learn
xgboost
```

## 📌 How to Run

1. Clone the repository or download the notebook.
2. Install the required libraries.
3. Run the notebook `Customer_Churn_Prediction.ipynb` in Jupyter or Google Colab.
4. Follow the workflow for EDA, training, and evaluation.

## 🏁 Conclusion

This churn prediction model helps businesses identify customers likely to leave, enabling targeted retention strategies. Among the evaluated models, the one with the best performance can be deployed for real-time churn forecasting.

---

