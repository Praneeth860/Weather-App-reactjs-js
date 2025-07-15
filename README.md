# Weather App 🌤️

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![OpenWeatherMap](https://img.shields.io/badge/API-OpenWeatherMap-FF6B00?style=for-the-badge&logo=cloud&logoColor=white)



A modern, responsive weather application built with React and Vite that provides real-time weather information for any city worldwide.

---
## ✨ Features

- 🌍 **Real-time Weather Data**: Get current weather conditions for any city
- 🎨 **Beautiful UI**: Clean, modern interface with gradient backgrounds and smooth animations
- 🌦️ **Weather Icons**: Dynamic weather icons that change based on current conditions
- 📊 **Detailed Information**: Temperature, humidity, and wind speed data
- 🔍 **Search Functionality**: Easy city search with Enter key support
- 📱 **Responsive Design**: Works seamlessly on desktop and mobile devices

## 📸 Screenshots

The app displays:
- 🌡️ Current temperature in Celsius
- 🏙️ City name
- 🌤️ Weather icon based on conditions
- 💧 Humidity percentage
- 💨 Wind speed in km/h
## 🛠️ Tech Stack

- ⚛️ **React 19.1.0** – Frontend framework  
- ⚡ **Vite** – Build tool and development server  
- 📜 **JavaScript (ES6+)** – Core programming language for app logic  
- 🧱 **HTML5** – Semantic markup structure  
- 🎨 **CSS3** – Styling with gradients and modern layouts  
- 🌐 **OpenWeatherMap API** – Weather data source  


## 📋 Prerequisites

Before running this application, make sure you have:

- 📦 Node.js (version 14 or higher)
- 🔧 npm or yarn package manager
- 🔑 An API key from [OpenWeatherMap](https://openweathermap.org/api)

## 🚀 Installation

1. **📥 Clone the repository**
   ```bash
   git clone <repository-url>
   cd weather-app
   ```

2. **📦 Install dependencies**
   ```bash
   npm install
   ```

3. **⚙️ Set up environment variables**
   Create a `.env` file in the root directory and add your OpenWeatherMap API key:
   ```
   VITE_API_KEY=your_openweathermap_api_key_here
   ```

4. **▶️ Start the development server**
   ```bash
   npm run dev
   ```

5. **🌐 Open your browser**
   Navigate to `http://localhost:5173` to view the application

## 🔑 API Key Setup

1. 🌐 Visit [OpenWeatherMap](https://openweathermap.org/api)
2. 📝 Sign up for a free account
3. 🔑 Generate an API key
4. ⚙️ Add the key to your `.env` file as shown above

## 📜 Available Scripts

- `npm run dev` - 🚀 Start development server
- `npm run build` - 📦 Build for production
- `npm run preview` - 👀 Preview production build
- `npm run lint` - 🔍 Run ESLint


## 🎯 Usage

1. 🔍 **Search for a city**: Type the city name in the search bar
2. 📊 **Get weather data**: Press Enter or click the search icon
3. 👀 **View results**: The app will display current weather conditions including:
   - 🌡️ Temperature
   - 🌤️ Weather icon
   - 💧 Humidity
   - 💨 Wind speed

## 🌈 Weather Icons

The app includes icons for various weather conditions:
- ☀️ Clear sky (day/night)
- ☁️ Clouds
- 🌦️ Drizzle
- 🌧️ Rain
- ❄️ Snow
- 🌫️ Mist/Fog

## ⚠️ Error Handling

The application includes error handling for:
- ❌ Invalid city names
- 🌐 Network errors
- 🔧 API failures
- 🔍 Empty search queries

## 🤝 Contributing

1. 🍴 Fork the repository
2. 🌟 Create a feature branch (`git checkout -b feature/amazing-feature`)
3. 💾 Commit your changes (`git commit -m 'Add some amazing feature'`)
4. 📤 Push to the branch (`git push origin feature/amazing-feature`)
5. 🔀 Open a Pull Request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- 🌐 Weather data provided by [OpenWeatherMap](https://openweathermap.org/)
- 🎨 Icons and design inspiration from modern weather applications
- ⚛️ Built with React and Vite for optimal performance

## 🆘 Support

If you encounter any issues or have questions, please open an issue on the GitHub repository.

---

**⚠️ Note**: Remember to keep your API key secure and never commit it to version control. The `.env` file is already included in `.gitignore` for security.
