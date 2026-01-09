🌦 Weather Forecast App (Python Tkinter)
A simple GUI-based Weather Forecast Application built using Python Tkinter and OpenWeatherMap API.
It allows users to enter a place name and view real-time weather information such as temperature, humidity, wind speed, and weather conditions.
📌 Features
User-friendly Tkinter GUI
Real-time weather data
Displays:
🌡 Temperature (°C)
☁ Weather description
💧 Humidity
🌬 Wind speed
Error handling for invalid input or API failure
🛠 Technologies Used
Python
Tkinter (GUI)
Requests library
OpenWeatherMap API
📂 Project Structure
weather-app/
│── weather.py
│── README.md
🔑 Prerequisites
Python 3.x
Internet connection
OpenWeatherMap API Key
📦 Required Libraries
Install the required library using:
pip install requests
🔐 Get OpenWeatherMap API Key
Go to 👉 https://openweathermap.org/api
Sign up / log in
Generate an API key
Copy the key
⚙ Configuration
In your Python file, replace the following:
api_key = "ENTER_YOUR_API_KEY_FROM_OPEN_WEATHER_MAP"
base_url = "ENTER_THE_BASE_URL_OF_OPENWEATHERMAP"
With:
api_key = "your_api_key_here"
base_url = "https://api.openweathermap.org/data/2.5/weather"
▶ How to Run the Application
python weather.py
🖥 Application UI
Enter a place name
Click Get Weather Data
View weather details instantly
❗ Common Errors
Invalid city name → Shows error message
No internet / wrong API key → Data fetch fails
🚀 Future Enhancements
Add weather icons
Show 7-day forecast
Save search history
Dark mode UI
