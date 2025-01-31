# Travel App Project

## Overview
This Travel App project is a web application that helps users plan their trips. It integrates multiple APIs to provide information about the destination, including weather forecasts, images, and other relevant details.

## Requirements
- Node.js version: **20.15.1**
- npm version: **Latest compatible**



## Features

- **Destination Autocomplete**: Suggests destinations as the user types, using the Geonames API.
- **Weather Forecast**: Provides weather information for the destination on the specified date, using the Weatherbit API.
- **Image Gallery**: Displays images of the destination using the Pixabay API.
- **Trip Details Display**: Shows detailed information about the trip, including location, date, weather, and images.
- **Local Storage**: Saves trip data locally for future reference.

## Dependencies
- Express
- Body-Parser
- Cors
- Node-fetch
- Path
- jQuery
- SwiperJS (for image gallery)
- Datepicker


## Installation and Setup
To run this project, you'll need Node.js and npm installed on your system.

1. Clone the repository:
git clone https://github.com/islammosmar1/travel-app.git

2. Navigate to the project directory:
cd travel-app

3. Install the dependencies:
npm install

4. Start the server:
npm start

5. Open `http://localhost:8082` in your browser.

## Usage
Enter your travel destination and date to get detailed information including weather forecasts and images.

## Contributing
Contributions to this project are welcome. Please fork the repository and submit a pull request with your updates.

## License
This project is licensed by Udacity.

## Acknowledgments
- Geonames API for location data
- Weatherbit API for weather forecasts
- Pixabay API for images
