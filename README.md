# Trader Behavior vs Market Sentiment Analysis

## Objective
Analyze how market sentiment (Fear/Greed) influences trader performance and behavior on Hyperliquid.

## Methodology
- Cleaned and standardized sentiment and trading datasets
- Converted timestamps and aligned both datasets at a daily level
- Engineered key metrics: PnL, win rate, trade frequency
- Segmented traders into Winner/Loser and High/Low frequency groups
- Performed comparative analysis across different sentiment regimes

## Key Insights
- Traders achieve higher profitability and win rates during Greed periods
- Neutral sentiment results in the weakest performance due to lack of clear market direction
- Winner traders show consistent performance across conditions, while losers depend heavily on market sentiment
- Market momentum during Greed can drive profits even for less consistent traders

## Strategy Recommendations
- Increase participation during Greed using trend-following strategies
- Reduce leverage and risk exposure during Fear periods
- Avoid or minimize trading during Neutral markets due to low edge

## Bonus: Predictive Modeling
A simple Random Forest model was trained to predict whether a trade is profitable based on trade features.
The model achieved reasonable accuracy, indicating that trader behavior features (such as trade size and fees) have predictive power when combined with market sentiment.
