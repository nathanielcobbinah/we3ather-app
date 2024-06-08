# Weather App

Welcome to the Weather App! This project allows users to enter a city name and see the current weather conditions (temperature, wind speed, humidity) along with a 5-day forecast. The app fetches data from the OpenWeatherMap API and displays it in a user-friendly format using HTML, CSS (Tailwind CSS), and JavaScript.

## Table of Contents

1. [Project Overview](#project-overview)
2. [Features](#features)
3. [Installation](#installation)
4. [Usage](#usage)
5. [API Integration](#api-integration)
6. [Technologies Used](#technologies-used)
7. [Project Structure](#project-structure)
8. [Contributing](#contributing)
9. [License](#license)
10. [Contact](#contact)

## Project Overview

The Weather App is a simple and intuitive application that allows users to check the current weather and get a 5-day forecast for any city in the world. It utilizes the OpenWeatherMap API to fetch real-time weather data and presents it in a clean and responsive interface.

## Features

- **Current Weather Conditions**: Get real-time data for temperature, wind speed, and humidity.
- **5-Day Forecast**: View weather predictions for the next five days.
- **Responsive Design**: The app is designed to work well on different screen sizes, including mobile devices.
- **User-Friendly Interface**: Easy to navigate and interact with the app.

## Installation

To set up the Weather App locally, follow these steps:

### Prerequisites

- Node.js installed on your machine.
- An API key from [OpenWeatherMap](https://openweathermap.org/api).

### Steps

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/nathanielcobbinah/weather-app.git
   ```

2. **Navigate to the Project Directory**:

   ```bash
   cd weather-app
   ```

3. **Install Dependencies**:

   ```bash
   npm install
   ```

4. **Create a `.env` File**:

   Create a `.env` file in the root directory and add your OpenWeatherMap API key:

   ```env
   REACT_APP_WEATHER_API_KEY=your_api_key_here
   ```

5. **Start the Development Server**:

   ```bash
   npm start
   ```

## Usage

1. **Open the App**:

   Navigate to `http://localhost:3000` in your web browser.

2. **Enter a City Name**:

   Use the search bar to enter the name of a city.

3. **View Weather Data**:

   The current weather conditions and 5-day forecast for the specified city will be displayed.

## API Integration

The app uses the OpenWeatherMap API to fetch weather data. Here’s a brief overview of how it integrates with the API:

- **API Key**: The API key is stored in an environment variable for security.
- **Endpoints**: The app uses the following endpoints:
  - Current Weather Data: `https://api.openweathermap.org/data/2.5/weather`
  - 5-Day Forecast: `https://api.openweathermap.org/data/2.5/forecast`
- **Fetching Data**: JavaScript's `fetch` function is used to make API requests and retrieve data in JSON format.

## Technologies Used

- **Frontend**: HTML, CSS (Tailwind CSS), JavaScript
- **API**: OpenWeatherMap API

## Project Structure

```
weather-app/
├── public/
│   ├── index.html
├── src/
│   ├── components/
│   │   ├── CurrentWeather.js
│   │   ├── Forecast.js
│   ├── App.js
│   ├── index.js
│   ├── styles.css
├── .env
├── package.json
├── README.md
```

- **public/**: Contains the HTML file for the app.
- **src/**: Contains JavaScript and CSS files.
  - **components/**: Contains React components for current weather and forecast.
  - **App.js**: Main React component.
  - **index.js**: Entry point for the React app.
  - **styles.css**: Tailwind CSS file.
- **.env**: Contains environment variables, including the API key.
- **package.json**: Lists the project dependencies and scripts.
- **README.md**: Project documentation.

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

Nathaniel Cobbinah - [nathanielamofah@gmail.com](mailto:nathanielamofah@gmail.com)

<!-- Project Link: https://github.com/nathanielcobbinah/weather-app -->
