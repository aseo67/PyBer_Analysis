# PyBer_Analysis
Module 5 Challenge Data Analysis File Links
- ![PyBer_Challenge.ipynb](https://github.com/aseo67/PyBer_Analysis/blob/main/PyBer_Challenge.ipynb)
- ![Outputs: PyBer_fare_summary.png & PyBer Summary Table](https://github.com/aseo67/PyBer_Analysis/tree/main/analysis)
- ![Resources folder](https://github.com/aseo67/PyBer_Analysis/tree/main/Resources)

## Overview of PyBer Analysis
PyBer, a large ride-sharing company, is looking to understand the relationship between type of city, number of drivers and riders, and fares from rideshare data, focusing on fare data from January through April 2019 in particular. This analysis and visualizations of results will be used by the company decision makers to help PyBer improve its accessibility and affordability of ride-sharing to under-served neighborhoods. 

## Results
Total number of rides and drivers are larger as population density increases; in other words, _Rural_ areas have the smallest number of rides (125) and drivers (78) while _Urban_ has the most rides (1,625) and drivers (2,405). 
Total sum of fares across city types add up to ~$64K, for which majority is driven by transactions from _Urban_ areas. Similar to the relationship of city type vs. total number of rides/drivers, the total sum of fares collected in _Urban_ areas (almost $40K) far exceed those of _Suburban_ (about $19K) or _Rural_ (about $4K). 
However, the average fare per ride and average fare per driver is most expensive for _Rural_ areas, followed by _Suburban_, then _Urban_. While the more densely populated areas see the most ride-sharing, each ride's price is much cheaper than _Rural_ areas which see much fewer rides with higher prices per trip. 
 
 **Summary of Ride-sharing by City Type**
  ![Screenshot](https://github.com/aseo67/PyBer_Analysis/blob/main/analysis/Screenshot_PyBer%20Summary%20Table.png)

On a weekly basis over the time period of Jan-April 2019, fares typically stay pretty consistent for each city type. The _Rural_ areas typically generate <$500 per week, _Suburban_ areas range from ~$700-1500 per week, and _Urban_ cities range from ~$1500-2500 per week. Peaks and dips in total fares over the weeks are pretty unique to the city type, with the only common peak across city types occuring in late February. However, overall this data seems to indicate that total fares are generally consistent for each city type, with _Rural_ areas generating the least amount and _Urban_ the most. 
  
  **PyBer Fare Summary Line Chart**
  ![Screenshot](https://github.com/aseo67/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png)

## Summary
1. Though average fares for riders are higher in _Urban_ cites than in _Rural_ areas, this can also be a factor of average distance traveled in _Rural_ areas, as destinations are often farther apart than in densely populated and infrastuctured _Urban_ cities. To make ride-sharing a more affordable option in _Rural_ areas, different methods of calculating fares can be explored to help take into account such differences. 
2. The number of drivers is also much smaller for _Rural_ areas than for _Urban_ cities. The fact that there are fewer drivers to host rides is likely another major contributing factor to the lower adoption of ride-sharing. That said, there is likely a smaller need for ride-sharing in _Rural_ areas, given the smaller population, so focusing on optimizing the number of drivers for the needs of each _Rural_ area and any tourists, is ideal. 
3. The average fare for drivers are also higher in _Rural_ areas than for _Urban_ cities. Similar to the average fares for riders, this is likely due to being distance-based. A more equalized method of calculating price of trips depending on the type of city can also help equalize pay for drivers who live/work in _Urban_ cities vs. _Suburban_ areas vs. _Rural_ areas. Again, the number the trips in _Urban_ cities is likely higher given the denser population and demand for rides; however, the aforementioned recommendation of optimizing the number of drivers based on city type can also help mitigate inequalities of pay between drivers who work/live in _Urban_ areas vs. _Rural_ areas.
