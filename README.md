# Hyperliquid Trader Behavior Analysis Using Bitcoin Market Sentiment

## Project Overview

This project analyzes the relationship between **Bitcoin Market Sentiment (Fear & Greed Index)** and **Hyperliquid trader behavior** using historical trading data.

The objective is to understand how market sentiment influences trader performance, trading behavior, and profitability while uncovering actionable trading strategies through data analysis and machine learning.

This project was completed using **Python, Pandas, Matplotlib, and Scikit-Learn** in Google Colab.

---

## Objectives

- Analyze trader performance across different market sentiment conditions.
- Examine changes in trading behavior during Fear and Greed periods.
- Identify different trader segments based on trading characteristics.
- Generate actionable trading recommendations from the analysis.
- Apply K-Means Clustering to discover trader behavioral archetypes.

---

## Dataset

This project uses two datasets:

### 1. Bitcoin Market Sentiment Dataset
Contains daily Bitcoin Fear & Greed Index information.

**Columns include:**
- Date
- Fear & Greed Classification
- Sentiment Value

---

### 2. Hyperliquid Historical Trader Dataset

Contains historical trading records including:

- Account
- Coin
- Execution Price
- Trade Size
- Closed PnL
- Trading Direction
- Fees
- Timestamp
- Transaction Information

---

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Scikit-Learn (K-Means Clustering)

---

# Project Workflow

1. Data Cleaning
2. Data Validation
3. Timestamp Conversion
4. Dataset Merging
5. Feature Engineering
6. Exploratory Data Analysis
7. Performance Analysis
8. Behavioral Analysis
9. Trader Segmentation
10. K-Means Clustering
11. Strategy Recommendations

---

# Key Metrics Analyzed

- Daily Closed PnL
- Win Rate
- Average Trade Size
- Trade Frequency
- Long/Short Ratio
- Drawdown Proxy

---

# Analysis Performed

### Performance Analysis

Compared trader performance across:

- Extreme Fear
- Fear
- Neutral
- Greed
- Extreme Greed

Metrics evaluated:

- Average Closed PnL
- Win Rate
- Drawdown Proxy

---

### Behavioral Analysis

Studied how traders changed their behavior based on market sentiment by analyzing:

- Trading Frequency
- Average Trade Size
- Long vs Short Position Bias

---

### Trader Segmentation

Traders were segmented into:

- Frequent vs Infrequent Traders
- Higher Win Rate vs Lower Win Rate Traders
- High Profit vs Low Profit Traders

---

### Machine Learning

K-Means Clustering was applied using:

- Total Trades
- Average Trade Size
- Total Closed PnL
- Win Rate

The optimal number of clusters was selected using the **Elbow Method**, resulting in **four distinct trader archetypes**.

---

# Key Insights

- Extreme Greed recorded the highest average profitability and win rate.
- Fear periods exhibited the highest trading activity and largest average trade sizes.
- Frequent traders generated substantially higher cumulative profits than infrequent traders.
- A higher win rate did not necessarily correspond to greater profitability.
- K-Means clustering identified four unique trader behavior patterns.

---

# Strategy Recommendations

- Apply stricter risk management during Extreme Fear periods.
- Focus on improving risk-reward ratio rather than maximizing win rate.
- Increase market participation only when supported by a disciplined trading strategy.
- Adjust position sizing according to prevailing market sentiment.

---

# Visualizations

The project includes visualizations such as:

- Average PnL by Market Sentiment
- Win Rate by Sentiment
- Drawdown Proxy Analysis
- Trade Frequency Analysis
- Average Trade Size Analysis
- Long/Short Ratio Analysis
- Elbow Method Plot
- K-Means Cluster Visualization

---

# How to Run

## Clone the Repository

```bash
git clone https://github.com/Kairyushin/Hyperliquid-Trader-Behavior-Analysis.git
```

## Navigate to the Project Folder

```bash
cd Hyperliquid-Trader-Behavior-Analysis
```

## Install Dependencies

```bash
pip install -r requirements.txt
```

## Open the Notebook

Open the notebook using either:

- Google Colab (recommended)
- Jupyter Notebook


Then open:

```
Hyperliquid_Trader_Behavior_Analysis.ipynb
```

Run all cells sequentially.

---

# Repository Structure

```
Hyperliquid-Trader-Behavior-Analysis
│
├── Hyperliquid_Trader_Analysis.ipynb
├── Hyperliquid Trader Behavior Analysis Using Bitcoin Market Sentiment_report.pdf
├── README.md
├── requirements.txt
├── Output charts/

```

---

# Author

**Srijan Roy**

Data Analyst

B.Tech in Electronics & Communication Engineering

---
