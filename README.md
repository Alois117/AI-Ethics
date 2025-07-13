# 🧠 AI Ethics Assignment – Fairness Audit & Case Study Analysis

## 📌 Overview

This repository contains all materials submitted for the **AI Ethics Assignment**, which explores ethical principles in artificial intelligence through theoretical reflection, real-world case analysis, technical bias auditing using the COMPAS Recidivism dataset, and a healthcare-focused AI policy proposal.

## 🎯 Objective

To evaluate our understanding of:
- Core AI ethics principles
- How to detect and mitigate algorithmic bias
- Practical use of AI Fairness 360 toolkit
- Transparent and fair AI in sensitive domains like hiring, policing, and healthcare

---


---

## 🛠️ Technologies Used

- **Python 3.11**
- **Jupyter Notebook / Google Colab**
- **Libraries**: 
  - `pandas`
  - `matplotlib`
  - `aif360`
  - `gdown` (for loading dataset)
- **Dataset**: COMPAS Recidivism Data ([ProPublica](https://projects.propublica.org/datastore/#compas-recidivism-risk-score-data-and-analysis))

---

## 🧪 Part 3: Technical Audit Summary

- Dataset: `compas-scores-two-years.csv`
- Tool Used: IBM AI Fairness 360
- Protected Attribute: `race` (focus on African-American vs. Caucasian)
- Target Variable: `two_year_recid`
- Fairness Metrics Reported:
  - **Statistical Parity Difference**: `0.2402`
  - **Disparate Impact**: `1.6902`
  - **Equal Opportunity Difference**: `0.1973`
  - **Average Odds Difference**: `0.2056`
  - **False Positive Rate Difference**: `0.2139`

📊 Visualizations and metric calculations are available in the Jupyter Notebook.

---

## 📚 Part 1–2: Theoretical Analysis & Case Studies

### ✅ Part 1: Theoretical Concepts
- Algorithmic Bias Definition & Examples
- Transparency vs Explainability
- GDPR's Role in Ethical AI
- Matching Core Ethics Principles (Justice, Non-maleficence, Autonomy, Sustainability)

### ✅ Part 2: Case Study Analysis
- **Case 1**: Biased Hiring Tool (Amazon)
  - Bias source: historical data
  - Fixes: diverse data, fairness constraints, human oversight
  - Metrics: Disparate Impact, Equal Opportunity Difference
- **Case 2**: Facial Recognition in Policing
  - Risks: misidentification, privacy violation, erosion of trust
  - Policies: audits, transparency, legal safeguards

---

## 🧭 Part 4: Ethical Reflection

A detailed 300-word reflection on how to apply ethical AI principles in future personal projects, including fairness, transparency, privacy, and human oversight.

---

## 🩺 Bonus: Ethical AI Policy in Healthcare

A 1-page policy guideline document covering:
- Patient consent and data rights
- Bias mitigation strategies
- Transparency and accountability requirements

---

## 📌 Submission Instructions

✅ Written Components: Submitted as PDFs (Parts 1–2, Reflection, and Bonus Policy)  
✅ Code & Visualization: Shared via GitHub in notebook form  
✅ Notebook: Fully functional with step-by-step bias audit using AIF360

---
