# Learning APIs through World Weather Analysis
## Description
The goal of this project was to learn to utilize APIs by obtaining weather data and using the weather data to locate suitable nearby lodging based on user input about temperature preferences as well as plot paths between cities on a travel itinerary. OpenWeather API was used to gather the weather data, Google places API was used to find nearby hotels, and Google directions API was used to plot the directions between travel destinations.  
## Methods
Random longitudes and latitudes were generated using the random and numpy modules, and a list of cities near the latitude longitude pairs was then generated using citipy. Open Weather API was then used to obtain current weather data for each of the cities found near the random longitudes and latitudes, and the collected weather data was saved in a csv. Input variables were used to obtain user temperature preferences and google places API was used to find lodging in cities that fit the input temperature criteria. Gmaps was used to display the locations with markers accompanied by popups displaying the city name, country, weather description, and maximum temperature as can be seen in the [Vacation Map](https://github.com/MDaily7/World_Weather_Analysis/blob/main/Vacation_Search/WeatherPy_vacation_map.png). Finally, Google directions API was used with gmaps to create a map with a directions layer plotting a travel path between four cities as seen in the [Itinerary Map](https://github.com/MDaily7/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map.png). A [Itinerary Marker Map](https://github.com/MDaily7/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map_markers.png) was also made with gmaps to display only the markers for the cities on the travel itinerary (one marker popup not displayed so as not to cover another marker).
## Resources
* Anaconda 4.11.0 and jupyter notebooks
* Python 3.7.11
* The following folders contain the jupyter notebook files as well as relevant csvs and images
  * [Weather_Database](https://github.com/MDaily7/World_Weather_Analysis/tree/main/Weather_Database)
  * [Vacation_Search](https://github.com/MDaily7/World_Weather_Analysis/tree/main/Vacation_Search)
  * [Vacation_Itinerary](https://github.com/MDaily7/World_Weather_Analysis/tree/main/Vacation_Itinerary)
