					Worldwide Earthquake Database Analysis

This repository contains Python code for analyzing a worldwide earthquake database. The dataset provides information about significant earthquakes, including their magnitudes, locations, and temporal patterns.

![image](https://github.com/Ngot97/Project-1/assets/150645979/35eb3f19-c4c7-4d21-bf8b-eee9a6813975)

Getting Started

Prerequisites

Make sure you have the following dependencies installed:

	Python 3
	Jupyter Notebook
	Required Python packages (matplotlib, pandas, numpy, hvplot, geoviews, geopandas, scipy, seaborn, folium)

Dataset

The dataset used for this analysis is available on Kaggle. "Global Significant Earthquake Database from 2150BC" 

Download the Worldwide-Earthquake-database.csv file and place it in the "Resources" folder.

Analysis Overview

![pacific-ring-of-fire](https://github.com/Ngot97/Project-1/assets/150645979/814b6be3-06ce-482b-964b-d166ccdd2c1e)

The analysis covers the following aspects:

1. Exploration and Cleaning:
   
	Loading and exploring the dataset.

	Narrowing down the columns for analysis.
	
 	Handling null values.

2. Visualization:
   
	Bar chart of the top 20 countries with the highest earthquake counts.
	
 	Bar chart of the top 20 countries with the highest earthquake intensity (intensity >= 7.5).
	
 	Scatter plot and an interactive map showcasing the distribution of earthquakes based on latitude and longitude.

3. Pattern Analysis:
	
	A heatmap depicting the distribution of earthquake intensity based on latitude and longitude.
	
 	Scatterplot based on earthquake intensity.
	
 	Distribution of earthquakes based on focal depth.
	
	Time series analysis, including trends in earthquake occurrences over time.


5. Magnitude Trends:
	
 	LLinear Regression: EQ_PRIMARY vs. INTENSITY - A scatter plot with a linear regression line exploring the correlation between earthquake magnitude and intensity.
	
 	Linear regression analysis to identify the overall trend in earthquake occurrences. - 

6. Tsunami Occurrence:
   
	A pie chart depicting the percentage of earthquakes that trigger tsunamis.

Results

The analysis provides valuable insights into earthquake patterns, intensity distribution, and trends over time. Explore the generated plots and maps to gain a comprehensive understanding of seismic activity worldwide.


Acknowledgments

Dataset Source: Kaggle - Global Significant Earthquake Database - "https://www.kaggle.com/datasets/mohitkr05/global-significant-earthquake-database-from-2150bc"

Feel free to contribute, report issues, or suggest improvements.
