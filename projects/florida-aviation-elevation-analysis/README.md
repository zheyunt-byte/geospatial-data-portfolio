# Florida Aviation Elevation Analysis

## Research Goal

Assess the elevation distribution of aviation facilities in Florida and compare the geographic mean center with an elevation-weighted mean center for airport locations.

## Data

- Aviation facilities dataset with latitude, longitude, state code, site type, and elevation attributes
- Florida subset extracted from the larger facilities table

The full source table is not included in this portfolio folder. The project documents the analytical schema and preserves the cleaned analysis code and report output.

### Data Schema

| Field | Role in Analysis |
| --- | --- |
| `STATE_CODE` | Filters records to Florida |
| `SITE_TYPE_CODE` | Selects airport records for spatial center mapping |
| `LAT_DECIMAL` | Latitude coordinate for mapping |
| `LONG_DECIMAL` | Longitude coordinate for mapping |
| `ELEV` | Elevation attribute used for descriptive statistics and weighted mean center calculation |

## Methods

- Descriptive statistics for facility elevation
- Distribution review with a boxplot
- State-level spatial filtering
- Mean center and weighted mean center calculation for airport locations

## Tools

- ArcGIS Pro
- R
- R Markdown
- Base plotting

## Main Results

- Mean elevation: `69.1 m`
- Median elevation: `55.0 m`
- Elevation range: `0.0 m` to `709.0 m`
- Interquartile range: `78.6 m`
- Standard deviation: `64.2 m`
- The median was identified as the more robust central tendency measure because of visible high-end outliers.

## Skills

- Spatial subsetting
- Descriptive statistics
- Outlier interpretation
- Coordinate visualization
- Weighted spatial center analysis

## Files

- [Source R Markdown](code/florida_aviation_elevation_analysis.Rmd)
- [HTML report](reports/florida_aviation_elevation_analysis.html)
