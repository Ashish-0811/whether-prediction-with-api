# whether-prediction-with-api


This project is a Python application that provides real-time weather and air quality information for any city using the OpenWeatherMap API. The application features a login system and a graphical user interface built with Tkinter. Users can view the current weather conditions, air quality index, and a 5-day weather forecast with plotted temperature trends.

Features

Login System: Secure access with username and password authentication.
Weather Data: Retrieve and display current temperature, weather description, and humidity for a specified city.
Air Quality Index: Display the air quality index based on the city’s coordinates.
5-Day Weather Forecast: Provide a detailed 5-day weather forecast, including average temperature and humidity.
Graphical Plot: Plot the temperature trend over the next 5 days using Matplotlib.


Technologies Used

Python
Tkinter for GUI
Requests for API calls
Matplotlib for plotting data
How to Use
Clone the repository.
Install the required libraries: requests, matplotlib.
Run the script: python weather_app.py.
Log in with the credentials: username: ashish, password: ashish.
Enter the city name to get weather and air quality information.

API Keys

This project uses the OpenWeatherMap API. You'll need to replace the placeholder API keys in the code with your own:

weather_api_key for weather data
air_quality_api_key for air quality data
