# Marriott Bonvoy Homes and Villas
![image](https://github.com/user-attachments/assets/f3324d01-4048-40cb-803d-40ff99a479ad)


A responsive web application for browsing and discovering Marriott Bonvoy Homes and Villas vacation rentals across the world. This project features an interactive map, destination recommendations, and a user-friendly interface.

## Project Overview

This web application helps users discover vacation destinations based on their preferences (city, beach, or mountains). The interface includes:

- Interactive destination map using OpenLayers
- Destination recommendations based on user preferences
- Responsive design for all device sizes
- Navigation menu with destination dropdown
- Filtering functionality for property types

## Features

- **Preference Selection**: Users are prompted to choose their travel preference (city, beach, or mountains) when the page loads
- **Dynamic Recommendations**: Destination recommendations update based on user preferences
- **Interactive Map**: Clickable map with location pins that display destination images
- **Destination Navigation**: Quick access to destinations via dropdown menu
- **Responsive Cards**: Destination cards with hover effects for better user experience

## Technologies Used

- HTML5 & CSS3
- JavaScript (ES6+)
- Bootstrap 5 for responsive layout
- OpenLayers for interactive mapping
- SweetAlert for modals

## Project Structure

- `index.html` - Main HTML structure
- `style.css` - Custom styling
- `script.js` - Core application functionality
- `places.js` - Destination data
- `provided.js` - Helper functions and map configuration
- `assets/` - Images, fonts, and other resources

## Core Functionality

The application implements several key functions:

- `filterPlacesByType(typePreference)`: Filters destinations by type (city, beach, mountains)
- `createCard(place)`: Generates HTML cards for each destination
- `populateRecommendationCards(filteredPlaces)`: Populates the recommendation section with filtered destinations
- `findPlaceByName(placeName)`: Locates a specific destination by name
- Map interaction with destination pins and popup information

## Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- Node.js and npm (if you want to run it locally with a server)

### Installation

1. Clone the repository:
   ```
   git clone [repository-url]
   ```

2. Navigate to the project directory:
   ```
   cd marriott-homes-and-villas
   ```

3. Install dependencies:
   ```
   npm install
   ```

4. Start the development server:
   ```
   npm start
   ```

5. Open your browser and visit `http://localhost:5000`

## Usage

1. When the application loads, select your preferred destination type (City, Beach, or Mountains)
2. Browse the recommended destinations that appear in the cards section
3. Click on any destination card to center the map on that location
4. Explore destinations via the interactive map by clicking on pins
5. Use the navigation dropdown to quickly jump to specific destinations

## Future Enhancements

- Adding search functionality for specific destinations
- Implementing date selection for trip planning
- Adding user authentication for saved favorites
- Expanding destination database
- Adding property details and booking functionality

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Marriott Bonvoy for inspiration
- OpenLayers for the mapping library
- Bootstrap team for the responsive framework
