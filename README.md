# 📊 Automated DCF & Credit Risk Analysis Tool for Public Companies

This project performs an enhanced **Discounted Cash Flow (DCF)** valuation and **financial risk analysis** for publicly listed companies using Python and Yahoo Finance data. The focus is currently on **Aegis Logistics Ltd. (AEGISLOG.NS)**.

---

## ✨ Features

- ✅ Automated DCF valuation with multi-scenario growth modeling.
- 📈 Sensitivity analysis across discount and growth rates.
- 🛡️ Credit risk analysis (Debt/Equity, Interest Coverage, ROE).
- 🧮 Intrinsic share value calculation with markdown reporting.
- 🧩 Comparative benchmarking (EV/EBITDA, P/E, ROA, ROE).

---

## 🔍 Example Output

A sample Markdown report is generated like:

```
📘 DCF Valuation Report – Aegis Logistics Ltd. (AEGISLOG.NS)

Intrinsic Value per Share (Base Case): ₹92.51
Valuation Scenarios:

- Optimistic: ₹106.78

- Pessimistic: ₹79.34

Key Financial Ratios:

- ROE: 11.54%

- Debt-to-Equity: 1.22

- Interest Coverage Ratio: 4.75

```


📁 View full generated report in `DCF_AegisLogistics_Report.md`.

---

## ⚙️ Requirements

- Python 3.7+
- `yfinance`
- `pandas`
- `numpy`
- `matplotlib`
- `fpdf` (optional for PDF export)

Install dependencies:

```
pip install yfinance pandas numpy matplotlib 
'''
