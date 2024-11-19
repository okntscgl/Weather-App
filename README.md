# Weather-App

This is a simple Weather Application built using Python, PyQt5, and the OpenWeatherMap API. The app allows users to enter a city name and get real-time weather data, including the temperature, weather description, and an appropriate weather emoji representing the current conditions.

Features
City-based Weather Search: Enter a city name to fetch the current weather.
Temperature in Fahrenheit: Displays the temperature in Fahrenheit (based on OpenWeatherMap's data).
Weather Emojis: Weather conditions are represented with emojis (e.g., 🌧 for rain, ☀ for sunny weather).
Error Handling: The app gracefully handles errors, such as invalid city names or issues with the API request.
Prerequisites
To run this app, you need the following:

Python 3.x
PyQt5 library
Requests library
An API Key from OpenWeatherMap
You can install the necessary dependencies using pip:


pip install pyqt5 requests
Setting Up the API Key
Sign up for a free API key at OpenWeatherMap.
Once you have the key, replace "YOUR API KEY GOES HERE" in the get_weather method with your actual API key.
Running the App
Clone the repository to your local machine:

git clone https://github.com/yourusername/weather-app.git
Navigate to the project directory:

cd weather-app
Run the app using the following command:


python weather_app.py
How It Works
Enter a city name in the input field.
Click on the "Get Weather" button.
The app will display the current temperature in Fahrenheit, an emoji representing the weather, and a description of the weather conditions.
If there is an error (e.g., incorrect city name or API issues), an appropriate error message will be displayed.
Error Handling
The app handles several error scenarios, including:

Bad requests (invalid city name)
Unauthorized access (invalid API key)
Server errors (e.g., 500 Internal Server Error)
Connection issues (e.g., no internet)
Screenshots
(Add screenshots here if available)

License
This project is licensed under the MIT License - see the LICENSE file for details.

Contributions
Feel free to fork the repository, submit issues, or create pull requests. Contributions are welcome!

