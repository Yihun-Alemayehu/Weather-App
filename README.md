# Weather App Documentation

## Overview

The Weather App is a mobile application developed using the Flutter framework for displaying weather information. It provides users with real-time weather data and forecasts for their location or any other specified location.

## Features

- Display current weather conditions, including temperature, humidity, wind speed, and more.
- Show a 5-day weather forecast with detailed information for each day.
- Allow users to search for weather information based on location or city name.
- Support for refreshing weather data to fetch the latest updates.

## Screens

### Home Screen

- The home screen displays the current weather information for the user's location.
- Users can pull down to refresh the weather data.
- It includes the option to search for weather information for a specific location.

### Weather Details Screen

- This screen provides detailed weather information for a specific location.
- It shows the 5-day weather forecast with detailed data for each day.

## Architecture

The app follows a modular architecture with the following components:

- **WeatherBloc**: Manages the business logic for fetching and processing weather data.
- **WeatherRepository**: Handles the data retrieval from external weather APIs.
- **UI Components**: Contains the widgets for displaying weather information and user interactions.

## Dependencies

The app uses the following dependencies:

- `http`: For making HTTP requests to fetch weather data from external APIs.
- `flutter_bloc`: For state management using the BLoC pattern.
- Other weather-related API packages for fetching weather data.

## Future Enhancements

- Integration with additional weather APIs for more accurate and comprehensive weather data.
- Support for user authentication and personalized weather settings.
- Implementation of push notifications for weather alerts and updates.

## Getting Started

To run the app locally, make sure you have Flutter and Dart installed on your development environment. Clone the repository, install the dependencies using `flutter pub get`, and run the app using `flutter run`.

## Contributors

- Yihun Alemayehu : Lead Developer
- Zerihun Kassahun : Testing and QA

## License

The Weather App is licensed under Yihun Alemayehu. You can find the full license details in the LICENSE file.
