# Customer Churn Prediction (Task 2)

*Objective:* Build a machine learning model to predict which customers are likely to leave a service (churn), and present business insights via a dashboard.

## 🔗 Dataset
- Telco Customer Churn (Kaggle) — WA_Fn-UseC_-Telco-Customer-Churn.csv by blastchar.  
  Download: https://www.kaggle.com/datasets/blastchar/telco-customer-churn

> Note: Original dataset not included in this repo due to licensing. Please download from Kaggle and place in data/ if you want to reproduce results.

## 🔧 Tools & Libraries
- Python (Pandas, Scikit-learn, XGBoost, Matplotlib, SHAP)  
- Power BI (dashboard)  
- Jupyter / Google Colab

## 📁 Repository Structure

Customer-Churn-Prediction-ML/ │── churn_prediction.ipynb         # Notebook: cleaning → modeling → evaluation │── churn_predictions_with_risk.csv # Final predictions with churn_prob and Risk_Level │── Dashboard_preview.png           # Screenshot of Power BI dashboard │── Final_Report.pdf                # Business recommendations (PDF) │── README.md │── data/ (optional: original dataset)

## 🧭 What I did
1. Cleaned and preprocessed the Telco dataset.  
2. Trained models: Logistic Regression, Random Forest, XGBoost.  
3. Evaluated models (Accuracy, Precision, Recall, F1, ROC-AUC).  
4. Selected best model (Logistic Regression, AUC ≈ 0.86).  
5. Predicted churn probabilities and created risk buckets (High/Medium/Low).  
6. Built a Power BI dashboard presenting KPIs, churn drivers, and high-risk customers.  
7. Prepared business recommendations to reduce churn.

## 📌 How to reproduce
1. Download the original dataset from Kaggle and place it in data/ (or update paths in the notebook).  
2. Open churn_prediction.ipynb in Colab or Jupyter and run cells top → bottom.  
3. Export churn_predictions_with_risk.csv and import into Power BI to view the dashboard.

## 📬 Deliverables
- churn_prediction.ipynb — Notebook with code and analysis.  
- churn_predictions_with_risk.csv — Customer predictions with probabilities and risk levels.  
- Dashboard_preview.png & Churn_Dashboard.pbix (if included) — Power BI dashboard.  
- Final_Report.pdf — Business recommendations summary.
