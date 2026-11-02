# Grid Down street maps

Offline street maps for the Grid Down: 100-Day Prep app, one file per U.S. state.

- Built from OpenStreetMap by `.github/workflows/maps.yml` (Geofabrik extracts → Planetiler, OpenMapTiles schema).
- Published as release assets under the `streets-v1` tag. The app downloads them from there.
- `.github/workflows/pages.yml` copies a few states to GitHub Pages for the browser preview.

Map data © [OpenStreetMap contributors](https://www.openstreetmap.org/copyright), available under the Open Database License. Map layout © [OpenMapTiles](https://openmaptiles.org/) (CC BY 4.0).
