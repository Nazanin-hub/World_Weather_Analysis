# World_Weather_Analysis

## Project Overview

PlanMyTrip is a top travel technology company that specializes in Internet related services in the hotel and Jack is a head of analysis for the user interface team. I helped him to filter the data for the weather preferences, which will be used to identify potential travel destinations and nearby hotels.Then, from the list of potential travel destinations, I choosed four cities to create a travel itinerary. Finally, using the Google Maps Directions API, created a travel route between the four cities as well as a marker layer map.

## Results

### Retrieve Weather Data

I used jupyter notebook and a citipy module to get cities for 2000 random latitude and longitude. Then, I performed request on the OpenWeatherMap API to retrieve weather data from cities. The following table is the result:

![](https://github.com/Nazanin-hub/World_Weather_Analysis/blob/main/Weather_Database/Weather_Database%20Result.png)


### Create a Customer Travel Destinations Map

The below image is the result of using input statements to retrieve customer weather preferences, then using those preferences to identify potential travel destinations and nearby hotels.

![](https://github.com/Nazanin-hub/World_Weather_Analysis/blob/main/Vacation_Search/WeatherPy_vacation_map.png)

### Create a Travel Itinerary Map

The below image is the result of using the Google Maps Directions API to create a travel itinerary that shows the route between four cities chosen from the customer’s possible travel destinations. Then, creating a marker layer map with a pop-up marker for each city on the itinerary.

![](https://github.com/Nazanin-hub/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map_markers.png)
