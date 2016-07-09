# MBS compatible vector tiles

This is a project to test [ClearTables](https://github.com/ClearTables/ClearTables) by creating vector tiles compatible with [Mapbox Streets Basic for Mapbox Studio](https://github.com/ClearTables/mapbox-studio-streets-basic.tm2).

## Resources
* https://github.com/ClearTables/mapbox-gl-styles
* https://github.com/ClearTables/mapbox-studio-streets-basic.tm2

## Usage

1. Clone this project

2. Import data with [ClearTables](https://github.com/ClearTables/ClearTables)

3. Set the `source` of the tm2 project to point at the location of this project on disk, e.g. `source: "tmsource:///home/osm/mbs-compatible.tm2source"`
