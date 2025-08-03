# 🏦 Loan Default Prediction

A machine learning project to predict whether a client will default on a loan based on their financial and demographic data. Built for a hackathon using real-world NBFC (Non-Banking Financial Company) data.

---

## 🔍 Problem Statement

The goal is to develop a classification model that predicts the probability of a customer defaulting on a loan. This is a critical task for financial institutions to reduce risk and improve credit decision-making.

---

## 📊 Dataset Overview

The dataset includes features such as:

- Customer demographics (e.g., age, gender, education)
- Loan characteristics (e.g., loan amount, tenure, interest rate)
- Financial indicators (e.g., income, credit history)

> ⚠️ Dataset not included due to policy. If you are a recruiter or reviewer, please contact me or use synthetic data for testing.

---

## 🧠 Project Workflow

1. **Data Preprocessing**
   - Handling missing values
   - Label encoding / one-hot encoding
   - Scaling numerical features

2. **Exploratory Data Analysis (EDA)**
   - Distribution analysis
   - Correlation heatmaps
   - Class balance check

3. **Model Building**
   - XGBoost Classifier with tuning
   - 5-Fold Stratified Cross-Validation

4. **Model Evaluation**
   - Accuracy, Precision, Recall, F1-Score
   - ROC-AUC Score
   - Confusion Matrix

---

## 📈 Model Performance

| Metric           | Score |
|------------------|-------|
| Cross-Validated Accuracy | XX%   |
| ROC-AUC Score    | XX%   |
| Precision / Recall / F1 | XX% / XX% / XX% |

> Final model: `XGBClassifier(n_estimators=200, learning_rate=0.05, max_depth=4)`

---

## 📦 Tech Stack

- Python 3.x
- Pandas, NumPy
- Scikit-learn
- XGBoost
- Matplotlib / Seaborn

---

## 🚀 Future Improvements

- Address class imbalance (SMOTE, ADASYN, or `scale_pos_weight`)
- Hyperparameter tuning (GridSearch / Optuna)
- Feature importance analysis
- Streamlit dashboard for predictions

---

## 🧾 License

This project is open-source under the MIT License.

---

## 🙋‍♂️ Author

**Your Name**  
🔗 [Your LinkedIn](https://linkedin.com/in/your-profile)  
💼 [Your Portfolio or Blog]  
📧 your.email@example.com

---

