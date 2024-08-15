# Weather App

## Overview

This is a simple weather application that provides current weather information based on the user's location or a city search input. The application leverages the OpenWeatherMap API to fetch real-time weather data.

## Files

- `Weather.html`: The main HTML file that structures the application layout.
- `Weather.css`: The CSS file that styles the application.
- `Weather.js`: The JavaScript file that handles the application logic and API interactions.

## Features

- User Location Weather: Automatically fetches and displays weather data based on the user's current location.
- City Search Weather: Allows users to search for weather information by entering a city name.
- Weather Details: Displays city name, country flag, weather description, temperature, humidity, wind speed, and cloudiness.

## Getting Started

### Prerequisites

- Basic knowledge of HTML, CSS, and JavaScript.
- An API key from [OpenWeatherMap](https://openweathermap.org/api).

### Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/weather-app.git
   cd weather-app

2. Insert your OpenWeatherMap API key:

  Open Weather.js.
  Replace the API_key value with your OpenWeatherMap API key:
  const API_key = "your_api_key_here";

3. Open Weather.html in your web browser:
   open Weather.html
4.File Descriptions
    Weather.html
    This file contains the HTML structure of the weather application. It includes the main container, tabs for user location weather and city search, and sections for       displaying weather data.

5. Weather.css
   This file styles the weather application, ensuring a responsive and visually appealing layout. Key styles include:

  Root variables for colors.
  Flexbox for layout management.
  Media queries for responsiveness.
  Weather.js
  This file contains the JavaScript logic to:

 Switch between the user location tab and the city search tab.
 Fetch and display weather data using the OpenWeatherMap API.
 Handle user interactions, such as granting location access and submitting the city search form.
