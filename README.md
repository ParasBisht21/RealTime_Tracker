# RealTime_Tracker
Overview
This project is a real-time tracking application that allows users to share their live location on a map using Leaflet.js and Socket.io. The application uses Node.js for the backend and serves an EJS template for the front end. The real-time communication between clients is handled by Socket.io.

Features
Real-time location tracking.
Multiple users can see each other’s locations on the map.
Location updates are handled efficiently using WebSockets.
User-friendly interface with Leaflet.js for map visualization.

Prerequisites
Node.js
npm (Node Package Manager)

Description
public/: Contains static files like CSS and JavaScript.
css/style.css: Stylesheet for the application.
js/script.js: Client-side JavaScript for handling map and location updates.
views/: Contains the EJS template for rendering the HTML.
index.ejs: The main HTML file for the application.
package.json: Contains metadata about the project and lists dependencies.
server.js: The main server file where the Express app and Socket.io server are configured.
