# Telco Churn Prediction (ML + BI)

📊 End-to-end Telco Customer Churn project combining **Python (ML)** + **SQL** + **Power BI**.

---

## 🔹 Project Overview
- Cleaned and prepared the Telco churn dataset.  
- Performed EDA with **Python** (pandas, seaborn, matplotlib).  
- Ran **SQL queries** inside Jupyter for churn insights.  
- Built and compared **ML models**: Logistic Regression, Random Forest, XGBoost.  
- Evaluated with metrics: Accuracy, Precision, Recall, F1, ROC-AUC.  
- Created an **interactive Power BI dashboard** for business users.

---

## 🔹 Key Results
- **Churn Rate**: ~26.5% of customers  
- **Best Model**: Random Forest → Accuracy **78.9%**, ROC-AUC **83%**  
- **Main Drivers of Churn**:  
  - Month-to-month contracts  
  - Electronic check payments  
  - Senior citizens  

---

## 🔹 Dashboard Preview
Power BI dashboard with churn KPIs, risk segmentation, and filters:

![Telco Churn Dashboard](bi/telco_churn_dashboard.png)

---

## 🔹 Repository Structure

telco-churn-ml-bi/
│── bi/                        # Power BI dashboard (.pbix file + PNG preview)
│   ├── telco_churn_dashboard.pbix
│   └── telco_churn_dashboard.png
│
│── notebooks/                 # Jupyter Notebook for EDA + SQL queries
│   └── telco-churn-eda.ipynb
│
│── outputs/                   # Processed data, model results, and saved model
│   ├── telco_churn_clean.csv
│   ├── model_results.csv
│   ├── at_risk_customers_testset_threshold_0_40.csv
│   ├── scored_all_customers_testset.csv
│   └── best_churn_model.joblib
│
│── requirements.txt           # Python dependencies
│── README.md                  # Project documentation
│── LICENSE                    # Open-source license
│── .gitignore                 # Git ignore rules

🔹 Tools & Technologies

Python: pandas, seaborn, matplotlib, scikit-learn, xgboost

SQL: queries inside Jupyter Notebook for churn analysis

Power BI: dashboard creation for interactive insights

GitHub: version control and project documentation

🔹 How to Run

Clone the repo:

git clone https://github.com/Anu779930/telco-churn-ml-bi.git


Install dependencies:

pip install -r requirements.txt


Run the notebook:

jupyter notebook notebooks/telco-churn-eda.ipynb


Open the Power BI file:

bi/telco_churn_dashboard.pbix

🔹 Future Enhancements

Deploy churn prediction model as a REST API.

Integrate with a real-time BI tool (Tableau / Power BI Service).

Automate churn alerts for at-risk customers.

