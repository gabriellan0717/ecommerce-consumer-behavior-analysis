# E-Commerce Consumer Behavior Analysis 📊

Analysis of e-commerce consumer behavior to understand factors influencing purchase decisions and brand loyalty using statistical methods in R and data visualization in Tableau. Includes ANOVA, regression, correlation analyses, and actionable business insights


**Course:** CIS 328: Introduction to Data Analytics  
**Team:** Angelika Kipenskaia, Abel Berhanu, Zach Miskell, Gabriella Njinimbot  

---

## Project Overview
E-commerce businesses struggle to understand what drives customer purchases and retention. This project analyzes customer behavior and loyalty to answer the core question:

**How can an e-commerce business effectively maximize sales and customer loyalty?**

We analyzed a 1,000-entry Kaggle dataset covering demographics, purchasing behavior, marketing influence, and loyalty metrics across 28 variables.

---

## Research Questions & Methods

| Research Question | Statistical Method |
|------------------|-----------------|
| Does education level affect time spent researching products? | One-Way ANOVA |
| Do loyalty program members spend more than non-members? | One-Way ANOVA |
| Is there a relationship between research time and purchase amount? | Correlation / Simple Linear Regression |
| Is there a relationship between purchase frequency and brand loyalty? | Multiple Linear Regression |

---

## Dataset
- **Source:** Kaggle — Ecommerce Consumer Behavior Analysis Data  
- **Size:** 1,000 entries, 28 variables  
- **Variable Types:** Demographic (age, gender, income, education), Behavioral (purchase amount, frequency, research time), Loyalty metrics (brand loyalty, satisfaction, loyalty program membership)

---

## Descriptive Statistics Summary

| Variable | Mean | SD | Min | Max |
|----------|------|----|-----|-----|
| Age | 34.3 | 9.35 | 18 | 50 |
| Purchase Amount ($) | 275.13 | 250.70 | 4 | 998 |
| Frequency of Purchase | 6.94 | 3.15 | 2 | 12 |
| Brand Loyalty (1–5) | 3.03 | 1.42 | 1 | 5 |
| Research Time (hrs) | 1.01 | 0.79 | 0 | 2 |
| Customer Satisfaction (1–10) | 5.40 | 2.87 | 1 | 10 |

---

## Key Findings

1. **Education Level vs. Research Time** – ANOVA  
   - **Result:** No significant difference — F(2, 997) = 0.319, p = 0.727  
   - **Conclusion:** Education does not predict time spent researching products.

2. **Loyalty Program vs. Purchase Amount** – ANOVA  
   - **Result:** Statistically significant — F(1, 998) = 10.72, p = 0.0011  
   - **Conclusion:** Non-members spent more on average than loyalty members, suggesting loyalty programs may attract discount-sensitive shoppers.

3. **Research Time vs. Purchase Amount** – Correlation  
   - **Result:** r = −0.02  
   - **Conclusion:** Research time does not predict purchase amount.

4. **Purchase Frequency vs. Brand Loyalty** – Regression  
   - **Result:** No significant relationship  
   - **Conclusion:** Frequent purchasing does not reliably indicate brand loyalty.

---

## Tools & Skills Used
- **R:** ANOVA, regression, correlation  
- **Tableau:** Data visualization and dashboards  
- **Kaggle:** Dataset sourcing  
- **Other Skills:** Hypothesis testing, descriptive statistics, data interpretation, teamwork, technical writing  

---
[CIS328 DA Team Project Final Submission_December 1 2025.docx](https://github.com/user-attachments/files/26530744/CIS328.DA.Team.Project.Final.Submission_December.1.2027.docx)

