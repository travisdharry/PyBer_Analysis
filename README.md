# PyBer_Analysis
Rideshare Analysis Project for UT Austin Data Analysis Bootcamp

## Project Overview
PyBer, a rideshare company, has requested we analyze ride data based on several city types (Urban, Suburban, and Rural) in order to determine the differences in the company’s ride counts, fares, and drivers from area to area. We created a summary DataFrame to display the total rides, total drivers, and total fares for each area, as well as the average fares per ride and average fares per driver. Then we analyzed the company’s total weekly fares over time, breaking them down once again by city type.

## Resources
- Data Sources: city_data.csv, ride_data.csv
- Software: Python 3.7.6, Jupyter Notebook

## Results
The summary of PyBer’s ride data shows several clear trends:
![PyBer Summary](Analysis/pyber_summary.png)

### Total Rides
The total number of rides given in each area shows that urban areas make up the greatest part of the company’s business, while rural areas only make a very small portion.

### Total Drivers
The total number of drivers in urban areas is vastly disproportionate to the amount of business being done there. There are five times as many drivers as in suburban areas, and thirty times as many as in rural areas. There are more drivers in urban areas than there are rides being given.

### Total Fares
The total fares taken in urban areas were much higher than those in rural areas, and more than double what they were in suburban areas. This indicates that the bulk of the company’s business is coming from urban areas, with a large portion coming from suburban areas. Rural business makes up only a small percentage of the company’s total fares. Even though fares per ride were lower in urban cities, there are a larger number of rides being given there, enough to offset the lower average fares.

### Average Fare per Ride
The average fare per ride in urban areas was lower than in suburban areas, which was lower in turn than rural areas. This can be explained by the fact that urban areas are more dense, with shorter distances likely being traveled per ride, and therefore lower fares per ride.

### Average Fare per Driver
The average fares per driver were significantly lower in urban areas, only $16.57 compared to the $55.49 average of their rural counterparts. This is due to a combination of factors. First, the average fare per ride is lower in urban areas, perhaps because shorter distances are traveled. Second, there are a disproportionate number of drivers in urban areas. In fact, there are more drivers than there are rides given.

### Weekly Fares Over Time
The trend of weekly fares grouped by city type shows only minor fluctuations over time. Urban areas consistently bring in the highest total fares, while rural areas consistently bring in the lowest total fares. This indicates that time of year is not as much of a factor in total fares as location.
![Weekly Fares by City Type](Analysis/weeklyFares_by_cityType.png)


## Summary 
In order to even out the disparities between business in the different city types, we offer three recommendations:
First, reduce the number of urban drivers. There are more drivers than there are rides being given, and the idle drivers are negatively impacting average fares per driver. Second, increase the number of drivers in suburban or rural areas. These additional drivers could be better utilized in locations where the average fare per ride is higher. There, they may be able to earn the company more money.
Third, an increase in fares in urban areas would raise the average fare per ride to a level that is more in line with that of rural and suburban areas. As long as this rate increase does not drive down demand it will earn the company more money and increase average fares per driver.
