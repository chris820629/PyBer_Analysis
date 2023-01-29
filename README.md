# PyBer_Analysis
## Overview of the analysis:
 - This study serves the purpose of finding the trend of total fare within the 4 months timeframe in 2019. There are three trendlines indicating the fares vary across different types of cities
## Results:
 - Urban total fare is the highest among other types of city.
 - There seems to be uptick of fare close to end of March timeframe
 - Driver count variance is the highest in the urban citie. 
 - The mean of driver count in urban cities is roughly 7 times more than the rural cities
 - The ride fare data shows that each ride fare is the highest in the rural cities but not significantly higher than other types of cities
 - Urban revenue accounts almost 2/3 of the total revenue
 - Since average $/ride is lower in urban cities, drivers need to get more rides to have the same amount of daily revenue

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
