# Aviation Facility Sampling and Inference

## Research Goal

Evaluate alternative sampling strategies for aviation facility records in the continental United States and frame inferential questions about elevation differences across facility types.

## Data

- Aviation facilities dataset with state, acreage, elevation, and facility-type attributes
- Filtered subset limited to continental U.S. records with non-missing acreage and elevation values

The full source table is not included in this portfolio folder. The project README documents the fields used so the analysis can be understood without exposing or redistributing the original dataset.

### Data Schema

| Field | Role in Analysis |
| --- | --- |
| `STATE_CODE` | Filters records to the continental United States |
| `SITE_TYPE_CODE` | Stratification variable for facility-type sampling |
| `ACREAGE` | Numeric variable used for quartile-based filtering |
| `ELEV` | Elevation variable used for filtering and inferential comparison |

## Methods

- Data cleaning and filtering
- Simple random sampling
- Stratified sampling by facility type
- Quartile-based thresholding
- Hypothesis formulation for mean comparison

## Tools

- ArcGIS Pro
- R
- R Markdown
- `dplyr`

## Main Results

- Quartile-based filtered subset size: `5232`
- Stratified sample size: `80`
- Balanced sample counts by facility type: `20` observations per category in the published report
- The analysis argues for stratified sampling when category representation matters across heterogeneous facility types.

## Skills

- Data filtering
- Reproducible sampling
- Stratified design
- Comparative methodology
- Inferential framing

## Files

- [Source R Markdown](code/aviation_sampling_and_inference.Rmd)
- [HTML report](reports/aviation_sampling_and_inference.html)
