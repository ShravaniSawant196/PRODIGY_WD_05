PRODIGY_WD_05: Weather Web Application
This project is a web-based weather application developed as part of the Prodigy Web Development Internship, Task 5. It allows users to fetch and display current weather conditions either by entering a city name or by detecting their current location using the browser's geolocation feature.

Features
City Search: Users can input any city name to retrieve its current weather data.

Current Location Detection: The application can automatically detect the user's geographical location (with permission) and display local weather.

Detailed Weather Display: Shows essential weather information including:

City Name

Temperature (in Celsius)

Weather Description (e.g., "clear sky", "partly cloudy")

Weather Icon

Humidity

Wind Speed

"Feels Like" temperature

Atmospheric Pressure

Error Handling: Provides user-friendly messages for city not found, API key issues, or geolocation errors.

Responsive Design: Built with Tailwind CSS for a clean, modern, and mobile-friendly interface.

Technologies Used
HTML: For structuring the application's user interface.

CSS: Custom styles are applied, augmented by Tailwind CSS, for visual appeal and responsiveness.

JavaScript: Handles all client-side logic, including:

Making API calls to OpenWeatherMap.

Processing and displaying weather data.

Handling user input and button clicks.

Implementing browser geolocation.

OpenWeatherMap API: Used to fetch accurate and up-to-date weather information.

Setup and Usage
Clone the repository (or download the weather.html file).

Obtain an API Key:

Go to https://openweathermap.org/api.

Sign up for a free account.

Navigate to the "API keys" section in your account dashboard and copy your default API key.

Insert API Key: Open weather.html in a text editor and replace 'YOUR_API_KEY_HERE' with your actual OpenWeatherMap API key:

const API_KEY = 'YOUR_API_KEY_HERE'; // Replace this line

Open the weather.html file in your web browser.
