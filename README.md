# 📉 Customer Churn Prediction System

This project develops a machine learning system that predicts which customers are likely to churn (leave) based on demographic, service usage, and account information. The solution is tailored for industries like **telecom**, **banking**, and **subscription services**, where customer retention is more valuable than acquisition.

---

## 📁 Dataset

- **Source:** [Telco Customer Churn Dataset]
- **Records:** 7,043
- **Features:** 20+ (e.g., gender, tenure, contract type, charges, etc.)
- **Target:** `Churn` (Yes/No)

---

## 🧠 Models Used

- ✅ `RandomForestClassifier` (primary)
- 🔍 `XGBoostClassifier` (explored)
- 📌 SMOTE for class imbalance handling

---

## 📊 Evaluation Metrics

| Metric         | Value        |
|----------------|--------------|
| Accuracy       | 77.86%       |
| Precision (1)  | 58%          |
| Recall (1)     | 59%          |
| ROC AUC Score  | ~0.84        |

Confusion Matrix:
           Predicted
         | No | Yes
     ----|----|----
Actual No |878 |158
Actual Yes |154 |219


---

## 🔍 Key Features

- 📊 Exploratory Data Analysis (histograms, boxplots)
- 📦 Data preprocessing (Label Encoding, missing handling)
- ⚖️ Class balancing with SMOTE
- 🤖 Model training & evaluation
- 📈 Feature Importance analysis
- 📄 Business-focused insights report (DOCX/PDF)

---

## 🛠️ Libraries & Tools

- **Python 3.10+**
- **Pandas, NumPy, Seaborn, Matplotlib**
- **Scikit-learn, DecisionTree
- **XGBoost, RandomForestClassifier**
- **Pickle** for saving the model

---


---

## 📌 How to Run

1. Clone the repo:
```bash
git clone https://github.com/your-username/churn-prediction.git
cd churn-prediction
```

📬 Contact Me
If you're interested in customer analytics, churn prediction, or collaborating on ML projects — feel free to connect!

📧 Email: kyaduka2803@gmail.com
🔗 LinkedIn: https://www.linkedin.com/in/krrish-yaduka-16aa72293/
