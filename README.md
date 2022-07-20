# World_Weather_Analysis

## Overview 

In this analysis, we wanted to offer information for anyone looking to booking future travel plans. We wanted to offer travelers the ability to look at "Current Weather Conditions" and then input their temperature preferences. Based on those preference, we could help identify potential travel destinations and nearby hotels. From that list of potential destinations, the travelers could pick 4 cities - which we could then tap into the Google Maps Direction API to showcase the travel route and marker layer map. 

## Sources
- Google Maps API
- OpenWeatherMap API

## Software
- Python 3.7.6
- Matplotlib 3.5.1
- Pandas 1.4.2
- Jupyter Notebook 6.4.8

## Weather Database 
The database allows customers to input their min and max temperature requirement for their vacation. Based on that input, the Weather Database can display the destinations that fit in those parameters. 
A popup marker was created to show the customers, the closest Hotel Name, City, Country, Current Weather and Temperature. 

![this is an image](https://github.com/eneubauer2022/World_Weather_Analysis/blob/main/Vacation_Search/WeatherPy_vacation_map.png)

The Vacation itinerary shows the customer a routed map of 4 destination cities they choose. 

![this is an image](https://github.com/eneubauer2022/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map.png)

There is also a popup marker to show the customers the Hotel Name, City, Country, Current Weather and Temperature of the 4 destination cities they chose. 

![this is an image](https://github.com/eneubauer2022/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map_markers.png)
