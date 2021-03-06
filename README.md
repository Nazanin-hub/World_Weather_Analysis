# World_Weather_Analysis

## Project Overview

PlanMyTrip is a top travel technology company specialized in internet related services in the hotel and lodging industry. I helped user interface team to filter the data for the weather preferences, which will be used to identify potential travel destinations and nearby hotels. Then, from the list of potential travel destinations, I chose four cities to create a travel itinerary. Finally, using the Google Maps Directions API, I created a travel route between the four cities as well as a marker layer map.

## Resources

  - Data Source: citipy, jupyter-gmaps, OpenWeatherMap API, Google Maps and Places API, Google Maps Directions API
  - Software: Python 3.8.3, Anaconda Navigator 1.9.6, Jupyter Notebook 6.0.3

## Results

### Retrieve Weather Data

I used jupyter notebook and a citipy module to get cities for 2000 random latitude and longitude. Then, I performed requests from OpenWeatherMap API to retrieve weather data for the cities. The following table is a sample of the result:

![](https://github.com/Nazanin-hub/World_Weather_Analysis/blob/main/Weather_Database/Weather_Database%20Result.png)


### Create a Customer Travel Destinations Map

The following customer travel destination map has been created by using input statements to retrieve customer weather preferences and requests to the Google Maps and Places API, then using those preferences to identify potential travel destinations and nearby hotels.

![](https://github.com/Nazanin-hub/World_Weather_Analysis/blob/main/Vacation_Search/WeatherPy_vacation_map.png)

### Create a Travel Itinerary Map

The following maps has been created by using the Google Maps Directions API that shows the route between four cities chosen from the customer’s possible travel destinations. Then, creating a marker layer map with a pop-up marker for each city on the itinerary.

![](https://github.com/Nazanin-hub/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map.png)
![](https://github.com/Nazanin-hub/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map_markers.png)
