# World_Weather_Analysis
weather trends for trip planning
## Overview

The purpose of this project is to retrieve information from websites using the application programming interface (API) from 2000 cities around the world for a vacation planning application, PlanMyTrip app.

## Results

 The application is customizable to the user input to filter weather preferences and return the expected information:

 potential travel destinations and nearby hotels
 User preference for Max and Min temperature criteria for their vacation
 Choose four cities, creating a travel itinerary and travel route map.

The weather data was retrieved from a set of 2,000 randomly generated latitudes and longitudes. The current weather conditions were captured from the Open Weather map (using respective API key) and saved to a dataframe.

!Image [dataframe]

From these cities' weather conditions, a user can filter the potential destinations based on a preferred temperature range as well as the nearest hotel. The destinations are displayed with a pop-up marker summarizing relevant city information.

Image [vacation map]


Using Google's directions API and the user's input, a travel map was created to show the route between the four cities chosen by a user. 

image [ travel route]


A marker layer map is added to provide additional information to the user describing the name of the city, a nearby hotel, and a quick capture of the current weather conditions at each city. The travel route between the cities can be customized.

Image [travel pop-pop route]




Advantage of the app allows users to quickly view destinations based on preferences and possible trip routes to assist with vacations planning. 