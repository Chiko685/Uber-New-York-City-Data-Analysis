## Uber New York City Data Analysis

This project conducts an in-depth Exploratory Data Analysis (EDA) of Uber trip data in New York City. The primary objective is to decode urban mobility patterns, temporal trends, and the spatial distribution of Uber pickups across the metropolitan area.

## 📊 Project Objectives
This analysis was developed to address several key questions regarding transportation behavior in New York:

a. Monthly Trends: Identifying months with the peak volume of trips.

b. Rush Hour Analysis: Determining daily peak hours and "rush hour" patterns.

c. Base Performance: Analyzing activity levels across various Uber dispatching base numbers.

d. Spatial Analysis: Identifying pickup hotspots using geographic coordinates (Latitude/Longitude).

e. Pairwise Correlation: Correlating multiple variables to gain granular insights into urban congestion patterns.

## 🛠️ Tech Stack

a. Language: Python

b. Libraries:

- Pandas & NumPy: For large-scale data manipulation and cleaning.
- Seaborn & Matplotlib: For static statistical visualizations and heatmaps.
- Plotly: For interactive temporal trends and mapping.

## 📁 Dataset

The project utilizes several raw data sources, including:

- Uber trip data from January to June 2015.
- Monthly datasets for 2014 (covering April through September).
- Comparative data from other For-Hire Vehicle (FHV) service providers.

## 💻 Code Examples

Below are key snippets from the analysis illustrating the data processing and visualization pipeline:

1. Temporal Pre-processing

Converting string-based timestamps into datetime objects to extract granular time features:


<img width="697" height="302" alt="Screenshot 2026-02-02 at 13 59 10" src="https://github.com/user-attachments/assets/7fc3dd66-df7c-4d10-81f8-4e4c9a839257" />


2. Rush Hour Analysis (Heatmap)

Generating a pivot table to visualize trip density by day and hour:

<img width="697" height="266" alt="Screenshot 2026-02-02 at 13 59 34" src="https://github.com/user-attachments/assets/cf3630d1-db00-47f9-9fa9-797f85de2be5" />

3. Base Activity Analysis
   
Evaluating Uber base performance using interactive boxplots:

<img width="697" height="235" alt="Screenshot 2026-02-02 at 14 00 05" src="https://github.com/user-attachments/assets/cba69015-b693-4fc8-9ae8-960289fc2872" />

## 🚀 Getting Started

Environment Setup: Ensure Python and Jupyter Notebook are installed.

Install Dependencies:

- pip install pandas numpy seaborn matplotlib plotly
- Data Configuration: Ensure the dataset folder structure matches the paths specified in the Uber.ipynb notebook.

Execute: Run the notebook cells sequentially to reproduce the analysis and visualizations.

This project is part of a Data Analyst portfolio, utilizing open-source data from the New York City Taxi and Limousine Commission (TLC).

