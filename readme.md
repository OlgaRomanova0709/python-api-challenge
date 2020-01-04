# What's the Weather Like?

## Background

Let's take what you've learned about **Python requests**, **APIs**, and **JSON** traversals to answer a fundamental question: **"What's the weather like as we approach the equator?"**

![Equator](Images/equatorsign.png)

## WeatherPy

In this example we created a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator. To accomplish this, we utilized a [simple Python library](https://pypi.python.org/pypi/citipy), the [OpenWeatherMap API](https://openweathermap.org/api), and a little common sense to create a representative model of weather across world cities.

We built a series of scatter plots to showcase the following relationships:

* Temperature (F) vs. Latitude
* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude

Our final notebook must:

* Randomly select **at least** 500 unique (non-repeat) cities based on latitude and longitude.
* Perform a weather check on each of the cities using a series of successive API calls.
* Include a print log of each city as it's being processed with the city number and city name.
* Save both a CSV of all data retrieved and png images for each scatter plot.

