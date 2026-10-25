 <div align="center">

# Vyom

*Somewhere between here and infinity.*

[Live Demo](https://vyomx.pages.dev/) · [GitHub Repository](https://github.com/Adarsh-61/Vyom)

</div>

<p align="center">
  <a href="https://www.youtube.com/watch?v=28LYppE14Vc">
    <img src="https://img.youtube.com/vi/28LYppE14Vc/hqdefault.jpg" alt="Vyom demo" width="640">
  </a>
</p>

## About

Vyom is a browser-based 3D space visualization. It includes objects from the Solar System, stars, galaxies, and models of space missions.

You can search for objects, move around the scene, change views, use guided tours, and control simulation time.

## Features

- **Solar System:** The Sun, eight planets, selected moons, dwarf planets, asteroids, and comets.
- **Deep Space:** Selected stars, exoplanets, nebulae, star clusters, galaxies, black holes, and pulsars.
- **Space Missions:** Models of Chandrayaan-1, its Moon Impact Probe, Chandrayaan-2, and Chandrayaan-3.
- **Other Models:** Tesla Roadster, Starman, and a theoretical white hole.
- **Navigation:** Object search, zoom, focus controls, different views, and guided tours.
- **Time Controls:** Change the simulation time and its speed.

## Accuracy

Vyom uses astronomical data and references, but it is not a scientific simulator. Some objects are simplified or procedurally generated, and sizes and distances are adjusted for visualization. Not every object or physical effect is represented accurately.

## Run Locally

1. Download the [Vyom repository](https://github.com/Adarsh-61/Vyom) as a ZIP file.
2. Extract it.
3. Open a terminal in the extracted `Vyom` folder.
4. Run:

   ```bash
   python -m http.server 8000
   ```

   On Windows, you can use:

   ```bash
   py -m http.server 8000
   ```

5. Open [http://localhost:8000](http://localhost:8000).

Keep the terminal open while using Vyom. Opening `index.html` directly may not work because the project uses JavaScript modules.

Vyom requires a modern browser with WebGL support. An internet connection is needed for some libraries, data, and textures.

## Technology

- Three.js r160
- WebGL and GLSL shaders
- HTML, CSS, and JavaScript
- HTML Canvas 2D fallback
- d3-celestial star catalogue data
- WebP textures and external assets

## Credits

Thanks to the people and projects whose work and resources are used in Vyom.

- [Three.js](https://github.com/mrdoob/three.js) for 3D rendering.
- [Solar System Scope](https://www.solarsystemscope.com/textures/) for planetary and Moon textures.
- [N3rson/Solar-System-3D](https://github.com/N3rson/Solar-System-3D) for referenced Solar System assets.
- [threex.planets](https://github.com/jeromeetienne/threex.planets) by Jerome Etienne for planetary textures.
- [d3-celestial](https://github.com/ofrohn/d3-celestial) by Olaf Frohn for star catalogue and Milky Way data.
- [NASA](https://science.nasa.gov/solar-system/) for Solar System reference material.
- [NASA Exoplanet Archive](https://exoplanetarchive.ipac.caltech.edu/) for exoplanet information.
- [ISRO](https://www.isro.gov.in/) for information about Indian space missions.

Thanks to all the developers, data contributors, and creators behind these resources.

## Contributing

Found a bug or have an idea? Open an [issue](https://github.com/Adarsh-61/Vyom/issues).

You can also fork the repository and submit a [pull request](https://github.com/Adarsh-61/Vyom/pulls).

For new data or assets, include the source and licence.

## License

Vyom's source code is released under the [MIT License](https://github.com/Adarsh-61/Vyom/blob/main/LICENSE). Third-party assets and libraries may have separate licence terms.
