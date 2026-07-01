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

🟢 Week 4 of 6 Complete — Tableau Dashboard Published (07/01/2026)

| Week | Deliverable | Status |
|------|-------------|--------|
| Week 1 | Data Cleaning & Preparation | ✅ Complete |
| Week 2 | Exploratory Data Analysis | ✅ Complete |
| Week 3 | ML Modeling (LR, RF, XGBoost) | ✅ Complete |
| Week 4 | Tableau Decision-Support Dashboard | ✅ Complete |
| Week 5 | Insights & Storytelling | 🔄 Up Next |
| Week 6 | Final Presentation & Wrap-up | ⬜ Pending |

---

## 📊 Interactive Dashboard

**🔗 Live Dashboard:** [Hospital Readmission Prediction Dashboard](https://public.tableau.com/app/profile/satish.kumar.akrura/viz/Book2_17829387676300/HospitalReadmissionDashboard)

The Tableau dashboard provides a clinical decision-support view for hospital staff with three panels:

- 📋 **Patient Risk Triage** — 3,111 high-risk patients ranked by ML-generated risk score with recommended interventions and color-coded severity
- 📊 **Readmission by Diagnosis** — 18 diagnosis categories ranked by readmission count; Circulatory diseases lead at ~6,000 readmissions
- 📈 **Risk Score Distribution** — Histogram showing clear separation of Low, Medium, and High risk tiers across all 19,611 patients

---

## 🛠️ Approach

This project follows an end-to-end analytics workflow:

1. **Discovery** — Industry research and problem framing
2. **Data Exploration**
