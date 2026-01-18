# CTA 'L' Ridership Seasonality (2023)

## Overview
A compact analysis of Chicago CTA 'L' ridership seasonality in 2023 using daily station entries.

## Data
- Source: City of Chicago open data (CTA 'L' station entries, daily totals)
- Note: The full CSV is not included in this repo due to file size. See below for download instructions.

## Method
- Aggregate station-level entries into system-wide daily totals
- Compute 7-day rolling mean for smoothing
- Resample to monthly average daily entries for seasonality view
- Compare summer (Jun–Aug) vs winter (Dec–Feb) averages

## Results
- Plots: daily (smoothed) trend and monthly seasonality
- Summary: Summer/Winter ratio printed in notebook output

## How to run
```bash
pip install -r requirements.txt
# open seasonality.ipynb in VSCode and run all cells
