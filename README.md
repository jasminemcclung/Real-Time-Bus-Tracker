# Real-Time-Bus-Tracker

## Adding animation to maps

<img src= "map.png"width='300'/>

In this animation exercise, the objective was to show every bus stop between the MIT and Harvard campuses and utilize the Mapbox open source platform to create and display a map on a web page, which would ilustrate with a marker the location of each stop second by second, beginning at the MIT campus until arrival at the Harvard campus. 

I created a Mapbox account to get the access token to access the mapboxgl instance defined in the bus_tracker.js file. Then, I created a marker and added it to the map using the mapboxgl pre-built function. Then, I created the function move() to be called when the button "Show stops between MIT and Harvard" is selected. This is how you can start the marker animation. After clicking the button, the setTimeout function nested within the function move will make each bus stop located along the way appear on the map every second, as the previous one disappears, until reaching the destination.

Licenced by MIT 'Full Stack Development with MERN program for educational purposes only.
