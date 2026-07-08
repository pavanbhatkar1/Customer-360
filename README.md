# Customer360 – Churn, CLV & Customer Segmentation
## Overview
Customer360 is an end-to-end customer analytics and prediction system built for e-commerce businesses.
It predicts churn probability, estimates Customer Lifetime Value (CLV), and segments customers into actionable groups — enabling data-driven retention and marketing strategies.
## Key Features
 Churn Prediction: Predicts customer churn with 93.5% accuracy using LightGBM (tuned via GridSearchCV).
 Customer Lifetime Value (CLV): Estimates long-term customer worth using CatBoost (R² = 0.922).
 Segmentation Engine: Groups customers into 5 categories —
   VIP Loyalists, Lost Customers, Occasional Buyers, Bargain Hunters, Casual Shoppers — using KMeans and GMM.
 End-to-End ML Pipeline: Data preprocessing, feature engineering, modeling, and insight generation in one unified workflow.
## Tech Stack
Languages: Python
ML Libraries: XGBoost, LightGBM, CatBoost, Scikit-learn
Clustering: KMeans, GaussianMixture (GMM)
Visualization: Matplotlib, Seaborn, Plotly
Optimization: GridSearchCV for hyperparameter tuning
## Model Performance
Task	Model	Metric	Score
Churn Prediction	LightGBM	Accuracy	93.5%
CLV Prediction	CatBoost	R² Score	0.922
Customer Segmentation	KMeans	Silhouette Score	0.71
## Business Impact
Customer360 enables e-commerce businesses to identify high-value customers, predict churn early, and target retention campaigns effectively — reducing potential revenue loss and improving marketing ROI.
## Future Work
Deploy as an interactive Streamlit dashboard.
Integrate real-time churn tracking via Airflow.
Add SHAP-based interpretability for customer-level insights

