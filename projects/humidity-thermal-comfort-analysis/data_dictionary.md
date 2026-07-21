# Data Dictionary

## Hourly Weather Observations

Source file: [hourly_weather_observations_2013.csv](data/hourly_weather_observations_2013.csv)

| Field | Description |
| --- | --- |
| `Year` | Observation year |
| `DOY` | Day of year |
| `Hour` | Observation time |
| `Ta (C)` | Air temperature in degrees Celsius |
| `Ts (C)` | Surface temperature in degrees Celsius |
| `RH (%)` | Relative humidity percentage |
| `wind_speed (ms-1)` | Wind speed in meters per second |
| `wind_dir (Deg)` | Wind direction in degrees |
| `precip (mm)` | Precipitation in millimeters |

## Daily Weather Observations

Source file: [daily_weather_observations_2013.csv](data/daily_weather_observations_2013.csv)

| Field | Description |
| --- | --- |
| `DOY` | Day of year |
| `Ta (C)` | Daily mean air temperature in degrees Celsius |
| `Tmax (C)` | Daily maximum air temperature in degrees Celsius |
| `RH (%)` | Daily relative humidity percentage |
| `wind_speed (ms-1)` | Daily wind speed in meters per second |
| `wind_dir (Deg)` | Daily wind direction in degrees |
| `precip (mm)` | Daily precipitation in millimeters |

## Derived Variables

| Variable | Description |
| --- | --- |
| Saturation vapour pressure | Moisture capacity of air at a given temperature |
| Vapour pressure | Actual atmospheric moisture pressure estimated from relative humidity |
| Vapour pressure deficit | Difference between saturation vapour pressure and actual vapour pressure |
| Dewpoint temperature | Temperature at which air reaches saturation |
| Lifting condensation level | Estimated cloud-base height from temperature and dewpoint spread |
| Humidex | Thermal comfort indicator combining air temperature and humidity |
