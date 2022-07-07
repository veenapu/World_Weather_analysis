# World_Weather_Analysis
## Weather analysis, vacation city selection using OpenWeather and Google APIs

## Overview of Projects

The task we have been assigned is to perform three technical analyses.

### 1: Retrieve Weather Data
#### Deliverable 1 Requirements
  - Generate a set of 2,000 random latitudes and longitudes.
  - Retrieve the nearest city.
  - Perform an API call with the OpenWeatherMap.
  - Retrieve the current weather description for each city using API skills.
  - Create a new DataFrame containing the updated weather data.

### 2: Create a Customer Travel Destinations Map
#### Deliverable 2 Requirements

  - Use input statements to retrieve customer weather preferences.
  - Use those preferences to identify potential travel destinations and nearby hotels.
  - Show those destinations on a marker layer map with pop-up markers.

### 3: Create a Travel Itinerary Map
#### Deliverable 3 Requirements

  - Choose 4 cities possible travel destinations,
  - Use the Google Directions API to create a travel itinerary that shows the route between four cities chosen.
  - Create a marker layer map with a pop-up marker for each city on the itinerary.

## Resources
  - Data Source: WeatherPy_Database.csv; WeatherPy_vacation.csv
  - Python Code: Weather_Database; Vacation_Search; Vacation_Itinerary
  - Software: Python 3.7.11
  - Jupyter Notebook; 
  - API 1: openWeatherWeather API (https://openweathermap.org/api); 
  - API 2: Google Maps APIs


## Results
### Weather Database
The following has been created and stored in the Weather_Database folder:

  - Generate a set of 2,000 random latitudes and longitudes
  - Retrieved nearest city to latitudes and longitudes
  - Executed an API call using OpenWeatherMap API
  - Retrieved current weather information including weather description for each city.
  - Created a DataFrame containing the updated weather data and printed to csv file
   
  https://github.com/veenapu/World_Weather_analysis/blob/main/Weather_database/WeatherPy_Database.csv

### Vacation Search
The following has been created and stored in the Vacation_Search folder:

  - Used input statements to retrieve customer weather preferences.
  - Used input preferences to select matching travel destinations and identify nearby hotels.
  - Exported a CSV of possible vacation locations meeting inpute weather criteria
  https://github.com/veenapu/World_Weather_analysis/blob/main/Vacation_Search/WeatherPy_vacation.csv

  - Display identified destinations on a Google map using marker layer showing pop-up markers.

![Vacation City Maps with Markers](https://github.com/veenapu/World_Weather_analysis/blob/main/Vacation_Search/WeatherPy_vacation.csv)


### Vacation Itinerary
The following has been created (Vacation_Itinerary folder):

  - Created travel itinerary using Google Maps API direction layer showing the route between four cities selected from list of possibilibities from Vacation_Search 
  - Add a pop-up marker using Google Maps API Marker Layer for each selected city in the proposed itinerary
  - Created map of vacation possible destinations with pop us markers including current weather.

![WeatherPy_travel_map](https://github.com/veenapu/World_Weather_analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map.PNG)

![WeatherPy_travel_map_markers](https://github.com/veenapu/World_Weather_analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map_markers.PNG)
