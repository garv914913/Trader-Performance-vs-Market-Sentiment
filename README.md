# Trader Performance vs Market Sentiment

## 📌 Objective

Analyze how market sentiment (Fear/Greed) impacts trader behavior and performance.

---

## 📂 Dataset

* Trader data (Hyperliquid)
* Bitcoin Fear & Greed Index

---

## ⚙️ Setup

```bash
pip install -r requirements.txt
```

---

## ▶️ How to Run

1. Open `analysis.ipynb`
2. Run all cells sequentially

---

## 📊 Methodology

* Cleaned and aligned both datasets on **daily date level**
* Created key metrics:

  * Daily PnL
  * Trade frequency
  * Average trade size
  * Win rate
  * Long/Short ratio
* Merged with sentiment classification
* Performed grouped analysis by sentiment

---

## 📈 Key Insights

1. **Higher profitability during Fear**

   * Average PnL is significantly higher in Fear vs Greed conditions

2. **Increased trading activity in Fear**

   * Traders execute more trades during Fear periods

3. **Risk reduction in extreme conditions**

   * Trade sizes drop during Extreme Fear → risk-off behavior

---

## 🎯 Strategy Recommendations

1. **Fear Market Strategy**

   * Increase trade frequency
   * Maintain moderate position size

2. **Greed Market Strategy**

   * Reduce trading activity
   * Avoid large positions (risk of overconfidence)

---

## 📌 Conclusion

Market sentiment strongly influences trader behavior. Fear periods present higher opportunities but require disciplined risk management.

---
