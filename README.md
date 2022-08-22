# WeatherPy_Analysis
_Analysis of World Weather Information using APIs & Jupyter Notebook_
---
## Overview of Project:
The purpose of this project was to build the backend coding script for app, which would allow  to allow customers of "PlanMyTrip" to input their temperature preferences and receive a customized vacation search and respective Itinerary--the app is built using Jupyter Notebook, Python, and APIs from OpenWeatherApp and Gmaps.

Utilizing Pandas, CityPy, Numpy, and Python APIs, the following analytical deliverables were created:

- Deliverable 1: Retrieve Weather Data 
 - Generate a set of 2,000 random latitude and longititudes 
 - Retrieve the nearest city
 - Perform an API call with the OpenWeatherMap
 - Retrieve the current weather descritpion for each city.
 - Create a new DataFrame containing the updated weather data.

- Deliverable 2: Create a Custom Travel Destinations Map
 - Create input statements to retrieve customer weather preferences
 - Utilize specified preferences to identify:
  - potential travel destinations
  - nearby hotels
 - Show destinations on a marker layer map with pop-up markers

![Deliverable_2](Vacation_search/Vacation_Destination_Markers.png)

- Deliverable 3: Create a Travel Itinerary Map
 - Use Google Directions API to create travel itinerary
  - Figure shows the route between four cities chosen from the customer's possible destinations
  - Create a marker layer map with pop-up markers for each city on itinerary
  
![Deliverable_3](Vacation_itinerary/Vacation_travel_map_markers.png)
