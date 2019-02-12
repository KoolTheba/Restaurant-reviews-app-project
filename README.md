# Restaurant Reviews App

## Project Overview

This is an App for restaurant's reviews and location in a map. It' responsive and accessible (tab and aria-roles).

![screenshot](other/restaurant_reviews_app.png)

### How to run it

1. Clone this repository
2. In this folder, start up a simple HTTP server to serve up the site files on your local computer. Python has some simple tools to do this, and you don't even need to know Python. For most people, it's already installed on your computer.
    * In a terminal, check the version of Python you have: `python -V`. If you have Python 2.x, spin up the server with `python -m SimpleHTTPServer 8000` (or some other port, if port 8000 is already in use.) For Python 3.x, you can use `python3 -m http.server 8000`. If you don't have Python installed, navigate to Python's [website](https://www.python.org/) to download and install the software.
    * Note -  For Windows systems, Python 3.x is installed as `python` by default. To start a Python 3.x server, you can simply enter `python -m http.server 8000`.
3. With your server running, visit the site: `http://localhost:8000`, and enjoy!!

## Leaflet.js and Mapbox:

This app uses [leafletjs](https://leafletjs.com/) with [Mapbox](https://www.mapbox.com/). You need to add your token in the file `js/config.js`. Mapbox is free to use, and does not require any payment information.


