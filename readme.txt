This project uses Leaflet and Leaflet Routing Machine to create an interactive map that allows users to add markers and generate routes between them.

Initial View:

The map initially centers on the coordinates [19.2856, 72.8691] with a zoom level of 11.
A marker is placed at the initial coordinates.
Includes the Leaflet and Leaflet Routing Machine JavaScript libraries.

Adding a New Marker:

Click anywhere on the map to add a new marker.
A route will be generated between the initial marker and the newly added marker.

Routing:

The route will be displayed on the map.
The initial marker will move along the route to the new marker's location, with a small delay between each coordinate update.
You can modify the initial coordinates and zoom level by changing the parameters in L.map().setView().
The setTimeout function in the route generation section updates the marker's position with a delay, creating an animation effect.