# Stock Prices ETL

## Objective
This project aims to collect stock data such as open and close prices, volume and date via API from Alpha Vantage website.
The data is stored into a table in a SQL Server database and is used to some basic data analysis, in order to show how one can integrate different tools to transform third-party data into actionable information.

## Structure
The "code" folder contains two jupyter notebooks used to develop the pipeline.
The first one focus on collecting and storing the data in SQL Server and the second one loads the data for transformation and graph creation.

The "figs" folder contains the produced figures in "02 Data Analysis.ipynb" in PNG format.

## Tools
- Jupyter notebooks,
- Python,
- SQL Server,
- Alpha Vantage API.
