# Finance Data Analysis Project (S&P 500 Stock Market Dataset)

## Project Overview  
This project is a data analysis of real-world **S&P 500 stock price data**. It includes data cleaning, feature engineering, exploratory analysis, visualisation, hypothesis testing, and statistical modeling with assumption checks.

The analysis is written in **R Markdown** and produces a clean HTML report suitable for business and stakeholder communication.

---

## Objectives  
The main objectives of this project are to:

- Import and explore the real-world finance dataset  
- Clean the dataset by removing duplicates and handling missing values  
- Engineer financial features such as daily returns and volatility measures  
- Generate descriptive statistics and grouped summaries  
- Create data visualizations using `ggplot2`  
- Test meaningful finance-based hypotheses using correlation and linear models
- Check statistical assumptions using the `performance` package
- Report results clearly and interpret findings

---

## Dataset Information  
**S&P 500 Stock Data (5 years of daily stock prices)**  
Download from Kaggle: https://www.kaggle.com/datasets/camnugent/sandp500  
File Used `all_stocks_5yr.csv`

### Key Variables  
| Column | Description |
|--------|-------------|
| `date` | Trading date |
| `open` | Opening stock price |
| `high` | Highest stock price of the day |
| `low` | Lowest stock price of the day |
| `close` | Closing stock price |
| `volume` | Trading volume |
| `name` | Stock ticker symbol |
