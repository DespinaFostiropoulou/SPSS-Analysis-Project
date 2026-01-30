# 📊 Statistical Analysis with SPSS  
### Author: Fostiropoulou Despoina

This repository contains the SPSS statistical analysis project completed as part of the postgraduate course **“Statistical Analysis Tools”**.  
The project includes:

- SPSS syntax files  
- Statistical outputs (P-P plots, Q-Q plots, tables, tests)  
- Interpretation and analysis of results  
- Visual material for each section  

---

## 📌 Project Overview

The purpose of this project is to perform a complete statistical analysis on a dataset using **IBM SPSS Statistics**, applying both parametric and non‑parametric methods.  
The analysis includes:

- Normality checks  
- Hypothesis testing  
- Independence tests  
- ANOVA  
- Correlation analysis  
- Simple linear regression  

Each section below includes a short explanation and a placeholder for the corresponding images.

---

## 1️⃣ P‑P Plots & Q‑Q Plots (Normality Check)

This section examines whether the quantitative variables follow a normal distribution using **P‑P** and **Q‑Q** plots.

Variables tested:
- Age  
- Years of Experience  
- Current Salary  

**Conclusion:**  
All three variables visually follow a normal distribution, as their values align closely with the diagonal reference line.

**Images:**  
![Picture.1](Picture1.png) 
![Picture2](Picture2.png) 
![Picture3](Picture3.png) 
![Picture4](Picture4.png) 
![Picture5](Picture5.png) 
![Picture6](Picture6.png) 

---

## 2️⃣ Kolmogorov–Smirnov Normality Test

A formal normality test was performed for the same quantitative variables.

**Hypotheses:**  
- H0: The data follow a normal distribution  
- H1: The data do not follow a normal distribution  

**Conclusion:**  
All p‑values > 0.05 → **H0 is accepted**.  
The variables follow a normal distribution.

**Image:**  
![Picture7](Picture7.png) 

---

## 3️⃣ One‑Sample T‑Test

Two tests were performed to compare the sample’s annual salary with:

1. The European average salary (22,000€)  
2. The Greek average salary (10,000€)

**Results:**  
- Comparison with 22,000€ → p > 0.05 → **No significant difference**  
- Comparison with 10,000€ → p < 0.05 → **Significant difference**

**Images:**  
![Picture8](Picture8.png) 
![Picture9](Picture9.png) 
![Picture10](Picture10.png) 
![Picture11](Picture11.png) 

---

## 4️⃣ Chi‑Square Test of Independence

Tested whether **Gender** is associated with:
- Having experienced bullying  
- Having been a bully  

Due to low expected frequencies, variables were recoded into binary categories.

**Conclusion:**  
In both cases, p > 0.05 → **No association** between gender and bullying-related variables.

**Images:**  
![Picture12](Picture12.png) 
![Picture13](Picture13.png) 
![Picture14](Picture14.png) 
![Picture15](Picture15.png) 
![Picture16](Picture16.png) 
![Picture17](Picture17.png) 
![Picture18](Picture18.png) 
![Picture19](Picture19.png) 
![Pictire20](Picture20.png) 
![Picture21](Picture21.png) 
![Picture22](Picture22.png) 

---

## 5️⃣ One‑Way ANOVA

Tested whether annual income differs based on:
- Employment type  
- Marital status  

**Conclusion:**  
All p‑values > 0.05 → **No statistically significant differences**.

**Images:**  
![Picture23](Picture23.png) 
![Picture24](Picture24.png) 
![Picture25](Picture25.png) 
![Picture26](Picture26.png) 
![Picture27](Picture27.png) 

---

## 6️⃣ Independent Samples T‑Test

Compared the mean annual salary between **men** and **women**.

**Conclusion:**  
p > 0.05 → **No significant difference** in salary based on gender.

**Image:**  
![Picture28](Picture28.png) 
![Picture29](Picture29.png) 

---

## 7️⃣ Pearson Correlation

Tested the linear relationship between:
- Age  
- Current Salary  

**Conclusion:**  
Pearson r = −0.259, p > 0.05 → **No linear correlation**.

**Image:**  
![Picture30](Picture30.png) 

---

## 8️⃣ Simple Linear Regression

Regression model predicting **Current Salary** based on **Years of Experience**.

Model:  


\[
Y = a + bX = 16.044 + 0.943X
\]



Prediction for 30 years of experience:  


\[
Y = 44.334
\]



**Conclusion:**  
Experience has a positive effect on salary, though the strength of the relationship depends on the dataset.

**Image:**  
![Picture31](Picture31.png) 
![Picture32](Picture32.png) 
