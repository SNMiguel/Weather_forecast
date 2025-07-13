# ⛅ Weather Forecast App

A sleek, Python-powered desktop weather app built with `Tkinter`, `OpenWeatherMap API`, and real-time geolocation using `Geopy` and `TimezoneFinder`. This app gives you current weather plus a 7-day forecast with icons, all packed in a clean GUI.

---

## 🌍 Features

- 📍 Search weather by **city name**
- 🕐 Shows **local time & timezone**
- 🌡️ Displays **temperature, wind, humidity, pressure, and description**
- 📅 7-day weather forecast with **daily icons**
- 🖼️ Styled with **custom graphics** and image assets

---

## ⚙️ Technologies Used

- **Python 3**
- `Tkinter` (GUI)
- `Geopy` (location → lat/long)
- `TimezoneFinder` (get timezone)
- `OpenWeatherMap API` (weather data)
- `PIL` / `ImageTk` (load images)
- `.env` file for API key (secure practice)

---

## 🛠️ Setup Instructions

### 1. Clone the repo

```bash
git clone https://github.com/YourUsername/weather-app.git
cd weather-app

### 2. Create a .env file in the root directory

```bash
touch .env

### 3. Add your own OpenWeatherMap API key:

WEATHER_API_KEY=your_openweathermap_api_key_here
