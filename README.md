# Aquila Vision

Aquila Vision is a web-based dashboard designed to monitor real-time data from smart bulletproof vests, particularly useful for military personnel or private security companies. The system allows for tracking vital signs, impact alerts, and location data, creating a safer environment for the wearer by facilitating remote monitoring and quick response.

## Features

- Smart Bulletproof Vest Dashboard: Displays vest IDs and critical information such as heart rate, impact alerts, and location.
- Real-time Map Integration: Monitors the wearer's location with live updates on Google Maps.
- Stopwatch: Built-in stopwatch functionality for mission timing.
- Heart Rate Monitor: Tracks heart rate with an animated waveform and provides real-time alerts if abnormal readings are detected.
- Impact Detection: Alerts the user if a significant impact is detected on the vest.

## Technologies Used

- HTML/CSS/JavaScript: Core web development technologies used to build the user interface.
- Google Maps API: For real-time location tracking and marker updates.
- Canvas API: For rendering a real-time heart rate waveform.
- Simulated Real-time Data: Updates include randomized location and heart rate data to mimic real-world functionality.

## Project Structure

bash
.
├── index.html       # Main HTML file
├── index.css        # Styling for the layout
├── menutab.css      # Additional styling for the menu tab
├── index.js         # Main JavaScript logic for the dashboard
├── images/          # Folder for image assets like logos and icons
└── README.md        # Project documentation


## How to Use

1. Clone the repository:
   bash
   git clone https://github.com/username/aquila-vision.git
   

2. Open the `index.html` file in your preferred browser.

3. The dashboard will load with real-time simulated data. You can:
   - View the location and data of bulletproof vests.
   - Monitor heart rates and receive alerts for abnormal readings.
   - Track the wearer's location via the integrated Google Map.
   - Start the stopwatch for timing operations.

## Future Enhancements

- Integration with actual hardware for real-time data.
- Improved UI/UX for enhanced usability.
- Backend support for data storage and retrieval.

## Acknowledgements

- This project utilizes the Google Maps API for real-time location tracking.
- The UI and logic are designed for future integration with real-world military applications.

