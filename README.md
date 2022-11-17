# World Weather Analysis

## Purpose
This project combines API resources from [Open Weather Map](https://openweathermap.org/) and from Google to create a program that helps travelers to chose ideal destinations based on weather and hotel availability and to plan a basic itinerary of nearby cities. 

### Generate random cities
The `numpy` module is used to generate random numbers fit for use as lattitude and longitude coordinates. Then the `citipy` module is used to create a list of cities based on the randomly generated coordinates. 

### Determine Weather
`Pandas` is used to create data frames to store information on the cities. API calls are made to Open Weather Map to get and store relevant weather data on those cities. More code is added to allow users to import their own preference for minimum and maximum temperatures and narrow the list of available cities based on those inputs. 

### Mapping
`Gmaps` and data from Google are used to create a heat map that displays the cities selected by the user and visualize their highest temperatureas. More data from google is used to create a map that displays markers and information boxes for a hotel in each of the selected cities. Finally, four cities are selected by the user, and Google Directions, along with gmaps, is used to create a map that shows a route between those four cities and information a hotel in each of them.
