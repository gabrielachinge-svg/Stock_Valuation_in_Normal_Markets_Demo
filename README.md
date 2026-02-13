# Stock Valuation in Normal Markets

## Overview

This project demonstrates Stock Valuation in Normal Markets using Python. It provides a modular framework for calculating a stock's intrinsic value using multiple standard methods:

- Discounted Cash Flow (DCF)
- Dividend Discount Model (DDM)
- Relative Valuation using Multiples (P/E, P/B)

The demo is designed for research, teaching, or prototyping and visualizes valuations for easy comparison.

---

## Features

- **DCF Valuation:** Project future free cash flows and discount them to present value.  
- **DDM Valuation:** Compute intrinsic value for dividend-paying stocks using Gordon Growth.  
- **Relative Valuation:** Price a stock using P/E and P/B multiples against comparable companies.  
- **Visualization:** Bar chart comparison of valuation results.  
- **Modular Design:** Separate Python modules for stock, cash flow models, and multiples.

## Installation

1. Clone the repository:
```
git clone <your-repo-url>
cd stock_valuation
```
2. Install dependencies:
```
pip install -r requirements.txt
```
3. Launch Jupyter Notebook:
```
jupyter notebook notebooks/stock_valuation_demo.ipynb
```
Folder Structure
```
stock_valuation/
│
├── core/                   # Core modules for valuation
│   ├── stock.py
│   ├── cashflow_models.py
│   └── multiples.py
│
├── notebooks/              # Jupyter notebook demo
│   └── stock_valuation_demo.ipynb
│
├── requirements.txt
└── README.md

