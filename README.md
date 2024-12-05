# Weather App

Weather App is a simple weather application built using React Native and TypeScript. The app provides current weather information using the OpenWeatherMap API.

## Features

- Fetch weather information by city name
- Display temperature, humidity, and weather descriptions
- Modern and stylish user interface

## Requirements

- Node.js (>= 14.x)
- React Native CLI
- Android Studio or Xcode (for iOS)

## Installation

1. Clone the project:

    ```bash
    git clone https://github.com/madtethys/havadurumu.git
    cd havadurumu
    ```

2. Install dependencies:

    ```bash
    npm install
    ```

3. Install platform dependencies for Android or iOS:

    Android:
    ```bash
    npx react-native run-android
    ```

    iOS (requires macOS):
    ```bash
    npx react-native run-ios
    ```

## Adding API Key

You will need an OpenWeatherMap API key to fetch weather data.

1. Get your API key from [OpenWeatherMap](https://openweathermap.org/).
2. Add your API key to the `API_KEY` variable in the `App.tsx` file:

    ```typescript
    const API_KEY = 'YOUR_API_KEY';
    ```

## Usage

1. After launching the app, enter a city name in the input field.
2. Press the "Get Weather" button to display the weather information.

## Project Structure

- **App.tsx**: Main application component. Takes city input and makes API requests.
- **components/Weather.tsx**: Component that displays weather data.
- **styles**: Application style files.

## Technologies Used

- **React Native**: Framework for mobile app development.
- **TypeScript**: Provides static type checking and safer code.
- **Axios**: Used for making HTTP requests.
- **OpenWeatherMap API**: API providing weather data.

## Development

1. Start the development mode with `npm start`.
2. You can live reload the app to see code changes on the device.

## License

This project is licensed under the Apache License 2.0. For details, see the [LICENSE](./LICENSE) file.
