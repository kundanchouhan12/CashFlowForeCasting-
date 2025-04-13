# CashFlowForeCasting-
# 💰 Financial Forecasting & Cash Flow Analyzer

This project is a comprehensive **Cash Flow and Profit/Loss Analysis Tool** built using Python, Pandas, ARIMA forecasting, and Matplotlib for visualization.

---

## 📊 Project Overview

The tool analyzes monthly business transactions like **income (inflow)** and **expenses (outflow)** to calculate:

- 💸 Net Cash Flow  
- 🧾 Opening & Closing Balances  
- 📈 Profit/Loss Percentage  
- 🔥 Savings Ratio and Burn Rate  
- 🔮 Forecasted cash flow for next 6 months using **ARIMA model**

---

## 🛠️ Technologies Used

- Python 🐍
- Pandas & NumPy – Data handling
- Statsmodels – ARIMA time series forecasting
- Matplotlib – Charts and Visualizations

---

## 📂 Data Structure

The input data includes the following:

| Column | Description |
|--------|-------------|
| `Labor`, `Materials` | Income sources |
| `Payroll`, `Insurance`, `Rent`, ... | Expense categories |
| `Cash Received from Loan/Investment` | Other inflows |
| `Loan Repayment`, `Owners Draw` | Outflows |

Each row represents a month, and all values are in ₹.

---

## 📈 Visualizations

Includes the following charts:

- ✅ Line chart of **Closing Balance**
- ✅ Bar chart of **Net Cash Flow per Month**
- ✅ Comparison of **Cash Inflow vs Outflow**
- ✅ **Profit/Loss % Trend** (inline + fullscreen chart)
- ✅ Forecasted Net Cash Flow for future months

---

## 🚀 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
