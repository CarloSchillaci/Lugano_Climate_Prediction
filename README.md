# Hackathon theme – Climate data

## Dataset – “openmeteo API”

Climate and weather data through the openmeteo python library (https://open-meteo.com/)
• Aggregates different sources and provides easy-to-use APIs for data retrieval
• Provided APIs:
  – Historical Weather: what was the weather like in the past?
  – Weather forecast: what will the weather be like in the next 7 days?
  – Climate change API: what will the climate be like in the far future?
  – …
  
In the Hackathon, you will:
• Explore data from the Historical Weather API
• Use the data to build linear regression models
• Compare with the results of the linear regression with the advanced models of the Climate change API


Sketch your query with the web-based interface (left)
• Visualize the results or get the python code to read the data to pandas (right)
• You can refine the query by editing the generated code (ex, extract multiple locations)

## Objectives

### 1. Data gathering. 
  – Use the Historical Weather API to extract the data you need:
  • Time range: January 1940 - now
  • Variables: “Temperature (2m)” and “Precipitation (rain + snow)”
  • Locations: Lugano + other cities of your choice
### 2. Data Visualization 
  – Visualize temperatures over the years at different resolutions (monthly, yearly)
  • What trends do you observe?
  • Are the trends consistent over the different locations?
  – Visualize the typical yearly pattern
  – Analyze precipitations in Lugano: 
  • how exceptional has been 2024 so far?
  • how exceptional was 2022?
3. Modeling
  – Make linear regression model(s) of temperature vs. year
  – Predict temperatures until 2070
  – Compare your predictions with the climate models available in the Climate Change API
