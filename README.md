# U.S. Electricity Price Forecasting

**ECON 415 | Economic Forecasting | Spring 2026**

**Contributors:** Jack Wilke and Donnell Young

## Project Overview

This repository contains the final research project completed by Jack Wilke and Donnell Young for ECON 415: Economic Forecasting. Throughout the semester, we analyzed historical U.S. electricity prices and progressively implemented different time-series forecasting methods in R.

The project examines monthly U.S. electricity prices from November 1978 through January 2026, applying STL decomposition, exponential smoothing (ETS), ARIMA, and ARIMAX models. We evaluated forecast performance using rolling-window time-series cross-validation across 1-, 3-, 6-, and 12-month horizons.

The repository includes the complete R Markdown analysis, the historical price dataset, and a PDF report containing our research, visualizations, and forecasting results.

## Introduction

U.S. electricity prices have risen sharply in recent years, raising questions about the underlying drivers of electricity inflation and the ability of existing infrastructure to accommodate accelerating energy demand.

Our research examines three potential catalysts contributing to this trend:

1. **Russia–Ukraine War (2022):** The global energy supply shock, particularly in natural gas markets, and its potential transmission into electricity prices.
2. **AI and Data Center Demand:** Rapid growth in electricity consumption associated with AI infrastructure, placing additional pressure on electricity generation and grid capacity.
3. **Strait of Hormuz Disruptions:** Geopolitical risks to global energy supply and the potential indirect effects of higher energy costs on U.S. electricity prices.

Using historical electricity price data, we apply statistical forecasting techniques to analyze trends, seasonality, and forecast accuracy. The geopolitical and AI-related developments provide economic context for the analysis rather than causal relationships established by the forecasting models.

## Methodology

The semester-long analysis was organized into six stages:

- **Project I:** Exploratory data analysis, moving averages, classical decomposition, and STL decomposition.
- **Project II:** STL forecasting and rolling-window time-series cross-validation.
- **Project III:** Exponential smoothing using ETS(A,A,A) and ETS(M,A,M).
- **Project IV:** ARIMA and ARIMAX model specification, estimation, and diagnostics.
- **Project V:** ARIMAX forecasting and cross-validation across multiple forecast horizons.
- **Project VI:** Forecast comparison, model evaluation, and final conclusions.

Models were evaluated using forecast error metrics, particularly Mean Percentage Error (MPE) and Mean Absolute Percentage Error (MAPE).

## Research Files

- **[Read the Final Research Report](report/U.S.-Electricity_Price_Forecasting_Report.pdf)** — Written analysis, graphs, tables, and forecasting results.
- **[View the R Markdown Analysis](U.S.%20Electricity%20Price%20Forecasting.Rmd)** — Complete R code and statistical modeling.
- **[Historical Electricity Price Data](data/APU000072610.csv)** — Monthly U.S. electricity price dataset.

## Tools & Techniques

**Programming:** R, R Markdown

**Libraries:** `forecast`, `ggplot2`, `zoo`, `urca`, `knitr`, `kableExtra`

**Methods:** STL Decomposition, Exponential Smoothing, ARIMA, ARIMAX, Time-Series Cross-Validation, Forecast Error Analysis
