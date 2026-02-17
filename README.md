#  Sentiment-Driven Trading Behavior Analysis

## 📌 Project Overview

This project analyzes how **market sentiment (Fear–Greed Index)** influences **trading behavior, risk, and performance** using trade-level data.
The goal is to understand **behavioral patterns**, **risk asymmetry**, and **economic significance**, not just raw profitability.

The goal is to interpret how sentiment shifts influence trader behavior,
risk-taking, and participation patterns using a behavioral-finance lens.
The focus is on regime-driven behavior rather than predictive modeling.


---


## 🔍 Analysis Pipeline

The project is organized into the following logical steps:

1. **Data Engineering**

   * Timestamp parsing and alignment
   * Sentiment data merging
   * Data validation and cleaning

2. **Feature Engineering**

   * Net PnL (after fees)
   * Win/Loss indicators
   * Normalized returns
   * Risk magnitude metrics

3. **Performance & Risk Analysis**

   * PnL, win rate, volatility
   * Downside and tail-risk analysis

4. **Behavioral Pattern Analysis**

   * Overtrading behavior
   * Trade size aggressiveness
   * Long vs short bias
   * Account-level adaptability

5. Behavioral Regime Analysis

   * Activity shifts across Fear vs Greed periods
   * Liquidity surges during Extreme Fear
   * Return dispersion changes across sentiment states
   * Regime persistence and emotional asymmetry


---

## 📈 Key Findings (High Level)

• Fear regimes are characterized by rapid participation increases and liquidity demand,
  consistent with loss-aversion driven repositioning.

• Greed regimes display slower but more persistent activity with wider payoff dispersion,
  indicating risk-seeking behavior rather than improved decision accuracy.

• Extreme Fear produces short-lived but intense market stress events,
  while Greed regimes persist longer as optimism decays gradually.

• Sentiment functions primarily as a risk-state indicator rather than a directional signal.


Detailed results and interpretations are available in **`ds_report.pdf`**.

---

## 🛠️ Tools & Libraries

* Python (Pandas, NumPy)
* SciPy, StatsModels
* Google Colab (execution environment)


## 📝 Notes

* The analysis avoids slow or naive statistical methods to ensure scalability.
* Emphasis is placed on **effect size and economic relevance**, not p-values alone.
* The project is fully reproducible within Colab.

---
This project should be read as a sentiment intelligence study rather than a predictive trading model.
