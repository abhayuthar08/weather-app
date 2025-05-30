# 🌦️ Weather App

## 🔍 Description
This is a simple and elegant Weather Web App that allows users to check real-time weather information for any city around the world. The app fetches weather data from the OpenWeatherMap API and displays essential weather details such as:

🌡️ Temperature (in Celsius)

🌆 City name

💧 Humidity percentage

🌬️ Wind speed

☁️ Weather condition icon

## ✨ Features
Responsive and clean UI using HTML, CSS, and JavaScript

Live API integration with OpenWeatherMap

Error handling for invalid city names

Dynamic weather icons based on current conditions




## Acknowledgements

I would like to express my heartfelt gratitude to the developers and contributors of the following tools and platforms that made this project possible:

OpenWeatherMap for providing accurate and easy-to-use weather data APIs.

All the open-source communities and tutorials that helped me understand and build this project with HTML, CSS, and JavaScript.

## API Reference 

📡 API Reference
This project uses the OpenWeatherMap API to fetch real-time weather data based on the user’s input city.

🟢 Base URL:

https://api.openweathermap.org/data/2.5/weather

🔧 HTTP Method:GET


📥 Request Parameters:
Parameter	Type	Required	Description
q	string	Yes	Name of the city (e.g., London, Mumbai)
appid	string	Yes	Your unique API key from OpenWeatherMap
units	string	No	Measurement unit. Use metric for Celsius

🧪 Example API Call:

https://api.openweathermap.org/data/2.5/weather?q=Delhi&appid=1040b94f8aa597c393a87ea01e12d90b&units=metri

✅ Successful Response (Sample):

{
  "name": "Delhi",
  "main": {
    "temp": 32.0,
    "humidity": 55
  },
  "wind": {
    "speed": 4.1
  },
  "weather": [
    {
      "main": "Clear"
    }
  ]
}


❌ Error Response (Example - Invalid City):

{
  "cod": "404",
  "message": "city not found"
}
## Deployment

Live Demo : https://to-do-app-delta-rust.vercel.app/
```

