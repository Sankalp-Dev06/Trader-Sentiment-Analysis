
---

# Summary

```markdown
# 📊 Trader Performance vs Market Sentiment

## Objective
To analyze how market sentiment (Fear/Greed) influences trader behavior and profitability.

---

## Methodology
The analysis combined trader-level transaction data with daily market sentiment indicators. Data was cleaned, timestamps standardized, and aligned at a daily level. Key features such as PnL (profit and loss), win rate, trade frequency, position size, and long ratio were engineered.

Behavioral and performance comparisons were conducted across sentiment states. Additionally, traders were segmented based on activity and risk exposure. A simple predictive model was also built as a proof-of-concept.

---

## Key Insights

1. Traders achieve higher profitability and win rates during Fear phases, indicating better trading opportunities in volatile markets.

2. Trade frequency increases significantly during Fear, suggesting heightened market participation.

3. Traders take larger positions during Fear, reflecting increased risk appetite.

4. Greed phases show a higher long bias, indicating bullish sentiment but reduced efficiency.

5. High-frequency traders benefit the most during Fear but also face higher variability in outcomes.

---

## Strategy Recommendations

- Increase trading activity during Fear phases to leverage volatility  
- Reduce position sizes during Greed to avoid overexposure  
- Implement strict risk controls for high-frequency traders  
- Consider contrarian strategies during Greed phases  

---

## Conclusion
The analysis demonstrates that sentiment-driven behavioral patterns significantly impact trading outcomes. Fear phases present higher opportunity but require disciplined risk management, while Greed phases highlight the risks of overconfidence.

---

## Limitations
- Limited dataset (~6 trading days)
- Small sample size (~75 observations)
- Results are indicative and not generalizable