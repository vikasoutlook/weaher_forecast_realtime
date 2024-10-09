# Weather Forecast App

## Overview
This Weather Forecast App is a simple web application that allows users to check the current weather and 5-day forecast for any city. It uses the OpenWeatherMap API to fetch weather data and provides a user-friendly interface for displaying the information.

## Features
- Search weather by city name
- Get weather for current location
- Display current weather conditions including temperature, humidity, and wind speed
- Show 5-day weather forecast
- Recent searches functionality
- Responsive design for various screen sizes

## Technologies Used
- HTML5
- CSS3 (with Tailwind CSS framework)
- JavaScript (ES6+)
- OpenWeatherMap API

## Setup
1. Clone this repository to your local machine.
2. Open the `index.html` file in a web browser.
3. Ensure you have an active internet connection for the app to fetch weather data.

## API Key
The app uses an OpenWeatherMap API key to fetch weather data. For security reasons, it's recommended to keep API keys private. In a production environment, you should:
1. Set up a server to handle API requests.
2. Store the API key securely on the server.
3. Make requests to your server, which then communicates with the OpenWeatherMap API.

## Usage
1. Enter a city name in the search box and click "Search" or press Enter.
2. Click "Use My Location" to get weather data for your current location (requires geolocation permission).
3. Select a recently searched city from the dropdown menu to quickly access its weather information.
4. View the current weather conditions and 5-day forecast displayed on the page.

## File Structure
- `index.html`: The main HTML file containing the structure of the web page.
- `js/script.js`: The JavaScript file containing all the functionality of the app.
- `README.md`: This file, containing documentation for the project.

## Future Improvements
- Add more detailed weather information (e.g., feels like temperature, pressure, visibility).
- Implement unit conversion (e.g., Celsius to Fahrenheit).
- Add charts or graphs for visualizing weather trends.
- Improve error handling and user feedback.
- Implement caching to reduce API calls for frequently searched cities.

## Contributing
Contributions to improve the app are welcome. Please follow these steps:
1. Fork the repository.
2. Create a new branch for your feature.
3. Make your changes and commit them with clear, descriptive messages.
4. Push your changes to your fork.
5. Submit a pull request with a description of your changes.

## License
This project is open source and available under the [MIT License](LICENSE).

## Acknowledgements
- Weather data provided by [OpenWeatherMap](https://openweathermap.org/)
- Icons from [OpenWeatherMap](https://openweathermap.org/weather-conditions)
- Styling assisted by [Tailwind CSS](https://tailwindcss.com/)
