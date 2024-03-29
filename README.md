## Weather App

## Overview
**The Weather App** is a Flask-based web application that provides current weather conditions using the OpenWeather API. 

It allows users to input a location and receive weather updates.

## Features
The application does the following:

* [✓] User Authentication: Secure login page with email and password fields.
* [✓] Form to enter OpenWeather API key, zip code, and country code.
* [✓] Error handling for incorrect API keys or unavailable weather data.
* [✓] Real-time weather display
* [✓] Weather icons to visually represent current conditions.
  
## Usage
* Access the login page, authenticate, and navigate to the dashboard.
* Input your API key, zip code, and country code.
* View the weather conditions displayed on the dashboard.

## App demo
<img src='demo.gif' title='Video Demo' width='400' alt='Video Demo' />

## File Structure
* 'result.py': Main Flask application script with route definitions.
* 'weather.py': Python class for OpenWeather API interaction.
* 'login.html', 'dashboard.html', 'weather_display.html': HTML pages for the respective app sections.
* 'login.css', 'dashboard.css', 'weather_display.css': Styling for the HTML pages.

## Setup
* Obtain an API key from <a href="https://www.oracle.com/java/technologies/downloads/" target="_blank">OpenWeather</a> Obtain an API key
* Install dependencies: Flask.
* Run 'result.py' to start the server.
