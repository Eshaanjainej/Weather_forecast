# Weather Forecast Application
### Problem Statement
Keeping track of weather conditions is essential for planning daily activities, travel, and outdoor events. However, accessing accurate and up-to-date weather forecasts can be challenging, especially when using traditional weather websites or applications. Users often need to navigate through complex interfaces or rely on inaccurate data sources.

This project aims to address these challenges by developing a user-friendly weather forecast application using a Tkinter GUI model. The application gathers real-time weather data from the OpenWeatherMap API to provide users with accurate and reliable weather forecasts for their desired location.

### Project Overview
The Weather Forecast Application is a GUI-based model built using the Tkinter library in Python. It leverages the OpenWeatherMap API to fetch current weather data for a specified location. The application offers users an intuitive interface to easily input their location and view detailed weather forecasts.

### Features
Real-time Weather Data: The application fetches real-time weather data from the OpenWeatherMap API, ensuring accuracy and reliability.
Location Input: Users can input their desired location, such as city name or zip code, to retrieve weather forecasts for that location.
Weather Details: Detailed weather information, including temperature, humidity, wind speed, and weather conditions, is displayed to users.
Intuitive Interface: The Tkinter-based GUI provides users with a simple and intuitive interface for accessing weather forecasts effortlessly.
Architecture
The project follows a Model-View architecture, where the GUI serves as the view, and the OpenWeatherMap API integration acts as the model.

Model: The OpenWeatherMap API serves as the model component, responsible for fetching weather data based on user input.
View: The Tkinter-based GUI serves as the view component, providing users with an interactive interface to input their location and view weather forecasts.
Controller: The controller manages user interactions, processes input data, and updates the view with the retrieved weather information.
API Used
The application utilizes the OpenWeatherMap API to fetch weather data. The API endpoint used for weather forecast retrieval is:

bash
Copy code
https://api.openweathermap.org/data/2.5/weather?q={city}&appid={API_KEY}
### Getting Started
To run the Weather Forecast Application locally, follow these steps:

Sign up for an account on OpenWeatherMap and obtain an API key.
Clone the repository to your local machine.
Install the required libraries using pip:
Copy code
pip install requests
Replace {API_KEY} in the code with your actual OpenWeatherMap API key.
Run the main Python file to start the application.

### Acknowledgments
Special thanks to the developers of Tkinter and OpenWeatherMap for their valuable resources and APIs, which made this project possible.
### project snippets
![Screenshot 2024-03-03 112218](https://github.com/Eshaanjainej/Weather_forecast/assets/150604431/dc1bbb5e-4be1-4987-a703-cf104fa7be65)
![Screenshot 2024-03-03 112147](https://github.com/Eshaanjainej/Weather_forecast/assets/150604431/6a82ba46-b01f-4909-884d-7b6e1a8c6697)
