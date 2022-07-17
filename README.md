# World_Weather_Analysis
Using APIs to visualize weather data
## Purpose
In this analysis, I’m going to collect weather data from over 600 cities around the world, plot the data using Google maps API, and then perform the statistical analysis. First, I’ll create a weather database from 2,000 random latitudes and longitudes, and add the current weather description to the weather database. Then, I’ll use input statements to filter the data for users’ weather preferences to find the nearest hotels. Finally, I’ll choose four cities to create a travel itinerary, use the Google Maps Directions API, create a travel route between the four cities as well as a marker layer map.
## Analysis
1. Create a weather database from 2,000 random latitudes and longitudes, and add the current weather description to the weather database.<br/>
![1 generate 2000 random coordinates](https://user-images.githubusercontent.com/107179765/179388639-2341e376-e6a2-403b-bfad-945d931e875f.png)
![2 create weather database](https://user-images.githubusercontent.com/107179765/179388642-8344d940-4178-4e41-a39e-59bef7c82e6f.png)
2. Use input statements to filter the data for users’ weather preferences to find the nearest hotels.
![3 input statements](https://user-images.githubusercontent.com/107179765/179388648-184b5aa0-dbd9-43a9-8082-3287018abeb1.png)
![4 search for nearby hotels](https://user-images.githubusercontent.com/107179765/179388663-1532d1d3-f260-4989-b493-ceab88054e74.png)
![5 WeatherPy_vacation_map](https://user-images.githubusercontent.com/107179765/179388687-40caa1bd-fdf5-4928-93ea-679c12ced958.png)
3. Choose four cities to create a travel itinerary, use the Google Maps Directions API, create a travel route between the four cities as well as a marker layer map.
![6 choose 4 cities](https://user-images.githubusercontent.com/107179765/179388692-eb9b3f54-d739-4998-8076-b2d0b3fae5e9.png)
![7 WeatherPy_travel_map](https://user-images.githubusercontent.com/107179765/179388695-88ec7e1d-867b-4520-8ceb-6df8eb97ee20.png)<br/>

This is how PlanMyTrip use the data to recommend ideal hotels based on clients' weather preferences, and create a travel itinerary for our clients.
## Summary
As we can see, with the random list of latitudes and longitudes we can obtain over 600 cities, and request the current weather data for eavh city by using OpenWeatherMap API. Then, we can create a map or make a travel itinerary with pop-up markers that can display information on specific cities based on a customer's travel preferences. Thus, it's very usful to retrieve data using APIs.
