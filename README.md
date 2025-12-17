<h1 align="center">JPMorgan Chase Quantitative Research Virtual Job Simulation — Full Solution (Forage)</h1>
<h2 align="center">Natural Gas Pricing • Storage Valuation • Credit Risk Modeling • FICO Bucketing</h2>

A complete quantitative analytics project covering commodity price analysis, storage contract valuation, credit risk modeling, and FICO score quantization using Python.

---

## 💡 Overview

This project simulates quantitative research and analytics work commonly performed within JPMorgan Chase’s commodities and risk teams.

The project integrates:

- Natural gas price analysis and extrapolation  
- Commodity storage contract valuation  
- Probability of Default (PD) modeling and expected loss estimation  
- FICO score bucketing using data-driven quantization  

All implementations are provided as Jupyter Notebooks.

---

## 📁 Project Deliverables

| Task | Focus Area | File |
|------|------------|------|
| **Task 1** | Natural Gas Price Analysis & Extrapolation | `Task 1.ipynb` |
| **Task 2** | Commodity Storage Contract Valuation | `Task 2.ipynb` |
| **Task 3** | Credit Risk Modeling & Expected Loss | `Task 3.ipynb` |
| **Task 4** | FICO Score Quantization | `Task 4.ipynb` |

---

## ✅ Task 1: Natural Gas Price Analysis & Extrapolation

Monthly natural gas price data from **October 2020 to September 2024** was analyzed to understand historical behavior and estimate prices beyond the available horizon.

### Key Objectives
- Estimate gas prices for any historical date
- Extrapolate prices one year into the future
- Identify trends and seasonal behavior

### Key Insights
**Observed Market Behavior**
- **2020–2021:** Relatively stable and low prices  
- **2022:** Sharp price spike  
- **2023–2024:** Gradual decline, remaining above pre-spike levels  
- Seasonal effects are visible, particularly during winter months  

**Model Characteristics**
- Clean monthly time series data
- Smooth interpolation and forward extrapolation
- Pricing function implemented:
predict_price(date) → estimated gas price


---

## 📈 Task 2: Commodity Storage Contract Valuation

A prototype pricing model was developed to evaluate the value of a natural gas storage contract under flexible operational assumptions.

### Model Inputs
- Injection and withdrawal dates
- Purchase and sale prices
- Injection and withdrawal rates
- Maximum storage capacity
- Storage operating costs

### Model Output
**Sample Contract Value:**  
-9900.0


### Interpretation
The negative value in the test scenario is driven by:
- High operating and injection costs
- Insufficient price spread between buy and sell dates
- Overall negative net cash flow across the contract lifecycle

---

## 💳 Task 3: Credit Risk Modeling & Expected Loss

A supervised machine learning model was built to estimate borrower **Probability of Default (PD)** using historical loan data.

Expected loss is calculated as:
Expected Loss = PD × Exposure × (1 − Recovery Rate)

**Recovery Rate Assumed:** 10%

### Key Output
**Expected Loss (Sample Loan):**
22497.71


### Interpretation
- The borrower exhibits meaningful default risk
- High exposure significantly increases potential loss
- The model captures key financial risk indicators effectively

---

## 📚 Task 4: FICO Score Quantization

A quantization approach was implemented to bucket continuous FICO scores into discrete credit ratings, where a lower rating represents better credit quality.

### Resulting Buckets

| FICO Range | Count | Defaults | Default Rate |
|------------|-------|----------|--------------|
| 300–579 | 354 | 58 | 0.1638 |
| 580–669 | 904 | 124 | 0.1372 |
| 670–739 | 1095 | 98 | 0.0895 |
| 740–799 | 850 | 43 | 0.0505 |
| 800–850 | 1657 | 77 | 0.0465 |

### Insights
- Default probability decreases consistently with higher FICO scores
- Buckets clearly separate high-risk and low-risk borrowers
- Useful for credit scoring, loan pricing, and portfolio risk analysis

---

## 📂 Repository Structure

| File / Folder | Description |
|--------------|-------------|
| `Task 1.ipynb` | Natural gas price analysis and extrapolation |
| `Task 2.ipynb` | Commodity storage contract valuation |
| `Task 3.ipynb` | Credit risk modeling and expected loss |
| `Task 4.ipynb` | FICO score bucketing and quantization |
| `Nat_Gas_Data.csv` | Natural gas price data (Tasks 1 & 2) |
| `Loan_Data.csv` | Loan and borrower data (Tasks 3 & 4) |
| `Completion_Certificate.pdf` | Job simulation completion certificate |
| `README.md` | Project documentation |

---

## 🙋‍♀️ About Me

👤 **Dolly Gupta**  
📧 **Email:** dollygupta362@gmail.com  
🔗 [Connect on LinkedIn](https://www.linkedin.com/in/dolly-gupta-3b54b8229)

---
