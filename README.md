# Entertainment Web App

## Deployment
- [Live Server](https://entertainment-app-frontend-110.onrender.com)

## Live Demo
- [Demo](https://youtu.be/d0fYdGMTsVE)

## Features
- **User Authentication**: Secure login and registration using JWT.
- **Media Exploration**: Discover trending movies and TV shows.
- **Bookmarks**: Save favorite media for easy access.
- **Detailed Information**: Get in-depth details about movies and TV shows.

## Getting Started

### Backend Setup
1. **Navigate to Backend Directory**: `cd entertainment-app/backend`

2. **Install Dependencies**: `npm install`

3. **Configure Environment Variables**:

- **MONGODB_URL= "your mongodb url"**

- **SECRET_TOKEN= "your secret token"**

- **TMDB_TOKEN= "your tmdb api key"**

4. **Start the Server**: `npm start`

### Frontend Setup

1. **Navigate to Frontend Directory**: `cd ../frontend`

2. **Install Dependencies**: `npm install`

3. **Configure Environment Variables**:

**REACT_APP_BACKEND_URL= "your backend server url"**

**VITE_APP_TMDB_API_KEY= "your tmdb api key"**

4. **Start the Application**: `npm run dev`

5. **Access the Application**: Open your browser and go to `http://localhost:3000`

## Project Structure

### Backend
- **Controllers**: Handle API requests.
- **Models**: Define database schemas.
- **Routes**: API endpoints.
- **Middleware**: Authentication and error handling.
- **Utils**: Helper functions.

### Frontend
- **Components**: Reusable UI elements.
- **Pages**: React components for different views.
- **Services**: API request functions.
- **Store**: Redux setup for state management.
- **Utils**: Utility functions.

## API Documentation
- [API Documentation](https://documenter.getpostman.com/view/29682764/2sA2xmVB3S)

## Database Design
- [Database Design](https://docs.google.com/document/d/1iWpAIfILl7cN4DK83MJfC0teh3CVMQW79ts3X503EkQ/edit?usp=sharing)

## Additional Optimizations

- **React + Vite**: Efficient setup for development

## Note
If TMDB API isn't accessible, try using VPN or change your DNS settings.
