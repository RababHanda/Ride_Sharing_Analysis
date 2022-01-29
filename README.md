# Ride_Sharing_Analysis

## Overview of Project
The project studies the data retrieved from a ride sharing app based on city types from 2019.

### Purpose

**Analytical:** The project analyzes the ride sharing data from 120[^1] different cities. It aims at understanding the corelation betweem the average fare and the city type, as well as what other factors affect this dependency.

[^1]: `len(city_data_df["city"].unique())`

**Technical:** The project employs matplotlib library within python along with pandas, to visually represent the relation between the drivers, fares and city types.

## Results

Of the 120 cities, 66 are Urban, 36 Suburban and 18 Rural[^2]. This model is reflective of most settlements acorss the world rural cities, in general, are fewer than their counterparts. The following table displays the summary of the data over 4 months in the year 2019. 

[^2]: `city_data_df["type"].value_counts()`

![PyBer Summary Table](/Resources/PyBer_summary_table.png)

As can be seen in the table above, the difference in numbers of the types of cities also trickles down into the number of drivers across and fares accumulated across each city type. 

However, the per ride fare is still highest in Urban cities and lowest in rural cities, this clearly indicates that the number of Urban cities being higher in the dataset has not skewed the data. 

The following chart reflects the Average Fare in the 3 different city types along with the number of rides taken and the drivers available in those city types

![PyBer Ride Sharing Data](/analysis/CityTypeData.png)

#### Conclusion

From the chart above one can deduce
1. Urban cities have more number of rides compared to Rural and Suburban
2. Urban cities have the highest number of drivers 
3. Rural cities have the highest fares


 this makes sense as urban cities are more populated, so by shear numbers, more people need transportation hence the higher number of rides 

![Pyber Fare Summary](/Resources/PyBer_fare_summary.png)



![Old Math percent results](/Resources/PyBer_summary_table.png)

<p align="center">
<img src="/Resources/PyBer_summary_table.png" width="80%" height="60%">
</p>

New dataset results:
<p align="center">
<img src="/Resources/THS_new.png" width="80%" height="60%">
</p>



## Summary

3 business recommendations to the CE for addressing any disparities among city types
