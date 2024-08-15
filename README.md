# Weather Application

A simple weather application built with Python and Tkinter that provides real-time weather information for cities worldwide.

## Features

- Search weather information by city or country name
- Displays current temperature in both Celsius and Fahrenheit
- Shows weather condition, humidity, and pressure
- User-friendly graphical interface
- Real-time data fetched from OpenWeatherMap API

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Python 3.x installed
- Required Python libraries: tkinter, requests, Pillow (PIL)

## Installation

1. Clone the repository:
   ```python
   git clone https://github.com/yourusername/weather-application.git
2. Navigate to the project directory:
   ```python
   cd weather-application

## Usage

1. Run the application:
   ```python
   python weather.py
2. Enter a city or country name in the text field.
3. Click the "Search" button to retrieve weather information.

## API Key

This application uses the OpenWeatherMap API. You need to replace the `api_key` in the `weather.py` file with your own API key:

```python
self.api_key = 'Your_API_Key_Here'
