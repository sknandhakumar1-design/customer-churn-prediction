# 📡 Customer Churn Prediction — No-Churn Telecom

![Python](https://img.shields.io/badge/Python-3.x-blue)
![ML](https://img.shields.io/badge/Machine%20Learning-Classification-green)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

## 📌 Project Overview
No-Churn Telecom is an Indian telecom company facing a churn rate above 10%.
This project uses Machine Learning to identify customers likely to churn,
enabling the marketing and support teams to take proactive retention actions.

**Client:** No-Churn Telecom
**Category:** Telecom — Churn Rate ML
**Project Ref:** PM-PR-0017

---

## 🎯 Project Goals
- Identify key variables influencing customer churn
- Predict customers likely to churn
- Generate a `CHURN_FLAG` (YES = High Risk, NO = Low Risk)
- Help marketing team target high-risk customers
- Help support team prioritize high-risk customers

---

## 📂 Dataset
- **Source:** MySQL Database (project_telecom)
- **Total Records:** 2,43,553 customers
- **Features:** 14 columns

| Column | Description |
|--------|-------------|
| customer_id | Unique customer ID |
| telecom_partner | Service provider |
| gender | Customer gender |
| age | Customer age |
| state | State of residence |
| city | City of residence |
| pincode | Postal code |
| date_of_registration | Join date |
| num_dependents | Number of dependents |
| estimated_salary | Annual salary |
| calls_made | Total calls made |
| sms_sent | Total SMS sent |
| data_used | Total data used (GB) |
| churn | Target variable (1=YES, 0=NO) |

---

## 🔧 Tech Stack
- **Language:** Python 3.x
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
- **Database:** MySQL (via SQLAlchemy + PyMySQL)
- **Environment:** Jupyter Notebook

---

## 📊 Exploratory Data Analysis
- Churn distribution analysis
- Feature-wise comparison against churn
- Correlation heatmap
- Gender, age, telecom partner vs churn visualizations

---

## 🤖 Models Trained
| Model | ROC-AUC Score |
|-------|--------------|
| Logistic Regression | X.XX |
| Random Forest | X.XX |
| Gradient Boosting | X.XX |

**Best Model: [Your best model] with ROC-AUC = X.XX**

---

## 📈 Key Findings
Top features influencing churn:
1. **Gender** — strongest predictor
2. **Estimated Salary** — higher/lower income affects loyalty
3. **Number of Dependents** — family size impacts retention
4. **SMS Sent** — usage pattern matters
5. **Age** — younger customers churn more

---

## 🚩 CHURN_FLAG Results
| Flag | Count |
|------|-------|
| 🔴 HIGH RISK (YES) | XX,XXX |
| 🟢 LOW RISK (NO) | XX,XXX |

---

## 💡 Business Recommendations
**Marketing Team:**
- Target HIGH risk customers with exclusive loyalty offers and discounts
- Focus retention campaigns on top churning telecom partners

**Customer Support Team:**
- Prioritize HIGH risk customers in support queues
- Proactively reach out to customers showing churn patterns

---

## 📁 Project Structure
```
customer-churn-prediction/
├── Customer_Churn_Prediction_PR0017.ipynb
├── high_risk_customers.csv
├── full_data_with_churn_flag.csv
├── requirements.txt
└── README.md
```

---

## 🚀 How to Run
1. Clone the repository
```bash
git clone https://github.com/your-username/customer-churn-prediction.git
```
2. Install dependencies
```bash
pip install -r requirements.txt
```
3. Open Jupyter Notebook
```bash
jupyter notebook Customer_Churn_Prediction_PR0017.ipynb
```

---

## 👤 Author
**Your Name**
- Intern @ DataMites
- GitHub: [@your-username](https://github.com/your-username)
- LinkedIn: [your-linkedin](https://linkedin.com/in/your-profile)