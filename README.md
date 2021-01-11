# World_Weather_Analysis

## Overview  :
Jack loves the PlanMyTrip app. And, as with any new product, they’ve recommended a few changes to take the app to the next level. Specifically, they recommend adding the weather description to the weather data you’ve already retrieved.  From the list of potential travel destinations, the beta tester will choose four cities to create a travel itinerary. Finally, using the Google Maps Directions API, you will create a travel route between the four cities as well as a marker layer map.

This new assignment consists of three technical analyses with the following deliverables:
### Deliverable 1: Retrieve Weather Data of the following information from the API call:

* Latitude and longitude
* Maximum temperature
* Percent humidity
* Percent cloudiness
* Wind speed
* Weather description (for example, clouds, fog, light rain, clear sky)
* Add the weather data to dataframe [city data](https://github.com/raajasrini/World_Weather_Analysis/blob/main/Weather_Database/city_data.png)
* Export the DataFrame as [WeatherPy_Database.csv](https://github.com/raajasrini/World_Weather_Analysis/blob/main/Weather_Database/WeatherPy_Database.csv) into the Weather_Database folder

### Deliverable 2: Create a Customer Travel Destinations Map
* Input statements are written to prompt the customer for their minimum and maximum temperature preferences.
* A new DataFrame is created based on the minimum and maximum temperature, and empty rows are dropped.
* The hotel name is retrieved and added to the DataFrame, and the rows that don’t have a hotel name are dropped.
* The DataFrame is exported as a CSV file into the Vacation_Search folder and is saved as [WeatherPy_vacation.csv](https://github.com/raajasrini/World_Weather_Analysis/blob/main/Vacation_Search/WeatherPy_vacation.csv).
* A marker layer map with pop-up markers for the cities in the vacation DataFrame is created, and it is uploaded as a PNG. Each marker has the following information:
 * Hotel name
 * City
 * Country
 * Current weather description with the maximum temperature
* The marker layer map is saved and uploaded to the Vacation_Search folder as [WeatherPy_vacation_map.png](https://github.com/raajasrini/World_Weather_Analysis/blob/main/Vacation_Search/WeatherPy_vacation_map.png)

### Deliverable 3: Create a Travel Itinerary Map
* Four DataFrames are created, one for each city on the itinerary.
* The latitude and longitude pairs for each of the four cities are retrieved.
* A directions layer map between the cities and the travel map is created and uploaded as [WeatherPy_travel_map](https://github.com/raajasrini/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map.png%20.png).
* A DataFrame that contains the four cities on the itinerary is created.
* A marker layer map with a pop-up marker for the cities on the itinerary is created, and it is uploaded as [WeatherPy_travel_map_markers](https://github.com/raajasrini/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map_markers.png).Each marker has the following information:
   * Hotel name
   * City
   * Country
   * Current weather description with the maximum temperature