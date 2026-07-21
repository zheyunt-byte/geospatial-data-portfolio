# Humidity and Thermal Comfort Analysis

## Research Goal

Analyze short-interval and daily weather observations to derive atmospheric moisture metrics and thermal comfort indicators, then compare their temporal variation across multiple dates.

## Data

- [Hourly observations](data/hourly_weather_observations_2013.csv)
- [Daily observations](data/daily_weather_observations_2013.csv)
- [Data dictionary](data_dictionary.md)

The hourly file supports diurnal analysis of air temperature, surface temperature, and relative humidity. The daily file supports derived comfort metrics such as humidex.

### Sample Raw Data

Hourly observations:

```csv
Year,DOY,Hour,Ta (C),Ts (C),RH (%),wind_speed (ms-1),wind_dir (Deg),precip (mm)
2013,1,0:30,-1.24,-1.614355226,75.9,6.6,256.7,0
2013,1,1:00,-1.4,-1.990294913,72.5,6.3,281.8,0
2013,1,1:30,-1.81,-2.547567717,73.8,6.1,262,0
```

Daily observations:

```csv
DOY,Ta (C),Tmax (C),RH (%),wind_speed (ms-1),wind_dir (Deg),precip (mm)
1,-5.73,-4.00,69.63,4.18,254.28,0
2,-5.35,-1.00,80.17,4.17,254.59,0
3,-3.83,0.00,87.62,3.81,242.97,0
```

## Methods

- Saturation vapour pressure calculation
- Vapour pressure and vapour pressure deficit derivation
- Dewpoint temperature estimation
- Lifting condensation level calculation
- Humidex-based comfort interpretation

## Tools

- Python
- Jupyter Notebook
- CSV-based tabular analysis

## Main Results

- Project materials document a workflow for deriving multiple atmospheric moisture indicators from observational data.
- The included archived report and notebook source material preserve the analysis workflow and outputs that were available in the downloaded project set.

## Skills

- Environmental data analysis
- Time-series feature engineering
- Scientific computing workflow design
- Thermal comfort interpretation

## Files

- [Notebook source](notebooks/humidity_thermal_comfort_analysis.ipynb)
- [Data dictionary](data_dictionary.md)
- [Archived report](reports/humidity_thermal_comfort_report.pdf)
