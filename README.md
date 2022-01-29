# Ride Sharing Analysis

## Overview of Project
The project studies the data retrieved from a ride sharing app based on city types from 2019.

### Purpose

**Analytical:** The project analyzes the ride sharing data from 120[^1] different cities. It aims at understanding the corelation betweem the average fare and the city type, as well as what other factors affect this dependency.

[^1]: `len(city_data_df["city"].unique())`

**Technical:** The project employs matplotlib library within python along with pandas, to visually represent the relation between the drivers, fares and city types.

## Results

Of the 120 cities, 66 are Urban, 36 Suburban and 18 Rural[^2]. This model is reflective of most settlements acorss the world rural cities, in general, are fewer than their counterparts. The following table displays the summary of the data over 4 months in the year 2019. 

[^2]: `city_data_df["type"].value_counts()`

<p align="center">
<img src="/Resources/PyBer_summary_table.png" width="80%" height="60%">
</p>

As can be seen in the table above, the difference in numbers of the types of cities also trickles down into the number of drivers across and fares accumulated across each city type. 

However, the per ride fare is lowest in Urban cities and highest in rural cities, this clearly indicates that the number of Urban cities being more in number in the dataset has not skewed the data. 

Taking a look at just the amount of fare earned, Urban cities seem surpass Suburban and Rural cities by milestone (see chart below):

![Pyber Fare Summary](/Resources/PyBer_fare_summary.png)

By one look, the above chart makes Urban cities look more profitable/costly, however the chart doesn't truly reflect how much each ride costs. It is only upon looking at the bubble chart that one can pick up true reflection of cost of rides. The following chart reflects the Average Fare in the 3 different city types along with the number of rides taken and the drivers available in those city types

![PyBer Ride Sharing Data](/analysis/CityTypeData_report.png)

#### Conclusion

From the chart above one can deduce:
1. Urban cities have more number of rides compared to Rural and Suburban
2. Urban cities have the highest number of drivers 
3. Rural cities have the highest fares
4. Urban cities have the lowest fares

This makes sense as urban cities are more populated, so by shear numbers, more people need transportation hence the higher number of rides. To be able to cater to the demand, more drivers are required, and hence the higher number of drivers.

## Summary

Following table outlines an important ratio that dictates how the fares rise and fall, the lower the ratio, the lower the fares for the clients and vice vera

| City Type | Ratio (Rides : Drivers) |
| --- | --- |
| Urban | 0.7:1 |
| Suburban | 1.3:1 |
| Rural | 1.6:1 |

1. As can be seen, rural cities have the lowest rides : drivers ratio, with every driver being responsible for 1.6 rides, whereas urban cities almost have a 1:1 ratio with one driver available per ride. Although the rural city model might be profitable the company/drivers in terms of higher average fare, it isn't lucrative to the general population (the clientele of PyBer ), therefore the company should look into ***hiring more drivers for rural areas*** to bring the cost per ride

2. 
