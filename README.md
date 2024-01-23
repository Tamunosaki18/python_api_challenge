Instructions

This activity has been broken down into two deliverables, WeatherPy ansd VacationPy

WeatherPy Apyton script was created to visualize the weather over 500 cities of varying distances from the equator. CitipyPython library and the OpenWeatherMap Api was given to create a representative model of weather across cities.

Part 1 I used the OpenWeatherMap API to retrieve weather dadtafrom cities list given and created series of scatter plots to showcase the following relationships:

Latitude vs. Temperature
Latitude vs. Humidity
Latitude vs. Cloudiness
Latitude vs. Wind Speed

Part 2 I used linear regression for each relationship. seperated the plots into Northern Hemispher(greater than or equal to 0 degrees latitude) and southern Hemispher(less than 0 degrees latitude). the model's formula and r value was used. The following plots were created

Northern Hemispher: Temperature vs. Latitude
Southern Hemispher: Temperature vs. Latitude
Northern Hrmispher: Humidity vs. Latitude
Southern Hemispher: Humidity vs. Latitude
Northern Hemispher: Cloudiness vs. Latitude
Southern Hemispher: Cloudiness vs. Latitude
Northern Hemispher: Wind Speed vs. Latitude
Southern Hemispher: Wind Speed vs. Latitude
VacationPy

I used Geoapify API and the geoViews Python library to create map visualizations using the following steps:

I used a map that displays a point for every city in the dataframe, the size of the point in each city is humidity
I narrowed down my data frame to find the ideal weather conditionn with max temp 27 degrees but higher than 21
Wind speed less than 4.5m/s
Zero cloudiness
A new data frame called hotel_df was created to store the city, country, cordinates and humidity.
I also used Geoapify API to find the first hootel located within 10,00 metres of my coordinates and the hotel names
