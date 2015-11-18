# Maps

This is a webpage that employs the Google Maps Javascript API. Its function is to use HTML5 Geolocation to get the location of the user and map it to a destination (in this case, hardcoded). Allows user to search for waypoints before reaching his/her destination using the search box. Search results will appear on the map. They can be viewed with a single click and selected as a waypoint with a double click. Clicking "Route!" will route the user from his/her initial location to destination, stopping on all waypoints selected. User can choose to bike, drive, walk, or use public transit to reach destination.

I ran into an issue with Geolocation in Google Chrome as Chrome does not allow your location to be found if you simply open up the html file. I solved this issue by starting up a Python server (with Python 2.7.6). I ran "python -m SimpleHTTPServer 8000" in the correct directory and got to view my webpage at "http://localhost:8000/Maps.html". 
