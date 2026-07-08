WeCo - Weather App

https://img.shields.io/badge/Deployed%20on-Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white
https://img.shields.io/badge/GitHub-Repository-181717?style=for-the-badge&logo=github&logoColor=white
https://img.shields.io/badge/Powered%20by-OpenWeatherMap-EB6E4B?style=for-the-badge&logo=openweathermap&logoColor=white
https://img.shields.io/badge/License-MIT-4ADE80?style=for-the-badge
https://img.shields.io/badge/Version-2.0-5B9BD5?style=for-the-badge

---

🌤️ Overview

WeCo is a sophisticated, real-time weather application built with vanilla HTML, CSS, and JavaScript. It provides comprehensive weather data with a beautiful, modern interface and complete customization options.

Live Demo: https://weco-alpha.vercel.app

GitHub Repository: https://github.com/martinonyisi/Weco-weather

---

✨ Key Features

📊 Comprehensive Weather Data

· Current Conditions: Temperature, humidity, wind speed, pressure, and more
· Extended Statistics: UV index, visibility, cloud coverage, feels-like temperature
· Min/Max Temperatures: Daily temperature range at a glance
· Real-time Updates: Auto-refresh every 10 seconds

📅 7-Day Forecast

· Daily weather predictions with high/low temperatures
· Visual weather icons for quick understanding
· Scrollable interface for easy navigation

🎯 Smart Location

· Auto-Geolocation: Detects your location on first visit
· Manual Search: Search any city worldwide
· Search History: Remembers your last 8 searches for quick access

🎨 Complete Customization

· Dark/Light Mode: Toggle between themes with smooth transitions
· Accent Colors: Choose from 5 vibrant colors (Blue, Purple, Green, Gold, Coral)
· Unit Preferences: Switch between metric (°C, km/h) and imperial (°F, mph)
· Full Settings Panel: Complete control over your experience

🚀 Performance & UX

· Splash Screen: Elegant loading animation
· Responsive Design: Perfect on desktop, tablet, and mobile
· Glass-morphism: Modern blur effects and gradients
· Smooth Animations: Buttery transitions and hover effects
· Live Indicator: Visual pulse showing auto-update status

---

📦 Installation

Local Development

1. Clone the repository

```bash
git clone https://github.com/martinonyisi/Weco-weather.git
cd Weco-weather
```

1. Open in browser

```bash
# Option 1: Direct open
open index.html

# Option 2: Use Python server
python3 -m http.server 8000

# Option 3: Use Node.js
npx http-server
```

1. Visit http://localhost:8000

API Key Setup

The app includes a demo API key. For production:

1. Get your free key from OpenWeatherMap
2. Open index.html and replace the API_KEY variable:

```javascript
const API_KEY = 'YOUR_API_KEY_HERE'; // Replace this
```

---

🚀 Deployment

This app is deployed on Vercel. To deploy your own instance:

Deploy on Vercel

1. Push to GitHub

```bash
git add .
git commit -m "Initial commit"
git push origin main
```

1. Deploy with Vercel

```bash
# Install Vercel CLI
npm i -g vercel

# Deploy
vercel
```

1. Manual Deployment

· Go to Vercel.com
· Click "Add New" → "Project"
· Import your GitHub repository
· Click "Deploy"

Deploy on Netlify

· Go to Netlify.com
· Drag your project folder to the deploy area
· Your site is live!

---

🎯 Usage Guide

Getting Started

1. First Visit: The app automatically detects your location
2. Manual Search: Type a city name and press Enter or click the search button
3. View Weather: All stats update instantly with smooth animations

Interactive Features

Weather Card

· Temperature: Large display with unit toggle
· Weather Icon: Dynamic icons based on conditions
· Description: Human-readable weather description
· Stats Grid: 8 key metrics at a glance

Forecast Section

· 7-Day View: Scroll horizontally to see all days
· Daily Details: Day name, weather icon, and temperature

Settings Panel (⚙️)

Click the settings icon to access:

· Theme Toggle: Switch dark/light mode
· Accent Color: Choose from 5 colors
· Units: Customize temperature and wind speed
· Clear History: One-click history reset
· Developer Info: Credits and contact details

History

· Quick Access: Click any recent city to reload
· Auto-save: Cities are saved automatically
· Clear History: Remove all history from settings

---

🛠️ Technologies Used

Technology Purpose
HTML5 Semantic structure
CSS3 Modern styling with variables, flexbox, grid, and animations
JavaScript ES6+ Async/await, DOM manipulation, API integration
Font Awesome 6 Premium icon library
OpenWeatherMap API Weather data provider
Vercel Hosting and deployment

---

📁 Project Structure

```
Weco-weather/
├── index.html          # Main HTML file with embedded CSS and JS
├── README.md           # Project documentation
├── LICENSE             # MIT License
└── vercel.json         # Vercel deployment configuration
```

---

🎨 Customization

Color Scheme

Modify CSS variables in the :root selector:

```css
:root {
  --accent: #5b9bd5;    /* Primary accent color */
  --bg-primary: #0b121f; /* Background color */
  --text-primary: #eef6ff; /* Main text color */
}
```

Available Accent Colors

Color Hex Code Preview
Blue #5b9bd5 🔵
Purple #6c5ce7 🟣
Green #00b894 🟢
Gold #fdcb6e 🟡
Coral #e17055 🔴

---

📊 API Endpoints

Current Weather

```javascript
GET https://api.openweathermap.org/data/2.5/weather
Parameters: q={city}, appid={API_KEY}
```

7-Day Forecast

```javascript
GET https://api.openweathermap.org/data/2.5/forecast
Parameters: q={city}, appid={API_KEY}
```

Geolocation Weather

```javascript
GET https://api.openweathermap.org/data/2.5/weather
Parameters: lat={latitude}&lon={longitude}, appid={API_KEY}
```

---

🧪 Browser Support

· ✅ Chrome (latest)
· ✅ Firefox (latest)
· ✅ Safari (latest)
· ✅ Edge (latest)
· ✅ Mobile Safari (iOS)
· ✅ Mobile Chrome (Android)

---

🤝 Contributing

We welcome contributions! Here's how:

1. Fork the repository
2. Create a feature branch:

```bash
git checkout -b feature/amazing-feature
```

1. Commit your changes:

```bash
git commit -m 'Add amazing feature'
```

1. Push to branch:

```bash
git push origin feature/amazing-feature
```

1. Open a Pull Request

Guidelines

· Keep code clean and well-commented
· Test on multiple browsers
· Update documentation if needed
· Follow existing design patterns

---

🐛 Bug Reports

Found a bug? Please open an issue with:

· Description: What happened?
· Expected: What should happen?
· Steps: How to reproduce?
· Screenshots: If applicable
· Environment: Browser, OS, device

---

👨‍💻 Developer

Martin Onyisi (Martony)

· 🌐 Website: Martony.gt.tc
· 🐙 GitHub: @martinonyisi
· 📧 Email: martin.onyisi@gt.tc
· 🔗 Repository: Weco-weather

---

📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

```
MIT License

Copyright (c) 2024 Martin Onyisi

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

---

🙏 Acknowledgments

· Weather data by OpenWeatherMap
· Icons by Font Awesome
· Hosting by Vercel
· Inspiration from modern design trends

---

📞 Support

For support, email martin.onyisi@gt.tc or open an issue on GitHub.

---

⭐ Star History

If you find this project useful, please give it a ⭐ on GitHub!

https://api.star-history.com/svg?repos=martinonyisi/Weco-weather&type=Date

---

🚀 Roadmap

· Air Quality Index
· Hourly Forecast
· Weather Alerts
· Multiple Locations
· Custom Widgets
· Offline Mode
· PWA Support
· Weather Maps
· Voice Search
· Weather News Integration

---

Built with ❤️ by Martin Onyisi (Martony)

WeCo - Your Weather Companion

---

🔗 Quick Links

· 🌐 Live Demo: https://weco-alpha.vercel.app
· 📁 GitHub: https://github.com/martinonyisi/Weco-weather
· 👨‍💻 Developer: https://martony.gt.tc