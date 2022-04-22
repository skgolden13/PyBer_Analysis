# PyBer Analysis

## Project Overview

PyBer has requested a new analysis with a summary DataFrame of the ride-sharing data by city type. Additionally, a multiple-line graph showing the total weekly fares for each city type has been requested for comparison and decision making at PyBer.

All raw data files can be found [here](https://github.com/skgolden13/PyBer_Analysis/tree/main/Resources).</br>
All charts and images can be found [here](https://github.com/skgolden13/PyBer_Analysis/tree/main/analysis).</br>
The jupyter notebook file for the original analysis can be found [here](https://github.com/skgolden13/PyBer_Analysis/blob/main/PyBer.ipynb).</br>
The jupyter notebook file for this analysis can be found [here](https://github.com/skgolden13/PyBer_Analysis/blob/main/PyBer_Challenge.ipynb).</br>

## Analysis Results

The summary data frame (shown in Figure 1) shows multiple differences between urban, suburban, and rural cities:
- Urban cities have the most total rides
- Rural cities have the least total rides
- Urban cities have the most total drivers
- Rural cities have the least total drivers
- Urban cities produce the most total fares
- Rural cities produce the least total fares
- Urban cities have the lowest average fare per ride and per city
- Rural cities have the highest average fare per ride and per city

<p align="center">
  <img width="900" alt="Summary_DF" src="https://github.com/skgolden13/PyBer_Analysis/blob/main/analysis/Summary_DF.PNG"><br/>
  Figure 1: PyBer Summary DataFrame
  <br/>
</p>

The fare summary line plot by week and city type (shown in Figure 2) shows that the difference in total fares in each city type is consistent from January to April 2019. Each city type trends similarly on a week by week basis and the overall difference from Figure 1 is not being driven by any outliers.

<p align="center">
  <img width="900" alt="PyBer_fare_summary" src="https://github.com/skgolden13/PyBer_Analysis/blob/main/analysis/Pyber_fare_summary.png"><br/>
  Figure 2: PyBer Fare Summary by Week and City Type
  <br/>
</p>

## Analysis Summary

Urban cities produce the greatest valie of total fares and have the highest ride volume. It would be worthwhile to invest more in advertising for both the service itself and positions as a driver. More drivers would allow for PyBer to handle an increase in demand while increased usage would drive revenue higher.

Rural cities have the highest average ride fare. This is likely due to an increased distance between locations in rural areas. Increased advertising in rural areas leading to increased demand may be able to lower average ride fares while keeping total fares at a similar or increased rate.

Advertising the higher average fares for rural areas to prospective drivers may be able to increase the number of drivers in rural areas. An increased number of drivers in rural areas may lead to more rides in these locations. To understand the effect of this recommendation, it would be useful to know the average wait time for a ride in rural areas before and after along with the available data for the number of rides.
