# Loan Status Prediction

**"Can we predict if a loan will be approved — before the paperwork even begins?"**

This project takes a real-world loan application dataset and turns it into a predictive machine learning model.  
From deep **exploratory data analysis (EDA)** to advanced **data balancing** techniques like **SMOTE** and **ADASYN**,  
the notebook walks through the full pipeline of building, training, and evaluating a loan approval prediction system.

---

##  Highlights

- **End-to-End ML Workflow**
  - Hypothesis building
  - Data cleaning & preprocessing
  - Exploratory data analysis with meaningful visualizations
  - Feature encoding, scaling, and handling imbalanced data
  - Model training & evaluation

- **Smart Data Handling**
  - Tackles class imbalance using **Synthetic Minority Oversampling (SMOTE)** and **ADASYN**
  - Uses **Label Encoding** for categorical features
  - Standardizes data for algorithm efficiency

- **Transparent Evaluation**
  - Performance comparison between:
    - Original vs. Balanced data
    - Scaled vs. Unscaled datasets
  - Metrics include accuracy, precision, recall, and F1-score

---

## Dataset

**Source:** [Loan Prediction Dataset — Kaggle](https://www.kaggle.com/altruistdelhite04/loan-prediction-problem-dataset)  

- **Training set:** 614 records, 15 columns (features + target)
- **Test set:** 367 records, 14 columns (features only)
- Features include demographic info, financial details, loan parameters, and credit history - just basic information

---

##  Methodology

1. **Project Hypotheses**
   - Education, income, and credit history likely increase approval chances
   - Higher loan amount or longer loan term may reduce approval chances

2. **EDA**
   - Distribution analysis for categorical & numerical features
   - Outlier detection
   - Correlation analysis

3. **Data Preprocessing**
   - Label encoding of categorical variables
   - Standard scaling for normalization
   - Train-test split for unbiased evaluation

4. **Balancing**
   - SMOTE and ADASYN to fix the approval-to-rejection imbalance

5. **Model Building**
   - Logistic Regression (baseline)
   - Trained on both raw and balanced datasets

6. **Evaluation**
   - Compared metrics across preprocessing strategies

---

## Managerial Insights

- **Credit History is the strongest approval driver** — ensuring applicants maintain good credit records could significantly reduce default risk and improve approval efficiency.
- **Loan Amount and Term impact approval rates** — shorter terms and moderate amounts have a higher approval probability, suggesting potential for differentiated product offerings.
- **Education and Employment Stability matter** — graduates and self-employed applicants with consistent income show stronger repayment likelihood, informing targeted marketing.
- **Balanced evaluation benefits both sides** — using data balancing techniques improves detection of potentially risky applications, reducing false approvals without heavily impacting approval volume.
- **Data-driven policies can refine lending criteria** — patterns identified here can help managers adjust loan eligibility thresholds for higher profitability and lower risk.

---
