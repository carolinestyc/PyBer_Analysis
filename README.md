# PyBer_Analysis
   Challenge 5
## Project Overview
My new boss at PyBer, V. Isualize, has given Omar and I a new assignment. She has asked for a summary DataFrame of the ride-sharing data by city type and a multiple-line graph that shows the total weekly fares for each city type. Using this analysis and summary, the differences by city type are extrapolated and can be used by decision-makers at PyBer. 
### Resources
            Data Sources: city_ride.csv & ride_data.csv
            
            Software: Python 3.9.7 & Jupyter Notebook
## Results
By aggregating and analyzing the provided PyBer ride-share data, the differences in use among city type are clear. As you can see in the summary table below, rural cities have much fewer rides and drivers, therefore collecting fewer money in total fares. As we move into urban cities, ridership goes up 12 times and total fares increase by over 9 times rural cities. This should come as no surprise as population and density are much higher in urban areas compared to rural areas. There is a larger population of both users and available drivers in urban cities and even suburban cities than rural cities to increase ride-share usage and decrease the average fare per ride and driver. Based on geographical patterns of cities, we can also assume rides in urban cities are shorter as the area is much denser than suburban and rural areas; so rides are longer distances as the area is more dispersed. Therefore, costing more money to riders as distance increases and available drivers decrease.
In fact, the data shows that urban cities have almost 5 times the number of drivers as suburban cities and over 30 times as many in rural cities. Additionally, average fares per drivers is only $16.57 in urban cities but $55.49 in rural cities. Although the average fare is much higher in rural cities, ride usage is so low that total fares only amounted to $4,328. 4.5 times less than suburban cities where total fares were $19,356 and 9 times less than urban cities where total fares amounted to $39,854. 

<img width="585" alt="pyber_summary_table" src="https://user-images.githubusercontent.com/96352625/152709569-ac5f11c8-39bf-4bb0-be7f-5ac6c18122f7.png">

In the multiple line graph below, we can see the pattern in fares by city type across the months of January to April 2019. As discussed previously, total fares are lowest in rural cities and highest in urban cities for all 4 months. Interestingly, each city type does not experience the same ridership pattern. Rural communities saw the highest total fare count in early April but suburban cities saw a spike in late February. Urban cities saw highest usage in late February and then again in early March. Although this graph goes week by week, we may see additional patterns if broken up day by day to see what days of the week saw higher usage. 

![pyber_fare_summary](https://user-images.githubusercontent.com/96352625/152709589-12b85480-0140-4d7b-938f-4be1bc9f7451.png)

## Summary
