# HDFC Mutual Fund Analysis (2013-2026)

A data-driven analysis of 4 HDFC Mutual Fund categories using Python and Power BI, covering 13 years of real NAV data to uncover insights on returns, risk and SIP growth.

## Project Objective
Which fund delivers the best returns? How does risk vary? How does a monthly SIP grow over 13 years?

## Tools Used
- Python, Pandas, Requests - data collection and analysis
- Jupyter Notebook - development environment
- Power BI - dashboard and visualization

  ## data Source
  mfapi.in - Free public API for Indian Mutual Fund NAV data

| Fund Category | Scheme Code | Scheme Name |
|---|---|---|
| Mid Cap | 118989 | HDFC Mid Cap Fund - Direct Growth |
| Large Cap | 119018 | HDFC Large Cap Fund - Direct Growth |
| ELSS | 119060 | HDFC ELSS Tax Saver - Direct Growth |
| Bond | 113070 | HDFC Bond Fund - Direct Growth |

---

## Analysis Performed

### 1. Fund Performance Comparison
- Calculated 1 Year, 3 Year and 5 Year returns for all 4 funds
- Used pct_change() over 252, 756 and 1260 trading days
- Measured risk using rolling standard deviation (window = 252 days)

## 2. SIP Growth Analsysis
- Simulated ₹5000 monthly SIP from 2013 to 2026
- Tracked units purchased, cumulative units and portfolio value every month
- Compared total invested vs final portfolio value across all funds

## 3. NAV Trend Analysis
- Visualized 13 years of daily NAV movement for all 4 funds
- Identified key market events (COVID crash 2020, recovery 2021)

---


## Key Findings

### Fund Returns Comparison (as of Feb 2026)

| Fund | 1Y Return | 3Y Return | 5Y Return | Risk (Std Dev) |
|---|---|---|---|---|
| Mid Cap | 21.52% | 103.00% | 211.10% | 0.81 |
| ELSS | 12.94% | 80.11% | 157.81% | 0.69 |
| Large Cap | 10.97% | 58.86% | 112.84% | 0.72 |
| Bond | 7.03% | 25.37% | 35.31% | 0.08 |

### SIP Growth Summary (Rs.5,000/month since 2013)

| Fund | Total Invested | Portfolio Value | Profit | Growth |
|---|---|---|---|---|
| Mid Cap | Rs.7,90,000 | Rs.33,98,258 | Rs.26,08,258 | 330% |
| ELSS | Rs.7,90,000 | Rs.23,72,262 | Rs.15,82,262 | 200% |
| Large Cap | Rs.7,90,000 | Rs.21,16,214 | Rs.13,26,214 | 168% |
| Bond | Rs.9,45,000 | Rs.17,73,557 | Rs.8,28,557 | 88% |

---

## Key Insights

1. **Risk-Return Tradeoff is clearly visible** - Mid Cap gave the highest return (211% in 5Y) but carried the highest risk (0.81). Bond was safest (0.08 risk) but lowest return (35% in 5Y).
2. **SIP is a powerful wealth creation tool** - Rs.5,000/month in Mid Cap grew to Rs.33.98 lakhs over 13 years - 4x wealth creation.
3. **Staying invested through crashes pays off** - Despite COVID crash in 2020, all equity funds recovered and delivered superior long-term returns.
4. **ELSS is the balanced choice** - 158% five-year returns plus tax saving under Section 80C makes it ideal for salaried investors.

---

## Power BI Dashboard

The dashboard contains 3 pages:
- **Page 1 - Fund Performance Analysis:** Bar chart comparing 1Y, 3Y, 5Y returns and risk
- **Page 2 - SIP Growth Analysis:** Line chart showing portfolio value growth from 2013 to 2026
- **Page 3 - NAV Trend Analysis:** Line chart showing daily NAV movement over 13 years

---

## Done by

**Anakha Fobbin**
- Email: anakhafobbin@gmail.com
- LinkedIn: https://www.linkedin.com/in/anakha-fobbin/
- GitHub: https://github.com/Anakha-18

---
## Disclaimer

This project is for educational purposes only and is not financial advice.
  
