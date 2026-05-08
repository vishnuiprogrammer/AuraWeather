# 🌤️ Aura Weather - Weather Forecast App

<div align="center">

![GitHub stars](https://img.shields.io/badge/stars-%E2%AD%90%E2%AD%90%E2%AD%90%E2%AD%90%E2%AD%90-brightgreen)
![License](https://img.shields.io/badge/license-MIT-blue)
![Version](https://img.shields.io/badge/version-1.0.0-success)
![API](https://img.shields.io/badge/API-OpenWeatherMap-orange)
![Status](https://img.shields.io/badge/status-Active-brightgreen)

A beautiful, responsive weather forecast application with real-time weather data.  
Built with **vanilla JavaScript**, **HTML5**, **CSS3**, and **OpenWeatherMap API**.

[🚀 Live Demo](#-live-demo) • [✨ Features](#-features) • [🛠️ Installation](#-installation) • [🔑 API Setup](#-api-setup) • [📖 Usage](#-usage) • [🤝 Contributing](#-contributing)

</div>

---

## 🎨 Preview

<div align="center">

### 🖥️ Desktop View
```
┌─────────────────────────────────────────────────────────┐
│  Aura Weather  [📍] [⚙️]                                 │
│                                                           │
│  Weather Forecast                                        │
│  Check the weather for any city                          │
│                                                           │
│  [🔍 Search city...]  [Search]                           │
│                                                           │
│  ╔═══════════════════════════════════════════════════╗  │
│  ║  Pune, IN              ☀️                          ║  │
│  ║  CLEAR SKY                                         ║  │
│  ║                                                    ║  │
│  ║  28°C                                              ║  │
│  ║  Feels like: 28°C    Humidity: 45%                 ║  │
│  ╚═══════════════════════════════════════════════════╝  │
│                                                           │
│  ┌──────────┐ ┌──────────┐ ┌──────────┐ ┌──────────┐  │
│  │ 💨 Wind  │ │ 📊 Press │ │ 👁 Visib │ │ ☁ Cloud  │  │
│  │ 2.62 m/s │ │ 1008 hPa │ │ 10 km    │ │ 2%       │  │
│  └──────────┘ └──────────┘ └──────────┘ └──────────┘  │
│                                                           │
│  [🏠 Home] [📅 Forecast] [❤ Saved] [👤 Profile]       │
└─────────────────────────────────────────────────────────┘
```

### 📱 Mobile View
```
┌─────────────────┐
│ Aura Weather    │
│ Weather Forecast│
│ [🔍 Search...] │
│ [Search]       │
│ ╔═════════════╗│
│ ║  28°C Pune  ║│
│ ║  CLEAR SKY  ║│
│ ╚═════════════╝│
│ [Wind][Press]  │
│ [Visib][Cloud] │
│ [Home] [+]     │
└─────────────────┘
```

</div>

---

## ✨ Features

<table>
<tr>
<td width="50%">

### 🌍 Core Features
- ✔️ **Search Weather** - Get weather for any city worldwide
- ✔️ **Real-time Data** - Live weather from OpenWeatherMap API
- ✔️ **Current Weather** - Temperature, conditions, description
- ✔️ **Weather Icon** - Dynamic icons based on conditions
- ✔️ **Temperature Unit** - Display in Celsius/Fahrenheit
- ✔️ **Responsive Design** - Works on all devices

</td>
<td width="50%">

### 📊 Weather Details
- ✔️ **Feels Like** - Perceived temperature
- ✔️ **Humidity** - Current humidity percentage
- ✔️ **Wind Speed** - Wind velocity in m/s
- ✔️ **Pressure** - Atmospheric pressure (hPa)
- ✔️ **Visibility** - Visibility distance (km)
- ✔️ **Cloud Cover** - Cloud percentage
- ✔️ **Sunrise/Sunset** - Daily sun timings
- ✔️ **Temperature Range** - Min/Max daily temps

</td>
</tr>
</table>

---

## 🌈 Weather Conditions Supported

| Condition | Icon | Condition | Icon |
|-----------|------|-----------|------|
| Clear | ☀️ | Mist | 🌫️ |
| Clouds | ☁️ | Smoke | 💨 |
| Rain | 🌧️ | Haze | 🌫️ |
| Drizzle | 🌦️ | Dust | 💨 |
| Thunderstorm | ⛈️ | Fog | 🌫️ |
| Snow | ❄️ | Sand | 💨 |

---

## 🛠️ Tech Stack

| Layer | Technology | Purpose |
|-------|-----------|---------|
| **Markup** | HTML5 | Semantic structure |
| **Styling** | CSS3 | Gradient design, animations |
| **Scripting** | Vanilla JavaScript (ES6+) | API calls, DOM manipulation |
| **API** | OpenWeatherMap REST API | Real weather data |
| **Icons** | Font Awesome 6.4.0 | Beautiful weather icons |
| **Storage** | localStorage API | Save preferences |

---

## 🚀 Quick Start

### Option 1: Direct File
```bash
# 1. Clone the repository
git clone https://github.com/vishnuiprogrammer/AuraWeather.git
cd AuraWeather

# 2. Open in browser
# Option A: Use VS Code Live Server
# - Install "Live Server" extension
# - Right-click index.html → "Open with Live Server"

# Option B: Direct browser
# - Double-click index.html

# 3. Get API Key (see API Setup section below)
# 4. Replace API_KEY in script.js
```

### Option 2: Python Server
```bash
# Python 3.x
python -m http.server 8000

# Then open: http://localhost:8000
```

---

## 📦 Installation

### Prerequisites
- ✅ Modern web browser (Chrome, Firefox, Safari, Edge)
- ✅ Internet connection (for API calls)
- ✅ OpenWeatherMap API Key (free)

### Step-by-Step Setup

```bash
# Step 1: Clone repository
git clone https://github.com/vishnuiprogrammer/AuraWeather.git

# Step 2: Navigate to folder
cd AuraWeather

# Step 3: Get API Key (see section below)

# Step 4: Update API Key in script.js
# Open script.js and replace:
# const API_KEY = '#####';
# with your own key

# Step 5: Open index.html in browser
```

### Project Structure
```
AuraWeather/
├── 📄 index.html          # Main HTML file
├── 🎨 style.css           # All styling (gradient, animations)
├── ⚙️ script.js            # JavaScript logic & API calls
├── 📖 README.md           # Documentation
└── 📁 assets/             # (Optional) Screenshots
    ├── desktop.png
    ├── mobile.png
    └── features.gif
```

---

## 🔑 API Setup (Important!)

### Get Your Free API Key

#### Step 1: Visit OpenWeatherMap
Go to: https://openweathermap.org/api

#### Step 2: Sign Up
- Click "Sign Up" → Create free account
- Verify your email

#### Step 3: Get API Key
- Login to your account
- Go to "API Keys" section
- Copy your API key (usually 32 characters)

#### Step 4: Update Code
Open `script.js` and replace:

```javascript
// OLD (Remove this)
const API_KEY = '***********';

// NEW (Add your key here)
const API_KEY = 'YOUR_API_KEY_HERE';
```

#### Step 5: Verify
- Search for a city in the app
- If weather displays → API key works! ✅
- If error → Check API key is correct

### API Rate Limits (Free Tier)
```
60 calls per minute
1,000,000 calls per month
```

---

## 📖 Usage

### Searching for Weather

```
1. Type city name in search box
2. Press Enter or click "Search" button
3. Weather data loads automatically
4. View all details in the main card
```

### Default Weather
```
First load shows Pune, India weather
You can change default city in script.js:

window.addEventListener('load', async () => {
    const data = await fetchCurrentWeatherByCity("Mumbai"); // Change city here
    displayWeatherInformation(data);
});
```

### Understanding Weather Data

| Field | Example | Meaning |
|-------|---------|---------|
| **Temperature** | 28°C | Current temperature |
| **Feels Like** | 32°C | Perceived temperature |
| **Humidity** | 65% | Moisture in air |
| **Wind Speed** | 5.5 m/s | Wind velocity |
| **Pressure** | 1008 hPa | Atmospheric pressure |
| **Visibility** | 10 km | How far you can see |
| **Cloud Cover** | 10% | Sky coverage percentage |
| **Sunrise/Sunset** | 6:00 AM | Sun timings |

---

## 🎨 Customization

### Change Color Scheme

Edit `style.css` - Update these CSS variables:

```css
/* Current theme: Purple gradient */
.weather-card {
  background: linear-gradient(135deg, #8b5cf6 0%, #7c3aed 100%);
}

.search-btn {
  background: linear-gradient(135deg, #7c3aed 0%, #a855f7 100%);
}

/* Change to Blue theme */
.weather-card {
  background: linear-gradient(135deg, #3b82f6 0%, #2563eb 100%);
}

.search-btn {
  background: linear-gradient(135deg, #2563eb 0%, #1d4ed8 100%);
}

/* Change to Green theme */
.weather-card {
  background: linear-gradient(135deg, #10b981 0%, #059669 100%);
}

.search-btn {
  background: linear-gradient(135deg, #059669 0%, #047857 100%);
}
```

### Change Default Temperature Unit

Currently: **Celsius**

To change to **Fahrenheit**, update script.js:

```javascript
// Change from metric to imperial
function buildURL(city) {
    return `https://api.openweathermap.org/data/2.5/weather?q=${city}&appid=${API_KEY}&units=imperial`;
    //                                                                                      ^^^^^^^^
    // Change "metric" to "imperial"
}

// Then update display text:
const temp_unit = "°F";  // Change from °C to °F
```

### Customize Font Family

```html
<!-- In index.html <head> -->
<link href="https://fonts.googleapis.com/css2?family=YOUR_FONT&display=swap" rel="stylesheet">
```

```css
/* In style.css */
body {
  font-family: 'YOUR_FONT', sans-serif;
}
```

### Add More Weather Icons

Edit the `getWeatherIcon()` function in script.js:

```javascript
function getWeatherIcon(weatherType) {
    const iconMap = {
        'Clear': 'fas fa-sun',
        'Clouds': 'fas fa-cloud',
        'Rain': 'fas fa-cloud-rain',
        // Add more here:
        'Hurricane': 'fas fa-hurricane',
        'Extreme': 'fas fa-triangle-exclamation'
    };
    return iconMap[weatherType] || 'fas fa-sun';
}
```

---

## ⚙️ Configuration

### Change Default City

In `script.js`, find this code:

```javascript
window.addEventListener('load', async () => {
    const data = await fetchCurrentWeatherByCity("Pune");  // Change this
    displayWeatherInformation(data);
});
```

### Auto-detect User Location (Future Feature)

```javascript
// Add this to detect user's location
if (navigator.geolocation) {
    navigator.geolocation.getCurrentPosition((position) => {
        const { latitude, longitude } = position.coords;
        // Use coordinates to fetch weather
    });
}
```

### Change API Endpoint

Current: `https://api.openweathermap.org/data/2.5/weather`

Other options:
```
// Forecast (5 days)
https://api.openweathermap.org/data/2.5/forecast

// Air Quality
https://api.openweathermap.org/data/3.0/air_pollution

// UV Index
https://api.openweathermap.org/data/2.5/uvi
```

---

## 📚 Code Examples

### Access Weather Data (Browser Console)

```javascript
// Get current city data
const city = document.getElementById('cityName').textContent;
console.log(city);

// Get current temperature
const temp = document.getElementById('temp').textContent;
console.log('Temperature: ' + temp + '°C');

// Get humidity
const humidity = document.getElementById('humidity').textContent;
console.log('Humidity: ' + humidity + '%');
```

### Fetch Weather Programmatically

```javascript
// Get weather for multiple cities
const cities = ['Mumbai', 'Delhi', 'Bangalore'];

cities.forEach(async (city) => {
    const data = await fetchCurrentWeatherByCity(city);
    console.log(`${city}: ${data.main.temp}°C`);
});
```

### Export Weather Data as JSON

```javascript
// Create JSON backup of current weather
const weatherData = {
    city: document.getElementById('cityName').textContent,
    temp: document.getElementById('temp').textContent,
    humidity: document.getElementById('humidity').textContent,
    timestamp: new Date().toISOString()
};

const json = JSON.stringify(weatherData, null, 2);
console.log(json);

// Download as file
const blob = new Blob([json], { type: 'application/json' });
const url = URL.createObjectURL(blob);
const a = document.createElement('a');
a.href = url;
a.download = 'weather-data.json';
a.click();
```

### Handle API Errors

```javascript
// Better error handling
async function searchWeatherSafe() {
    try {
        const city = document.getElementById('cityInput').value;
        
        if (!city || city.length < 2) {
            alert('Please enter city name (2+ characters)');
            return;
        }
        
        const data = await fetchCurrentWeatherByCity(city);
        
        if (!data || data.cod !== 200) {
            alert('❌ City not found. Try another name.');
            return;
        }
        
        displayWeatherInformation(data);
    } catch (error) {
        console.error('Error:', error);
        alert('⚠️ Connection error. Check internet and try again.');
    }
}
```

---

## 🎓 Learning Concepts

This project teaches:

| Concept | Topic | Example |
|---------|-------|---------|
| **Async/Await** | JavaScript | `async function`, `await fetch()` |
| **API Integration** | REST API | OpenWeatherMap API calls |
| **Fetch API** | Browser API | `fetch()`, `response.json()` |
| **DOM Manipulation** | JavaScript | `getElementById()`, `textContent` |
| **Event Listeners** | JavaScript | Click events, Enter key press |
| **Template Literals** | ES6 | String interpolation with `${}` |
| **Gradient Design** | CSS | `linear-gradient()` |
| **Responsive Design** | CSS | Media queries, Flexbox, Grid |
| **Error Handling** | JavaScript | Try/catch blocks |
| **JSON Data** | JavaScript | Parse API responses |

---

## 🐛 Troubleshooting

### Weather Not Loading?

```
❌ Issue: "City not found" error
✅ Solution:
  - Check spelling of city name
  - Use English city names only
  - Try famous cities first (Mumbai, London, etc.)

❌ Issue: API Key Error
✅ Solution:
  - Verify API key is correct in script.js
  - Check API key is activated (OpenWeatherMap website)
  - Wait 10 minutes if newly created key
  - Try different browser

❌ Issue: "CORS Error"
✅ Solution:
  - This shouldn't happen with OpenWeatherMap API
  - Check if you have internet connection
  - Disable browser extensions (AdBlock, etc.)

❌ Issue: Data loads slowly
✅ Solution:
  - Check internet connection speed
  - Wait 2-3 seconds for API response
  - Close other active browser tabs
```

### Icons Not Displaying?

```
❌ Issue: Font Awesome icons not showing
✅ Solution:
  - Check CDN link is active (in HTML <head>)
  - Update Font Awesome version if outdated
  - Clear browser cache (Ctrl+Shift+Delete)
  - Try different browser
```

### Search Not Working?

```
❌ Issue: Search button doesn't respond
✅ Solution:
  - Check JavaScript is enabled
  - Open browser console (F12) to see errors
  - Verify script.js is loading
  - Try pressing Enter instead of clicking button

❌ Issue: Enter key doesn't trigger search
✅ Solution:
  - Check if focus is on input field
  - Verify event listener is attached
  - Try using Search button instead
```

### Performance Issues?

```
❌ Issue: App is slow/laggy
✅ Solution:
  - Close browser developer tools
  - Clear browser cache
  - Disable browser extensions
  - Use modern browser (Chrome, Firefox)
  - Check internet connection
```

---

## 🌐 Browser Support

| Browser | Support | Version |
|---------|---------|---------|
| **Chrome** | ✅ Full | 90+ |
| **Firefox** | ✅ Full | 88+ |
| **Safari** | ✅ Full | 14+ |
| **Edge** | ✅ Full | 90+ |
| **Opera** | ✅ Full | 76+ |
| **IE 11** | ❌ Not Supported | - |

---

## 📱 Responsive Breakpoints

```css
/* Desktop: 769px+ */
@media (min-width: 769px) {
  .main-container { max-width: 900px; }
}

/* Tablet: 481px - 768px */
@media (max-width: 768px) {
  .stats-grid {
    grid-template-columns: repeat(2, 1fr);
  }
}

/* Mobile: 480px and below */
@media (max-width: 480px) {
  .main-container { padding: 20px; }
  .stats-grid {
    grid-template-columns: 1fr;
  }
}
```

---

## 🚀 Performance Optimization

### API Call Optimization

```javascript
// Cache weather data (don't call API too often)
let lastSearchTime = 0;
const CACHE_DURATION = 60000; // 1 minute

async function searchWeatherOptimized() {
    const now = Date.now();
    
    if (now - lastSearchTime < CACHE_DURATION) {
        console.log('Using cached data...');
        return;
    }
    
    const data = await fetchCurrentWeatherByCity(city);
    lastSearchTime = now;
    displayWeatherInformation(data);
}
```

### Lazy Loading Images

```javascript
// If you add background images
<img loading="lazy" src="weather.jpg" alt="Weather">
```

---

## 📈 Future Enhancements

### Planned Features
- 🌙 Dark Mode toggle
- 📅 5-Day Weather Forecast
- ⭐ Save Favorite Cities
- 📍 Location Auto-detection
- 🔔 Weather Alerts & Notifications
- 📊 Historical Weather Data
- 🗺️ Weather Map View
- 🌍 Multiple Language Support
- 📱 Progressive Web App (PWA)
- ☁️ Cloud Storage Sync

### Advanced Features
- 🤖 AI Weather Predictions
- 🎨 Custom Themes
- 📈 Weather Analytics Dashboard
- 🔄 Real-time Updates (WebSocket)
- 📲 Push Notifications
- 🌡️ Air Quality Index
- 🌊 Pollen Count
- ⚡ UV Index

---

## 🤝 Contributing

Contributions are welcome! Here's how to help:

### Steps to Contribute

```bash
# 1. Fork the repository
# 2. Create feature branch
git checkout -b feature/your-feature-name

# 3. Make changes and commit
git commit -m "Add: Description of your changes"

# 4. Push to branch
git push origin feature/your-feature-name

# 5. Open Pull Request on GitHub
```

### Code Style Guidelines
- Use semantic HTML5
- Follow Airbnb JavaScript style guide
- Comment complex logic
- Keep CSS organized by sections
- Test on multiple browsers & devices
- Add descriptive commit messages

### Areas to Contribute
- 🐛 Bug fixes
- ✨ New features
- 📖 Documentation improvements
- 🎨 UI/UX enhancements
- ⚡ Performance optimizations
- 🌐 Translations
- 📱 Mobile improvements

### Reporting Issues
1. Check if issue already exists
2. Provide clear description
3. Include browser & OS version
4. Share error message (if any)
5. Provide steps to reproduce

---

## 📄 License

This project is licensed under the **MIT License** - see LICENSE file for details.

```
MIT License

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software...
```

---

## 🙌 Credits & Acknowledgments

### Built With
- ❤️ **Vanilla JavaScript** - No framework dependencies
- 🌍 **OpenWeatherMap API** - Real-time weather data
- 🎭 **Font Awesome** - Icon library
- 🎨 **CSS3** - Modern styling & gradients

### APIs & Services
- [OpenWeatherMap API](https://openweathermap.org/api) - Weather data
- [Font Awesome](https://fontawesome.com/) - Icons
- [Google Fonts](https://fonts.google.com/) - Typography

### Inspiration
- 🌤️ Weather.com - UI/UX inspiration
- 📱 iOS Weather App - Design patterns
- 🌐 Modern Web Standards - Best practices

### Contributors
- Your name here! (Open for contributions)
- [Original Author](https://github.com/vishnuiprogrammer)

---

## 📞 Support & Contact

| Channel | Link |
|---------|------|
| 🐛 **Issues** | [GitHub Issues](https://github.com/vishnuiprogrammer/AuraWeather/issues) |
| 💬 **Discussions** | [GitHub Discussions](https://github.com/vishnuiprogrammer/AuraWeather/discussions) |
| 📧 **Email** | vishnuiprogrammer@gmail.com |

---

## 🔐 Privacy & Security

### Data Collection
- ✅ No personal data stored
- ✅ No account required
- ✅ All data stored locally in browser
- ✅ API calls only to OpenWeatherMap

### API Key Safety
- ⚠️ Never share your API key publicly
- ⚠️ Don't commit API key to GitHub
- ✅ Use environment variables for production

---

## 📊 Project Statistics

```
Total Lines of Code: ~400
├── HTML: ~120 lines
├── CSS: ~200 lines
└── JavaScript: ~80 lines

API Requests: 1 per search
Response Time: ~500-800ms
Cache Duration: Real-time
Browser Coverage: 99%
Mobile Responsive: ✅ Yes
```

---


---

## 📚 Additional Resources

### Learning Resources
- [MDN Web Docs - Fetch API](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API)
- [OpenWeatherMap API Docs](https://openweathermap.org/api)
- [CSS Gradient Generator](https://cssgradient.io/)
- [Font Awesome Icon Library](https://fontawesome.com/icons)

### Similar Projects
- Weather Dashboard with Forecast
- Temperature Converter App
- Climate Change Tracker
- Air Quality Monitor

---

<div align="center">

### Made with ❤️ for the web development community

[⬆ back to top](#-aura-weather---weather-forecast-app)

**[Star ⭐ this repo if you find it helpful!](https://github.com/vishnuiprogrammer/AuraWeather)**

</div>
