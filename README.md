# 📊 Customer Churn Pattern Analysis & Visualization

Welcome to the **Customer Churn Pattern Analysis and Visualization** project! This repository provides an end-to-end data analysis and machine learning solution for understanding and predicting customer churn—helping businesses take action to retain more customers.

---

## 📝 Introduction

**Customer churn** is when customers stop using a company's service. In competitive industries, reducing churn is vital to sustainable growth.  
This project leverages the **Telco Customer Churn dataset** (demographics, account details, usage patterns) to:

- Explore and visualize key churn drivers
- Build and evaluate predictive models
- Deliver actionable insights for retention strategies

---

## 💡 What You'll Find Here

- **Data Cleaning & Preprocessing:** Handling missing values, encoding categorical variables, and transforming features.
- **Exploratory Data Analysis (EDA):** Interactive charts, churn distribution, feature correlations, and trend identification.
- **Predictive Modeling:** Training machine learning models (e.g., Logistic Regression, Random Forest) to forecast churn.
- **Model Evaluation:** Accuracy, precision, recall, F1-score, and ROC-AUC metrics.
- **Business Intelligence Reporting:** Visual dashboards and targeted recommendations.

---

## 🏆 Business Impact

- **Actionable Insights:**  
  - Identify why customers leave and who’s at high risk.
  - Pinpoint features (tenure, contract type, charges) most linked to churn.
  - Recommend strategies for retention and reducing revenue loss.
- **Targeted Interventions:**  
  Use insights for personalized follow-ups and marketing campaigns.

---

## ⚙️ Requirements

- **Python 3.7+**
- **Jupyter Notebook**
- **Libraries:**  
  ```
  pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn
  ```
  *(Add more as needed, e.g., xgboost, plotly, etc.)*

- **Dataset:**  
  - Telco Customer Churn dataset (`WA_Fn-UseC_-Telco-Customer-Churn.csv` or similar)

---

## 🚦 How to Run This Project

1. **Clone the repository:**
   ```bash
   git clone https://github.com/karanpansuriya/Customer-Churn-Pattern-Analysis-and-Visualization.git
   cd Customer-Churn-Pattern-Analysis-and-Visualization
   ```

2. **Install requirements:**  
   See above or run:
   ```bash
   pip install -r requirements.txt
   ```

3. **Start Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```
   - Open the notebook file (e.g., `Customer_Churn_Analysis.ipynb`).
   - Run cells sequentially.

4. **Download Dataset:**  
   If not included, download the Telco dataset from [Kaggle](https://www.kaggle.com/blastchar/telco-customer-churn) and place it in the project folder.

---

## 📊 Key Findings & Model Results

- **Important Features:** Tenure, MonthlyCharges, TotalCharges, contract type.
- **Churned Customers:**  
  - Shorter tenures, more month-to-month contracts.
  - Higher churn in specific product/service segments.
- **Model Accuracy:**  
  - Achieved up to **XX% accuracy** (update with your final model score!)  
  - Includes confusion matrix, ROC curves, and other metrics.

---
## 🏆 Model Results: Accuracy & Metrics

Our most accurate models and their performance:

- **XGBoost Accuracy:** **79.2%**
  - *Code reference:*
    ```python
    print("XGBoost Accuracy:", accuracy_score(y_test, y_pred))
    # Output: XGBoost Accuracy: 0.792
    ```
- **Stacking Ensemble Accuracy:** **79.1%**
  - *Code reference:*
    ```python
    print("Stacking Accuracy:", stack_model.score(X_test_scaled, y_test))
    # Output: Stacking Accuracy: 0.791
    ```

### Model Types Used

- XGBoost (with early stopping & feature selection)
- Stacking Ensemble (Random Forest, SVC, Gradient Boosting, Logistic Regression)
- Logistic Regression with regularization

---

## 📚 Project Learnings

- Data cleaning and preprocessing
- EDA and visualization best practices
- Model building, evaluation, and interpretation
- Reporting actionable business insights

---

## ❓ FAQ

- **Can I use a different dataset?**  
  Yes! Replace the CSV in the data loading cell.

- **Where are the insights?**  
  All analysis and key findings are in the notebook outputs and summary cells.

- **How do I contribute?**  
  Fork the repo, create a branch, and submit a pull request.

---

## 🤝 Contributing

Suggestions, feedback, or new features?  
Open an issue or submit a pull request!

---

## 📬 Contact

- [karanpansuriya](https://github.com/karanpansuriya)

---
