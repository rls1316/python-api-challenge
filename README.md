# python-api-challenge

## What's the Weather Like?

# Part 1: WeatherPy

Create a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator. (See [WeatherPy](WeatherPy))

*Create a series of scatter plots to showcase the following relationships:

    *Temperature (F) vs. Latitude
    *Humidity (%) vs. Latitude
    *Cloudiness (%) vs. Latitude
    *Wind Speed (mph) vs. Latitude

*Run linear regression on each relationship. This time, separate the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude):

    *Northern Hemisphere - Temperature (F) vs. Latitude
    *Southern Hemisphere - Temperature (F) vs. Latitude
    *Northern Hemisphere - Humidity (%) vs. Latitude
    *Southern Hemisphere - Humidity (%) vs. Latitude
    *Northern Hemisphere - Cloudiness (%) vs. Latitude
    *Southern Hemisphere - Cloudiness (%) vs. Latitude
    *Northern Hemisphere - Wind Speed (mph) vs. Latitude
    *Southern Hemisphere - Wind Speed (mph) vs. Latitude

# Part 2: VacationPy

Create a series of maps from the City data in Part I. (See [VacationPy](VacationPy))

*Create a heat map that displays the humidity for every city from Part I.

*Narrow down the DataFrame to find your ideal weather condition:

    *A max temperature lower than 85 degrees but higher than 70.
    *Wind speed less than 9 mph.
    *Cloudiness less than 5%

*Using Google Places API to find the first hotel for each city located within 5000 meters of your coordinates.

*Plot the hotels on top of the humidity heatmap with each pin containing the Hotel Name, City, and Country.
