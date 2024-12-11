This repository contains an analysis of European ETFs and Mutual Funds datasets
from Morningstar. The analysis compares the two investment instruments in terms
of returns, volatility, and risk-adjusted performance.

Installation
------------

1.  Clone the repository: git clone
    https://github.com/dankends/morningstar-etfs-vs-mutual-funds.git cd
    morningstar-etfs-vs-mutual-funds

2.  Install dependencies: pip install -r requirements.txt \#\# Datasets

The datasets are located in the `data/` directory: - `etfs.csv`: European ETFs
dataset. - `mutual_funds.csv`: European Mutual Funds dataset.

Notebooks
---------

Use `analysis.ipynb` to reproduce the results.

Results
-------

Key findings: 1. ETFs generally exhibit lower volatility compared to Mutual
Funds. 2. ETFs offer better risk-adjusted returns as indicated by Sharpe Ratios.
