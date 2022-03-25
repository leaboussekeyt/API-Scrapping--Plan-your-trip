# Project-2 (Web-scrapping, API and EDA) - Plan-your-trip

Project to help someone plan their trip depending on weather and recommending the best hotels in the area. 

## Objective
The scope of this project is limited to the top 35-cities to visit in France, according to https://one-week-in.com/35-cities-to-visit-in-france/. Those cities are put into a list as an input at the beginning o
This project is done in four parts: 
   * 1 - Get the city coordinates from the nominatim API
   * 2 - From those coordinates, request weather data from the Open weather API.
           * Following this, we'll clean up this data and select the cities with the best weather
   * 3 - Now that we have our cities to visit, we will scrap booking.com with scrapy for the best hotels in the area (as determined by their score on the website)
   * 4 - Finally, we'll produce two maps for the user to clearly see recommended cities to visit and hotels. 


## Dataset
As this is a project focusing on API and Web Scraping, there's no need to download any dataset to use the notebook. All the data is automatically pulled from those various sources. 

## Pre-requisites

Dependencies

* The source code is written in Python 3.
* The python packages can be installed with pip : pip3 install -R requirements.txt


API

* An API key is needed to use the openweather API, mine is encoded as it is a free API, if however for any reason the key expires then you would need to request a new one on https://openweathermap.org/api 

# Usage
Plan Your Trip.ipynb  
Project file with the requests and the findings. 
