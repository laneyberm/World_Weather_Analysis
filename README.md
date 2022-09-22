# World Weather Analysis for the Beta Testing of a Travel APP

## Overview
PlanMyTrip, a travel itinerary app, is beta testing and is recommending a few changes to take the app to the next level. Specifically, they recommend adding the weather description to the weather data. Then, we'll have the beta testers use input statements to filter the data for their weather preferences, which will be used to identify potential travel destinations and nearby hotels. From the list of potential travel destinations, the beta tester will choose four cities to create a travel itinerary. Finally, using the Google Maps Directions API, we will create a travel route between the four cities as well as a marker layer map.

## Recources
- Data Source: WeatherPy_Database.csv, WeatherPy_vacation.csv
- Software: Jupyter Notebook 6.4.8, Python 3.7.13, Pandas 1.3.5, 
- Library: Pandas Library, CitiPy, Python Requests, Directions API in Google Cloud Platform

## Results

To retrieve weather data, we completed the following:
- Generate a set of 2,000 random latitudes and longitudes
- Retrieve the nearest city 
- Perform an API call with the OpenWeatherMap
- Use your API skills to retrieve the current weather description for each city 
- Create a new DataFrame containing the updated weather data

To create a customer travel destinations map, we completed the following:
- Use input statements to retrieve customer weather preferences 
- Use those preferences to identify potential travel destinations and nearby hotels
- Show those destinations on a marker layer map with pop-up markers

To create a travel itinerary map, we completed the following:
- Use the Google Directions API to create a travel itinerary that shows the route between four cities chosen from the customer’s possible travel destinations
- Create a marker layer map with a pop-up marker for each city on the itinerary.

This is an example of 4 locations in Spain for the travel itinerary.
<img src="https://github.com/laneyberm/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map.png" width="600">
<img src="https://github.com/laneyberm/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map_markers.png" width="600">

## Summary
After completing the testing on PlanMyTrip, all of the functions work. Users will be able to filter the data for their weather preferences, which will be used to identify potential travel destinations and nearby hotels and create a travel itinerary including a travel route. 
