# Pyber Rideshare Analysis

## Project Overview
Analyze PyBer rideshare data to determine market differences between urban, rural, and suburban markets. In order to make this analysis, extract the following data points from ride share data:

-	Number of drivers in each type of market
-	Number of rides in each market
-	Average fare by market
-	Average fare per driver by market

## Resources

- Data Sources: ride_data.csv and city_data.csv (extracted from PyBer records)
- Software: Python 3.9.4, Jupyter Notebook 6.3.0

## Market Data by City Type

The table below reflects the breakdown of ride data by city type.  Below the table is analysis on what conclusions can be drawn from this data.

<img width="656" alt="PyBer_Summary_Table" src="https://user-images.githubusercontent.com/78807451/120079602-a0bdb200-c082-11eb-9edf-5d0e3df9d5de.png">

This data indicates that PyBer is realizing a majority of company revenue from urban environments at about 63% of total revenue. Suburban and rural come in at 30% and 7% respectively.  The average ride per fare increases in the lesser populated areas by about five or six dollars per ride. However, the average fare by driver shows a significant increase from urban to suburban and again from suburban to rural. The increase in average ride fare is likely due to the length of the ride, since the more urban the area, the more likely points of interest are close by. The increase in average driver fare is attributable to the density of drivers. In the rural areas, a driver averaged 1.6 rides across the four-month sample period. Suburban drivers averaged 1.3 rides and urban drivers only 0.67 rides. This shows that the density of drivers is considerably higher in urban areas. Of course, there are many registered drivers who are not actively taken rides at any given time.

## Market Data by City Type Over Time

This chart illustrates PyBer rideshare data over time and compares the three types of environments.
