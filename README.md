# WeatherPy 
PlanMyTrip app enhancement

## Overview of the analysis: 
The purpose of this analysis is to improve the PlanMyTrip application, including input statements to filter the data according to your weather preferences to identify possible travel destinations and nearby hotels and create a travel itinerary with a a marker layer map.


## Summary: 
In the Weather_Database folder we have the Weather_Database.ipynb file containing the generation of a set of 2,000 random latitudes and longitudes to retrieve the nearest city and make an API call with OpenWeatherMap. With that we create a new DataFrame containing the updated weather data of Latitude and longitude, Maximum temperature, Percent humidity, Percent cloudiness, Wind speed and Weather description (for example, clouds, fog, light rain, clear sky).  
In the Vacation_Search folder, in the Vacation_Search.ipynb file, input instructions were included to retrieve the customer's weather preferences and, based on this choice, identify possible travel destinations and nearby hotels. With the weather and hotel data, we created a CSV file, WeatherPy_vacation.csv. Finally, a marker layer map was created with pop-up markers showing these destinations. This map is saved as WeatherPy_vacation_map.png.  
In the Vacation_Itinerary folder, in the Vacation_Itinerary.ipynb file, we use the Google Directions API to create a travel itinerary that shows the route between four cities chosen from the customer's possible travel destinations. The map with this itinerary is saved in the WeatherPy_travel_map.png file. Finally, we create a marker layer map with a pop-up marker for each city on the itinerary, as shown in the WeatherPy_travel_map_markers.png file.  
All the files .ipynb mentioned above have the code all commented out.
