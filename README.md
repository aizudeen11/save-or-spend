# 💰 Save or Spend: Loan vs Investment Optimization Model

This project helps answer a practical personal finance and macro-financial decision problem:

> Should you use extra cash to **prepay your loan** or **invest it instead**?

It builds a comparative framework between:
- 📉 Interest savings from early loan repayment  
- 📈 Returns from investing in financial instruments  

The goal is to identify which option yields higher financial benefit over time.

---

## 🧠 Concept

When you have a loan (e.g. housing or personal loan), you often have two choices:

### Option 1: Prepay Loan
- Reduce outstanding principal
- Save on total interest paid
- Shorten loan tenure

### Option 2: Invest Extra Cash
- Place additional monthly payments into investment accounts
- Earn compound returns (e.g. fixed deposit, EPF, etc.)
- Grow wealth over time

This model quantifies both options for direct comparison.

---

## 📊 Key Features

- Computes **loan amortization (EMI model)**
- Estimates **loan tenure dynamically**
- Simulates **investment growth (future value of annuity)**
- Compares:
  - Interest saved from loan prepayment
  - Wealth generated from investment
- Generates:
  - 📈 Comparative graphs
  - 📊 Summary dataset

---

## 📐 Mathematical Framework

### 🏦 1. Equated Monthly Instalment (EMI)

EMI/M = P x R x (1+R)^N / [(1+R)^N-1]

Where:
- **P** = Principal loan amount  
- **R** = Monthly interest rate  
- **N** = Loan tenure (months)  

---

### ⏳ 2. Loan Tenure Formula

N = ln(M/(M-PR))/ln(1+R)

Where:
- **M** = Monthly installment (EMI)  

---

### 📈 3. Future Value of Investment (Annuity)

A = P([(1+r/n)^nt]-1)/(r/n)

Where:
- **A** = Future value  
- **P** = Monthly investment amount  
- **r** = Annual interest rate  
- **n** = Compounding frequency per year  
- **t** = Time in years  

---

## 🧩 Project Structure

```bash id="calc-structure"
Calculation.ipynb
