# An Analysis of World Weather Data

Analyzing Weather data from around the world to create an interactive analysis of potential basic vacation plans

## Resources

- Data:
  - OpenWeather API
  - Google Maps API

- Software: Python 3.10.5

## Overview

For the beta of the hypothetical PlanMyTrip App, 2000 random coordinates (both latitude and longitude) were generated. These coordinates were used to find the nearest unique city, and use OpenWeather API was used to generate the weather data for identified cities. This data was then imported into a DataFrame, which was exported to a csv file: [WeatherPy_Database.csv](https://github.com/bradleywb426/World-Weather-Analysis/blob/main/weather_database/WeatherPy_Database.csv). The csv file is opened in a new file as a Dataframe, and users are prompted for their preferred minimum and maximum temperatures for vacationing. The Dataframe is then filtered using the inputted temperatures to find ideal cities before the Google Maps API is used to find the nearest hotels in the aforementioned cities. A Dataframe previous data with hotels added on was exported into the [WeatherPy_vacation.csv](https://github.com/bradleywb426/World-Weather-Analysis/blob/main/vacation_search/WeatherPy_vacation.csv) file. Cities with hotels that fit in the user's preferred fields are then identified on a map with markers that can be clicked to display basic hotel, city, and weather for the marker. From there, four nearby cities were chosen to demonstrate a potential intinerary function for the app.

Below are example images demonstrating parts of the process.

## Images

<p align ="center">
<img src="https://github.com/bradleywb426/World-Weather-Analysis/blob/main/vacation_search/WeatherPy_vacation_map.png" width="900">
</p>
<p align="center">
Example section of map with markers and information boxes containing some city and weather data
</p>

---

<p align="center">
<img src="https://github.com/bradleywb426/World-Weather-Analysis/blob/main/vacation_itinerary/WeatherPy_travel_map.png" width="600">
</p>
<p align="center">
Example intineray of travel routes between four close cities
</p>

---

<p align="center">
<img src="https://github.com/bradleywb426/World-Weather-Analysis/blob/main/vacation_itinerary/WeatherPy_travel_map_markers.png" width="600">
</p>
<p align="center">
Displaying the city information for the cities in the previous image
</p>
