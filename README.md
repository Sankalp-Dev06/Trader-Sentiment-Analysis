#  Trader Performance vs Market Sentiment Analysis

##  Objective
Analyze how market sentiment (Fear/Greed) impacts trader behavior and performance using Hyperliquid trading data.

---

##  Dataset
1. Bitcoin Market Sentiment (Fear/Greed Index) : fear_greed_index.csv
2. Historical Trader Data (Hyperliquid) : historical_data.csv

---

##  Methodology

### 1. Data Preparation
- Cleaned and standardized datasets
- Converted timestamps to daily format
- Aligned trading data with sentiment data
- Handled missing values and removed outliers

### 2. Feature Engineering
Created daily trader-level metrics:
- **PnL (Profit and Loss):** Net profit/loss per day
- **Win Rate:** Percentage of profitable trades
- **Trades Count:** Number of trades per day
- **Position Size:** Average capital per trade (proxy for risk)
- **Long Ratio:** Proportion of long trades

### 3. Analysis
- Compared trader performance across sentiment states
- Analyzed behavioral changes (activity, risk, bias)
- Performed segmentation (activity level, position size)

### 4. Optional Modeling
- Built a Random Forest model to predict profitability

---

##  Key Insights

- Traders perform best during **Fear phases**, with higher PnL and win rate
- Trading activity increases significantly during Fear
- Risk-taking (position size) is highest in volatile conditions
- Greed phases show higher long bias but lower efficiency
- High-activity traders benefit most during Fear but face higher risk

---

##  Strategy Recommendations

- Increase activity during Fear phases to exploit volatility
- Reduce risk exposure during Greed phases
- Apply strict risk controls for high-frequency trading
- Consider contrarian strategies in overly bullish markets

---

##  Limitations

- Dataset contains only ~6 trading days
- Results are indicative, not conclusive
- Position size used as proxy for leverage

---

##  How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/Sankalp-Dev06/Trader-Sentiment-Analysis.git
   cd Trader-Sentiment-Analysis
   ```

2. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn jupyter
   ```

3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

4. Open `trader_sentiment_analysis.ipynb` and run all cells to execute the analysis

5. View the outputs:
   - Data summaries in Part A (Data Preparation)
   - Visualizations and insights in Part B (Analysis)
