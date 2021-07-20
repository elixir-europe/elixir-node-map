# ELIXIR Node map
A small project to generate a map of [ELIXIR Node institutes](https://elixir-europe.org/about-us/who-we-are). It can show all the institutes across Europe or you can set it to just show institutes from one country. 

The map uses [Leaflet.js](https://leafletjs.com/index.html) and [OpenStreetMap](https://www.openstreetmap.org/). It is intended to replace a Google Maps implementation. The Google maps are not visible to people with who are logged in to a Google account from an institute that does not pay for Google Maps, but that pays for other Google services. A very odd quirk!

## To-do
1. Dynamically generate a JSON dump of institutes from the [ELIXIR website](https://elixir-europe.org/) database, and pull this in instead of assets/coos-geojson.js. Maintenance of coos-geojson.js will be a nightmare otherwise.
