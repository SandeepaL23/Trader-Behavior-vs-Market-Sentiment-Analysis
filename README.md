# Trader-Behavior-vs-Market-Sentiment-Analysis
Analysis of trader behavior and profitability across different market sentiment phases using Fear &amp; Greed Index data.

## Project Overview

This project explores how **market sentiment influences the performance and behavior of cryptocurrency traders**. By combining trading data with the **Fear & Greed Index**, the analysis investigates whether different market moods—such as fear or greed—have any noticeable impact on trading outcomes.

The main objective is to understand **how traders perform under different sentiment conditions** and identify patterns that may influence profitability or trading activity.

---

## Dataset

Two datasets were used in this analysis.

### 1. Trader Data

This dataset contains information about individual trades made by traders. Important fields include:

* `account` – Wallet address of the trader
* `symbol` – Trading pair (e.g., BTCUSDT)
* `side` – Whether the trade was a buy or sell
* `size` – Size of the trade
* `price` – Execution price of the trade
* `fee` – Transaction fee paid
* `closed_pnl` – Profit or loss from the completed trade

### 2. Market Sentiment Data

This dataset provides **daily sentiment classifications** based on the Fear & Greed Index. Each day is categorized into one of the following sentiment levels:

* Extreme Fear
* Fear
* Neutral
* Greed
* Extreme Greed

Fields included:

* `date`
* `classification`

---

## Project Workflow

The analysis follows a typical data science workflow:

1. Loading and understanding the datasets
2. Performing exploratory data analysis (EDA)
3. Cleaning the data and checking for missing values
4. Creating useful features such as numerical sentiment scores and time-based attributes
5. Analyzing trader performance metrics
6. Examining the relationship between sentiment and profitability
7. Visualizing patterns and trends
8. Drawing insights from the results

---

## Key Analysis Performed

### Data Exploration

* Initial inspection of datasets
* Checking for missing or inconsistent values
* Generating statistical summaries

### Feature Engineering

* Converting sentiment labels into numerical scores
* Extracting time-related features from timestamps

### Trader Performance Analysis

* Measuring profitability of traders
* Identifying top-performing traders
* Calculating trader win rates

### Sentiment Impact Analysis

* Comparing average profits across sentiment phases
* Analyzing trading activity during different sentiment conditions
* Examining correlations between sentiment and profitability

---

## Key Insights

Some interesting patterns emerged from the analysis:

* **Market sentiment appears to influence trading outcomes.**
* **Greed and Extreme Greed periods tend to show higher average profits.**
* **Extreme Fear phases are often associated with weaker trading performance.**
* **Top-performing traders generally maintain higher win rates than others.**
* **Most trades cluster around small gains and losses, suggesting limited profit per trade.**

---

## Technologies Used

The project was implemented using the following tools:

* **Python**
* **Pandas** for data manipulation
* **NumPy** for numerical operations
* **Matplotlib** and **Seaborn** for visualization
* **Google Collab** for analysis and documentation


## Future Improvements

Possible extensions of this project include:

* Building machine learning models to predict trading profitability
* Clustering traders based on behavioral patterns
* Studying trading strategies across different market regimes
* Evaluating performance using risk-adjusted metrics

