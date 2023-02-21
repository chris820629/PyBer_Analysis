# PyBer_Analysis
This project focused on the application of Pandas, NumPy, and Matplotlib libraries, and how I leveraged their useful functions for performing efficient data analytics and data visualization.

## Table of Contents

- [Overview and Objective of Project](#overview-and-Objective-of-project)
  - [Resources](#resources)
- [Experimental and Analysis Results](#experimental-and-analysis-results)
  - [Discovery](#Discovery)
  - [Analysis Plots](#Analysis-Plots)
- [Summary and Next Step](#summary)
- [References](#references)

## Overview and Objective of Project:
This study serves the purpose of finding the trend of the rideshare trip data with 4 months timeframe in 2019. By using the interactive computational environment, Jupyter Notebook and integrating useful modules, functions, and data structures, I performed an analysis and visualization for each city type more efficiently. Some popular Python libraries, especially Pandas, NumPy, Statistics and Matplotlib were leveraged to generate multiple graphs then summarized the discoveries into a written report with suggestions to further support decision-makers at this ridesharing company.
### Resources
- Data Source: city_data.csv, ride_data.csv
- Source Code: Rideshare Revenue Analysis.ipynb, Seasonality_Analysis_preliminary_EDA.ipynb, Seasonality_to_Revenue.ipynb
- Output File: png files
- Software: [Matplotlib 3.5](https://matplotlib.org/3.6.0/users/release_notes.html), [conda 22.9.0](https://github.com/conda/conda/releases), [Python 3.9.12](https://docs.python.org/release/3.9.12/), [Visual Studio Code 1.71.1](https://code.visualstudio.com/updates/v1_71), or their newer releases
## Experimental and Analysis Results:
### Discovery
 - Urban total fare is the highest among other types of city.
 - There seems to be uptick of fare close to end of March timeframe
 - Driver count variance is the highest in the urban citie. 
 - The mean of driver count in urban cities is roughly 7 times more than the rural cities
 - The ride fare data shows that each ride fare is the highest in the rural cities but not significantly higher than other types of cities
 - Urban revenue accounts almost 2/3 of the total revenue
 - Since average $/ride is lower in urban cities, drivers need to get more rides to have the same amount of daily revenue

### Analysis Plots
<img src="https://github.com/chris820629/PyBer_Analysis/blob/main/Images/PyBer_fare_summary.png" width="600">
**Total Fare from Jan to Apr 2019 in different types of city**
<img src="https://github.com/chris820629/PyBer_Analysis/blob/main/Images/Fig4.png" width="600" height="350">
**Driver Count Data **
<img src="https://github.com/chris820629/PyBer_Analysis/blob/main/Images/Fig3.png" width="600" height="350">
**Ride Fare Data **
<img src="https://github.com/chris820629/PyBer_Analysis/blob/main/Images/Revenue_by_City_Type.png" width="300" height="300">
**Total Revenue by City Type**
<img src="https://github.com/chris820629/PyBer_Analysis/blob/main/Images/Average_Fare_vs_Total_Rides_City.png" width="800" > 
**Correlation Between Average Fare vs. Total Number of Rides vs. Drive Count Per City vs. City Type**


## Summary and Next Step:
- Rural cities seem to require effort to increase number of rides, one could be reducing the fare since rural ride fare shows the highest $/share. We could target unlikely to churn customers in urban areas with coupon codes to regain more customers.
- Suburban cities seem to be 30% of the revenue, it is critical to focus on the needs of suburban rides to reduce solely relying on urban ride revenue
- Urban cities already has the highest revenue among others but it requires high demand and supply of drivers to maintain the high revenue. We may need to look into the current driver churn rate to maintain our driver supply. 
- In terms of seasonality, summer time has the highest riders, which may due to the better weather. We could either use ML to discover hidden features that vary from seasonality or provide more incentives in low season timeframe. 


## References
[Pandas User Guide](https://pandas.pydata.org/pandas-docs/stable/user_guide/index.html#user-guide)\
[Matplotlib Stable Release](https://matplotlib.org/3.6.0/users/release_notes.html)\

