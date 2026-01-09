# 🌦 Weather Forecast App (Python Tkinter)

A simple GUI-based Weather Forecast Application built using **Python Tkinter** and **OpenWeatherMap API**.  
The app allows users to enter a place name and fetch real-time weather details.

---

## 📌 Features
- Simple and clean Tkinter GUI
- Fetches real-time weather data
- Displays:
  - 🌡 Temperature (°C)
  - ☁ Weather description
  - 💧 Humidity
  - 🌬 Wind speed
- Error handling for empty input and API failure

---

## 🛠 Technologies Used
- Python 3
- Tkinter (GUI)
- Requests library
- OpenWeatherMap API

---

## 📂 Project Structure
weather-app/ 
│── weather.py
│── README.md
---

## 🔑 Prerequisites
- Python 3.x installed
- Internet connection
- OpenWeatherMap API key

---

## 📦 Required Library
Install requests library using:
```bash
pip install requests
```
🔐 OpenWeatherMap API Setup

Visit https://openweathermap.org/api

Sign up or log in

Generate an API key

⚙ Configuration
Replace the following lines in the code:
api_key = "ENTER_YOUR_API_KEY_FROM_OPEN_WEATHER_MAP"
base_url = "ENTER_THE_BASE_URL_OF_OPENWEATHERMAP"

🖥 How It Works
Enter a place name
Click Get Weather Data
Weather details are displayed on the screen
❗ Error Handling
Shows error if place name is empty
Shows error if API request fails or city not found
🚀 Future Enhancements
Weather icons
7-day forecast
Dark mode UI
Save recent searches
