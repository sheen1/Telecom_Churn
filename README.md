#  Telco Customer Churn Prediction

This project uses machine learning to predict customer churn in the telecom industry using the [Telco Customer Churn dataset](https://www.kaggle.com/blastchar/telco-customer-churn). The goal is to identify customers who are likely to cancel their service and help the business take preventive actions.

---

## 📁 Dataset

The dataset includes information about:

- **Customer demographics** (gender, age, senior citizen)
- **Account details** (tenure, contract type, billing method)
- **Service usage** (internet, streaming, phone services)
- **Target variable**: `Churn` (Yes/No)

---

## 🧪 Model Used

- **Model**: [XGBoost](https://xgboost.readthedocs.io/)
- **Task**: Binary classification (`Churn: Yes/No`)
- **Preprocessing**:
  - Label encoding for categorical variables
  - Conversion of `TotalCharges` to numeric
  - Handling of missing/invalid values
- **Training & Evaluation**:
  - Train-test split (80/20)
  - Evaluation with accuracy, confusion matrix, classification report

---

## 📈 Performance

| Metric       | Score  |
|--------------|--------|
| Accuracy     | ~77%   | |

(*Note: These metrics can be improved with feature engineering, class balancing, or hyperparameter tuning.*)

---

## 🛠️ Requirements

- Python 3.x
- pandas
- scikit-learn
- xgboost
- numpy
- matplotlib (optional for EDA)

Install dependencies:
```bash
pip install -r requirements.txt

