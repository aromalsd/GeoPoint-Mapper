# GeoPoint Mapper

## Overview
Location Mapping is a simple web-based application that visualizes geographic locations using latitude and longitude on an interactive map. The project is developed as part of Task 1A.
The application focuses on clarity, correctness, and controlled user interaction rather than excessive features.

## Features
- Manual input of latitude and longitude.
- Button-based location update (Show Location).
- To chose a coordinate, double click on the map.
- Automatic update of coordinate values after map interaction.
- Zoom in and zoom out controls.
- Toggle between Street View and Satellite View.
- Wrapping left to right across the map, yet stopping at top and bottom edges. 
- Coordinate display in multiple formats.

## Technologies Used
- HTML
- CSS
- JavaScript
- Leaflet.js
- OpenStreetMap tiles
- Esri World Imagery (Satellite View)

## How the Application Works
1. The user types coordinate numbers into designated boxes and location details go where marked, one after another without overlap. Entries appear line by line, each value placed.
2. On clicking the Show Location button or pressing the Enter key, the input values are validated.
3. Leaflet.js initializes the interactive map.
4. The map centers on the provided coordinates.
5. A marker is placed at the specified location.
6. a double click on the map allows the user to pinpoint another location.
7. When a location is selected on the map, the input fields and coordinate display update automatically.

## User Interaction
- Manual Input: Enter latitude and longitude and click Show Location.
- Keyboard Support: Press Enter after entering values to update the map.
- Map Interaction: Double-click anywhere on the map to place the marker.
- Navigation: Zoom controls are available for map navigation.
- Layer Control: Switch between street and satellite map views.

## Coordinate Display
Coordinates are displayed in:
- Decimal Degrees (DD)
- Degrees, Minutes, Seconds (DMS)

This allows users to clearly understand and verify geographic positions.

## Deployment
The application is deployed as a static web application and is publicly accessible via a web URL.
No backend server, database, or authentication is used.

## Testing & Validation
- Tested using known latitude and longitude values.
- Verified correct marker placement.
- Verified double-click map interaction.
- Tested zoom and layer toggle functionality.
- Verified behavior across standard web browsers.

## Limitations
- No reverse geocoding (place names are not displayed)
- Requires an active internet connection to load map tiles
- Accuracy depends on user-provided coordinate values
