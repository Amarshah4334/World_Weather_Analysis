# World_Weather_Analysis
Generate destinations and travel maps using Google Maps Platform APIs.




## Resources Utilized to Complete Analysis
CSV Files: Weather_Database.csv, WeatherPy_vacation.csv

Jupyter Notebook Files:: Weather_Database.ipynb, Vacation_Search.ipynb, Vacation_Itinerary.ipynb

Python, Pandas, Matplotlib, CitiPy, SciPy, APIs, JSON, Numpy, Open Weather API, Google Maps API, Regression Analysis

## Vacation Search
### Purpose: Create a Customer Travel Destinations Map 

This report is created to retrieve customer weather preferences, then use those preferences to identify potential travel destinations and nearby hotels. Then, show those destinations on a marker layer map with pop-up markers.
List of deliverables in this report:-
1. For place of travel there is customers minimum and maximum temperature preferences for the cities the would like to visit.
2. The hotel name is shown per travel city.
3. A marker layer map with pop-up markers for the cities in the vacation is illustrated showing -
- Hotel name
- City
- Country
- Current weather description with the maximum temperature

![WeatherPy_vacation_map](https://user-images.githubusercontent.com/96351897/153704856-ef8e689e-7b04-4fda-870e-2f0630a7a7e5.png)

## Vacation Itinerary
### Purpose: Create a Travel Itinerary Map

In this Analysis with the use of Google Directions API i have created a travel itinerary that shows the route between four cities chosen from the customer’s possible travel destinations. Then, i added a marker layer map with a pop-up marker for each city on the customers itinerary.
1. Four DataFrames are created, one for each city on the itinerary.
2. The latitude and longitude pairs for each of the four cities are depicted.
3. A directions layer map between the cities and the travel map is shown. 
4. A DataFrame that contains the four cities on the itinerary is shown.
5. A marker layer map with a pop-up marker for the cities on the itinerary is seen. 
Each marker has the following information: 
- Hotel name
- City
- Country
- Current weather description with the maximum temperature

![WeatherPy_travel_map](https://user-images.githubusercontent.com/96351897/153705167-141679c9-b255-4f2a-8689-6b421f5f147d.png)


![WeatherPy_travel_map_markers](https://user-images.githubusercontent.com/96351897/153705171-0a1c90c1-f935-4921-b8b8-070c380d16a5.png)


## Scatter Plots
The use of scatter plots in this analysis is to write a summary report on how different weather parameters change based on the latitude.
the images below have depicted a series of scatter plots for each weather parameter against latitude vs. maximum temperature, humidity, cloudiness, and wind speed for all the cities.  



## Max Temperature
![Fig1](https://user-images.githubusercontent.com/96351897/153704598-a702d440-579b-4862-b8d0-1085b3f11cb0.png)
## Humidity
![Fig2](https://user-images.githubusercontent.com/96351897/153704593-a8f3e766-80e6-4383-a84a-937e7cf8c2c1.png)
## Cloudiness
![Fig3](https://user-images.githubusercontent.com/96351897/153704586-599f477c-2196-478a-84e8-0d6c01e252fd.png)
## Wind Speed
![Fig4](https://user-images.githubusercontent.com/96351897/153704576-815aa4b3-8d00-43c0-b3df-ecd76c8118a6.png)
