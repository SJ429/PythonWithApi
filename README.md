### Python API - What's the Weather Like?


Whether financial, political, or social -- data's true power lies in its ability to answer questions definitively. 

This project was designed to fetch data from OpenWeatherMap API to create visualizations. Pandas, Matplotlib and Jupyter Notebook as Python scripts were used to make visualizations of the weather of 500+ cities across the world of varying distance from the equator.


## Part I - WeatherPy

#Observations:
Latitude vs. Temperature Plot
There is one city in the northern hemisphere with temperature of about 40 degrees Celsius.

Latitude vs. Humidity Plot
The humidity level is not beyond 100% in any city in the northern or the southern hemisphere and one city in the northern hemisphere is about at 0% humidity.

Latitude vs. Wind Speed Plot
There are 2 cities with wind speed of 10 or more degrees and these cities are located in the northern hemisphere.

Scatter plots were built to display the following relationships:

* Temperature (F) vs. Latitude
* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude

Also, linear regression for each relationship in the Northern Hemisphere (greater than or equal to 0 degrees’ latitude) and Southern Hemisphere (less than 0 degrees’ latitude) for the following:

* Northern Hemisphere - Temperature (F) vs. Latitude
* Southern Hemisphere - Temperature (F) vs. Latitude
* Northern Hemisphere - Humidity (%) vs. Latitude
* Southern Hemisphere - Humidity (%) vs. Latitude
* Northern Hemisphere - Cloudiness (%) vs. Latitude
* Southern Hemisphere - Cloudiness (%) vs. Latitude
* Northern Hemisphere - Wind Speed (mph) vs. Latitude
* Southern Hemisphere - Wind Speed (mph) vs. Latitude


### Part II - VacationPy

* A heat map was created that displayed the humidity for every city from the part I above and then looked at an ideal weather condition. 

* Google Places API was used to find the first hotel for each city located within 5000 meters of the coordinates.


