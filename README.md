# 🦁 Animal GPS Tracker

An interactive web-based dashboard for tracking and visualizing animal movements in a wildlife reserve.

## 📋 Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Setup](#setup)
- [Usage](#usage)
- [Project Structure](#project-structure)

## ✨ Features

- 🗺️ Real-time animal tracking on an interactive map
- 📊 Dynamic statistics display (food eaten, missed, circle touches)
- 📈 Movement chart for individual animal analysis
- 🦒 Support for multiple animal types
- 🍎 Food throwing simulation
- 🔴 Inner and outer boundary circles
- 📱 Responsive design for various screen sizes

## 🛠️ Technologies Used

- **HTML5**: Structure of the web application
- **CSS3**: Styling and responsive design
  - 🎨 Custom styles for a modern, clean interface
  - 📐 Flexbox and Grid for layout
  - 🖥️ Media queries for responsiveness
- **JavaScript (ES6+)**: Core functionality and interactivity
- **Google Maps JavaScript API**: 🗺️ Map rendering and geolocation features
  - Marker creation and management
  - Circle overlays for boundaries
  - Distance calculations
- **Chart.js**: 📊 Data visualization for animal movements
- **Google Fonts**: 🖋️ Custom font (Poppins) for improved typography

## 🚀 Setup

1. Clone the repository to your local machine.
2. Replace `YOUR_API_KEY` in the Google Maps API script tag with your actual API key.
3. Open the `index.html` file in a modern web browser.

## 🖱️ Usage

- The map displays the current location of all tracked animals.
- Click on an animal in the "Tracked Animals" list to focus on it and view its movement chart.
- Statistics are updated in real-time, showing food interactions and boundary touches.
- The movement chart displays the selected animal's activity over time.

## 📁 Project Structure

- `index.html`: Main HTML file containing the structure and inline JavaScript
- Styles are included in the `<style>` tag within the HTML file
- JavaScript code is embedded in the `<script>` tag, including:
  - Animal and person data
  - Map initialization
  - Animal movement simulation
  - Chart creation and updates
  - Food throwing simulation

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check [issues page](link-to-your-issues-page) if you want to contribute.

## 📄 License

This project is [MIT](link-to-your-license-file) licensed.
