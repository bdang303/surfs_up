# Surfs Up Analysis

## Overview of the Project
In support of opening a new surf & ice cream shop in a particular location, the objective was to gather stats on weather data during 2 different time periods within the year. As weather data is a highly important factor in determining whether or not opening up this shop would be appropriate, we'll use insights from available data to validate this decision. Using a python script in addition to pandas methods combined with SQL Alchemy, we can retrieve summary statistics of a location based on a SQL lite fikle. 

## Results
Based on the summary statistics retrieved from the script, the following were key insights based on the two months of data observed (June & December)

- On average, temperatures in June tend to be slightly warmer (~74.9 degrees) compared to December temperatures (~71.0 degrees)
- Peak temperatures that were recorded during these two months were fairly close in the range of 83-85 degrees
- Despite the similar peaks, December timeframe recorded a low of 53 degrees, which is 9 degrees colder than lowest temperature recorded in June.

### June Weather Stats
![June Stats](https://github.com/bdang303/surfs_up/blob/main/JuneWeather.png)

### June Weather Stats
![December Stats](https://github.com/bdang303/surfs_up/blob/main/December%20Weather.png)

## Summary
In conclusion, if one were to make a decision to open up a Surf & Ice Cream shop in Hawaii, both June & December months have on average fairly warm weather. Of course the variance between the two months are reflected in the data, one could feel confident that weather may not have a significant impact on business. 

### Suggested Additional Queries

- Determine wind speeds & percipitation during these months
- If possible, determining on average how long temperatures stay at or around the average on a given day. This may be useful details in determining opening & closing hours of the shop 
