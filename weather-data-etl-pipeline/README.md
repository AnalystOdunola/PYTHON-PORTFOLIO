# Weather Data ETL Pipeline Using OpenWeather API

## Project Overview

This project demonstrates a simple ETL (Extract, Transform, Load) pipeline using real-time weather data from the OpenWeather API. The pipeline extracts weather information for multiple cities, transforms the raw API response into a structured format using Pandas, and loads the processed data into a CSV file for future analysis.

## Objective

To build a basic ETL pipeline that retrieves real-time weather data from the OpenWeather API, transforms the data into a clean and structured format, stores it for future analysis, and generates basic weather insights.

## Data Source

- API: OpenWeatherMap API
- Endpoint: Current Weather Data API 2.5
- Cities Analyzed: Lagos, London, New York
- Website: https://openweathermap.org/api

## Dataset Fields

The dataset contains the following attributes:

- City Name
- Temperature (°C)
- Humidity (%)
- Weather Condition
- Wind Speed (m/s)
- Date and Time

## ETL Process

### Extract

Weather data was retrieved from the OpenWeather API using Python's Requests library.

### Transform

The extracted JSON data was transformed using Pandas by:

- Converting the API response into a DataFrame
- Renaming columns for readability
- Formatting timestamps
- Organizing the data into a structured format

### Load

The transformed dataset was stored as:

- weather_data.csv

## Tools Used

- Python
- Pandas
- Requests
- Matplotlib
- Google Colab
- OpenWeather API

## Steps Taken

1. Generated an OpenWeather API key.
2. Retrieved weather data for Lagos, London, and New York.
3. Extracted temperature, humidity, weather condition, wind speed, and timestamp data.
4. Transformed the raw API response into a structured DataFrame.
5. Saved the processed data as a CSV file.
6. Performed basic weather analysis.
7. Created visualizations for comparison.

## Basic Analysis Performed

The following analyses were conducted:

- Calculated the average temperature across all cities.
- Identified the city with the highest humidity.
- Compared weather conditions across cities.
- Identified the hottest city based on current temperature.

## Key Findings

- The average temperature across the selected cities was **23.13°C**.
- **Lagos** recorded the highest temperature at **27.62°C**.
- **Lagos** recorded the highest humidity level at **78%**.
- All three cities experienced different weather conditions; **Lagos was rainy, London was cloudy and New York was clear** during data collection.

## Visualizations Created

- Temperature Comparison Across Cities
- Humidity Comparison Across Cities
- Weather Condition Distribution Chart

-    ## Jupyter Notebook
-    
   [Click here to view the full notebook](./Weather_epl.ipynb)

  ## Author

  Odunola Adewale
