# trader-sentiment-analysis
# Trader Sentiment Analysis 📉📈

This project explores the relationship between Bitcoin market sentiment (Fear & Greed Index) and trader performance on the Hyperliquid platform. The goal is to uncover hidden patterns, quantify trader behavior under different market conditions, and deliver insights to inform smarter trading strategies.

---

## 📁 Project Overview

**Objective:**  
Analyze how trader performance varies with market sentiment (Fear, Greed, Neutral) and discover actionable insights from trading behavior.

**Datasets Used:**
- **Bitcoin Fear & Greed Index**  
  Columns: `timestamp`, `value`, `classification`, `date`

- **Hyperliquid Historical Trader Data**  
  Columns include: `Account`, `Coin`, `Execution Price`, `Size Tokens`, `Side`, `Timestamp`, `Start Position`, `Direction`, `Closed PnL`, etc.

---

## 🔍 Key Analysis Performed

1. **Data Cleaning & Preprocessing**  
   - Converted timestamps to uniform datetime format  
   - Merged sentiment data with trader data  
   - Filtered irrelevant or incomplete trades

2. **Exploratory Data Analysis (EDA)**  
   - Sentiment distribution across time  
   - Trader activity and performance trends  
   - Profit & loss (PnL) distribution across sentiments

3. **Statistical Testing**  
   - Performed ANOVA to test for differences in trader PnL across sentiment groups  
   - Found statistically significant variance (p < 0.05)

4. **Insights & Patterns**  
   - Traders performed best during **Greed** sentiment periods  
   - Higher trading volume seen during **Fear** phases  
   - Identified consistently profitable accounts across sentiment cycles

---

## 📊 Key Results

| Sentiment | Avg Closed PnL ($) |
|-----------|--------------------|
| Fear      | 49.21              |
| Greed     | 53.88              |
| Neutral   | 34.31              |

- **ANOVA F-statistic**: 6.08  
- **p-value**: 0.0023 (Significant)

---

## 💡 Recommendations

- Identify and study top performers during each sentiment state  
- Incorporate sentiment signals into trading strategies  
- Consider risk-adjusted returns when analyzing sentiment-driven trades

---

## 📂 Files Included

- `trader_sentiment_analysis.ipynb` — Full code and analysis notebook  
- `final_report.pdf` — Visual summary of insights  
- `historical_data.csv` — Trader dataset  
- `fear_greed_index.csv` — Sentiment dataset

---

## 📧 Submission Info

This project is submitted as part of the application for:

**Role:** Junior Data Scientist – Trader Behavior Insights  
**Company:** Bajarangs / PrimeTrade.ai

---

## 🧠 Author

**Nishad Gharote**  
[LinkedIn](https://www.linkedin.com/in/nishadgharote) | [GitHub](https://github.com/NishadGharote)

---

## 🛠 Tech Stack

- Python (Pandas, NumPy, Matplotlib, Seaborn, Scipy)  
- Jupyter Notebook  
- Git/GitHub  
