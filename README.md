# surfs_up

## Project Overview
An investor wants to learn more about the weather before committing to build a Surf and Ice Cream shop in Oahu, Hawaii. The investor's main concern is the precipitation forcing the shop to close too frequently. To analyze Hawaii's weather data, SQLAlchemy was used to query the SQLite database.

## Results
The following tables summarize June's temperature statistics over time.

<p align="center">  
<img src="https://github.com/aem-saidur-rahman/surfs_up/blob/main/resources/June..png" width="100%" height="100%">
</p>
<p align="center">  
<i>Figure : June Temperate Statistics</i>
</p>

The following table summarizes Decembers temperature statistics over time.


<p align="center">  
<img src="https://github.com/aem-saidur-rahman/surfs_up/blob/main/resources/december.png" width="100%" height="100%">
</p>
<p align="center">  
<i> Figure : December Temperate Statistics</i>
</p>



These two tables tell us about the differing weather patterns for the two monthly periods. Some takeaways:
1) Average temperature between June and December is 75 and 71 degrees respectively, show a moderate temperature and very little difference between the two periods from an average standpoint.
2) the maximum temperatures of 85 (June) and 83 (December) are also remarkable similar.
3) the minimum temperature of 56 (December) and 64 (June) show the largest variance, and reflects a much lower temperature level in December that may not be conducive to ice cream or surfing. However, with standard deviations of 3.25 (June) and 3.74 (December) we would expect a little more variation in the december numbers.

## Summary
Oevrall the weather in December and June are historically very similar, although December has a wider range of results, with its high being close to June's but its low well below June's temperature.  

Additional queries that could be run include: Precipation difference between June and December to determine is one has more rainy weather, as well as a comaparison by weather station, as we may see higher/lower temperatures and precipitation levels at different locations. We would be primarily interested in the weather station closest to our prospective location, which would narrow the results and provide the best data for us to consider.
