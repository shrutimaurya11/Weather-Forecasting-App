# Weather Forecasting App 🌤️

A simple weather dashboard application that provides the current weather and a 5-day forecast for any city using the OpenWeatherMap API. It also has a feature to get the weather of your current location using geolocation.

## Features

- 🌍 **Search by City**: Enter the name of a city to get current weather and 5-day forecast.
- 📍 **Current Location**: Use your device's location to get the weather forecast.
- 📅 **5-Day Forecast**: See the weather forecast for the next 5 days.
- 📊 **Detailed Weather Info**: Displays temperature, wind speed, humidity, and weather icon.

## Technologies Used

- HTML
- CSS
- JavaScript
- [OpenWeatherMap](https://openweathermap.org/) API for weather data

## How to Use

1. **Clone the Repository**:
     ```bash
     git clone https://github.com/Punamkumari10/Weather-Forecasting-App.git
     cd weather-forecasting-app
     ```

2. **Open the project folder and edit the script.js file. Replace the API_KEY with your own API key from OpenWeatherMap**:
     ```bash
     const API_KEY = "your_api_key_here";
     ```
3. **Open `index.html` in your browser.**
   - Enter a city name in the input field and click "Search" to see the weather details for that city.
   - Click "Use Current Location" to get the weather of your current location.

## Usage

1. **Enter City Name**: Type the name of a city and click `Search`.
2. **Use Current Location**: Click `Use Current Location` to get the weather for your current geographical position.

## Screenshots

### Main Interface
![Weather App Main Screen](https://github.com/Punamkumari10/Weather-Forecasting-App/blob/main/screenshots/main.png)

### Weather Forecast
![Weather Forecast](https://github.com/Punamkumari10/Weather-Forecasting-App/blob/main/screenshots/weather_forecast.png)

## Getting an OpenWeatherMap API Key

1. Go to the [OpenWeatherMap](https://openweathermap.org/) website and sign up if you don’t have an account.
2. Navigate to the API keys section under your account.
3. Create a new API key and copy it.
4. Replace the placeholder in script.js with your API key.

## Project Structure

```plaintext
weather-dashboard-app/
│
├── index.html            # Main HTML file
├── style.css             # CSS file for styling
├── script.js             # JavaScript file for functionality
└── screenshots/          # Folder for screenshots
    ├── main.png   # Screenshot of the main screen
    └── weather.png # Screenshot of the weather forecast
```
## License

This project is licensed under the MIT License. See the [LICENSE](https://github.com/Punamkumari10/Weather-Forecasting-App/blob/main/License/MIT%20License) file for details.

## Acknowledgements

- [OpenWeatherMap](https://openweathermap.org/) for providing the weather data.
- Icons used from OpenWeatherMap.

