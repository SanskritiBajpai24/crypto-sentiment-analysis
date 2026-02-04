# Trader Sentiment Analysis

## Overview
This project analyzes historical trading data from Hyperliquid against the Bitcoin Fear & Greed Index to determine how market sentiment influences trader performance. The analysis provides actionable strategies for optimizing trade frequency and sizing based on market psychological states.

## Contents
* `ex.ipynb`: The main analysis notebook containing data cleaning, EDA, segmentation analysis, and predictive modeling.
* `fear_greed_index.csv`: Daily sentiment data.
* `historical_data.csv`: Historical trade logs (not included in repo due to size, ensure it is in the root directory).

## Key Findings
* **Extreme Greed** correlates with the highest win rates and average PnL.
* **Low Frequency traders** significantly outperform high-frequency traders during Greed cycles.
* **Trade Size** acts as a strong predictor for trade success in the Random Forest model.

## Setup & Usage

### Prerequisites
Ensure you have Python installed along with the following libraries:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn