# Weathery 🌤️

A modern, responsive weather application built with React and Vite that provides real-time weather information for any location worldwide.

![Weather App](https://img.shields.io/badge/React-18.2.0-blue.svg)
![Vite](https://img.shields.io/badge/Vite-5.0.0-green.svg)
![License](https://img.shields.io/badge/License-MIT-yellow.svg)

## ✨ Features

- **Real-time Weather Data**: Get current weather conditions for any city
- **Beautiful UI**: Clean, modern interface with weather-specific icons
- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Weather Icons**: Visual representation of weather conditions (clear, cloudy, rainy, snowy, etc.)
- **Detailed Information**: Display temperature, humidity, and wind speed
- **Search Functionality**: Easy-to-use search for any location worldwide
- **Fast Performance**: Built with Vite for lightning-fast development and optimized builds

## 🖼️ Weather Icons

The app includes custom icons for various weather conditions:
- ☀️ Clear skies
- ☁️ Cloudy weather
- 🌧️ Rain and drizzle
- ❄️ Snow
- 💨 Wind indicators
- 💧 Humidity display

## 🚀 Getting Started

### Prerequisites

Make sure you have the following installed:
- [Node.js](https://nodejs.org/) (version 16 or higher)
- npm or yarn package manager

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Nortcele7/Weathery.git
   cd Weathery
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Set up environment variables:**
   - Create a `.env` file in the root directory
   - Add your weather API key:
     ```env
     VITE_WEATHER_API_KEY=your_api_key_here
     ```

4. **Start the development server:**
   ```bash
   npm run dev
   ```

5. **Open your browser:**
   Navigate to `http://localhost:5173` to view the app

## 🛠️ Built With

- **[React](https://reactjs.org/)** - Frontend library for building user interfaces
- **[Vite](https://vitejs.dev/)** - Next generation frontend tooling
- **[CSS3](https://developer.mozilla.org/en-US/docs/Web/CSS)** - Styling and responsive design
- **Weather API** - Real-time weather data

## 📁 Project Structure

```
weathery/
├── public/
│   └── vite.svg
├── src/
│   ├── components/
│   │   ├── Weather.jsx
│   │   ├── Weather.css
│   │   └── [weather-icons]
│   ├── App.jsx
│   ├── main.jsx
│   └── index.css
├── .env
├── .gitignore
├── package.json
├── vite.config.js
└── README.md
```

## 🎯 Usage

1. **Search for a location**: Enter any city name in the search box
2. **View weather data**: See current temperature, weather conditions, humidity, and wind speed
3. **Visual indicators**: Weather icons automatically update based on current conditions

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint

## 🌟 Future Enhancements

- [ ] 5-day weather forecast
- [ ] Geolocation support
- [ ] Weather maps integration
- [ ] Dark/light theme toggle
- [ ] Favorite locations
- [ ] Weather alerts and notifications

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👤 Author

**Nortcele7**
- GitHub: [@Nortcele7](https://github.com/Nortcele7)

## 🙏 Acknowledgments

- Weather icons and data provided by weather API services
- React and Vite communities for excellent documentation
- Open source contributors who make projects like this possible

---

⭐ Star this repository if you found it helpful!
