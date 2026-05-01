## Customer Churn Prediction & Retention Strategy
### Python · Logistic Regression · Tableau · SQL · BRD

> Predicting telecom customer churn using machine learning and translating 
> model output into actionable business recommendations for a retention team.

---

## Business Problem
TelecomX, a mid-sized telecom provider, was experiencing a monthly churn rate 
of 26.5% — significantly above the industry benchmark of 15–18%. The retention 
team had no early-warning system to identify at-risk customers before they left.

## Project Objective
Build a data-driven churn prediction system that:
- Identifies customers with >70% churn probability
- Surfaces the top 5 drivers of churn
- Delivers an interactive Tableau dashboard for retention team use
- Provides 3 business recommendations with estimated revenue impact

---

## Tools & Technologies
| Tool | Purpose |
|------|---------|
| Python (pandas, scikit-learn, seaborn) | EDA, data cleaning, modelling |
| Logistic Regression | Churn prediction model |
| Tableau Public | Interactive retention dashboard |
| Excel / CSV | Data storage and output |

---

## Key Results
- Model accuracy: **81.5%** (target was 75%)
- High risk customers identified: **539**
- Estimated annual revenue at risk: **$27,600+**
- Top churn driver: Month-to-month contracts (42% churn rate)

---

## Project Structure
customer-churn-prediction/
│
├── 01_EDA_Churn_Analysis.ipynb   ← Full EDA + model notebook
├── dashboard_data.csv             ← Final dataset with predictions
├── churn_predictions.csv          ← Model output scores
├── docs/
│   └── BRD_CustomerChurn_TelecomX_ShrustiKhadji.pdf    ← Business Requirements Document
└── charts/
├── chart1_contract_churn.png
├── chart2_tenure_churn.png
├── chart3_internet_churn.png
├── chart4_correlation.png
└── chart5_churn_drivers.png

## Business Recommendations
1. **Contract upgrade incentive** at month 3 for month-to-month customers
2. **Tech support bundling** for fiber optic customers in first 6 months  
3. **Loyalty milestone rewards** at 6-month and 12-month tenure marks

---

## Dashboard
[[View Live Tableau Dashboard →](#)](https://public.tableau.com/views/CustomerChurnAnalysis_17773633746420/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

---

## Business Requirements Document
Full BRD including stakeholder register, KPIs, functional requirements, 
and success criteria available in `/docs/BRD_CustomerChurn_TelecomX_ShrustiKhadji

---

*Dataset: IBM Telco Customer Churn (Kaggle) | Project by Shrusti Khadji*
