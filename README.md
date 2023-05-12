In this assignment, I creates a Python script to visualize the weather of over 500 cities of varying distances from the equator. I used the citipy Python libraryLinks to an external site., the OpenWeatherMap APILinks to an external site., and problem-solving skills to create a representative model of weather across cities. I used my weather data skills to plan future vacations. I also used Jupyter notebooks, the geoViews Python library, and the Geoapify API.

For the first portion, I used the OpenWeatherMap API to retrieve weather data from the cities list generated in the starter code. Next, you'll create a series of scatter plots to showcase the following relationships:
    -Latitude vs. Temperature
    -Latitude vs. Humidity
    -Latitude vs. Cloudiness
    -Latitude vs. Wind Speed

Then, I was able to compute the linear regression for each relationship. I separated the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude). I found it helpful to define a function in order to create the linear regression plots.

After this, I created a series of scatter plots. I made sure to include the linear regression line, the model's formula, and the r values as you can see from the images in the output_data folder. After each pair of plots, I explained what the linear regression is modeling and noted the relationships that I noticed and any other findings.

In the second portion, I first had to import the required libraries and load the CSV file with the weather and coordinates data for each city which was created in Part 1. I created a map that displays a point for every city in the city_data_df DataFrame. The size of the point should be the humidity in each city. I then narrowed down the city_data_df DataFrame to find my ideal weather condition. With this, I ceated a new DataFrame called hotel_df to store the city, country, coordinates, and humidity. Lastly, for each city, I used the Geoapify API to find the first hotel located within 10,000 meters of my coordinates and added the hotel name and the country as additional information in the hover message for each city on the map.