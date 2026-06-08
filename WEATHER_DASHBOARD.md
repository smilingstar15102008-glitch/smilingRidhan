# 🌤️ Weather Dashboard

A beautiful, responsive weather dashboard that fetches real-time weather data from a public API.

## Features

- **🌍 Real-time Weather Data** - Get current weather conditions for any location
- **📍 Geolocation Support** - Automatically detect your location and fetch local weather
- **📅 7-Day Forecast** - View weather predictions for the next week
- **🕐 Hourly Forecast** - Check weather conditions for the next 24 hours
- **🌡️ Temperature Units** - Toggle between Celsius and Fahrenheit
- **📱 Fully Responsive** - Works perfectly on desktop, tablet, and mobile devices
- **✨ Beautiful UI** - Modern gradient design with smooth animations
- **⚡ Fast & Lightweight** - No dependencies, pure vanilla JavaScript
- **🔄 Real-time Updates** - Search for any city worldwide

## How to Use

### Open the Dashboard
Open `weather.html` in your web browser to start.

### Search for a Location
1. Enter a city name in the search box
2. Click the "Search" button or press Enter
3. View the current weather and forecasts

### Use Your Location
- Click the 📍 button to get weather for your current location
- Allow browser geolocation access when prompted

### Change Temperature Units
- Click **°C** for Celsius (km/h wind speed)
- Click **°F** for Fahrenheit (mph wind speed)

## Weather Information Displayed

### Current Weather
- **Temperature** - Real-time temperature
- **Conditions** - Weather description (clear, cloudy, rainy, etc.)
- **Humidity** - Moisture percentage
- **Wind Speed** - Current wind speed
- **Pressure** - Atmospheric pressure
- **Coordinates** - Latitude and longitude
- **Timezone** - Local timezone

### 7-Day Forecast
- High and low temperatures
- Weather conditions
- Weather emoji for quick visual reference

### 24-Hour Forecast
- Hourly temperature readings
- Weather conditions by hour
- Scrollable horizontal layout

## API Information

This dashboard uses the **Open-Meteo API**, which is:
- ✅ **Free** - No API key required
- ✅ **Open Source** - Available to everyone
- ✅ **Reliable** - High uptime and accuracy
- ✅ **Fast** - Quick response times
- ✅ **No Tracking** - Privacy-friendly

### API Endpoints Used

1. **Open-Meteo Weather API**
   - `https://api.open-meteo.com/v1/forecast`
   - Gets current weather, hourly, and daily forecasts

2. **Nominatim Geocoding API** (OpenStreetMap)
   - `https://nominatim.openstreetmap.org/search`
   - Converts city names to coordinates
   - `https://nominatim.openstreetmap.org/reverse`
   - Converts coordinates to location names

## Technologies Used

- **HTML5** - Structure
- **CSS3** - Styling with gradients and animations
- **Vanilla JavaScript** - All functionality without frameworks
- **Fetch API** - Making API requests
- **Geolocation API** - Getting user's location
- **Responsive Design** - Mobile-friendly layout

## Weather Codes

The dashboard interprets WMO (World Meteorological Organization) weather codes:

- **0** - Clear sky ☀️
- **1-2** - Mainly clear/Partly cloudy 🌤️
- **3** - Overcast ☁️
- **45-48** - Foggy 🌫️
- **51-55** - Drizzle 🌧️
- **61-65** - Rain 🌧️
- **71-77** - Snow ❄️
- **80-82** - Rain showers 🌧️
- **85-86** - Snow showers ❄️
- **95-99** - Thunderstorms ⛈️

## Browser Compatibility

- ✅ Chrome/Chromium
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ✅ Mobile browsers

## Responsive Breakpoints

- **Desktop** - Full layout with all information visible
- **Tablet** - Optimized grid layout
- **Mobile** - Stacked layout for easy scrolling

## Limitations

- Requires internet connection
- Geolocation requires browser permission
- City search works with OpenStreetMap data

## Future Enhancements

- [ ] Weather alerts and warnings
- [ ] Historical weather data
- [ ] Weather radar/satellite imagery
- [ ] Air quality index (AQI)
- [ ] UV index information
- [ ] Sunrise/sunset times
- [ ] Local time display
- [ ] Favorite locations
- [ ] Weather maps
- [ ] Severe weather notifications

## Example Usage

```html
<!-- Just open the HTML file in your browser -->
<a href="weather.html" target="_blank">Open Weather Dashboard</a>
```

## Troubleshooting

### "City not found" Error
- Check spelling of city name
- Try using a larger city
- Use quotes for multi-word cities

### Geolocation Not Working
- Check browser permissions
- Ensure HTTPS connection (or localhost)
- Try searching for a city instead

### Weather Data Not Loading
- Check internet connection
- Refresh the page
- Try a different city

## Credits

- Weather Data: [Open-Meteo](https://open-meteo.com/)
- Geocoding: [OpenStreetMap Nominatim](https://nominatim.openstreetmap.org/)
- Weather Icons: Emoji

## License

Free to use and modify!

---

**Last Updated:** June 2026
**Created by:** smilingstar15102008-glitch
