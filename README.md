
# Weather App 
   - webpage which shows current weather condition of entered Geolocation.

# Overview :
The Weather App is a simple web application that allows users to enter a city name or use their current location to fetch and display the current weather conditions. The weather data is retrieved from the OpenWeatherMap API.

# Features:

      - City Search: Users can enter the name of a city to get the current weather conditions.
      
      - Geolocation: Users can allow the app to use their current location to fetch weather data.
      
      - Weather Display: The app displays weather icon, temperature, description, and location on a separate page.

# How It Works
1. User Input: 
     - Users can type a city name in the search bar and press Enter.
     - Users can click the location icon to use their current location.
       
2. Fetching Data: 
   - The app fetches weather data from the OpenWeatherMap API based on the city name or geolocation.

3. Storing Data: 
   - The fetched weather data is stored in `localStorage`.

4. Display Data: 
   - The app redirects to a weather details page (`weather.html`) where the stored data is retrieved and displayed.

# Technologies Used

    - HTML, CSS, JavaScript
    
    - OpenWeatherMap API

# Getting Started

      1. Clone the repository.
      
      2. Open `index.html` in a web browser.
      
      3. Enter a city name or click the location icon to see the current weather.
      

# Example

      - Enter "London" and press Enter to see London's weather.
      
      - Click the location icon to fetch and display your current location's weather.
      

---
