# Delhi Urban Mobility Analysis 🚇

This project provides an exploratory data analysis (EDA) of the Delhi Metro Network using real-world open data. 

## Project Overview
The goal of this analysis was to clean and visualize the Delhi Metro transit system to better understand station distribution and network density across the National Capital Region (NCR).

## Key Features
* **Data Cleaning**: Handled missing values (NaNs) and standardized station metadata using Pandas.
* **Data Merging**: Performed relational merges across four disparate datasets (routes, trips, stop_times, stops) to create a unified view of the transit network.
* **Visualization**: Created a color-coded geographic map using Seaborn to highlight transit line density.

## Tech Stack
* **Language**: Python
* **Libraries**: Pandas, Seaborn, Matplotlib
* **Environment**: VS Code, Anaconda

## How to Run
1. Ensure you have Python and the required libraries installed.
2. The data is located in the `data/` folder.
3. Open `delhi_metro_analysis.ipynb` in VS Code to view the full analysis.
