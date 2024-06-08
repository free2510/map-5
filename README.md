# Map with Points of Interest

This project displays points of interest (POI) on a map using Mapbox. The points of interest are fetched from a Firebase database and plotted on the map as markers.

## Usage

To view the map with points of interest, open the following URL in a web browser:

https://free2510.github.io/map-5/index.html?firebaseUrl=https://smart-vilage-default-rtdb.firebaseio.com/locations.json?auth=AIzaSyCSMlIol-7KSVR22X7WS6uceayDyNZM3bM


## Parameters

- **firebaseUrl**: The URL of the Firebase database containing the points of interest data. The URL should be provided as a query parameter in the format:

?firebaseUrl=<FIREBASE_URL>

Ensure that the Firebase URL is properly authenticated if needed.

## Example

The following is an example URL that demonstrates how to use the application:

https://free2510.github.io/map-5/index.html?firebaseUrl=https://smart-vilage-default-rtdb.firebaseio.com/locations.json?auth=AIzaSyCSMlIol-7KSVR22X7WS6uceayDyNZM3bM


## Dependencies

- [Mapbox GL JS](https://docs.mapbox.com/mapbox-gl-js/api/)
- [Firebase](https://firebase.google.com/docs/web/setup)

## License

This project is licensed under the [MIT License](LICENSE).
