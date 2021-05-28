# World_Weather_Analysis

## Overview of the Project

The purpose of this project is to create an app that uses weather pattern accross the globe to provide travel guide 
to tourist and travellers by using input statements to filter the data for their weather preferences,
which will be used to identify potential travel destinations and nearby hotels.

I will create a list of potential travel destinations, and choose four cities to create a travel itinerary.

With the aid of Google Maps Directions API, I will create a travel route between the four cities as well as a marker layer map.

### Resources

Data Source: weatherPy_vacation.csv, WeatherPy_database.csv, Weather_Database.ipynb, Vacation_Search.ipynb, Vacation_Itinerary.ipynb

Software: Python 3.7.6, Visual Studio Code 1.56.0, Anaconda 4.9.2, Jupyter Notebook 6.1.4, Matplotlip 3.3.2, Request Library 2.24.0.

APIs: Open Weather Map, Directions API, Google Geocoding API, Google Maps JavaScript API, Google Places API.

## Project Results

Using the google API, I was able to retrive the following information;

* Latitude and longitude
* Maximum temperature
* Percent humidity
* Percent cloudiness
* Wind speed
* Weather description (for example, clouds, fog, light rain, clear sky)

I created a data frame to store the information, and the output is displayed in the image below;

![Dataframe](https://user-images.githubusercontent.com/81701640/119921424-f9366780-bf3b-11eb-876f-f8a76eb54eb7.png)

A hotel dataframe was also created to store hotel names along with city, country, max temp, and coordinates.

The image is displayed below;

![hotel_df](https://user-images.githubusercontent.com/81701640/119921642-59c5a480-bf3c-11eb-8cda-90f596771d38.png)

### Customer Travel Destinations Map

Using minimum and maximum temperature of 75 and 90 degrees farinheit respectively as search criteria, I was able to plot the hotel dataframe on google maps with the aid of the 
google map API.

The image is shown below;

![WeatherPy_vacation_map](https://user-images.githubusercontent.com/81701640/119922075-1586d400-bf3d-11eb-9ebe-58287d3de225.png)

### Travel Itinerary Map

Google Directions API to create a travel itinerary that shows the route between four cities chosen from the customer’s possible travel destinations.

The four cities are Bud, Westport, Havelock, and Crestview all located in the United States of America.

The travel itenery is plotted in map as shown below;

![WeatherPy_travel_map](https://user-images.githubusercontent.com/81701640/119922477-de64f280-bf3d-11eb-970d-1690ce71ea27.png)

** Nnaemeka Enukorah **
** May 29th, 2021 **

