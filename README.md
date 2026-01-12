# Location-Mapping
A simple web-based application that visualizes geographic locations using latitude and longitude on an interactive map. Built using HTML, JavaScript, and Leaflet.js as part of a hackathon software task.

The map updates dynamically when:
- Coordinates are entered manually
- The marker is dragged
- Picking a spot happens when someone taps twice on the screen. The map reacts right after those two quick presses. Two clicks lock in where you want to be.

This project is developed as part of the Task 1A.

## Technologies Used
- HTML
- CSS
- JavaScript
- Leaflet.js
- OpenStreetMap tiles
  
## How the Application Works

1. The user enters latitude and longitude values in the input fields.
2. From there, JavaScript grabs what's needed before sending it off into the mapping process.
3. A starting point appears when Leaflet.js loads the map.
4. Right where those numbers point, that is what fills the middle of the picture.
5. A marker is placed at the specified location.
6. When the input values change, the marker position and map center are updated dynamically.

## User interactions features 
- Manual input of latitude and longitude values.
- Double click on the map to place the marker.
- Automatic update of input fields when a location is selected on the map.
- Zoom in and zoom out controls for navigation.

## Coordinate Display
Coordinates show up on screen like this:
- Decimal Degrees (DD)
- Degrees Minutes Seconds (DMS)

This helps user clearly understand the exact geographic positions.

## Run and test
1. Open the deployed website link.
2. Enter valid latitude and longitude values.
3. Observe the marker update on the map.
4. Double click anywhere on the map to move the marker.
5. Moving the marker changes the position numbers right away.

## Deployment
The application is deployed as a static web application and is publicly accessible via a web URL.
No backend server or database is used.

## Testing & Validation
- Tested by entering known latitude and longitude values.
- Verified marker placement on correct locations.
- Tested map interactions such as zooming, double-clicking, and dragging.
- Verified functionality on standard web browsers.

## Limitations
- No reverse geocoding (place names not shown)
- Requires internet connection for map tiles
- Precision depends on user-provided coordinates
