# python--api

## Weather Analysis and Vacation Planning

# Project Overview

This project leverages Python to analyze weather patterns across more than 500 randomly selected cities at varying distances from the equator using the OpenWeatherMap API. It explores relationships between latitude and several weather parameters including temperature, humidity, cloudiness, and wind speed. Additionally, the project uses this data to assist in planning future vacations by identifying hotels in cities that meet specific weather criteria.

# Part 1: WeatherPy
- Objective: Visualize and analyze the weather of over 500 cities worldwide.
- Technologies: Python, Jupyter Notebook, OpenWeatherMap API, citipy library.
# Features:
- Generate scatter plots to showcase relationships between latitude and weather variables.
- Perform linear regression on weather data to observe trends.
- Analyze data specifically for Northern and Southern Hemispheres.
# Part 2: VacationPy
- Objective: Use weather data to plan vacations based on ideal weather conditions.
- Technologies: Python, Jupyter Notebook, Geoapify API, geoViews library.
# Features:
- Create a map displaying humidity levels for each city.
- Filter cities based on specific weather criteria.
- Locate hotels within a close radius of the selected cities and display them on a map.

## Data

Data is dynamically fetched using APIs:

- Weather Data: Retrieved from OpenWeatherMap.
- City Data: Generated using citipy based on random latitude and longitude.
