# 🌤️ Weather App - AI Engineer Tech Assessment

A modern, responsive weather application built with Next.js 14, TypeScript, and Tailwind CSS that provides real-time weather information and forecasts for any location worldwide.

## 📋 Assessment Overview

This project fulfills **Tech Assessment 1** requirements for the AI Engineer Intern position, demonstrating technical aptitude in building a comprehensive weather application with real-time API integration and user-friendly location input handling.

## ✨ Features

### Core Requirements ✅
- **Multi-format Location Input**: Support for various location formats:
  - ZIP/Postal Codes (e.g., "10001", "SW1A 1AA")
  - GPS Coordinates (e.g., "40.7128, -74.0060")
  - City Names (e.g., "New York", "London")
  - Landmarks (e.g., "Times Square", "Eiffel Tower")
  - State/Country combinations (e.g., "Paris, France")

- **Current Weather Display**: Comprehensive weather information including:
  - Temperature (current, high, low)
  - Weather conditions with descriptive text
  - Real-time clock for location timezone
  - Weather icons for visual representation

### Stand-Apart Features ⭐
- **5-Day Forecast**: Extended weather outlook with daily summaries
- **Current Location Detection**: Automatic weather based on user's GPS location
- **Professional UI/UX**: Clean, modern interface with:
  - Custom weather icons
  - Responsive design for all screen sizes
  - Dark/light theme support
  - Smooth animations and transitions

### Additional Enhancements 🚀
- **Interactive Map**: Dynamic weather map with various data layers
- **Command Menu**: Quick search functionality (⌘/Ctrl + J)
- **Intelligent Autocomplete**: Smart location suggestions
- **Real-time Updates**: Live weather data refresh
- **Keyboard Shortcuts**: Enhanced accessibility

## 🛠️ Technology Stack

- **Frontend**: Next.js 14 (App Router), TypeScript, React 18
- **Styling**: Tailwind CSS, Shadcn/ui Components
- **APIs**: 
  - OpenWeatherMap API (weather data)
  - Google Maps Places API (location autocomplete)
  - Google Geolocation API (coordinate resolution)
- **Map Integration**: React Map GL with Mapbox
- **State Management**: React Hooks
- **Deployment Ready**: Optimized for production deployment

## 🌐 API Integration

The application uses **real-time weather APIs** (no static data) to provide:
- Current weather conditions
- 5-day weather forecasts
- Hourly forecasts (24-hour)
- Multiple weather parameters (temperature, humidity, wind, pressure, UV index)

## 📱 Responsive Design

- **Mobile-first** approach
- **Tablet** optimized layouts
- **Desktop** enhanced experience
- **Cross-browser** compatibility

## 🚀 Getting Started

### Prerequisites
- Node.js 18+ 
- npm or yarn
- API keys for weather and location services

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Shehab-Hegab/Weather-App.git
   cd Weather-App
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   yarn install
   ```

3. **Environment Setup**
   ```bash
   cp .env.example .env.local
   ```
   
   Add your API keys to `.env.local`:
   ```env
   NEXT_PUBLIC_OPENWEATHER_API_KEY=your_openweather_api_key
   NEXT_PUBLIC_GOOGLE_MAPS_API_KEY=your_google_maps_api_key
   NEXT_PUBLIC_MAPBOX_ACCESS_TOKEN=your_mapbox_token
   ```

4. **Run the development server**
   ```bash
   npm run dev
   # or
   yarn dev
   ```

5. **Open your browser**
   Navigate to [http://localhost:3000](http://localhost:3000)

### Obtaining API Keys

1. **OpenWeatherMap API**:
   - Visit [OpenWeatherMap](https://openweathermap.org/api)
   - Sign up for a free account
   - Generate your API key

2. **Google Maps API**:
   - Go to [Google Cloud Console](https://console.cloud.google.com/)
   - Enable Places API and Geolocation API
   - Create credentials

3. **Mapbox**:
   - Sign up at [Mapbox](https://www.mapbox.com/)
   - Get your access token

## 💻 Usage

### Location Input Methods
1. **Search Bar**: Type any location format
2. **Current Location**: Click the location button for GPS-based weather
3. **Map Selection**: Click on the interactive map
4. **Command Menu**: Use ⌘/Ctrl + J for quick search

### Keyboard Shortcuts
- `⌘/Ctrl + J`: Open command menu
- `T`: Toggle theme (dark/light)
- `Esc`: Close modals/menus

## 🏗️ Project Structure

```
weather-app/
├── app/                    # Next.js App Router pages
├── components/            
│   ├── ui/                # Reusable UI components
│   ├── widgets/           # Weather-specific widgets
│   └── LocationWeatherApp.tsx
├── lib/                   # Utilities and types
├── public/                # Static assets
├── actions/               # Server actions
└── ...config files
```

## 🎯 Assessment Criteria Met

### Technical Aptitude ✅
- **Modern Framework**: Next.js 14 with latest features
- **Type Safety**: Full TypeScript implementation
- **Performance**: Optimized rendering and API calls
- **Error Handling**: Robust error boundaries and validation

### Creative Problem Solving ✅
- **Smart Input Handling**: Multiple location format support
- **User Experience**: Intuitive interface with helpful features
- **Visual Design**: Professional weather icons and layouts
- **Accessibility**: Keyboard navigation and screen reader support

### Real-time Integration ✅
- **Live Weather Data**: No static information
- **Multiple APIs**: Weather, location, and mapping services
- **Data Validation**: Input sanitization and error handling
- **Performance**: Efficient API usage and caching

## 🔧 Development

### Available Scripts
- `npm run dev`: Start development server
- `npm run build`: Build for production
- `npm run start`: Start production server
- `npm run lint`: Run ESLint
- `npm run type-check`: TypeScript type checking

### Code Quality
- **ESLint**: Code linting and formatting
- **Prettier**: Code formatting
- **TypeScript**: Type safety
- **Git Hooks**: Pre-commit validation

## 📞 Support

For technical support or questions about this assessment:

[![Support](https://img.shields.io/badge/Support-GitHub%20Issues-blue)](https://github.com/Shehab-Hegab/Weather-App/issues)

## 📄 License

This project is licensed under the Apache License 2.0 - see the [LICENSE](LICENSE) file for details.

## 🤝 Assessment Completion

**✅ Tech Assessment 1: COMPLETED**

This weather application successfully demonstrates:
- ✅ Multi-format location input handling
- ✅ Real-time weather API integration  
- ✅ 5-day forecast implementation
- ✅ Current location detection
- ✅ Professional UI/UX design
- ✅ Responsive cross-platform compatibility
- ✅ Creative feature enhancements

**Ready for Tech Assessment 2** - The foundation is prepared for CRUD operations and database integration.

---

*Built with ❤️ for the AI Engineer Intern Technical Assessment*
