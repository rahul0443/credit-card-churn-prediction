# Credit Card Customer Churn Prediction & Behavioral Analysis

This project presents a comprehensive, data-driven pipeline for analyzing and predicting credit card customer churn using a simulated real-world dataset. It integrates statistical inference, machine learning, and customer segmentation to inform actionable retention strategies.

---

## 🧠 Objective

To predict customer churn using classification models and explore behavioral patterns through segmentation and statistical analysis.

---

## 📊 Key Features of the Project

- **Dataset**: 10,000+ customer records including demographics, transactions, and account activity.
- **Target Variable**: `Attrition_Flag` → Churn (1 = churned, 0 = retained)
- **Techniques Used**:
  - Exploratory Data Analysis (EDA)
  - Hypothesis Testing (t-tests, Chi-Square, ANOVA)
  - Supervised Learning (Logistic Regression, Decision Tree, Random Forest)
  - Unsupervised Learning (K-Means Clustering)

---

## 🧰 Tools & Libraries

- Python 3.10
- pandas, numpy, seaborn, matplotlib
- scikit-learn, statsmodels
- Jupyter Notebook

---

## 📊 Model Performance Summary

| Model              | Accuracy | Precision (Churn) | Recall (Churn) | F1-Score |
|-------------------|----------|-------------------|----------------|----------|
| Logistic Regression | 82.6%   | 0.72              | 0.35           | 0.48     |
| Decision Tree       | 88.8%   | 1.00              | 0.50           | 0.66     |
| Random Forest       | 89.9%   | 0.98              | 0.56           | 0.71     |

✅ **Best Model**: Random Forest

---

## 🔍 Key Predictors of Churn

1. Total_Trans_Ct
2. Months_Inactive_12_mon
3. Credit_Limit
4. Avg_Utilization_Ratio
5. Total_Revolving_Bal

---

## 🎯 Customer Segmentation (K-Means)

| Cluster | Behavior Summary                                        | Size |
|---------|---------------------------------------------------------|------|
| 0       | High churn risk: low activity, high inactivity          | ~30% |
| 1       | Balanced usage and moderate risk                        | ~45% |
| 2       | Engaged, low churn risk: high transactions, low inactivity | ~25% |

---

## 📂 Project Structure

- `Code.ipynb`: Complete pipeline from EDA to modeling
- `credit_card.xlsx`: Dataset used
- `Report.pdf`: Final detailed report with methodology and insights
- `README.md`: Project documentation

---

## 🚫 Limitations

- Class imbalance (~22% churn)
- No real-time deployment or temporal modeling
- Limited feature scope (no NLP or time-series)

---

## 🧩 Future Work

- Integrate SHAP/LIME for interpretability
- Extend to real-time churn pipelines
- Introduce survival analysis to predict time-to-churn
- Include customer feedback/NPS for deeper sentiment analysis

---

## 👥 Team Members

Team 04  
- Rahul Muddhapuram  
- Yesha Modi  
- Sai Yashwanth Tumu  
- Daphney Rubio  

---

## 📄 License

This project is released under the [MIT License](LICENSE).

---

## 💬 Acknowledgments

Thanks to Professor Rong Pan and Arizona State University for fostering a strong foundation in applied data science.
