# Ride_Sharing_Analysis

## Overview of Project
The project studies the data retrieved from a ride sharing app based on city types.

### Purpose

**Analytical:** The project analyzes the ride sharing data from 120[^1] different cities. It aims at understanding the corelation betweem the average fare and the city type, as well as what other factors affect this dependency.

[^1]: `len(city_data_df["city"].unique())`

**Technical:** The project employs matplotlib library within python along with pandas, to visually represent the relation between the drivers, fares and city types.

## Results

Of the 120 cities, 66 are Urban, 36 Suburban and 18 Rural[^2]. This model is reflective of most settlements acorss the world rural cities, in general, are fewer than their counterparts. 

[^2]: `city_data_df["type"].value_counts()`



![Old Math percent results](/Resources/PyBer_fare_summary.png)



<p align="center">
<img src="/Resources/PyBer_fare_summary.png" width="80%" height="60%">
</p>

New dataset results:
<p align="center">
<img src="/Resources/THS_new.png" width="80%" height="60%">
</p>



## Summary

3 business recommendations to the CE for addressing any disparities among city types
