# 🌦️ Weather App (React)

A simple weather search application built with **React** and the OpenWeatherMap API. Enter a city name to view current conditions such as temperature, humidity, wind speed, and weather icons.

---

## ✨ Features

- 🔍 Search weather by city
- 🌡️ Display temperature, conditions, humidity, and wind speed
- 🎨 Responsive, clean UI with weather icons
- ⚠️ Error handling for invalid cities
- 🔑 Uses `.env` for API key security

---

## 🧰 Tech Stack

- React (with hooks)
- Vite
- CSS (custom or Tailwind)
- OpenWeatherMap API

---

## ▶️ Run Locally

Clone the project:

    git clone https://github.com/danish-hussain-dev/weather-app.git
    cd weather-app
    npm install
    npm run dev

---

## 🔐 Environment Variables

To run this project, you need an API key from [OpenWeatherMap](https://openweathermap.org/api).

Create a `.env` file in the root directory and add:

    VITE_WEATHER_API_KEY=your_api_key_here

In the code, access it like this:

    const apiKey = import.meta.env.VITE_WEATHER_API_KEY;

---

## 📸 Screenshots

Here’s how the app looks:

![Weather App Screenshot](./screenshots/hero.png)

---

## 📁 Project Structure

    src/
      assets/
      components/
        Weather.jsx
        Weather.css
      App.jsx
      main.jsx

---

## 📝 Notes

This project demonstrates:

- API integration
- Async data fetching with `fetch`
- State management with React hooks
- Handling loading and error states
- Clean, responsive UI design
