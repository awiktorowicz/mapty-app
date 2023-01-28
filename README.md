# Welcome to the Mapty Project

This is a simple workout tracking application that allows users to log their running and cycling workouts. The user's current location is used to initialize the map, and markers are placed on the map to indicate the location of each workout.

## Features
- Log running and cycling workouts
- View workout information such as date, location, distance, duration, and (for running) cadence or (for cycling) elevation gain
- View all logged workouts on a map

## Technologies Used
- JavaScript (ES6)
- HTML
- CSS
- Leaflet.js (for the map)
- Local storage (for saving workout data)

## How to Use
1. Allow the application to access your current location.
2. Click on the map to open the form to log a new workout.
3. Select the type of workout (running or cycling).
4. Input the distance and duration of the workout.
5. (For running) Input the cadence or (for cycling) the elevation gain.
6. Click on Enter to log the workout and place a marker on the map.
7. Click on a marker to view the workout information.

## Limitations
- Currently, the application only supports logging running and cycling workouts and does not support additional workout types.
- The application does not currently have a way to delete individual workouts, the user can only clear all workouts data.
- The application does not currently have a way to edit a workout.

## Future Improvements
- Add support for additional workout types.
- Add the ability to delete individual workouts.
- Add the ability to edit a workout.

Part of Jonas Schmedtmann course.
