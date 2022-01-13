# World Weather Analysis

## Overview

The purpose of this project was to collect, analyze and visualize weather data for cities that are possible vacation destinations. To accomplish this task many tools were used such as Python, Pandas, APIs and Google Maps. You can find the code & CSV files for this project in the Weather Database and Vacation Search folders. 

## Process and Results 


The first step in the project was to extract the cities we would like to look at and create a dataframe and CSV for their information. This was done by using an API to pull the information into a dataframe. See below for a section of this dataframe.

![Alt Image Text](https://github.com/mkback/World_Weather_Analysis/blob/main/Weather_Database/Images/Full_city_list.png)

Now that we have a list of cities, we want to narrow down to only those with the preferable weather conditions and add hotels in each city the traveler can stay in. To get the preferable weather, input boxes were created using Python. To pull in the hotels, a google API was used. See below for the updated dataframe. 

![Alt Image Text](https://github.com/mkback/World_Weather_Analysis/blob/main/Weather_Database/Images/City_list_withHotels.png)

Using gmaps, we were able to visualize these cities and add markers with the city information: 

![Alt Image Text](https://github.com/mkback/World_Weather_Analysis/blob/main/Weather_Database/Images/Vacation_heatmap.png)

Finally, the traveler chooses 4 locations from this list to vacation and created an itinerary. We again used gmaps to visualize this road trip: 

![Alt Image Text](https://github.com/mkback/World_Weather_Analysis/blob/main/Weather_Database/Images/Roadtrip_map.png)
