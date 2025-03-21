# Laboratory Assessment 4 - Weather App

# Project Description

This Weather App provides real-time weather updates and forecasts for any location worldwide. It is built using Next.js and TypeScript, utilizing modern UI components for a clean and intuitive design. The app is deployed via Vercel for seamless accessibility.

Vercel: https://v0-react-weather-app-lac.vercel.app

## Features Overview

- Search for weather data by city or location
- Display current weather conditions (temperature, humidity, wind speed, etc.)
- 7-day weather forecast
- Error handling for invalid locations or API failures
- Responsive UI with Tailwind CSS

### API Source:
The application fetches weather data from the OpenWeatherMap API. This API provides comprehensive weather data, including real-time and forecast information.

#### Usage of useState and useEffect:

- useState: Used to manage state variables such as the search input, fetched weather data, and error messages.
- useEffect: Used to trigger API calls when the user searches for a location or when the component mounts.

## Setup Instructions

1. Clone the repository:

git clone <repository-url>

2. Navigate to the project directory:

cd weather-app

3. Install dependencies:

npm install or yarn install

4. Set up environment variables (e.g., API key for OpenWeatherMap) in a .env.local file:

NEXT_PUBLIC_WEATHER_API_KEY=your_api_key_here

5. Start the development server:

npm run dev or yarn dev

6. Open http://localhost:3000 in your browser.
   
## Technologies Used

 - Next.js (React framework for SSR and performance optimization)

- TypeScript (for type safety and better developer experience)

- Tailwind CSS (for styling and UI components)

- OpenWeatherMap API (for weather data)

- Vercel (for deployment)


This documentation provides a comprehensive guide for understanding, setting up, and using the Weather App effectively.
