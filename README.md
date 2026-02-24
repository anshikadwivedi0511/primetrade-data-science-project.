# primetrade-data-science-assignment.

# Trader Performance vs. Market Sentiment Analysis

## Objective
An analysis of how Bitcoin market sentiment (Fear/Greed) influences trader behavior and performance on the Hyperliquid platform.

## Key Insights
* **Fear drives Alpha:** Total PnL during Fear regimes is 8x higher than in Greed, with a significant jump in win rates (41.5%).
* **Greed Trap:** Win rates hit their lowest (30.4%) during Greed days, likely due to unsuccessful "trend-fading" short biases.
* **Consistency is Activity:** High-performing traders are characterized by 18x higher trade frequency rather than massive trade sizes.

## Strategy Recommendations
1. **Capitalize on Fear:** Increase liquidity provision and trade frequency for consistent winners during Fear regimes.
2. **Defensive Guardrails:** Suggest a 25% reduction in leverage for inconsistent traders during Greed regimes to mitigate short-bias losses.

## How to Run
1. Open `assignment.ipynb` in Jupyter Notebook or Google Colab.
2. Ensure the sentiment and trader datasets are in the same directory.
3. Run all cells to reproduce the analysis and charts.
