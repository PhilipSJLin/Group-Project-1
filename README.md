# Group-Project-1
Presentation

Project Title: A Whirlwind Year, Inflation Trends and Impacts

Team Members: Anthony Parry, Colven Benjamin, Priya Jain, Philip Lin

Project Summary
Evaluate the impact of inflation on unemployment rates, fed funds rates in relation to GDP in the US. Analyze the last 20 years to capture the economic downturn of 2008 due to the housing market crash as well as more specifically the last 24 months to analyze the impact of the pandemic.

Link To Presentation (Repo or Google Doc)

Repository Link
https://github.com/PhilipSJLin/Group-Project-1

How To Run Guide (What Packages Imported, Files (1 or 2 notebooks) A User Should Run To Repeat Your Process)

Install Fred API library
!pip install fredapi

Import Fred API
from fredapi.version import version as __version__
from fredapi.fred import Fred

Import the Fred and BLS API key
from api_keys import fred_api_key, BLS_key

Notebooks
FRED FFR GDP UNRATE CPI Combined.ipynb

List of Data Sources Consulted 
BLS API (Inflation/CPI, Unemployment)
BLS CSV (Data for last 24 months)
FRED API (Interest Rates, GDP)
BEA, BLS, FRED Sites (Key Economic Definitions)

Acronymns
BLS: Bureau of Labor Statistics
FRED: Federal Reserve Economic Data
BEA: Bureau of Economic Analysis


