# Smorrery: a simple orrery app

## Demo
(https://drive.google.com/file/d/1n4XBMjihIupCVz_MHQmb5AzGiEtHELOf/view?usp=sharing)

## Description

1. The **index page** offers a streamlined interface for viewing [Near-Earth Object](https://en.wikipedia.org/wiki/Near-Earth_object) (NEO) data retrieved from NASA's SBDB API.
2. The **orrery web app** simulates the orbital motion of the eight planets in our solar system from 1900 to 2100. Users can adjust the simulation speed via a control panel and toggle visual elements such as orbits, labels, and axes for enhanced viewing. 

## Usage

1. Create a Python virtual environment and install the packages listed in `requirements.txt`.
2. Run `flask run` in shell to launch the Flask development server locally.
3. Open a browser and access the index page at `http://127.0.0.1:5000/`.
4. Access the orrery web app at `http://127.0.0.1:5000/orrery`.

## Features 

- Render the traces of 20 NEOs.
- Add textures for the Sun and planets.
- Include a starry sky background with Milky Way.
- Add rings of Saturn 
- Hovering over celestial objects with the mouse triggers a green glow
- Clicking on the mesh or label of a celestial object displays its information, currently printed in the console


## References
- Orbital mechanics
    - [*Approximate Positions of the Planets*](https://ssd.jpl.nasa.gov/planets/approx_pos.html) provides the Keplerian elements of the 8 planets and some useful formulae.


- Domain knowledge: 
    - [**orbital mechanics**](https://en.wikipedia.org/wiki/Orbital_mechanics)
    - [**orbital elements**](https://en.wikipedia.org/wiki/Orbital_elements)
    - [**Kepler's equation**](https://en.wikipedia.org/wiki/Kepler%27s_equation)


- APIs
    - [NASA SBDB Query API](https://ssd-api.jpl.nasa.gov/sbdb_query.api)  — API
    - [NASA SBDB Query API](https://ssd-api.jpl.nasa.gov/doc/sbdb_query.html) — document, description about the parameters
    - [NASA Small-Body Database Query](https://ssd.jpl.nasa.gov/tools/sbdb_query.html) — GUI tool 
  

