# Example datasets for EFI-NEON forecasting challenge to develop Python workflows

These datasets are generated using the R template provided by Freya Olsson as part of the EFI-NEON forecasting challenge at GLEON 2022.

The code used to generate these templates can be found in the GLEON_forecast_challenge.Rmd file in this folder.

Here is a brief guide to the files:

lake_sites.csv - metadata about the 7 lakes that are part of NEON and are used in the forecast challenge

targets.csv - historical observed water temperature, dissolved oxygen, and chl-a data for the 7 NEON lakes

noaa_past_mean.csv - a historical stacked forecast product, where the one-day-ahead forecast for each day's NOAA weather forecast is stacked to create a historical weather timeseries for the 7 NEON lake sites; this data file includes the MEAN of each one-day-ahead ensemble forecast for each weather variable

noaa_future_daily.csv - a single 35 day, 31-member ensemble weather forecast from NOAA aggregated from an hourly to a daily timestep