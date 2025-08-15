# (Currency Momentum Effects and Strategies (Fama-Macbeth Cross-Sectional Regression and Portfolio Sorts))

This code analyzes data of 21 currencies between 2000 and 2022 to assess the presence of
momentum effects in currency markets. The results show the existence of momentum effects,
especially for brief holding periods, although the explanatory power is limited. Anyhow, the
profitability of momentum portfolios in real-world applications may be restricted by practical
issues like transaction costs and market inefficiencies, despite historically extraordinary
profits.

---
### Objective
To analyse the performance and statistical significance of momentum strategies in currency markets.

### Methodology
- Data: Monthly spot and forward rates from Bloomberg & Refinitiv Datastream.
- Approach: Ranked 21 currencies by excess returns, constructed 112 portfolios with varying formation (1–12 months) and holding periods (1–12 months).
- Analysis: Applied Fama–French regressions (with/without momentum factor) to assess risk-adjusted performance.
  
### Key Results
- Documented presence of momentum premium across tested strategies.
- Identified optimal formation/holding combinations with highest Sharpe ratios.
