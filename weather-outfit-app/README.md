# Weather, Worn

A responsive, single-file weather-and-outfit app built with HTML, CSS, and vanilla JavaScript in `index.html`. Search for a city, see its current forecast, and get a practical outfit idea with an illustrative outfit photo.

## Features

- Search cities worldwide using Open-Meteo's free geocoding service.
- Current conditions, feels-like temperature, daily high/low, precipitation, wind, and UV index.
- Switch between Celsius and Fahrenheit; your choice is remembered in the browser.
- Weather-aware outfit suggestions with photos, clothing tags, and rain/wind/sun tips.
- **Quick-step check:** an original 0–100 outdoor comfort score combining how the air feels, precipitation, and wind.
- Responsive layout and helpful loading/error messages.

## Run locally

Open `index.html` in a browser, or use Visual Studio Code's Live Server extension. All app markup, styles, and JavaScript are in this file. The app uses Open-Meteo's public APIs and Unsplash-hosted photos, so an internet connection is required. No API key or build step is needed.

## Publish on GitHub Pages

Push this folder to a GitHub repository, then enable GitHub Pages in the repository's **Settings → Pages**. Choose the branch and folder where `index.html` lives. The app is plain static HTML, CSS, and JavaScript.

## Copilot prompt

> Make a simple weather app using HTML, CSS, and vanilla JavaScript. Use the free Open-Meteo forecast API for current conditions and add city search with Open-Meteo Geocoding. Suggest practical outfits based on feels-like temperature, rain, wind, and UV; include outfit images, a Celsius/Fahrenheit switch, and an original outdoor comfort score. Make it responsive and ready to publish on GitHub Pages, with no API key or build tools.
