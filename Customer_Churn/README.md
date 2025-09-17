# Telco Customer Churn Analysis 

Hi! , This repository contains my end-to-end Exploratory Data Analysis (EDA) on the **Telco Customer Churn dataset**.  

EDA is not just descriptive; it gives **perspective**. My goal here was to go beyond basic statistics and visualize insights in a **business-friendly way**, identifying which customers are at risk of churning and suggesting actionable strategies to retain them.

---

## Project Objective

Customer churn is one of the biggest threats to subscription-based businesses.  
Through this analysis, I aimed to:

- Understand **key factors driving churn**.  
- Segment customers based on **risk levels**.  
- Provide **actionable insights** for retention campaigns.  
- Prepare a strong foundation for predictive modeling.

---

## What I Did

1. **Data Loading & Quick Overview**  
   - Imported dataset, checked structure, missing values, and data types.

2. **Missing Value Analysis**  
   - Identified columns with missing data and decided how to handle them.

3. **Data Cleaning & Type Fixes**  
   - Converted `SeniorCitizen` to categorical.  
   - Ensured numerical columns are correctly typed.

4. **Univariate Analysis**  
   - Histograms, KDEs for numerical features.  
   - Countplots & pie charts for categorical features.  
   - Interpreted distributions and outliers.

5. **Bivariate Analysis**  
   - Churn % for each categorical variable using heatmaps.  
   - Numerical vs Churn relationships using boxplots and violin plots.  
   - Statistical tests to validate significant features.

6. **Risk Segmentation & Feature Interaction**  
   - Pairwise heatmaps for categorical features.  
   - Binning numerical columns (tenure, MonthlyCharges, TotalCharges).  
   - Multi-dimensional segmentation to find **Top-10 risky customer groups**.

7. **Business Insights & Next Steps**  
   - Identified early lifecycle churn, high monthly charge churn, and payment method risks.  
   - Suggested retention strategies for high-risk segments.  
   - Created executive-ready visual summary (PPT slide included).

---

## Key Takeaways

- Month-to-month contracts, electronic check payments, and high monthly charges are **strong churn drivers**.  
- Early lifecycle customers (0–12 months) are at highest risk.  
- Even AutoPay users can churn when combined with high charges + month-to-month contracts — **a counterintuitive but important insight**.  
- Upselling Tech Support and Online Security can help retain customers.  

> **If I had to take a decision, I would focus retention efforts on these high-risk segments first.**  

---

## Files in this Repo

- `Telco_EDA.ipynb` → Complete Jupyter notebook with all analysis, visualizations, and insights.  
- `README.md` → This file.

---

## Next Steps

- Feature engineering for predictive modeling.  
- Train models (Logistic Regression, Random Forest, XGBoost) to predict churn probability.  
- Simulate business strategies based on model scores.  

---

🙏 Thank you for taking the time to read through this notebook!  
I hope you found it useful and enjoyable.

If you have any questions or suggestions, feel free to connect with me.  
You can also check out my other projects here:  
🔗 [My GitHub](https://github.com/Aman-sys-ui)
