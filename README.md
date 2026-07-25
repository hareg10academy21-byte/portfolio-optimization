# 📈 Time Series Forecasting for Portfolio Management Optimization

## 👤 Author

**Name:** Haregeweyn Ataklt Reda  
**Program:** 10 Academy – AI Mastery Training Program  
**Project:** Week 9 Challenge  
**Institution:** Bahir Dar University  
**Department:** Software Engineering

---

# 📌 Project Overview

This project focuses on building a data-driven portfolio optimization strategy using historical financial market data.

The objective is to forecast Tesla (TSLA) stock prices using time series forecasting models, optimize a diversified investment portfolio using Modern Portfolio Theory (MPT), and evaluate the strategy through historical backtesting.

The project uses financial data obtained from the Yahoo Finance API (YFinance) covering the period from **January 1, 2015 to June 30, 2026**.

---

# 🎯 Business Objective

Guide Me in Finance (GMF) Investments aims to improve portfolio management by combining:

- Time Series Forecasting
- Machine Learning
- Portfolio Optimization
- Risk Analysis
- Performance Backtesting

The goal is to maximize returns while minimizing investment risk.

---

# 📊 Assets Used

| Asset | Ticker | Description |
|--------|--------|-------------|
| Tesla | TSLA | High-growth stock |
| Vanguard Total Bond Market ETF | BND | Low-risk bond ETF |
| SPDR S&P 500 ETF | SPY | Broad U.S. stock market ETF |

---

# 📂 Project Structure

```
portfolio-optimization/

│
├── data/
│   └── processed/
│
├── notebooks/
│   ├── Task1_EDA.ipynb
│   ├── Task2_Modeling.ipynb
│   ├── Task3_Forecasting.ipynb
│   ├── Task4_Portfolio_Optimization.ipynb
│   └── Task5_Backtesting.ipynb
│
├── figures/
│
├── src/
│
├── tests/
│
├── requirements.txt
│
├── README.md
│
└── .gitignore
```

---

# 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- YFinance
- Statsmodels
- pmdarima
- TensorFlow / Keras
- Scikit-Learn
- SciPy

---

# Task 1 – Data Collection & Exploratory Data Analysis

## Objective

Collect, clean, and explore financial market data before modeling.

## Activities

- Downloaded historical data using YFinance
- Cleaned missing values
- Checked data types
- Generated descriptive statistics
- Visualized stock price trends
- Calculated daily returns
- Computed rolling volatility
- Performed outlier analysis
- Conducted Augmented Dickey-Fuller (ADF) stationarity tests
- Calculated:
  - Sharpe Ratio
  - Value at Risk (VaR)

## Deliverables

- Cleaned dataset
- Exploratory Data Analysis notebook
- Statistical analysis
- Risk metrics
- Multiple visualizations

---

# Task 2 – Time Series Forecasting Models

## Objective

Build forecasting models to predict Tesla stock prices.

## Models Implemented

### ARIMA

- Automatic parameter selection using Auto ARIMA
- Model fitting
- Forecast generation

### LSTM

- Sequence generation
- Data normalization
- Neural network training
- Future prediction

## Evaluation Metrics

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- Mean Absolute Percentage Error (MAPE)

## Deliverables

- Trained ARIMA model
- Trained LSTM model
- Model comparison table
- Performance analysis

---

# Task 3 – Future Market Forecasting

## Objective

Forecast Tesla stock prices for the next 6–12 months.

## Activities

- Generated future forecasts
- Created confidence intervals
- Visualized future price predictions
- Compared historical and forecasted prices
- Performed trend analysis
- Identified market opportunities
- Discussed forecasting uncertainty

## Deliverables

- Forecast plot
- Confidence interval visualization
- Trend analysis
- Investment insights

---

# Task 4 – Portfolio Optimization

## Objective

Construct an optimal investment portfolio using Modern Portfolio Theory (MPT).

## Activities

- Calculated expected returns
- Computed covariance matrix
- Built Efficient Frontier
- Identified:
  - Maximum Sharpe Ratio Portfolio
  - Minimum Volatility Portfolio
- Recommended optimal asset allocation

## Portfolio Assets

- TSLA
- SPY
- BND

## Deliverables

- Efficient Frontier plot
- Covariance matrix heatmap
- Portfolio weights
- Risk and return analysis

---

# Task 5 – Portfolio Backtesting

## Objective

Evaluate portfolio performance against a benchmark.

## Benchmark

- 60% SPY
- 40% BND

## Activities

- Simulated portfolio performance
- Calculated cumulative returns
- Compared strategy with benchmark
- Computed:

  - Total Return
  - Annualized Return
  - Sharpe Ratio
  - Maximum Drawdown

## Deliverables

- Performance comparison plot
- Portfolio metrics
- Strategy evaluation
- Final investment recommendation

---

# 📈 Results Summary

The forecasting models successfully captured Tesla's historical price behavior and generated future price estimates.

Portfolio optimization balanced growth and risk by combining Tesla, SPY, and BND.

Backtesting demonstrated how the optimized portfolio performed relative to a traditional benchmark portfolio, providing insights into the effectiveness of the forecasting-driven investment strategy.

---

# 📚 Libraries

```bash
pandas
numpy
matplotlib
yfinance
statsmodels
pmdarima
tensorflow
keras
scikit-learn
scipy
```

---

# ▶️ Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/portfolio-optimization.git
```

Move into the project directory:

```bash
cd portfolio-optimization
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

# ▶️ Run the Project

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open the notebooks folder and execute the notebooks sequentially:

1. Task1_EDA.ipynb
2. Task2_Modeling.ipynb
3. Task3_Forecasting.ipynb
4. Task4_Portfolio_Optimization.ipynb
5. Task5_Backtesting.ipynb

---

# 📊 Key Skills Demonstrated

- Financial Data Analysis
- Time Series Forecasting
- ARIMA Modeling
- LSTM Deep Learning
- Portfolio Optimization
- Risk Analysis
- Modern Portfolio Theory
- Backtesting
- Data Visualization
- Python for Finance

---

# 📖 References

- Yahoo Finance (YFinance)
- Statsmodels Documentation
- Scikit-Learn Documentation
- TensorFlow Documentation
- PyPortfolioOpt Documentation
- Modern Portfolio Theory (Harry Markowitz)

---

# 📄 License

This project was completed as part of the **10 Academy AI Mastery Training Program** for educational purposes.

---

# 🙏 Acknowledgements

Special thanks to:

- 10 Academy
- Guide Me in Finance (GMF) Investments
- Yahoo Finance
- The open-source Python community