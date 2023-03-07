# python-api-challenge

This is my submission for the python-api-challenge. As the map output was not visible in github, I have saved both html and png files for them.

In WeatherPy, I have:
- Used the OpenWeatherMap API to retrieve weather data from the cities list generated in the started code
- Created scatter plots to showcase the relationship between Latitude and Temperature, Humidity, Cloudiness, and Wind Speed
- Created separate dataframes for northern and southern hemispheres
- Created a function to plot linear regression plots for the above mentioned relationships in the northern and southern hemispheres and added discussion on their linear relationships

In VacationPy, I have:
- Created a map that displays a point for every city in the city_data_df DataFrame and saved html and png files of it
- Narrowed down the city_data_df DataFrame to find the ideal weather condition
- Used the Geoapify API to find the first hotel located within 10,000 metres of the coordinates of each city in the hotel_df DataFrame
- Created a map that displays these cities and added the hotel name and the country as additional information in the hover message for each city in the map and saved html and png files of it
