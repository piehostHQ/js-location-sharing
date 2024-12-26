# Real-Time Geolocation
Real-Time Geolocation and Routing Map with Leaflet and PieSocket
This project demonstrates a real-time map application using Leaflet.js for mapping and routing and PieSocket for real-time communication. The app enables users to visualize their location, click on the map to add destination markers, and broadcast location updates and routes to other connected users.

### Features
Real-Time Geolocation
Automatically fetch and display the user's current location on the map using the browser's Geolocation API.

### Interactive Map
Users can click on the map to set a destination marker. The app calculates and displays the route between the user's location and the destination using Leaflet Routing Machine.

### Real-Time Updates
User location and routing data are broadcast and synchronized in real-time across all connected clients using PieSocket.

### Dynamic Marker Updates
User markers and destination markers are dynamically updated as location changes or new routes are set.

### Technologies Used
Leaflet.js: For interactive maps and routing.
PieSocket: For real-time communication via WebSockets.
HTML5 Geolocation API: To fetch the user's location.
Installation
Clone the repository:

```bash
git clone https://github.com/your-username/real-time-geolocation.git
cd real-time-geolocation
```
Open the project directory and serve the HTML file using a local server:
