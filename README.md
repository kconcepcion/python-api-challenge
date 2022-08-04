# module 6 python-api-challenge 
## Observable trends found in part 1 WeatherPy
1. One trend I did note was realted to the first visual generated in part 1. The max temperature v latitude table shows an arch (or a rise in heat in the middle). This is interesting because it shows how the closer you get to the equator the higher temperatures will rise

2. Another trend I noted was that wind speeds typically stay between 0-15 mphs. There are some that go above, but the majority of wind speeds are between those two values. Wind speeds also has a pretty equal distribution across the latitude x axis, this denotes that winspeeds are pretty much equal across the globe and indepdendent from their position.

3. Finally, the last trend that I noted was there seems to be more population in the northern hemisphere than the southern hemisphere. If you look at the scatter plots you will see that typically there are more cities generated from the northern hemisphere than there the sounthern hemisphere. This trend can be seen on all 12 scatter plots generated from WeatherPy.ipynb

## Part 1: WeatherPy
In this section i created a Python script to visualize the weather of 500+ cities of varying distance from the equator.

The first requirement is to create a series of scatter plots to showcase the following relationships:

* Temperature (F) vs. Latitude
* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude

The second requirement is to compute the linear regression for each relationship.

* Northern Hemisphere - Temperature (F) vs. Latitude
* Southern Hemisphere - Temperature (F) vs. Latitude
* Northern Hemisphere - Humidity (%) vs. Latitude
* Southern Hemisphere - Humidity (%) vs. Latitude
* Northern Hemisphere - Cloudiness (%) vs. Latitude
* Southern Hemisphere - Cloudiness (%) vs. Latitude
* Northern Hemisphere - Wind Speed (mph) vs. Latitude
* Southern Hemisphere - Wind Speed (mph) vs. Latitude

## Part 2: VacationPy
Created a heat map that displays the humidity for every city from Part 1

Narrowed down a DataFrame to find the ideal weather conditions
* A max temperature lower than 80 degrees but higher than 70.

* Wind speed less than 10 mph.

* Zero cloudiness.

* Drop any rows that don't satisfy all three conditions. You want to be sure the weather is ideal.

for a screenshot of the heatmap generated from this code, please refer to the picture in the repository titled "heatmap.png"

