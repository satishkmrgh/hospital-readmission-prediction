# Hospital Readmission Prediction

> Predicting 30-day hospital readmissions to reduce Medicare penalties and improve patient outcomes

![Status](https://img.shields.io/badge/status-in_progress-yellow)
![Python](https://img.shields.io/badge/python-3.11-blue)
![License](https://img.shields.io/badge/license-MIT-green)

---

## 📋 Business Problem

US hospitals lose approximately **$26 billion annually** due to 30-day readmissions, with an estimated **$17 billion (roughly 65%)** considered preventable. CMS penalizes hospitals up to **3% of Medicare reimbursements** through the Hospital Readmissions Reduction Program (HRRP), which tracks six high-impact conditions: heart attack, heart failure, pneumonia, COPD, coronary artery bypass graft surgery, and hip/knee replacement.

Despite over a decade of HRRP enforcement, most hospitals still lack a systematic way to identify high-risk patients before discharge, leading to one-size-fits-all interventions that waste resources on low-risk patients while missing preventable readmissions among high-risk ones.

This project builds a predictive model and decision-support dashboard that allows hospital staff to flag at-risk patients before discharge and target post-discharge interventions where they will have the greatest clinical and financial impact, projecting annual savings of **$1.3 to $1.6 million** for a mid-sized hospital admitting approximately 10,000 patients per year.

---

## 🎯 Project Status

🟡 In Progress — Week 2 of 6

Current phase: Deep Analysis and Insights

Completed so far:
- Week 1: Industry research, dataset acquisition, environment setup, GitHub repo
- Data cleaning: 101,766 raw records → 98,053 cleaned (96.35% retained)
- Binary target created: 30-day readmission (11.3% positive class)
- Exploratory data analysis: 5 univariate charts with documented findings
- Feature engineering: 5 model-ready features built

Next: bivariate analysis, then predictive modeling (Week 3)

---

## 🛠️ Approach

This project follows an end-to-end analytics workflow:

1. **Discovery** — Industry research and problem framing
2. **Data Exploration** — Cleaning and EDA on 100,000+ patient records
3. **Predictive Modeling** — Logistic Regression, Random Forest, XGBoost
4. **Dashboard** — Tableau executive view with risk scoring and ROI calculator
5. **Business Case** — Financial impact and recommendations

---

## 💻 Tools and Technologies

- **Languages:** Python, SQL
- **Libraries:** pandas, NumPy, scikit-learn, XGBoost, matplotlib, seaborn
- **Visualization:** Tableau Public
- **Environment:** Anaconda, Jupyter Notebook
- **Version Control:** Git, GitHub

---

## 📂 Project Structure
hospital-readmission-prediction/
├── data/
│   ├── raw/              # Original dataset (not committed)
│   └── processed/        # Cleaned data (not committed)
├── notebooks/            # Jupyter notebooks for analysis
├── dashboards/           # Tableau workbooks
├── reports/              # Executive summary and findings memos
├── images/               # Visualizations and charts
├── .gitignore
└── README.md
---

## 📊 Dataset

- **Source:** UCI Machine Learning Repository — Diabetes 130-US Hospitals (1999–2008)
- **Records:** 101,766 patient encounters
- **Features:** 50 columns spanning demographics, diagnoses, medications, and outcomes
- **Target:** 30-day readmission (binary)

---

## 👤 Author

**Satish Kumar Akrura**

Healthcare Data Analyst | Business Analytics, SNHU 2024

- 💼 LinkedIn: [linkedin.com/in/satishakrura (https://linkedin.com/in/satishakrura)
- 📧 Email: satishkmr2023@gmail.com
- 🌐 GitHub: [@satishkmrgh](https://github.com/satishkmrgh)

---

*Last updated: May 2026*
