# python-api-challenge

Analysis results from the WeatherPy part of the challenge.

Temperature vs. Latitude Linear Regression Plot

 o The main relationship for the southern hemisphere and the northern hemispere is that the closer you get to the 0 degrees or the equator the higher the temp gets.

Humidity vs. Latitude Linear Regression Plot

 o It is very difficult to see a relationship that exists to the humidity vs the latitude. It seems to be shattered randomly based on the location and the humidity can very.

Cloudiness vs. Latitude Linear Regression Plot

 o The same with the cloudiness. There doesn't seem to be a relationship that exist due to the location of latitude. I would assume this is due to the land masses vs the water masses.

Wind Speed vs. Latitude Linear Regression Plot

 o The wind speeds are averaged across all latitudes of the northern and southern hemispheres. But was it interesting is that there are a few outlyiers of greater speeds the further you get from 0 degrees or the equator.

Requirements

The requirements for "Part 1: WeatherPy" are the following

Create Plots to Showcase the Relationship Between Weather Variables and Latitude (30 points)

Use the OpenWeatherMap API to retrieve weather data from the cities list generated in the started code (10 points)

Create a scatter plot to showcase the relationship between Latitude vs. Temperature (5 points)

Create a scatter plot to showcase the relationship between Latitude vs. Humidity (5 points)

Create a scatter plot to showcase the relationship between Latitude vs. Cloudiness (5 points)

Create a scatter plot to showcase the relationship between Latitude vs. Wind Speed (5 points)

Compute Linear Regression for Each Relationship (40 points)
Linear regression scatter plot for Northern Hemisphere: Temperature (C) vs. Latitude (5 points)

Linear regression scatter plot for Southern Hemisphere: Temperature (C) vs. Latitude (5 points)

Linear regression scatter plot for Northern Hemisphere: Humidity (%) vs. Latitude (5 points)

Linear regression scatter plot for Southern Hemisphere: Humidity (%) vs. Latitude (5 points)

Linear regression scatter plot for Northern Hemisphere: Cloudiness (%) vs. Latitude (5 points)

Linear regression scatter plot for Southern Hemisphere: Cloudiness (%) vs. Latitude (5 points)

Linear regression scatter plot for Northern Hemisphere: Wind Speed (m/s) vs. Latitude (5 points)

Linear regression scatter plot for Southern Hemisphere: Wind Speed (m/s) vs. Latitude (5 points)

The requirements for "Part 2: VacationPy" are the following (30 points)

Create a map that displays a point for every city in the city_data_df DataFrame (5 points)

Narrow down the city_data_df DataFrame to find your ideal weather condition (5 points)

For each city in the hotel_df DataFrame, use the Geoapify API to find the first hotel located within 10,000 metres of your coordinates (10 points)

Add the hotel name and the country as additional information in the hover message for each city in the map. (10 points)
