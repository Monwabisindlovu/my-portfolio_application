# WeatherApp - Your Personal Weather Station

## Overview
WeatherApp is a simple web application that provides users with real-time weather information for a specified location.
Users can input their location and retrieve weather details such as temperature, humidity, wind speed, and weather description.

## Backend
The backend of WeatherApp is built using Python with the Flask framework.
It fetches weather data from the OpenWeatherMap API and serves it to the frontend for display.

### Technologies Used (Backend)
- Python (Flask framework)
- OpenWeatherMap API

## Frontend
The frontend of WeatherApp is built using HTML, CSS (with Bootstrap), and Jinja2 templating engine.
It presents the weather data retrieved from the backend in a user-friendly manner.

### Technologies Used (Frontend)
- HTML
- CSS (Bootstrap)
- Jinja2 templating engine

## Features
- Get real-time weather updates based on user-provided location
- Display temperature in Celsius
- Show additional weather details including humidity, latitude, longitude, wind speed, and weather description
- Visual representation of weather conditions with weather icons
- Responsive design for seamless user experience on different devices

## How to Use
1. Clone or download the repository to your local machine.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Get an API key from [OpenWeatherMap](https://openweathermap.org/api) and replace `YOUR_API_KEY` in the code with your actual API key.
4. Run the Flask application by executing `python app.py` in your terminal.
5. Access the WeatherApp in your web browser by navigating to `http://localhost:5000`.

## Acknowledgements
- Weather data provided by [OpenWeatherMap](https://openweathermap.org/)

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

