# map
This is the main map of restaurants

## Find me, Directions and Copy address

`map-tools.js` is the same file as `js/map-tools.js` in the members site repo (officeOfTheNines/site): change it there and copy it here.

- **Find me**: a round button under the zoom buttons. Only when tapped does it ask the browser for the position; it shows a blue dot with its accuracy circle and centres the map. If the position is refused, unavailable or too slow, a short message says so. The position is never sent, logged or stored.
- **Directions**: in the restaurant panel, a gold button next to View menu opening Google Maps directions by public transport from where the person is (`https://www.google.com/maps/dir/?api=1&destination=<name, address, postcode>&travelmode=transit`; the coordinates when the name or address is missing).
- **Copy address** under the address copies "name, address, postcode".
- Labels: English (Directions, Copy address, Show my location).
