# python-api-challenge

By Grace Yoo

**Programming Languages, Libraries, and Tools Used:** Python, APIs, JSON, hvplot.pandas

## Purpose

Using [Geoapify API](https://apidocs.geoapify.com/playground/places/) and [OpenWeatherMap API](https://openweathermap.org/api), visualize weather conditions in potential vacation locales. 

## Steps

1. Generate a list of cities using citipy API libary and grab location data. 
2. Use OpenWeatherMap API to generate weather data for each city. 
3. Create visualizations comparing location data to various weather measurements.  
4. Filter a list of cities around the world to fit my ideal weather condition (i.e. lower than 40% humidity, and temperatures between 2 to 20 C.)
5. Using Geoapify API, find the first hotel located within 10,000 meters of the city coordinate. 
6. Display hotel/city name in a pandas map. 

## Selected Visualizations

# City Data Generated by Citipy API Snippet 

| City            | Lat      | Lng       | Max Temp | Humidity | Cloudiness | Wind Speed | Country | Date       |
|-----------------|----------|-----------|----------|----------|------------|------------|---------|------------|
| mataura         | -46.1927 | 168.8643  | 17.88    | 36       | 11         | 3.54       | NZ      | 1674441674 |
| laredo          | 27.5064  | -99.5075  | 16.16    | 18       | 0          | 3.60       | US      | 1674441782 |
| sabha           | 27.0377  | 14.4283   | 9.85     | 27       | 0          | 2.22       | LY      | 1674441954 |
| atar            | 20.5169  | -13.0499  | 17.59    | 17       | 0          | 4.64       | MR      | 1674441696 |
| awbari          | 26.5921  | 12.7805   | 9.92     | 21       | 0          | 2.37       | LY      | 1674441990 |
| general cepeda  | 25.3833  | -101.4500 | 12.26    | 32       | 4          | 1.64       | MX      | 1674441925 |


# City Latitude vs. Max Temperature

![fig1](https://github.com/geyo/python-api-challenge/blob/main/WeatherPy/output_data/Fig1.png)

# Latitude vs. Wind Speed in Southern Hemisphere

![fig12](https://github.com/geyo/python-api-challenge/blob/main/WeatherPy/output_data/Fig12.png)

