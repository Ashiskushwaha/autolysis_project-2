# Data Analysis and Narrative Generator

This script performs data analysis on a CSV dataset, generates visualizations, and creates a narrative summary of the data using a language model. The script can be used for exploring and understanding data in a structured manner.

## Features

- **Data Loading**: Automatically detects file encoding and loads the dataset.
- **Basic Data Analysis**: Generates a summary of the dataset, including descriptive statistics, missing values, and correlations.
- **Data Visualization**: Plots distribution histograms for numeric columns and saves them as PNG images.
- **Narrative Generation**: Sends the analysis summary to an external AI service to generate a detailed narrative.

## Requirements

- Python 3.11 or higher
- Required Python packages:
  - `pandas`
  - `seaborn`
  - `matplotlib`
  - `httpx`
  - `chardet`
  - `python-dotenv`

To install the necessary packages, you can use:

```bash
uv pip install
