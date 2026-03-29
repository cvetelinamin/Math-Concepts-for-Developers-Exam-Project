# 📊 Credit Risk Analysis Using PD, LGD, EAD and Stress Testing

## 📌 Project Overview

This project presents a comprehensive credit risk analysis using three key components:

- Probability of Default (PD)
- Loss Given Default (LGD)
- Exposure at Default (EAD)

The goal is to estimate the Expected Loss (EL) of a loan portfolio and analyze how it behaves under different conditions, including economic stress scenarios.

---

## 🎯 Objectives

- Calculate PD based on historical default data  
- Estimate EAD using simulated remaining loan balances  
- Approximate LGD due to missing recovery data  
- Compute Expected Loss (EL)  
- Perform sensitivity analysis  
- Simulate economic stress scenarios  

---

## 📂 Dataset

The dataset contains borrower information such as income, loan amount, loan term, home ownership, and default indicator.

Source: Kaggle Credit Risk Dataset

---

## ⚙️ Methodology

1. Data preprocessing  
2. Exploratory Data Analysis (EDA)  
3. PD estimation  
4. EAD estimation  
5. LGD approximation  
6. Expected Loss calculation  
7. Sensitivity analysis  
8. Stress testing  

---

## 📊 Key Formula

EL = PD × LGD × EAD

---

## 📈 Key Results

- PD ≈ 17.6%  
- Average LGD ≈ 55%  
- Total EAD ≈ 171 million  
- Expected Loss (baseline) ≈ 16.6 million  
- Expected Loss (crisis) ≈ 35.1 million  

---

## ⚠️ Assumptions

- Remaining balance is simulated  
- LGD is approximated  
- PD is based on historical data  
- No macroeconomic variables are included  

---

## 💡 Conclusion

The project shows that expected losses increase significantly under economic stress, highlighting the importance of credit risk management.

---

## 🛠️ Technologies Used

Python, Pandas, NumPy, Matplotlib, Jupyter Notebook

---

## 👤 Author

Cvetelina Mincheva
