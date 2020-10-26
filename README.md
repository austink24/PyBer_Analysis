# PyBer_Analysis

## Overview of Pyber Anaysis

We set out to provide an analysis of Pyber ride share service's over a 4 month period. We analyzed two data files, the first was the ride data file which kept track of the city name, date, cost of the fare, and the far ID. The second file we analyzed was the city data file that documented city name, city type, and driver count for the city. After merging these data files we were able to report many different data points that could be used to make strategic organizational decisions; key metrics like average fare per City type, average fare per driver, total fares per city type, total drivers per type.





## Results of the Analysis
As mentioned we started by merging the two data files into a single dataframe so we can analyze the data more easily.

![Merging_Code](https://github.com/austink24/PyBer_Analysis/blob/main/Pyber_Code1.png)

Once we merged and grouped the data we were able to calculate total driver count, total fares, and total rides by city; along with average fares and total fares for Pyber Ride Share.

![PyBer_Summary](https://github.com/austink24/PyBer_Analysis/blob/main/Pyber_Summary.png)

After getting this data we would need to graph it to make it easier to present to our audience. To do the graphing we used MatPlotlib library in Python to display the data in a friendly easy to interpret graph. 

![Summary_Graph](https://github.com/austink24/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png)

The details of the Summary graph above shows that Ride Share service in the Urban areas are much more utilized and frequented.
Urban City Type was at the top by a large margin over 2nd place Suburban with almost 3 times as many rides, and nearly 5 times as many drivers. The Urban average fare wasn't as high as the other two classes suburban and rural but, that can be expected as rides tend to be short distances and more frequent in Urban areas. 

