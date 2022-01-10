# Mod4_Challenge (Using Pandas to compare the risk and returns of portfolios)

This is a python Pandas project that uses a Jupyter Lab notebook called risk_return_analysis.ipynb to analyze the risk and return 
of four portfolios (Soros Fund, Paulson & Co, Berkshire Hathaway, Tiger Global) against each other and the S&P 500. 
The analysis included daily returns, cumulative returns, standard deviations, rolling windows, annualized average returns, 
covariance Sharpe Ratios and betas.

---

## Technologies

This project leverages python 3.7 with the following packages:

* Pandas - to handle financial data analysis 

* Numpy - for analytics

* Jupyter Lab - IDE program

* Path - from pathlib to handle relative paths to data files

* Matplotlib - for plotting graphs of data

* [csv] - import csv to allow for proper reading and writing to csv files

---

## Import Guide

Before running the application first import the following dependencies.

```python
  import pandas as pd
  from pathlib import Path
  %matplotlib inline 
  import numpy as np  
    
```

---

## Usage

To use the risk_return_analysis.ipynb application launch the notebook in Jupyter Lab

The program requires one data file which is imported using date_time format parameters. It contains data on four funds (Soros Fund, Paulson & Co, Berkshire Hathaway, Tiger Global) and the S&P 500:
```
./Resources/whale_navs.csv

```


## Plots
---
Data is plotted using line graphs and box plots


## Contributors

Brought to you by Ann Howell with support from Rice FinTech Bootcamp.

---

## License

MIT
