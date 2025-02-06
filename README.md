# Weather App in Python

The Weather App is a command-line Python application that retrieves real-time weather data for any city using the OpenWeatherMap API. This project demonstrates how to work with external APIs, handle JSON data, and implement user input validation, making it an excellent example of intermediate Python development.

<h2>Key Features</h2>

- <b>Real-Time Weather Data:</b> Fetches current weather details such as temperature, humidity, wind speed, and a brief description of the weather conditions
- <b>API Integration:</b> Utilizes the OpenWeatherMap API to obtain up-to-date weather information
- <b>User-Friendly Interface:</b> Offers a simple CLI where users can input a city name to retrieve weather information
- <b>Error Handling:</b> Incorporates robust error checking to handle scenarios such as invalid city names, network errors, or issues with the API key
- <b>Modular Code Structure:</b> The code is organized into functions for fetching and displaying weather data, which makes it easy to maintain and extend

<h2>Technologies Used</h2>

- Python
- Requests Library:
    - Facilitates HTTP requests to communicate with the OpenWeatherMap API.
- JSON:
    - Parses the API response to extract and display weather details.
- APIs:
    - Integration with the OpenWeatherMap API for real-time data.

<h2>How to Use the Weather App</h2>


    API Key Setup:
        Sign up at OpenWeatherMap to obtain a free API key.
        Replace the placeholder <YOUR_API_KEY> in the code with your actual API key.

    Installation:
        Ensure Python is installed on your system.
        Install the requests library if you haven't already:

    pip install requests

Running the Application:

    Save the script as weather_app.py.
    Run the script from your terminal:

        python weather_app.py

        Enter a city name when prompted to view its current weather data.

<h2>Example Output</h2>

Welcome to the Weather App!

Enter the city name: London

Weather in London, GB:

- Description: Light rain
- Temperature: 15°C
- Humidity: 82%
- Wind Speed: 4.1 m/s

<h2>Conclusion</h2>

This Weather App project is a practical example of how to integrate external APIs into Python applications. It provides a solid foundation in working with HTTP requests, data parsing, and user interaction, making it a valuable addition to your portfolio for showcasing your intermediate-level programming skills.

<h2></h2>
<p align="center">
  <a href="https://github.com/rlangc"><b>Return to Home</b></a>
