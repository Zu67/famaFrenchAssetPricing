# Fama French asset pricing

This repository has no notebook and no scraper. On 2021-07-11 Zu67 uploaded `Fama French 3-Factor Asset Pricing.ipynb` ("Add files via upload", recorded as 19:03 -0500), replaced it at 19:13 ("Update Fama French 3-Factor Asset Pricing.ipynb"), and deleted it at 19:16.

The uploaded file is a nine-cell notebook. Separate cells import `getFamaFrenchFactors` as `gff` and `DataReader`, and set `end` to `datetime.datetime.today()`. The saved output on the price cell is a `RemoteDataError` from Yahoo Finance for ticker M. The merge cell's saved output is `NameError: name 'macyDataF' is not defined`. The price cell assigns `macyData` and then calls `macydata` and `macydataF`. The regression cell's saved output is `NameError: name 'datanow' is not defined`. The pip cell's saved output says getFamaFrenchFactors 0.0.5 was already installed under Anaconda Python 3.8.

The update replaced that notebook with a plain-text copy of the price, factor, scatter, and OLS lines. It drops the import cell and the `end = today` line, and it is not notebook JSON.

That text, aside from a trailing blank line, is the only cell in [FamaFrench3FactorModelExpectedReturns](https://github.com/Zu67/FamaFrench3FactorModelExpectedReturns). On 2025-10-25, after the notebook was already gone, a one-line README was added: "Pulls data from famaFrench library for regressions on stock returns."
