# Stock & Financial Data Analysis

A Python-based financial analysis project exploring historical stock market data using Pandas, NumPy, Matplotlib, and yfinance.

## Objectives

- Retrieve historical stock market data
- Calculate daily and cumulative returns
- Measure annualized volatility
- Analyze 50-day and 200-day moving averages
- Calculate maximum drawdown
- Compare the performance and risk of multiple stocks
- Examine correlations between stock returns
- Visualize historical performance and hypothetical investment growth

## Technologies

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- yfinance

## Project Structure

```text
stock-financial-analysis/
├── notebooks/
│   └── stock_analysis.ipynb
├── data/
│   └── .gitkeep
├── .gitignore
├── README.md
└── requirements.txt
```

## Getting Started

### 1. Clone the repository

```bash
git clone <your-github-repository-url>
cd stock-financial-analysis
```

Replace the placeholder with your actual GitHub repository URL.

### 2. Create a virtual environment

```bash
python -m venv venv
```

Activate it on Windows PowerShell:

```powershell
.\venv\Scripts\Activate.ps1
```

### 3. Install dependencies

```bash
python -m pip install -r requirements.txt
```

### 4. Launch Jupyter Notebook

```bash
python -m notebook
```

Open `notebooks/stock_analysis.ipynb` and run the notebook cells.

## Analysis Features

- Historical stock price analysis
- Daily and cumulative returns
- Average daily returns and best/worst trading days
- Annualized volatility
- 50-day and 200-day moving averages
- Maximum drawdown analysis
- Multi-stock performance comparison
- Sharpe ratio calculation
- Stock return correlation matrix and heatmap
- Hypothetical investment growth comparison

## Results

The Jupyter Notebook contains the analysis, charts, performance summary tables, and conclusions.

Stocks analyzed include Apple (AAPL), Microsoft (MSFT), and NVIDIA (NVDA).

## Limitations

- Historical performance does not guarantee future results.
- Results depend on the selected date range and data source.
- Taxes, transaction costs, and other real-world trading frictions are not fully modeled.
- The Sharpe ratio uses a simplified risk-free-rate assumption.
- The analysis is educational and does not constitute investment advice.

## Current Status

**Version 1.0 — Core financial analysis completed.**

Future enhancements may include portfolio optimization, more robust risk metrics, and interactive visualizations.

## Disclaimer

This project is for educational purposes only and does not constitute investment advice.
