# Trader Performance vs Market Sentiment

This project analyzes how trader behavior and performance on Hyperliquid vary across different Bitcoin market sentiment regimes (Fear vs Greed).

## Objective
To study the relationship between market sentiment and trading behavior, and identify actionable insights that can inform smarter trading strategies.

## Datasets
- Bitcoin Fear & Greed Index (daily sentiment classification)
- Historical Trader Data from Hyperliquid

> Note: Raw CSV files exceed GitHub size limits and are therefore not uploaded here.  
> They are publicly available from the links provided in the assignment and are loaded directly in the Google Colab notebook.

## Repository Structure
ds_<tanshya_mishra>/
├── notebook_1.ipynb
├── csv_files/
│ └── README.md
├── outputs/
│ ├── avg_pnl_by_sentiment.png
│ └── win_rate_by_sentiment.png (optional)
├── ds_report.pdf
└── README.md

## How to Run
1. Open the Google Colab notebook using the link below.
2. Upload the required CSV files when prompted.
3. Run all cells from top to bottom.

## Google Colab Notebook
(https://colab.research.google.com/drive/1cMK0uH12LrPf8YM4OiefNLJgrUvQx-Fc?usp=sharing)

## Key Insights
- Trader profitability is higher during Greed periods compared to Fear periods.
- Win rates and trade frequency vary significantly across sentiment regimes.
- Fear periods warrant reduced risk exposure, while Greed periods require stricter risk controls.

## Strategy Recommendations
- Reduce position size and leverage during Fear regimes.
- Allow higher trade activity during Greed regimes with strict risk management.
