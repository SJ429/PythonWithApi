### Python API - What's the Weather Like?


Whether financial, political, or social -- data's true power lies in its ability to answer questions definitively. 

This project was designed to fetch data from OpenWeatherMap API to create visualizations. Pandas, Matplotlib and Jupyter Notebook as Python scripts were used to make visualizations of the weather of 500+ cities across the world of varying distance from the equator.


## Part I - WeatherPy

A series of scatter plots was built to display the following relationships:

* Temperature (F) vs. Latitude
* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude

Also, linear regression on each relationship in the Northern Hemisphere (greater than or equal to 0 degrees’ latitude) and Southern Hemisphere (less than 0 degrees’ latitude):

* Northern Hemisphere - Temperature (F) vs. Latitude
* Southern Hemisphere - Temperature (F) vs. Latitude
* Northern Hemisphere - Humidity (%) vs. Latitude
* Southern Hemisphere - Humidity (%) vs. Latitude
* Northern Hemisphere - Cloudiness (%) vs. Latitude
* Southern Hemisphere - Cloudiness (%) vs. Latitude
* Northern Hemisphere - Wind Speed (mph) vs. Latitude
* Southern Hemisphere - Wind Speed (mph) vs. Latitude


### Part II - VacationPy

* Created a heat map that displays the humidity for every city from the part I above and then narrow down to find an ideal weather condition. 
* Used Google Places API to find the first hotel for each city located within 5000 meters of the coordinates.

* Plotted the hotels on top of the humidity heat map with each pin containing the **Hotel Name**, **City**, and **Country**.

 API key needs to be used to fetch data from data source. API key can be obtained by signing up an account on the OpenWeatherMap API.

