# PyBer Analysis
## Overview
We were tasked with summarizing our previous finding and presenting them in a simpler format and showing how fares changed week to week for each city type. To do this I first created a summary data frame of the previous findings. For the week to week graph I stared by sorting and grouping the data by date and creating a new dataframe, locating the desired data, then applying a resample to total the fares in weekly bins.

## Results
The summary dataframe show the major differences in rides, drivers, and fares in the city types. The major difference between the data is the market size of each city type. Rural having the least amount of rides and drivers, and lowest total fare shows but having the highest average fare per ride and driver. Suburban is the middle in all the categories and Urban is the highest. Another difference between the city types is the ratio of drivers to rides. In Rural and Suburban there were more rides than drivers while Urban had more drivers than rides. All this can be seen in the table below. 

Table 1: Summary DateFrame

![summary_dataframe](https://user-images.githubusercontent.com/57120024/160017685-81fac91b-373b-4a58-9413-952976f3f854.PNG)

The week by week graph of fare total for each city type shows that the total are pretty consistent. 

![PyBer_fare_summary](https://user-images.githubusercontent.com/57120024/160017482-7e1a7bf4-a475-4707-b3fe-7d80223b75ff.png)
Figure 1: Total Fare by City Type

## Summary
Three recommendations I would make based on my finding are:
  - Incentivize people signing up to become drivers
      - This will help to give more availability especially for rural and suburban rides
  - Provide riders, mainly rural and suburban, discount codes to bring down their average fare cost and increase ride count 
  - Increase advertising to bring in more riders
      - the lower average fare per Driver in urban cities means driver will need to take more ride to make the same money are suburban and rural drivers. 
