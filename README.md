# Weather Information App

## Overview

The Weather Information App is a Java-based graphical user interface (GUI) application that provides real-time weather updates for a specified location. It leverages the OpenWeatherMap API to fetch current weather data, including temperature, humidity, wind speed, and weather conditions. The application also includes features for unit conversion, a forecast display (mock data), and maintains a history of searched locations.

## Features

- **Real-time Weather Data:** Fetches and displays current weather information based on user input.
- **Unit Conversion:** Supports conversion between Celsius and Fahrenheit, as well as km/h and mph.
- **Forecast Display:** Shows a mock 4-day weather forecast.
- **Search History:** Stores and displays a history of searched locations.
- **Dynamic GUI:** Changes background color based on current weather conditions.

## Getting Started

### Prerequisites

- Java Development Kit (JDK) 11 or later
- Internet connection for API access
- API Key for OpenWeatherMap (replace the provided API key with your own if needed)

## Configuration

1. Obtain an API Key from OpenWeatherMap.
2. Replace the API_KEY constant in the WeatherAPI class with your own API key.

## Usage

1. Launch the application by running the Main class.
2. Enter a location (e.g., city name) into the input field and click "Search."
3. View current weather information, including temperature, humidity, wind speed, and conditions.
4. Use the unit selector to switch between Celsius and Fahrenheit.
5. View the mock 4-day weather forecast and the search history on the GUI.

## Code Structure

- 'Main.java': Entry point of the application.
- 'UnitConverter.java': Contains methods for unit conversion.
- 'WeatherAPI.java': Handles API requests and data retrieval from OpenWeatherMap.
- 'WeatherAppGUI.java': Defines the graphical user interface and interaction logic.
- 'WeatherHistory.java': Manages the history of searched weather data.
- 'WeatherData.java': Represents weather data with temperature, humidity, wind speed, and condition.
- 'WeatherIconManager.java': Manages fetching and displaying weather icons.


## Example

Here is an example of the application in use:
1. Enter a location (e.g., "Jeddah") in the text field.
2. Click the "Search" button to fetch the weather data.
3. The current weather information will be displayed, including temperature, humidity, wind speed, and conditions.
4. The weather forecast will also be displayed below the current weather information.
5. Use the combo box to switch between Celsius and Fahrenheit units.
6. View previous searches in the search history list.


## Contributing

Contributions are welcome. Please open an issue or submit a pull request to propose changes or enhancements.

## License

This project is licensed under the MIT License.

