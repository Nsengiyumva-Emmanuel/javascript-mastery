Advanced Countdown Timer
A modern, feature-rich countdown timer web application built with HTML, CSS, and JavaScript.
It supports multiple timers, preset durations, Pomodoro technique, dark mode, progress tracking, and persistent storage using localStorage.
Features
•	Create Custom Timers – Set hours, minutes, and seconds for any activity.
•	Quick Presets – Choose from pre-set timers (5, 10, 15, 20, 25, 30 minutes).
•	Pomodoro Technique – Includes built-in work (25min) and break (5min) cycles.
•	Dark & Light Mode – Switch themes easily with one click.
•	Multiple Timers Management – Create, activate, delete, and track multiple timers.
•	Progress Bar & Notifications – Visual progress indicator and completion alerts.
•	Timer History – Keep track of completed timers.
•	Responsive Design – Optimized for desktop, tablet, and mobile.
•	Persistent Data – Timers are saved in browser localStorage.
Technologies Used
•	HTML5 – Semantic structure
•	CSS3 – Custom styling with variables, grid & flexbox layouts, animations
•	JavaScript (ES6+) – State management, event handling, DOM manipulation
•	Font Awesome – Icons for controls and UI elements
•	localStorage – Save timers across sessions
Project Structure
project/
│── index.html   # Main application file
│── README.md    # Documentation
All styles and JavaScript logic are embedded directly in index.html.
For production, you may refactor into separate .css and .js files.
Getting Started
1.	Clone this repository or download the source code:
2.	git clone https://github.com/yourusername/advanced-countdown-timer.git
3.	Open index.html in your browser.
4.	Start creating timers! 
How to Use
1.	Create a New Timer
	Enter a name and set duration (hours, minutes, seconds).
	Click Create Timer.
	Activate your timer from the "Your Timers" list.
2.	Use Quick Presets
	Click a preset (5, 10, 15, 20, 25, or 30 minutes).
	A timer is created instantly.
3.	Pomodoro Mode
	Click Start Pomodoro to begin a 25-minute work session.
	Break timer follows automatically.
4.	Controls
	Start / Pause / Reset timers from the main dashboard.
	Delete timers from the list if no longer needed.
5.	Theme Toggle
	Click 🌙 or ☀️ icon to switch between dark and light modes.
Responsive Design
•	Desktop: Full dashboard view with sidebar and main content.
•	Tablet & Mobile: Adjusts layout into a single column for usability.
Future Improvements
•	Add sound effects for completion alerts.
•	Export and import timer history.
•	Cloud sync for multi-device use.
•	Advanced Pomodoro settings (custom work/break cycles).






Weather Dashboard
A modern Weather Dashboard web application built with HTML, CSS, and JavaScript.
It provides real-time weather updates, 5-day forecasts, air quality index, favorite cities, and dark/light theme support.
Features
	🌍 City Search – Search weather information by city name.
	📍 Geolocation Support – Fetch weather using the user’s current location.
	🌡 Current Weather – Displays temperature, humidity, wind speed, pressure, and "feels like".
	📆 5-Day Forecast – View upcoming weather trends with icons and temperatures.
	❤️ Favorites – Save and quickly access favorite cities.
	🎨 Dark/Light Mode – Toggle between light and dark themes with persistence (saved in local storage).
	🔄 Unit Toggle – Switch between Celsius (°C) and Fahrenheit (°F).
	🌫 Air Quality Index (AQI) – Displays air quality with color-coded status.
	🗺 Map Placeholder – Integrated map container for future weather map API integration.
	⚡ Responsive Design – Works seamlessly on desktop, tablet, and mobile.
	🎬 Smooth Animations – Fade-in and transition effects for UI elements.
Project Structure
weather-dashboard/
├── index.html      # Main HTML file with inline CSS & JS
└── README.md       # Documentation
Getting Started
1. Clone the Repository
git clone https://github.com/yourusername/weather-dashboard.git
2. Open in Browser
Simply open the index.html file in your favorite browser.
No build step or server required – it’s pure client-side.
How It Works
•	State Management: Maintains city, favorites, temperature unit, and theme in a state object with persistence via localStorage.
•	Weather Data: Currently uses mock data (setTimeout simulates API calls).
o	For real implementation, connect to APIs like OpenWeatherMap or WeatherAPI.
•	Geolocation: Uses the browser's navigator.geolocation API to fetch latitude and longitude.
•	Dynamic Rendering: Weather info, forecasts, favorites, and AQI are updated dynamically with JavaScript DOM manipulation.
Customization
	🌐 API Integration: Replace mock weather data with a real API call.
	🎨 Theme: Customize CSS variables in :root and .dark-mode for branding.
	🗺 Map: Embed an actual interactive weather map using APIs like Leaflet or Google Maps API.
Responsive Design
•	Desktop: Dashboard layout with sidebar and main content.
•	Tablet/Mobile: Stacked layout with fluid resizing and optimized controls.
Future Improvements
	Real-time API integration.
	Hourly forecast.
	Interactive map with weather overlays.
	Drag-and-drop favorite city ordering.

