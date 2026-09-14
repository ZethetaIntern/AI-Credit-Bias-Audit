# AI-Credit-Bias-Audit
Algorithmic Bias Audit for Credit Scoring Model using Python &amp; SHAP
# ⚖️ Algorithmic Bias Audit for AI Credit Scoring Model

## 📌 Overview
This project performs an end-to-end **Algorithmic Bias Audit** on a synthetic Credit Scoring dataset (50,000 records). It detects initial gender disparities, explains root causes using **SHAP**, and applies post-processing threshold tuning to achieve compliance with regulatory standards like the **Four-Fifths Rule (80% Rule)**.

## 📊 Key Findings
* **Initial Demographic Parity Ratio (DPR):** `0.22` (High Bias against Female applicants)
* **Initial Approval Rates:** Male `52.17%` vs Female `11.47%`
* **Mitigated Demographic Parity Ratio (DPR):** `1.00` (Passed / Fair)

## 🛠️ Tech Stack & Methods
* **Python**, Pandas, NumPy
* **XGBoost** (Machine Learning Model)
* **SHAP** (Explainable AI / Feature Importance)
* **Fairness Metric:** Demographic Parity Ratio (DPR)
* **Mitigation Technique:** Percentile-Based Equal Opportunity Thresholding

## 🚀 How to Run
1. Open the `.ipynb` notebook in **Google Colab**.
2. Run all cells sequentially.
