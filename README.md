# World_Weather_Analysis

## Overview

The purpose of this project is to retrieve information from the Open Weather Map website using the application programming interface (API) for 2,000 cities around the world for a vacation planning application, PlanMyTrip app.

## Results

 The application is customizable to the user input to filter weather preferences and return the expected information:

 -potential travel destinations and nearby hotels

 -User preference for max and min temperature criteria for their vacation

 -Choose four cities, creating a travel itinerary and travel route map

The weather data was retrieved from a set of 2,000 randomly generated latitudes and longitudes. The current weather conditions were captured from the Open Weather map and saved to a dataframe.

![Image](https://github.com/courtneysims/World_Weather_Analysis/blob/168899119ad6d5e02ca10bd5832aedef2d7d9ece/Vacation_Search/prefered_city_dataframe.PNG)

From these cities' weather conditions, a user can filter the potential destinations based on a preferred temperature range as well as the nearest hotel. The destinations are displayed with a pop-up marker summarizing relevant city information.

![Image](https://github.com/courtneysims/World_Weather_Analysis/blob/168899119ad6d5e02ca10bd5832aedef2d7d9ece/Vacation_Search/WeatherPy_vacation_map.PNG)


Using Google's directions API and the user's input, a travel map was created to show the route between the four cities chosen by a user. 

![Image](https://github.com/courtneysims/World_Weather_Analysis/blob/168899119ad6d5e02ca10bd5832aedef2d7d9ece/Vacation_Itinerary/WeatherPy_travel_map.PNG)


A marker layer map is added to provide additional information to the user describing the name of the city, a nearby hotel, and a quick capture of the current weather conditions at each city. The travel route between the cities can be customized.

![Image](https://github.com/courtneysims/World_Weather_Analysis/blob/168899119ad6d5e02ca10bd5832aedef2d7d9ece/Vacation_Itinerary/WeatherPy_travel_map_markers.png)


Advantage of the app allows users to quickly view destinations based on preferences and possible trip routes to assist with vacation planning. 