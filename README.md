# Unemployment Analysis with Python

## Project Overview

This project analyzes unemployment rate data for Indian states and union territories using Python.

The analysis focuses on:

- Cleaning and preparing unemployment data
- Exploring unemployment trends
- Visualizing unemployment rates
- Investigating the impact of Covid-19
- Comparing urban and rural unemployment
- Identifying potential seasonal patterns
- Developing insights relevant to economic and social policy

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

## Dataset

The dataset contains monthly unemployment observations for Indian states/UTs, including:

- State
- Date
- Area (Urban/Rural)
- Unemployment Rate
- Estimated Employed
- Labour Participation Rate

The available data covers May 2019 to June 2020.

## Key Findings

The analysis found a major increase in unemployment during April-May 2020.

| Period | Mean Unemployment |
|---|---:|
| Pre-Covid | 9.61% |
| April-May 2020 | 24.26% |
| June 2020 | 11.90% |

The average unemployment rate increased by approximately **14.64 percentage points** during April-May 2020 compared with the pre-Covid period.

Both urban and rural observations experienced substantial increases.

## Covid-19 Analysis

April-May 2020 represents the clearest disruption in the unemployment series.

The unemployment rate subsequently declined considerably in June 2020, suggesting partial recovery.

However, this analysis is descriptive and does not establish that Covid-19 alone caused every observed change.

## Seasonality

The dataset contains only approximately one year of observations, so there is not enough historical data to confidently establish recurring annual seasonal patterns.

Additional years of monthly data would be required for robust seasonal analysis.

## Project Structure

```text
unemployment-analysis-python/
│
├── data/
│   └── cleaned_unemployment_data.csv
│
├── notebooks/
│   └── unemployment_analysis.ipynb
│
├── reports/
│   └── unemployment_analysis_report.html
│
├── images/
│   ├── monthly_trend.png
│   ├── urban_rural_covid.png
│   └── largest_covid_changes.png
│
└── README.md
