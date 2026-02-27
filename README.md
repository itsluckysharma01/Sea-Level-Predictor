# Sea Level Predictor

## Overview

A data analysis and visualization project that examines global sea level rise from 1880 to 2013 using EPA data, and predicts future trends through 2050.

## Dataset

- **Source**: EPA Sea Level Data
- **File**: `epa-sea-level.csv`
- **Coverage**: 1880-2013 (134 data points)
- **Measurements**: CSIRO Adjusted Sea Level with error bounds

## Key Findings

- Total sea level rise: **8.98 inches** (1880-2013)
- Average annual change: **0.0675 inches/year**
- Strong linear correlation (R² = 0.97)
- **Acceleration detected**: Recent period (1990-2013) shows nearly 3x faster rise rate compared to early period (1880-1950)

## Features

- Statistical analysis of historical sea level data
- Multiple visualizations:
  - Time series with error bounds
  - Linear regression analysis
  - Distribution of annual changes
  - Period-by-period acceleration comparison
  - Future predictions to 2050

## Technologies

- Python
- Pandas (data manipulation)
- Matplotlib & Seaborn (visualization)
- NumPy (numerical operations)
- SciPy (statistical analysis)

## Files

- `main.ipynb` - Main analysis notebook with all visualizations
- `sea_level_predictor.py` - Core prediction functions
- `epa-sea-level.csv` - Raw data
- `test_module.py` - Unit tests

## Usage

Run the Jupyter notebook `main.ipynb` to see the complete analysis and visualizations.

## Project

This is a FreeCodeCamp Data Analysis certification project.
