# PyBer_Analysis
## Project Overview
The project requires the analysis of all the rideshare data from January to early May of 2019 in order to create a compelling visualization for the CEO, V. Isualize. The purpose of the project is to understand how the ride-sharing information by city differs, and how that information can be used by V. Isualize and the rest of the Pyber team to make analysis based decisions by looking at city type to compete effectively in the ride sharing market. The analysis will be used to supply three business recommendations to the CEO for addressing any disparities among the city types.

### Resources:
- Data Source: city_data.csv
- Data Source: ride_data.csv
- Sofware: Jupyter Notebook
- Library: Matplotlib.pyplot
- Library: Pandas
- Library: Matplotlib (imported style)
- Language: Python 3.6.7

## Results
### Pyber Summary DataFrame:
![Deliverable1.png](PyBer_Analysis/Analysis/Deliverable1.png)

Based on the PyBer Summary DataFrame above, heavily populated cities have more drivers and a higher ride count. The Urban cities have 1,500 more rides than the Rural cities and 2,327 more drivers. As a result, there is a higher count of fares in areas where there is a more dense population and the average fare per ride decreases by $10 from a Rural area to an Urban area. The average fare per driver also decreases by around $40. The Suburban areas also conduct 1,000 less rides than Urban areas and have 1,915 less drivers.

### Total Fare per City Type:
![PyBer_fare_summary.png](PyBer_Analysis/Analysis/PyBer_fare_summary.png)

The multiple line plot above details the weekly total fares for each city type. The data shows: 
- urban cities generally generate between $2,000 to $2,300
- suburban cities generally generate $900 to $1,200
- rural cities generally generate $170 to $287

By viewing the PyBer data by city type, we see that the average total fare has a similar pattern over various months of the year between January and April with total fares peaking around March.

## Summary
Based on the above results, I would recommend to the CEO of PyBer the following three business suggestions in order to address disparity among city types:

1. Focus recruiting efforts on rural and suburban areas to increase amount of drivers in those areas. Given the high average fare per ride of $34.62 and average fare per driver at $55.49 in the Rural areas, it appears that this type of city is underserviced. I recommend increasing drivers in rural and suburban locations as you may be able to provide more rides while still being a profitable on a per driver basis.
2. Redirecting efforts to increasing the amount of rides in the summertime months. Given the sudden drop in Urban cities after the month of May, it may be worth focusing on advertising rides and analyzing the root cause of the drop to continue to be profitable.
3. Decreasing the number of drivers in Urban cities could prove to be beneficial. The number of rides to number of drivers shows that they are overstaffed. This is also driving the average fare per ride down. In order to maximize profits, it is recommended to repurpose extra drivers to other company apps such as delivery services.
