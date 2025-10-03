# Project2

## Overview
This project analyzes and cleans a dataset of car information from `2_Cars_Data.csv` using Python and pandas in a Jupyter notebook.

## Data Cleaning Steps
1. **Load the dataset** using pandas.
2. **Inspect the data** for missing values.
3. **Fill missing values:**
	- Numeric columns: filled with the mean of each column.
	- Non-numeric columns: filled with the mode (most frequent value) of each column.
4. **Verify** that all missing values are handled.

## Usage
1. Open `Project2.ipynb` in Jupyter or VS Code.
2. Run the cells step by step:
	- Import libraries
	- Load the dataset
	- View data and shape
	- Check for missing values
	- Clean the data using the provided code
	- Confirm that all missing values are filled

## Requirements
- Python 3.x
- pandas
- numpy

## File Structure
- `2_Cars_Data.csv`: The dataset
- `Project2.ipynb`: Jupyter notebook with code and analysis
- `README.md`: Project documentation