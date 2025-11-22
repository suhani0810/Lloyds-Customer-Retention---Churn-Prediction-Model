# 📉 Customer Churn Prediction Model (LLOYDS)

### 📄 Project Summary
This project analyzes customer demographics, transactions, and service history to predict churn for **LLOYDS Financial Services**. The goal was to build a 360-degree customer view to identify "at-risk" users and improve retention.

### 🛠️ Tech Stack & Methods
* **Language:** Python (Pandas, Scikit-Learn).
* **Data Processing:** Merged 3 disparate datasets; applied **One-Hot Encoding** and **Z-Score Normalization**.
* **Handling Imbalance:** Used **SMOTEENN** to address the severe lack of churn cases.
* **Model:** Random Forest Classifier (chosen for resistance to overfitting).

### 📊 Key Results
* [cite_start]**Top Predictors:** `Avg_Amount_Spent`, `Total_Amount_Spent`, and `Days_Since_Last_Transaction` were the strongest indicators of churn.
* **Performance:** The model achieved **56% Accuracy** and **0.48 ROC-AUC**.
    * *Insight:* The analysis revealed that transactional data alone provides a weak signal.Stronger behavioral data (e.g., login frequency) is recommended to improve accuracy.

### 💡 Business Value
Despite data limitations, this analysis enables:
1.  **Risk Ranking:** Prioritizing the top 10% of at-risk customers for intervention.
2.  **Targeted Testing:** Identifying segments for A/B testing new retention offers.

### 📂 Files Included
* `DocumentationandCode(LLOYDS_task1).pdf`: Full code walkthrough, EDA, and feature engineering.
* `Customer_Churn_Model_Report(LLOYDS_task2).pdf`: Final model evaluation and strategic recommendations.
