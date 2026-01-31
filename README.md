#  Sentiment-Driven Trading Behavior Analysis

## 📌 Project Overview

This project analyzes how **market sentiment (Fear–Greed Index)** influences **trading behavior, risk, and performance** using trade-level data.
The goal is to understand **behavioral patterns**, **risk asymmetry**, and **economic significance**, not just raw profitability.

The analysis follows a **structured, end-to-end data science pipeline** covering data engineering, feature creation, behavioral analysis, and statistical inference.

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

5. **Statistical Inference**

   * Mann–Whitney U test (returns)
   * Effect size (rank-biserial)
   * Win-rate proportion tests
   * Bootstrap confidence intervals

---

## 📈 Key Findings (High Level)

* **Fear regimes** show higher win rates and larger trade sizes, indicating cautious but higher-conviction trading.
* **Greed regimes** generate slightly higher average returns through payoff asymmetry but expose traders to severe tail risk.
* **Extreme Fear** is the most unstable regime, with the highest volatility and panic-driven losses.
* Statistical tests confirm these differences are **robust but economically modest**, suggesting sentiment affects **behavior and risk** more than it provides a standalone trading edge.

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