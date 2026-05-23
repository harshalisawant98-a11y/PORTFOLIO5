# portfolio5
openweathermap.html
# Weather API Integration Demo

This project demonstrates how to connect to the OpenWeatherMap API using JavaScript's `fetch()` method and display results in an attractive card layout.

## Setup
1. Copy the `index.html` file.
2. Insert your API key into the script (`const apiKey = "YOUR_KEY"`).
3. Open the file in a browser.

## Output
- Console: Full JSON response from the API.
- Webpage: Displays temperature, condition, and humidity in a styled card.

## Requirements
- Modern browser (Chrome, Edge, Firefox).
- Valid API key from [OpenWeatherMap](https://openweathermap.org/api).

## Example
Mumbai
🌡 Temperature: 32°C
☁ Condition: scattered clouds
💧 Humidity: 70%
london
🌡 Temperature : 33°C
☁ Condition: rainy clouds
💧 Humidity:80%
singapur
🌡 Temperature: 29°C
☁ Condition: few clouds
💧 Humidity: 95

---

## Endpoint Documentation

### Endpoint Used
https://api.openweathermap.org/data/2.5/weather?q={city}&appid={API_KEY}&units=metric (api.openweathermap.org in Bing)

- **q** → City name (e.g., `Mumbai`)
- **appid** → Your API key
- **units** → `metric` for Celsius, `imperial` for Fahrenheit

### Response Format (JSON)
```json
{
  "weather": [
    { "description": "scattered clouds" }
  ],
  "main": {
    "temp": 32.33.29.0,
    "humidity": 70,80,95
  },
  "name": "Mumbai,london,singapur"
}
