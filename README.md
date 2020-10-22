### What's the Weather Like? 
#### Practice with APIs


## WeatherPy
______________________________________________

Created a Python script that calls for 606 different cities across the world and created visual aids comparing the weather and it's distance from the equator.

Made scatter plots and small analysis for each of the following relationships: 
* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude

Separated the data into Northen and Southern Hemispheres and ran linear regression on each scatter plot for each of the following relationships: 
* Northern Hemisphere - Temperature (F) vs. Latitude
* Southern Hemisphere - Temperature (F) vs. Latitude
* Northern Hemisphere - Humidity (%) vs. Latitude
* Southern Hemisphere - Humidity (%) vs. Latitude
* Northern Hemisphere - Cloudiness (%) vs. Latitude
* Southern Hemisphere - Cloudiness (%) vs. Latitude
* Northern Hemisphere - Wind Speed (mph) vs. Latitude
* Southern Hemisphere - Wind Speed (mph) vs. Latitude
______________________________________________

## VacationPy
______________________________________________


Created a heat map that displays the humidity for every city from part one of the homework.

Made a clean DataFrame by dropping all null values to find ideal weather condition:

  * A max temperature greater than or equal to 60 degrees, but less than or equal to 90 degrees.

  * Wind speed less than 10 mph.

  * Cloudiness less than 40 percent.
  
  * Humidity less than 30 percent.

Used Google Places API to find the first hotel for each city located within 5000 meters of set coordinates.

Plotted the hotels on top of humidity heatmap with each pin containing the **Hotel Name**, **City**, and **Country**.
