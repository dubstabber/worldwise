# WorldWise 🌍✈️

![WorldWise Application](https://via.placeholder.com/800x400?text=WorldWise+Travel+Tracker)

## 📋 Overview

WorldWise is a sophisticated React application that helps travelers track and visualize their global adventures. With an interactive map interface, users can mark cities they've visited, add personalized notes, and maintain a visual record of their worldwide journey.

> *"You travel the world. WorldWise keeps track of your adventures."*

## ✨ Key Features

- **Interactive World Map**: Visualize all your traveled destinations on an intuitive map interface
- **City & Country Tracking**: Maintain a detailed list of cities and countries you've explored
- **Travel Notes**: Add personalized notes to each location to remember your experiences
- **Geolocation Support**: Find and add your current location with a single click
- **Secure Authentication**: Protected routes ensure your travel data remains private
- **Responsive Design**: Enjoy a seamless experience across all devices
- **Performant Loading**: Implemented code splitting and lazy loading for optimal performance

## 🛠️ Technologies

### Frontend
- **React 18**: Utilizing the latest features of React for building the UI
- **React Router 7**: For seamless navigation and routing management
- **Leaflet/React Leaflet**: Powering the interactive map functionality
- **Context API**: For efficient state management throughout the application
- **CSS Modules**: For component-scoped styling
- **React DatePicker**: For intuitive date selection when adding travel entries

### Backend
- **JSON Server**: Simulating a RESTful API for data persistence

### Development & Build Tools
- **Vite**: For lightning-fast development and optimized production builds
- **ESLint**: Ensuring code quality and consistency
- **Code Splitting**: Implemented with React.lazy for optimized loading performance

## 🚀 Getting Started

### Prerequisites
- Node.js (v14+)
- npm or yarn

### Installation

```bash
# Clone the repository
git clone https://github.com/dubstabber/worldwise

# Navigate to the project directory
cd worldwise

# Install dependencies
npm install

# Start the JSON Server (API)
npm run server

# In a new terminal, start the development server
npm run dev
```

## 🏗️ Architecture

WorldWise is built with a modern React architecture:

- **Component-Based Structure**: Modular components for reusability and maintainability
- **Context-Based State Management**: Using React Context API for global state
- **Custom Hooks**: Abstracting complex logic into reusable hooks
- **Protected Routes**: Implementing authentication checks for secure access
- **Code Splitting**: Using React.lazy for optimized loading

## 📱 Application Flow

1. Users begin at the homepage where they can learn about the application
2. After logging in, they access the main application with the interactive map
3. Users can view their traveled cities and countries in list format
4. Clicking on the map allows adding new cities to their collection
5. Each city can be viewed in detail with notes and visit dates

## 🔍 Unique Implementation Details

- **Custom Map Interaction**: Enhanced Leaflet integration with custom markers and popups
- **Performance Optimization**: Implemented React's Suspense and lazy loading for improved loading times
- **Geolocation Integration**: Seamless browser geolocation API integration
- **Responsive Design Approach**: Adaptable UI for all device sizes

## 📊 Future Enhancements

- User authentication with JWT
- Social sharing capabilities
- Travel statistics and visualizations
- Trip planning features
- Photo uploads for each destination

## 👨‍💻 Developer Notes

This project demonstrates proficiency in:

- Modern React patterns and best practices
- State management using Context API and reducers
- Working with third-party APIs and libraries
- Creating responsive and intuitive user interfaces
- Implementing secure authentication flows
- Code optimization and performance tuning

---

Developed with ❤️ using React, Vite, and modern web technologies.
