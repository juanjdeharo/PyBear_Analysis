# PyBear_Analysis

## Overview of the Analysis
> V. Isualize has asked me to further analyze PyBer data and complete the following tasks in order to analyze average weekly fares by city type over time and possibly use this information for decision-making:

1. Create a summary DataFrame for the ride-sharing data by city type.
2. Create a multiple line graph displaying the average weekly fares by city type over time.
3. Write a report summarizing the findings

## Resources
> Data Source: city_data.csv, ride_data.csv
> Software: Pandas, Jupyter Notebook

## Results:

### PyBer Summary DataFrame
![PyBer Summary DataFrame](https://github.com/juanjdeharo/PyBear_Analysis/blob/main/analysis/PyBer%20Summary%20DataFrame.PNG)
> The PyBer Summary DataFrame gives allows us to make the following inferences about the city types:

- Rural: Rural cities have the least amount of drivers, total rides and total fares. However rural cities have the highest average fare per ride and average fare per driver.
- Suburban: Lies in the middle between rural and urban in terms of total rides, drivers and fares as well as average fares per ride and driver
- Urban: Urban cities have the most drivers and therefore have the most rides and the highest total fares. However drivers in rural cities have the smallest fares per ride as well as in general.

### PyBer Weekly Fare Averages
![PyBer_fare_summary](https://github.com/juanjdeharo/PyBear_Analysis/blob/main/analysis/PyBer_fare_summary.png)
> Based on the multiple line graph, I find no identifiable pattern other than perhaps fluctuating fares around the times of Spring Break. Other than that the only inference I can make is that urban cities have much more total weekly fares than rural cities.

## Summary
> It would appear that total fares and rides vary proportionally with the amount of drivers per city type. If we could assume that there is a demand in rural areas then increasing the amount of drivers in rural areas would increase the total fare, dicreasing disparities. Perhaps suggesting for/reallocating urban and suburban drivers to rural cities could decrease disparieies. Also it would seem that both urban and suburban fares are lower in the winter while rural stay relatively the same, which means we could suggest/reallocate drivers from urban and suburban cities to rural cities on those dates. Or promote to hire more drivers in rural areas in the winter.
