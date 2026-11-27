# barycadabra-cdn

Data files read by [barycadabra](https://github.com/bricadabra/barycadabra), served
by GitHub Pages and read with HTTP range requests. Generated and replaced as a
whole: do not edit, do not open pull requests.

| File | Content |
| --- | --- |
| `manifest.json` | zooms, offsets, decoding, reach, files, counts, sources |
| `mesh-{car,bike,foot}.pmtiles` | travel-time mesh of a mode: Web Mercator tiles (z8 / z9 / z10), binary payload, gzip |
| `venues-{bar,cafe,restaurant,park,station}.pmtiles` | venues of a category: vector tiles (MVT), layer `venues`, zoom 10 |

Data © [OpenStreetMap](https://www.openstreetmap.org/copyright) contributors,
[ODbL 1.0](https://opendatacommons.org/licenses/odbl/). Travel times measured
with [OSRM](https://project-osrm.org/) at build time.
