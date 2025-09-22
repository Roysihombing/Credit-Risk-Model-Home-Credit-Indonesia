# Credit Risk Modeling - Home Credit Indonesia

## 📌 Project Overview
This project was developed as part of a **Project-Based Virtual Internship** at **Home Credit Indonesia**.  
The main objective is to build a **Credit Risk Model** to support financial inclusion while minimizing revenue loss from incorrectly rejected customers.

### Problem Statement
One of the main challenges faced by the company is that **good customers are being rejected**.  
This issue:
- Leads to **lost revenue opportunities**.
- Limits **financial inclusion**, as eligible individuals are unfairly excluded from accessing credit.

### Objectives
1. **Reduce false rejections** by ensuring eligible customers are correctly approved.  
2. **Support financial inclusion** by widening access to credit for good customers.  
3. **Maintain business growth** by minimizing revenue loss from rejected eligible applicants.  

---

## 🏢 Company Profile
**Home Credit Indonesia** is a consumer finance company operating since 2013, providing installment-based lending services without the need for credit cards.  
The company focuses on:
- Expanding **financial inclusion**  
- Offering **accessible, fast, and transparent financing solutions**  
- Leveraging **data-driven risk modeling** to ensure sustainable growth  

---

## ⚙️ Workflow
1. **Business Understanding**  
2. **Data Understanding**  
3. **Data Preparation**  
4. **Modeling**  
5. **Evaluation**  
6. **Business Recommendations**  

---

## 📊 Data Insights
- Around **91.9% customers pay on time**, while **8.1% default**.  
- Majority of on-time payers are **laborers, sales staff, and core staff**.  
- Customers aged **30–45 dominate** on-time repayment.  
- Most have **secondary education**, followed by higher education.  

---

## 🤖 Modeling
The modeling process focused on **recall** as the most important metric.  
- **Why Recall?**  
  Since the business goal is to **avoid rejecting eligible customers**, recall helps minimize false rejections.  

### Key Features
- **Family Factors** : `CNT_CHILDREN`, `CNT_FAM_MEMBERS`  
- **Financial Status** : `AMT_INCOME_TOTAL`, `AMT_CREDIT`, `AMT_GOODS_PRICE`  
- **Employment & Age** : `DAYS_EMPLOYED`, `DAYS_BIRTH`  
- **Risk Indicators** : `EXT_SOURCE_2`, `EXT_SOURCE_3`  
- **Credit History** : `BUREAU_*`, `INST_*`  

### Best Model
- **LightGBM (Tuned)**  
- Consistent performance on validation and test sets  
- Strong generalization and reliability  

---

## 📈 Model Performance
The comparison of recall scores between models is shown below:

![Recall Comparison](recall_comparison.png)

---

## 📝 Business Recommendations
1. **Strengthen credit scoring** by incorporating family and income factors.  
2. **Prioritize recall for Target 0** to reduce false rejections of good applicants.  
3. **Retrain models regularly** with updated credit bureau and payment behavior data.  
4. Conduct **further hyperparameter tuning** with extended computation for improved results.  

---

## 📂 Repository Structure
