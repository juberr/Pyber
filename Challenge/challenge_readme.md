# Fares by City Type

## Overview of the Analysis

Offering insights into how different types of cities use Uber allows the organization to make more informed decisions when it comes to strategic planning. This analysis takes Uber ride and driver data from January until April 2019, and provides a comprehensive view of how Urban, Suburban, and Rural cities use Uber.

## Results

![Summary Dataframe](https://github.com/juberr/Pyber/blob/main/Challenge/analysis/city%20type%20df.png?raw=true)

### Urban Cities

Urban cities had the highest number total fares and drivers. This follows as Urban cities have much higher population densities than Suburban and Rural. A higher population density means more demand for an Uber ride at any given time of day, which leads to more drivers. Urban cities also have the lowest average fares (per driver and per fare). The distance of trips in Urban cities is shorter because of their geographic density. If the trips themselves are shorter, Urban city drivers can complete more trips in a day than Suburban and Rural cities. The combination of these two factors drive the average fare (per driver and fare) down in Urban cities.

### Suburban Cities

Suburban cities lay between Urban and Rural cities in terms of number of total fares, drivers, and average fare prices. The demand for drivers lessens within Suburban cities as both population and geographic density lessens, and car ownership increases. People in Suburban cities are generally more likely to own a car for commuting to work, or just getting around the city.

### Rural Cities

Rural cities have the lowest number of drivers and highest average fare prices. The trends seen in Suburban cities become even stronger in Rural cities. Not only do Rural cities have the lowest population density among the three types of cities presented here, they are also the most geographically spread out. Since one of the determining factors of an Uber fare is how long the ride will be, this will keep prices in Rural cities inherently higher. The combination of a higher average fare, and low population density lead Rural cities to use Uber less. If there are less customers in Rural cities, that leaves little incentive for drivers to "set up shop" in Rural cities.

### Total Fares by City Type Chart

The following line chart demonstrates the results described above in a visual format for total fares.

![Fare summary graph](https://github.com/juberr/Pyber/blob/main/Challenge/analysis/PyBer_fare_summary.png?raw=true)

## Summary

Based on the analysis provided here, there are opportunities for the business to address the gaps seen between the three city types:

* Incentivize use in Rural cities by changing how fare prices are structured to exclude distance (e.g. a flat rate to get anywhere in the city). This can decrease the average fare, and make an Uber ride a more viable option for users.

* Uber can work with Rural and Suburban city municipalities to present themselves as an alternative to installing a public transportation system. Working with a municipality can allow Uber to lower the prices of operating in a Rural city, and incentivize more users within Rural and Suburban cities.

* Offer more stable forms of compensation for Uber drivers within Rural and Suburban cities than a share of the total fare. Rural and Suburban city drivers aren't guaranteed the quantity of rides drivers in Urban cities are. The lack of demand (when compared to Urban cities) for rides means there is far less financial incentive for drivers to "set up shop" in Rural cities and Suburban. Examples of more stable forms of compensation could be: a daily rate for staying within a Suburban/Rural city, or offer to cover a percentage of operating costs (such as car gas and maintenance).

