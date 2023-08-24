# python-api-challenge
Challenge 6

Please view the final code in the folder: WeatherPy.

In this project, we use python and APIs to:

1. Find the weather conditions at cities all over the globe and determine if those weather conditions change based on the latitude of the cities.  Simple scatterplot visualizations gave the first indication, then linear regressions backed up our findings.  Temperature is strongly correlated with latitude, while cloudiness, wind speed, and humidity were found to have weak or no correlation to latitude. Please see the WeatherPy.ipynb python file for a complete analysis. 

2. Find hotels near the cities with the most favorable weather conditions.  We used the same cities and weather conditions from WeatherPy.ipynb.  We narrowed favorable weather conditions down to no cloudiness, wind speed of less than 10 m/s, humidity <50%, and max temperatures between 50 and 85 degrees.  We used the Geoapify API to find hotels within 10 km of these cities, and display those results on a map with only our favorable cities.  When you hover over the city, you will see key factors in the pop-up box, including the closest hotel (if there is one), and the country.  Please see VacationPy.ipynb for maps.
