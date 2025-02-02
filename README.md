# Weather App

## Overview
This is a simple command-line weather application written in Python. The app fetches and displays the current weather and a multi-day forecast for a given city using the SheCodes Weather API. The project was created as the final assignment for SheCodes Python Basics.

## Features
- Displays the current temperature of a city.
- Provides a multi-day weather forecast.
- Uses the SheCodes Weather API to fetch weather data.
- Nicely formatted output using the `rich` Python library.
- Includes a welcome message and credit acknowledgment.

## Prerequisites
Before running the script, make sure you have the following installed:
- Python 3
- Required Python packages: `requests` and `rich`

You can install the required dependencies using:
```sh
pip install requests rich
```

## How to Run the App
1. Clone this repository:
   ```sh
   git clone https://github.com/erikaalban/weather-app-python.git
   ```
2. Navigate to the project directory:
   ```sh
   cd weather-app-python
   ```
3. Run the script:
   ```sh
   python weather_app.py
   ```
4. Enter the name of the city when prompted.

## Code Breakdown
### Main Functions
- `display_temperature(day, temperature, unit="C")`: Prints the temperature for a given day in Celsius.
- `display_current_weather(city)`: Fetches and displays the current temperature for the specified city.
- `display_forecast_weather(city_name)`: Retrieves and prints the multi-day weather forecast.
- `credit()`: Displays the credit message.
- `welcome()`: Prints a welcome message at the start of the program.

### API Usage
The script fetches weather data from the SheCodes Weather API using:
- **Current Weather API:** `https://api.shecodes.io/weather/v1/current`
- **Forecast API:** `https://api.shecodes.io/weather/v1/forecast`

## Example Output
```
Welcome to my weather app
Enter a city: New York
Today: 22ºC

Forecast:
Monday: 20ºC
Tuesday: 18ºC
Wednesday: 21ºC
Thursday: 19ºC

This app was built by Erika Alban.
```

## Certificate
This project was created as part of the **SheCodes Python Basics** course, and I have successfully received my certificate. You can view it here:
[SheCodes Certificate](https://www.shecodes.io/certificates/f49e1b0c714f2a3f7ef53de1760c7c5a)

## Author
**Erika Alban**

## License
This project is for educational purposes and is open for learning and improvements.
