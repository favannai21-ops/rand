# Little Weather Lab

Little Weather Lab is a small, responsive weather dashboard and an interactive playground for learning how scalar neurons and recurrent state work. It is a single HTML file with no build step, package installation, or external JavaScript dependencies.

## Run it

Open `index.html` in a modern browser. An internet connection enables live forecasts from the Open-Meteo geocoding and weather APIs. Search for a city, switch between Celsius and Fahrenheit, and see current conditions alongside the next five days. If the APIs are unreachable or a city cannot be found, the app shows clearly labeled sample weather instead.

## Play and learn

- **The Neuron Mix Deck:** Adjust the input, weight, and bias cards; choose `tanh`, ReLU, or linear activation. The displayed equation and output update from the scalar neuron calculation.
- **The Melody Memory Deck:** Deal note cards into a short sequence and adjust its note weight, memory weight, and bias. Each step shows the recurrent hidden-state calculation and a note suggested by the final state. Clear the hand to start over.

These are transparent JavaScript learning demos, not PyTorch running in the browser. The weather dashboard and learning cards are designed to work together in one narrow, responsive page, with colors adapting to the system light/dark preference.
