# surfs_up
# Overview
The purpose of this analysis is to study weather conditions in Hawaii to determine the viability of an ice cream and surf shop business. I look at temperature data stored in a SQLite file and ran queries with SQLAlchemy to extract and read the data. First, I look at the temperatures across all available years of data for June, and then December, to compare the two and ensure that the business will have the weather to support itself throughout the year. I then run some summary statistics for June and December with measures of spread to see how variable the temperature can be in Hawaii. 
# Results
## Temperatures Summary Statistics
The summary statistics for each month can be found below:

<img width="144" alt="JuneTempsSummaryStats" src="https://user-images.githubusercontent.com/76958825/114455376-b138cc80-9ba9-11eb-8dec-2fd399330074.png">
<img width="160" alt="DecemberTempsSummaryStats" src="https://user-images.githubusercontent.com/76958825/114455430-bf86e880-9ba9-11eb-8c8b-16b39692b704.png">

- As we see in the summary statistics, June had a mean temperature about 4 degrees farenheit higher than Decembers at 74.9 degrees compared to 71.0. This is a strong indicator that the ice cream and surf shop will be able to thrive throughout the year, as 71 degrees is still comfortable surfing weather, and hot enough to drive ice cream sales. 
- June temperatures have a standard deviation of 3.3 degrees, and December's standard deviation is 3.7 degrees. This is another good sign for the prospective business, because approximately 66% of the temperatures in each month are only approximately 3.5 degrees on either side of their respective means. 
- As for the minimum, June had a minimum temperature of 64 degrees while December had a minimum of 56 degrees. I suspect that each of these minimums are more than three standard deviations below their respective means - it is certainly an infrequent occurence to have a temperature that low in either month. However, it is important to note that the business should be prepared to make up for those colder days by having a big sales day on any particularly hot days of the month. 

# Summary 
I created a box and whisker plot for each month to visualize the spread of the data. They are below:
<img width="374" alt="June_boxplot" src="https://user-images.githubusercontent.com/76958825/114457879-88fe9d00-9bac-11eb-89c7-2dd366107871.png">
<img width="385" alt="December_Boxplot" src="https://user-images.githubusercontent.com/76958825/114457886-8b60f700-9bac-11eb-9e47-f7f01b7eb435.png">

As we see in the boxplot comparison, each month follows a similar distribution, where December generally follows the distribution of June, just a few degrees lower.
Overall, the ice cream and surf rental business has favorable weather conditions to thrive in these two months. Further analysis would be required to look at weather for each month of the year in Hawaii, as there might be a stormy season that would cut sales numbers. The business owner should note this exception when he/she plans their profit model for the year as a whole. I'd also want to further examine some qualitative data about the weather conditions - a cloudy and muggy 80 degree day will likely in different sales outcomes compared to a sunny and cloudless 75 degree day. 
