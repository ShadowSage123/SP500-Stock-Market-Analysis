# S&P 500 Stock Market Analysis and Visualization Using Python

## 📌 Project Overview

This project focuses on analyzing and visualizing historical stock market data from companies in the **S&P 500 index** using Python.

The main objective is to understand stock price trends, company performance, daily returns, volatility, trading volume, moving averages, and relationships between different numerical variables through **Exploratory Data Analysis (EDA)** and data visualization.

The project is developed as a group project using **Google Colab** and Python.

---

## 🎯 Objectives

- Analyze historical S&P 500 stock data.
- Perform data cleaning and exploratory data analysis.
- Analyze stock price trends over time.
- Compare the performance of different companies.
- Calculate and analyze daily stock returns.
- Measure stock volatility.
- Analyze trading volume.
- Use moving averages to identify price trends.
- Study correlations between stock-market variables.
- Present findings using clear and meaningful visualizations.

---

## 📊 Dataset

The dataset used in this project is the **S&P 500 Historical Stock Data** dataset from Kaggle.

**Dataset Source:**  
https://www.kaggle.com/datasets/camnugent/sandp500

### Dataset File

```text
all_stocks_5yr.csv
```

### Main Features

| Column | Description |
|---|---|
| `date` | Date of the stock record |
| `open` | Opening price |
| `high` | Highest price during the day |
| `low` | Lowest price during the day |
| `close` | Closing price |
| `volume` | Number of shares traded |
| `Name` | Stock ticker/company identifier |

The dataset contains historical daily stock information for multiple S&P 500 companies.

---

## 🛠️ Technologies and Libraries

The project uses:

- **Python**
- **Google Colab**
- **Pandas** – Data manipulation and analysis
- **NumPy** – Numerical computations
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical visualization
- **Git & GitHub** – Version control and project collaboration

### Libraries Used

```python
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
```

---

## 🔍 Analysis Performed

### 1. Data Cleaning

The dataset is inspected and prepared for analysis by:

- Checking missing values
- Checking duplicate records
- Converting the `date` column to datetime
- Checking data types
- Sorting records chronologically

### 2. Exploratory Data Analysis

Basic statistical analysis is performed on:

- Opening prices
- Closing prices
- High and low prices
- Trading volume

### 3. Stock Price Trend Analysis

Historical closing prices are visualized for selected companies to understand how their stock prices changed over time.

### 4. Company Performance Analysis

Company performance is compared using the percentage change between the first and last available closing prices.

The analysis identifies:

- Top-performing companies
- Lowest-performing companies

### 5. Daily Returns Analysis

Daily percentage returns are calculated to understand the day-to-day movement of stock prices.

A histogram is used to visualize the distribution of daily returns.

### 6. Volatility Analysis

Stock volatility is measured using the standard deviation of daily returns.

Companies with higher volatility show larger variations in their daily returns.

### 7. Trading Volume Analysis

Trading volume is analyzed to compare the level of trading activity across different companies.

### 8. Moving Average Analysis

20-day and 50-day moving averages are calculated for selected stocks.

These moving averages are plotted along with the closing price to help identify overall price trends.

### 9. Correlation Analysis

A correlation matrix and heatmap are used to examine relationships between:

- Open
- High
- Low
- Close
- Volume

---

## 📈 Visualizations

The project includes visualizations such as:

- Stock price trend line charts
- Top and bottom performing company charts
- Daily returns histogram
- Volatility comparison charts
- Trading volume charts
- Moving average charts
- Correlation heatmap

These visualizations make it easier to identify patterns and trends within the dataset.

---

## 📁 Project Structure

```text
SP500-Stock-Market-Analysis/
│
├── data/
│ └── all_stocks_5yr.csv
│
├── notebooks/
│ └── SP500_Stock_Market_Analysis.ipynb
│
├── visualizations/
│ └── charts and graphs
│
├── README.md
│
└── requirements.txt
```

> **Note:** The dataset may not be included in the GitHub repository because of its file size. The original dataset can be downloaded from the Kaggle link provided above.

---

## 👥 Team Members

| Name | Enrollment No. |
|---|---|
| Ekatra Pandey | IU2541231862 |
| Dev Naik | IU2541231863 |

---

## 📌 Project Scope

This project focuses on **historical data analysis and visualization**.

It does not attempt to predict future stock prices or provide investment recommendations.

The results are based only on the historical data available in the dataset.

---

## 📚 Conclusion

The project demonstrates how Python can be used to process, analyze, and visualize large financial datasets.

Through exploratory data analysis, the project provides insights into stock price movements, company performance, returns, volatility, trading activity, moving averages, and correlations between financial variables.

The analysis also demonstrates the importance of data visualization in understanding large and complex datasets.

**Historical stock performance does not guarantee future results.*
