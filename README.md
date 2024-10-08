
# Map Integration Project
## Project Overview
This project integrates an interactive map using the Mapbox API, allowing users to search for locations, track their current position, switch between various map styles, and get directions to a destination. It is designed to be user-friendly and responsive for different screen sizes.

## Technologies Used
- **HTML5**: Structuring the web pages.
- **CSS3**: Styling for visual elements.
- **JavaScript (ES6)**: Adding interactivity and handling map functionalities.
- **Mapbox GL JS**: For rendering the map and handling geolocation.
- **Mapbox Directions API**: Providing route directions from the user’s location.

## Features

### 1. **Mapbox GL JS Integration**
   - This feature integrates Mapbox GL JS to provide users with an interactive and customizable map.
   - **Why**: It enables users to explore locations and visualize routes in real-time.
   
### 2. **Geolocation Tracking**
   - The project allows users to track their current location using geolocation services.
   - **Why**: Tracking the user’s location helps in providing personalized directions based on where the user is.

### 3. **Directions Feature**
   - Users can get real-time directions from their current location to a specific destination.
   - **Why**: Simplifies navigation by showing users the most efficient route based on live data.

### 4. **Map Style Switcher**
   - This feature allows users to switch between different map styles such as Streets, Satellite, Outdoors, etc.
   - **Why**: It provides flexibility for users who may prefer different map views for specific tasks.

### 5. **Custom Destination Marker**
   - A custom marker is displayed on the map for highlighting important destinations.
   - **Why**: It adds visual clarity and helps users identify key locations quickly, like Delhi.

## Project Structure
```plaintext
├── index.html          # Main landing page with welcome card
├── home.html           # Main map interface with Mapbox features
├── style.css           # Styling for index.html and other UI elements
├── home.css            # Styling for map interface and controls
├── home.js             # JavaScript for map interaction, geolocation, and directions
├── giphy.gif           # Favicon for the website
```

## Usage
1. Open `index.html` to access the welcome screen.
2. Click the "Go to Website" button to open the main map interface (`home.html`).
3. Use the map controls to:
   - **Track your location** using the geolocation feature.
   - **Get directions** from your current location to a destination.
   - **Switch map styles** between Streets, Satellite, Outdoors, etc.
   
## Welcome Page : 
![image](https://github.com/user-attachments/assets/2e8bb322-8092-4f22-a741-99d32310613c)

## Home Page : 
![image](https://github.com/user-attachments/assets/ec24b2dc-c9a0-424b-ab0e-82fa51d18cb0)

