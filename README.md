## 📂 Contents & Project Summaries

| File | Description |
|------|-------------|
| `Nat_Gas.csv` | Monthly natural gas prices (sample data) |
| `NatGas_Analysis.ipynb` | **Task 1:** Time series analysis and ARIMA forecasting of natural gas prices for indicative pricing over 18 months |
| `NatGas_Storage_Pricing.ipynb` | **Task 2:** Prototype pricing model for a commodity storage contract, using forecasted prices, injection/withdrawal rates, and storage costs |
| `Task 3 and 4_Loan_Data.csv` | Customer loan data with features for credit risk modeling |
| `Credit_Risk_Analysis.ipynb` | **Task 3:** Credit risk model predicting probability of default (PD) using a Random Forest classifier; includes function to estimate expected loss |
| `FICO_Bucketing_Quantization.ipynb` | **Task 4:** FICO score bucketing for quantization; mapped FICO scores into 5 buckets, calculated default probability per bucket, minimized mean squared error (MSE) |

---

## 📝 Project Highlights

### ✔ **Task 1: Natural Gas Price Analysis**
- Loaded historical monthly prices and visualized trends.
- Built an ARIMA model to forecast future prices.
- Used results to extrapolate indicative future pricing for storage contracts.

### ✔ **Task 2: Storage Pricing**
- Developed a Python function to price a commodity storage contract.
- Incorporated injection and withdrawal dates, market price estimates, storage volume, and costs.
- Provided a flexible template for client scenarios.

### ✔ **Task 3: Credit Risk Analysis**
- Cleaned and prepared loan data with borrower features.
- Trained a Random Forest to predict the probability of default.
- Created a reusable Python function to estimate expected loss based on PD and recovery rate.

### ✔ **Task 4: FICO Bucketing & Quantization**
- Bucketed FICO scores into 5 discrete categories.
- Calculated the average default rate per bucket.
- Demonstrated how quantization reduces input complexity for categorical models.

---

## ✅ Skills Demonstrated

- **Python**: pandas, scikit-learn, statsmodels
- **Time Series Forecasting (ARIMA)**
- **Machine Learning Classification**
- **Financial Risk Modeling**
- **Quantization & Bucketing**

---

## ⚡ Notes

> This repository is based on the **JPMorgan Chase & Co. Quantitative Research Virtual Experience Program** by Forage.  
> Data is sample-only, used for educational and portfolio purposes.

---

