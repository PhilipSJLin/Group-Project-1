Project Title: A Whirlwind Year, Inflation Trends and Impacts
----------------------------------------------------------------------
Team Members: Anthony Parry, Colven Benjamin, Priya Jain, Philip Lin
----------------------------------------------------------------------

Project Summary: As a team, we wanted to:
-Evaluate the impact of inflation on unemployment rates, <br />
-Analyze fed funds rates in relation to GDP in the US. <br />
-Analyze the last 20 years to capture the economic downturn of 2008 due to the housing market crash as well as more specifically the last 24 months to analyze the impact of the pandemic.

----------------------------------------------------------------------
Links To Repository and Powerpoint Presentation

Repository Link
https://github.com/PhilipSJLin/Group-Project-1

Powerpoint Google Doc Link
https://docs.google.com/presentation/d/1rFRXyHEoDGeSDQ36eKq1BJsqsuLDgUItYZ9vga9daKc/edit?usp=sharing

----------------------------------------------------------------------
How To Run Guide

Packages Imported

Install Fred API library
!pip install fredapi

Import Fred API
from fredapi.version import version as __version__
from fredapi.fred import Fred

Import the Fred and BLS API key
from api_keys import fred_api_key, BLS_key

Install pandas-datareader library
!pip install pandas-datareader

Install yfinance library 
!pip install yfinance

Notebooks, CSVs

Run For Graphs On Slides 9, 12-15, 20 "FRED FFR GDP UNRATE CPI Combined.ipynb"

Run For Graph On Slides 17 "FRED FFR CPI 24 Month Scatter.ipynb"

Run For Graph On Slide 18-19 "BLS CPI UNRATE 24 Month Scatter.ipynb" using "CPI.csv" and "unemployment.csv"

----------------------------------------------------------------------

List of Data Sources Consulted 

BLS API (Inflation/CPI, Unemployment)
BLS CSV (Inflation/CPI, Unemployment Data for last 24 months)
FRED API (Interest Rates, GDP, Inflation/CPI, Unemployment)
BEA, BLS, FRED Sites (Key Economic Definitions)

Acronymns

BLS: Bureau of Labor Statistics
FRED: Federal Reserve Economic Data
BEA: Bureau of Economic Analysis


