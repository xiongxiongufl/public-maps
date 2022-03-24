# public-maps

This repository hosts some popular public map data accessible over HTTPS.

## How to use

Raw map data is accessible by adding `?raw=true` to the url of the source.

```python
import geopandas
world_countries = geopandas.read_file("https://github.com/xiongxiongufl/public-maps/blob/main/countries/World_Countries_(Generalized).zip?raw=true")
print(world_countries.head())
```

## Catalog

### World Continents

[World Continents](https://hub.arcgis.com/datasets/esri::world-continents/about) provides a base map layer of the continents for the world.

Data Updated: October 26, 2021

Published Date: June 29, 2013

### World Countries Generalized

[World Countries (Generalized)](https://hub.arcgis.com/datasets/esri::world-countries-generalized/about) provides optimized country boundaries with useful name and country code attribute fields. Current to November 2019.

Data Updated: April 14, 2021

Published Date: December 21, 2019

