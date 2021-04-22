# Weather API

![npm](https://img.shields.io/npm/v/@alisherbegmatov/date-lib)
![NPM](https://img.shields.io/npm/l/@alisherbegmatov/date-lib)
![GitHub repo size](https://img.shields.io/github/repo-size/alisherbegmatov/date-lib)
![GitHub issues](https://img.shields.io/github/issues/alisherbegmatov/date-lib)

## Description

### A library that can be used by anyone who wants to use the OpenWeatherMap API in any project they might create.

this repository is powered by [Open Weather Map API](https://openweathermap.org).

1. **`getWeatherByZip()`** allows searching by zip code.

- `(params)` are:
- `zip`: A 5 digit USA based zip code
- `apiKey`: You will need to input your own API Key for your project.
- `units`: No entry will default to 'imperial', but options are 'metric' or 'kelvin'

2. **`getWeatherByCity()`** allows searching by city name.

- `params` are:
- `city`: City Name
- `apiKey`: Your API Key
- `units`

3. **`getWeatherByGeo()`** allows searching with Latitude & Longitude.

- `params` are:
- `lat`: Latitude
- `lon`: Longitude
- `apiKey`: Your API Key
- `units`
