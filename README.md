# World_Weather_Analysis

## Overview of project

In this project, weather data had to be collected and analyzed across various cities worldwide for a travel technology company, PlanMyTrip. This collected data had to be presented to customers via search page which would be filtered by them based on their preferred travel criteria for finding their ideal hotel anywhere around the world.

### Purpose

The purpose of this project is to use Jupyter notebook and CityPy module to get the cities for more than 500 random latitudes and longitudes for performing requests on a weather map APIs and retrieving weather data from those cities. In addition to collection and analysis of weather data, travelers will be provided with a tool that will allow them to filter data for their weather preferences to help them identify their travel destinations and nearby hotels by choosing four different cities for creating travel itinerary. Hence, displaying a travel route between the chosen cities with the use of Google Maps Directions API and marker layer map.

## Resources

- Python: CitiPy module, Python requests, APIs, JSON Traversals, Pandas Library.

- Jupyter Notebook Files: [Weather_Database.ipynb](Weather_Database/Weather_Database.ipynb), [Vacation_Search.ipynb](Vacation_Search/Vacation_Search.ipynb), [Vacation_Itinerary.ipynb](Vacation_Itinerary/Vacation_Itinerary.ipynb).

## Results

This section of the report focuses on the results achieved in terms of weather databases, vacation search preferences and vacation itinerary for the chosen cities.

### Weather Database

In this part of the project, 2,000 random set of latitudes and longitudes was generated for retrieving the nearest city using CitiPy module, thus performing an API call using OpenWeatherMap for retrieving the following data for the cities:

- Latitude and longitude
- Maximum temperature
- Percent humidity
- Percent cloudiness
- Wind Speed
- Weather description

The retrieved data was then added to a new DataFrame as shown in figure below and exported as a CSV file.

![City Data DataFrame](Resources/City_data_DataFrame.png)


### Vacation Search

In this part of the project, customer weather preferences were retrieved by allowing them to input their desired maximum and minimum temperature for their trip using input statements for identifying the potential travel destinations and nearby hotels. As a result, those destinations had to be plotted and shown on marker layer map with pop-up markers as illustrated in the figure below.

![Customer travel destinations map](Vacation_Search/WeatherPy_vacation_map.png)

### Vacation Itinerary

In this portion of the project Google Directions API was utilized for creating travel itinerary for displaying the route between four cities from customer's travel destinations.

As a result, a sample directions layer map was creating showing the route between four chosen cities in India as demonstrated in the figure below.

![Vacation Itinerary](Vacation_Itinerary/WeatherPy_travel_map.png)

Additionally, a marker layer map with a pop-up marker for each city was created as depicted in the figure below.

![Travel map with pop up markers](Vacation_Itinerary/WeatherPy_travel_map_markers.png)


## Summary

In conclusion, the project was successfully completed by practicing our statistical and visualization skills with the use of Python CitiPy module, Pandas library, Jupyter notebook, APIs, JSON Traversals and Gmaps platforms for retrieving the required weather data for helping PlanMyTrip to achieve their goal by adding additional  feature to their application. 
