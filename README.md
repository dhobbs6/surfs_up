# **Overview of the Statistical Analysis**

The purpose of this analysis is to utilize Python, Pandas functions and methods, and SQLAlchemy, to filter the date column of the Measurements table in the hawaii.sqlite database to retrieve all the temperatures for the month of June and December. Then, converting those temperatures to a list, create a DataFrame from the list, and generate the summary statistics for the months of June and December. Then, offer a report that describes the key differences in weather between June and December. 
-

## **Results**

The average temperature in June (74.9) is almost four degrees higher than the recorded average temperature in the month of December (71.04). With respect to the distribution, the standard deviation for the month of June is lower (3.25) when compared to the standard deviation of the month of December (3.74). This indicates that, for the month of June, the distribution has a tighter bell curve, and the data tends to cluster more toward the mean. For the month of December, the standard deviation is higher indicating the temperature data is more spread out when compared to June's. 
-

### **Summary**
-

I would summarize that the temperature variation is only about 4 degrees. Not a massive amount. Therefore, I would say that the ice cream shop and surfing shop could be operational year-round. When looking at the month of December, we see that the minimum is 56 degrees, which would not be surfing weather. However, we can also tell from the data that the median hovers around the mean. This leads me to be more inclined to see that the surfing shop can be operational year-round. Two additional queries that I would perform to gain additional data would be gathering temperature data on every month, not just June and December, as well as other weather conditions. Gathering more data on more than two months would offer a more precise analysis on whether or not both shops could be operational year-round. Also, gathering other weather data, such as wind conditions, the likelihood of hurricanes, precipitation, etc. would all allow for a more accurate assessment of how successful both shops could be. 
