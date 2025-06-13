# Weather App

A modern weather application built with React, TanStack Query, and Shadcn UI that allows users to search for cities and view detailed weather information.


## Features

- **City Search**: Search for weather information by city name
- **Weather Dashboard**: View current weather conditions and forecasts
- **City Details**: Detailed weather information for specific cities
- **Dark/Light Theme**: Toggle between dark and light themes
- **Responsive Design**: Works on desktop and mobile devices
- **Real-time Data**: Fetches weather data from OpenWeather API

## Technology Stack

- **Frontend**: React 18, TypeScript
- **Routing**: React Router v6
- **State Management**: TanStack Query (React Query) v5
- **UI Components**: Shadcn UI, Radix UI
- **Styling**: Tailwind CSS
- **Charts**: Recharts
- **Theming**: next-themes
- **Notifications**: Sonner
- **Build Tool**: Vite

## Prerequisites

- Node.js (v18 or higher)
- npm or yarn
- OpenWeather API key

## Installation

### Local Setup

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   ```
3. Create a `.env` file in the root directory with your OpenWeather API key:
   ```
   VITE_OPENWEATHER_API_KEY=your_api_key_here
   ```
4. Start the development server:
   ```bash
   npm run dev
   ```
5. Open your browser and navigate to `http://localhost:5173`

### Docker Setup

1. Make sure you have Docker and Docker Compose installed
2. Create a `.env` file with your OpenWeather API key as shown above
3. Build and start the container:
   ```bash
   docker-compose up -d
   ```
4. Access the application at `http://localhost:5173`

## Build for Production

```bash
npm run build
npm run preview
```

## Project Structure

- `/src`: Source code
  - `/api`: API integration
  - `/components`: Reusable UI components
  - `/context`: React context providers
  - `/hooks`: Custom React hooks
  - `/lib`: Utility functions
  - `/pages`: Application pages

## License

MIT
