### Road Routing
Introducing the road routing module - a powerful tool designed to quickly display road route maps in Mendix. With just a few input waypoints in the form of latitude and longitude, this module generates a clear and accurate map in mere minutes. Built on the reliable Leaflet framework, this module guarantees accurate and up-to-date information.
The module comes equipped with a microflow that includes sample values, allowing users to easily change the waypoints of the route.

## Module Setup
1. Open your project directory, Copy index.html file from deployment->web and paste it to theme->web folder.
2. Open index.html from theme->web folder. Paste the below dependencies at the top of head section.

<link rel="stylesheet" [href="https://unpkg.com/leaflet@1.9.3/dist/leaflet.css
(mailto:href=%22https://unpkg.com/leaflet@1.9.3/dist/leaflet.css)" integrity="sha256-kLaT2GOSpHechhsozzB+flnD+zUyjE2LlfWPgU04xyI="
crossorigin="" />
<script [src="https://unpkg.com/leaflet@1.9.3/dist/leaflet.js](mailto:src=%22https://unpkg.com/leaflet@1.9.3/dist/leaflet.js)" integrity="sha256-WBkoXOwTeyKclOHuWtc+i2uENFpDZ9YPdf5Hf+D7ewM=" crossorigin=""></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/leaflet-routing-machine/3.2.5/leaflet-routing-machine.js"></script>
<script src="https://rawgit.com/perliedman/leaflet-routing-machine/master/examples/Control.Geocoder.js"></script>'

While the current version of the module supports road routing exclusively, rest assured that future iterations will introduce a range of new features and functionalities related to maps.

## Future release:

* Marker setup
* Annotation shows in map
* Image,video overlay on maps

## Dependencies:

Mendix studio pro version 9.6.0 or above.
