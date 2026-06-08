# 📉 B2C Revenue-at-Risk & Customer Retention Predictive Engine

An end-to-end machine learning pipeline that shifts customer retention strategies from reactive damage control to proactive, financially optimized intervention. This system doesn't just predict if a customer will churn; it quantifies the exact Revenue at Risk to prioritize operational outreach based on maximum ROI.

## 🚀 Live Demo & Interactive Analytics
* **Interactive Frontend UI:** [View Live Tableau Dashboard](https://public.tableau.com/path-to-your-published-dashboard)
* **Portfolio Context:** [abeinathan.github.io](https://abeinathan.github.io/)

## 🛠️ Technology Stack & Environment
* **OS Environment:** Zorin OS 17 (Native Linux Runtime Engine)
* **Data Pipelines & ML:** Python 3.12, Pandas, NumPy, Scikit-Learn (Random Forest Engine)
* **Explainable AI (XAI):** SHAP (Shapley Additive exPlanations)
* **Business Intelligence:** Tableau Public Web Authoring Engine

## 🏗️ Pipeline Architecture
1. **Automated ETL & Leakage Mitigation:** Features are isolated dynamically into categorical and numerical vectors. The leaky churn_risk feature is systematically purged to ensure genuine behavioral learning.
2. **Predictive Modeling Engine:** A tree-ensemble Random Forest model balances class weights to mitigate customer churn minority representation, achieving an optimized ROC-AUC score of 0.989.
3. **Financial Impact Formulation:** Algorithmic continuous probabilities are transformed into business metrics via the Revenue-at-Risk formula:
   Revenue at Risk = Churn Probability * Total Spent
4. **Explainable AI (XAI) Framework:** Deploys a TreeExplainer sequence to break open the black-box model and map global behavioral indicators.

## 📊 Core Operational Insights
* **The Revenue Exposure:** Identified high-value VIP accounts representing over $24,000 each in immediate revenue exposure, despite showing lower raw churn flags than low-tier metrics.
* **Primary Churn Drivers:** SHAP calculations mathematically isolated recency_days (time since last user interaction) and cart_abandonment_rate as the most critical determinants of customer attrition.

## 📁 Repository Directory
* customer_churn.csv: Raw tracking profile data (100,000 entries).
* churn_pipeline.ipynb: Production Jupyter Notebook containing the end-to-end codebase.
* shap_summary_plot.png: Static high-resolution Explainable AI summary visualization.
* bi_retention_queue.csv: Pre-calculated tactical database feeding the Tableau frontend.
* bi_feature_importance.csv: Aggregated feature impact table for BI visualizations.

---
**Architected by Abei Nathan** *Technical inquiries can be directed to:* abeinathan@protonmail.com
