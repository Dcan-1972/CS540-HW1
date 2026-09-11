# CS540-HW1

Machine Learning in Finance: Homework 1

This repository contains a Jupyter Notebook submission for CS 440/540 Machine Learning in Finance Homework 1. The assignment focuses on portfolio construction and evaluation using S&P 500 constituent data.

## Contents

- Homework notebook - main implementation, charts, and written answers
- `sp500tickers.txt` - S&P 500 ticker universe used by the notebook
- `requirements.txt` - Python packages needed to run the notebook

## Topics Covered

The notebook works through four portfolio optimization exercises:

1. Mean-variance portfolio optimization with long-only constraints
2. Mean-variance optimization with leverage
3. Risk parity portfolio optimization
4. Weekly rebalanced mean-variance portfolio optimization

## Setup

Create and activate a virtual environment:

```bash
python -m venv .venv
```

On Windows:

```bash
.venv\Scripts\activate
```

On macOS/Linux:

```bash
source .venv/bin/activate
```

Install the required packages:

```bash
pip install -r requirements.txt
```

Start Jupyter:

```bash
jupyter notebook
```

Then open the homework notebook file in the repository root.

## Data Notes

The notebook uses `yfinance` to download historical market data. Results may vary slightly over time if Yahoo Finance updates or adjusts its historical price data.

## Requirements

The project uses:

- Python 3
- Jupyter Notebook
- NumPy
- pandas
- Matplotlib
- CVXPY
- yfinance

## Repository Status

This repository is organized as a coursework submission. The notebook contains the implementation, charts, and written discussion for the homework problems.
