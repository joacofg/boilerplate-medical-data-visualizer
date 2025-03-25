# Medical Data Visualizer

A Python project that analyzes and visualizes medical examination data using pandas, seaborn, and matplotlib.

## Description

This project visualizes and makes calculations from medical examination data. The dataset contains information about:
- Body measurements (height, weight, etc.)
- Blood test results
- Lifestyle choices
- Cardiac health indicators

## Features

- BMI calculation and overweight classification
- Blood marker normalization (cholesterol, glucose)
- Categorical visualization of health factors
- Correlation heatmap of all variables

## Requirements

- Python 3.x
- pandas
- seaborn
- matplotlib
- numpy

## Installation

```bash
git clone https://github.com/joacofg/medical-data-visualizer.git
cd medical-data-visualizer
pip install -r requirements.txt
```

## Usage

```bash
python main.py
```

This will generate two visualization files:
- `catplot.png`: Shows the distribution of health factors
- `heatmap.png`: Displays correlations between variables
