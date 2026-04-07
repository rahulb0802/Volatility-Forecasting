# Volatility Forecasting Analysis

This project explores volatility forecasting techniques applied to a selection of exchange-traded funds (ETFs). We implement and compare various models, including basic forecasting methods and GARCH models, to predict future volatility based on historical price data.

## Overview

The analysis covers ten major sector ETFs: SPY, XLB, XLE, XLF, XLI, XLK, XLP, XLU, XLV, and XLY. We examine daily returns and develop forecasting models to estimate future variance and volatility.

## Data

The `data/` directory contains:
- Individual ticker data for each ETF in CSV format
- Basic forecast results for each ETF
- GARCH model variance forecasts

All data is sourced from historical price information and processed for analysis.

## Notebooks

The `notebooks/` folder includes Jupyter notebooks detailing the analysis:
- `01_data_prep.ipynb`: Data preparation and cleaning
- `02_estimators.ipynb`: Implementation of various estimators
- `03_garch.ipynb`: GARCH model development and forecasting
- `report.ipynb`: Comprehensive report generation

## Report

For a detailed walkthrough of the methodology, results, and conclusions, view the interactive HTML report by visiting this link: https://rahulb0802.github.io/Volatility-Forecasting/

## Requirements

To run the notebooks and reproduce the analysis:
- Python 3.8+
- Jupyter Notebook or JupyterLab
- Required packages: pandas, numpy, matplotlib, statsmodels, arch (for GARCH models)

Install dependencies with: `pip install pandas numpy matplotlib statsmodels arch`

## Usage

1. Clone or download the repository
2. Navigate to the project directory
3. Open the notebooks in Jupyter to explore the code
4. View `index.html` for the complete report
