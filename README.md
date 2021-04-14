
# World Weather Analysis
## Overview of Project:
Collect and analyze weather data across cities worldwide.
### Purpose:
The website *PlanMyTrip* will use the weather data collected from over 500 cities to recommend ideal hotels based on clients’ weather preferences. 
## Results:
1.	Using Jupyter Notebook and pulling API URLs’ from *openweathermaps* and *googlemaps* (see images below) we were able to generate a DataFrame. 
![](https://github.com/Apollo619/World_Weather_Analysis/blob/main/Resources/openweathermap_code.PNG)
![](https://github.com/Apollo619/World_Weather_Analysis/blob/main/Resources/googlelocation_url.PNG)
2.	This DataFrame contained basic information such as “City Name”, “Country”, “Latitude”, “Longitude”, “Max Temp.”, “Wind Speed”, and a multitude of other categories. (see below image)
![](https://github.com/Apollo619/World_Weather_Analysis/blob/main/Resources/weather_db.PNG) 
-	Using our pulled API information for nearby searches, code was used to look up Hotels near the lat and lng in the DataFrame.
-	Once this information was introduced to the DataFrame, a new script was created to let the client look up at hotels and locations based on the preferred temperature range. (see below image)
![](https://github.com/Apollo619/World_Weather_Analysis/blob/main/Resources/temp_range.PNG)
-	Based on the preferred criteria, a map was generated with geo markers that contained the above basic information allowing the client to pick from suggested locations. 
![](https://github.com/Apollo619/World_Weather_Analysis/blob/main/Vacation_Search/WeatherPy_vacation_map.png)
3.	Lastly, client could then plan out an itinerary that that allowed them to start in one city and make stops in alternate cities with similar temperature ranges.  
![](https://github.com/Apollo619/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map.png)
## Summary:
With the newly created script a client can view and see real time current weather information as well as nearest hotels based on the preferred maximum and minimum temperatures. The script will also allow the client to view this information on a map with geo markers that provides pertinent details, and even map routes to additional location nearby with similar temperatures. 
