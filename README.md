# Weather App Android Studio
A simple app for creating Weather Application using Android Studio

# Screenshot

![image](https://user-images.githubusercontent.com/13933391/84575355-1d9c4100-adca-11ea-9d9b-16050ff408ed.png)

# Features
1. Uses https://openweathermap.org/ API for fetching current weather
2. Detects users location and accordingly fetches the weather from the API and display it to the user.
3. Display different weather images according to the climate.
4. Display Temperatur, Humidity, Pressure, Weather Condition, Location name, updated time.

These are some basic features that are available in the app but can be extended since we receive a lot of information from the openweathermap API in JSON format.
For example

```json
{"coord": { "lon": 139,"lat": 35},
  "weather": [
    {
      "id": 800,
      "main": "Clear",
      "description": "clear sky",
      "icon": "01n"
    }
  ],
  "base": "stations",
  "main": {
    "temp": 281.52,
    "feels_like": 278.99,
    "temp_min": 280.15,
    "temp_max": 283.71,
    "pressure": 1016,
    "humidity": 93
  },
  "wind": {
    "speed": 0.47,
    "deg": 107.538
  },
  "clouds": {
    "all": 2
  },
  "dt": 1560350192,
  "sys": {
    "type": 3,
    "id": 2019346,
    "message": 0.0065,
    "country": "JP",
    "sunrise": 1560281377,
    "sunset": 1560333478
  },
  "timezone": 32400,
  "id": 1851632,
  "name": "Shuzenji",
  "cod": 200
}
