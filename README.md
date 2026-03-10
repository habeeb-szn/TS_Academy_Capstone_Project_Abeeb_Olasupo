# TS_Academy_Capstone_Project_Abeeb_Olasupo
TS Academy Track 3 | Personal Repository A time series forecasting project on Nigerian household food basket prices and Food CPI, using SARIMAX, GARCH, and macroeconomic drivers.

# Project Overview
This project builds a data-driven forecasting system for two critical indicators of Nigerian food affordability:
- Basket Cost — the weighted monthly cost of a standardised household food basket comprising 14 essential commodities
- Food CPI — Nigeria's official Consumer Price Index for food, published by the National Bureau of Statistics (NBS)

Using monthly data spanning January 2017 to January 2026, the project investigates how macroeconomic shocks — particularly the June 2023 fuel subsidy removal and naira unification — permanently altered the structure and volatility of Nigerian food prices.

# Objectives
- Decompose Nigerian food price dynamics into trend, seasonal, and structural shock components
- Quantify the transmission of fuel price and exchange rate movements into food costs
- Build SARIMAX models incorporating macroeconomic exogenous regressors and structural break dummies
- Model time-varying forecast uncertainty using GARCH(1,1) with Student-t errors
- Produce a 6-month forward forecast (November 2025 – April 2026) for both targets
