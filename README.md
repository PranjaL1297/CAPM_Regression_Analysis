
# 📊 CAPM_Regression_Analysis

A practical implementation of the Capital Asset Pricing Model (CAPM) using Python, with real-world financial data (AAPL & S&P500). This project includes full regression diagnostics such as multicollinearity (VIF) and heteroskedasticity (Breusch-Pagan test), using the `statsmodels` library.

---

## 🔍 Objective
To implement and validate the CAPM framework and assess its assumptions using statistical diagnostics in Python.

---

## 📁 Project Highlights

- **Data Source:**
  - Monthly returns from 2020–2023 for:
    - Apple Inc. (**AAPL**)
    - **S&P 500** (^GSPC) as market proxy
    - 1-month US Treasury Bill rate (**^IRX**) as risk-free rate

- **Methodology:**
  - Computed monthly excess returns for AAPL and the market
  - Ran OLS regression to estimate **alpha (α)** and **beta (β)**
  - Visualized CAPM regression line and residuals

- **Diagnostics:**
  - ✅ **Heteroskedasticity** check using **Breusch-Pagan** test  
  - ✅ **Multicollinearity** detection using **Variance Inflation Factor (VIF)**
  - ✅ **Residual Analysis**: Evaluated distribution, variance, and model assumptions

- **Tools & Libraries:**
  - Python, `pandas`, `numpy`, `matplotlib`, `seaborn`, `statsmodels`, `yfinance`

---

## 🧠 Key Learning Outcomes
- Understood the mechanics of CAPM and asset pricing
- Gained practical experience in regression modeling and diagnostics
- Validated financial models against real-world noise and statistical assumptions

---



---

## 💬 Future Enhancements
- Expand to multi-factor models (Fama-French 3-Factor, Carhart 4-Factor)
- Automate diagnostics reporting
- Incorporate more asset classes and macroeconomic factors
