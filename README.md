# 30 Day Map Challenge 2025

Repo for the **30 Day Map Challenge 2025**  
https://30daymapchallenge.com/  

This repo holds my daily solutions to each of the challenges :) 

---

## Day 01 — Points 📌

---

## Day 02 — Lines 📏

---

## Day 03 — Polygons 🛑

---

## Day 04 — My Data 🏃‍♀️

I used my Strava data from a multiday hike I did in New Zealand - the Kepler Track. I used QGIS to
- combine the different days GPX
- to create the elevation map using 8m DEM data from LINZ
- used the QuickOSM plugin for the water bodies (the lakes)

I touched it up on Photoshop and added icons and labels

![Day 5 Map](maps/day4/day4_final.png)


---

## Day 05 — Earth 🌍

For the Earth theme, I built an interactive 3D globe visualizing the [RESOLVE Ecoregions Dataset (2017) dataset](https://developers.google.com/earth-engine/datasets/catalog/RESOLVE_ECOREGIONS_2017).  
I converted the source shapefiles into vector tiles (Mapbox Tilesets) and rendered them using Mapbox GL JS’s globe projection. Each region is styled by biome, with hover interactions to explore ecosystems across the planet. 

![Day 5 Map](maps/day5/day5.png)

---

## Day 06 — Dimensions 🧊

A map of ocean depth using data from [GEBCO](https://www.gebco.net/data-products/gridded-bathymetry-data) overlayed with migration patterns of 20 humpback whales from [OBIS](https://obis.org/data/access/).

I picked a sample of male and female whales with most sightings and plotted their weekly moves in the last 20 years.

![Day 6 Map](maps/day6/day6.png)

---

## Day 07 — Acessibility 🏙️

A map of Sofia sidewalk quality using OSM data.

Sofia sidewalks are notoriously bad, especially in autumn/winter when it is raining and you don't know if you'll step on a tile and your foot will sink into a puddle...

Apparently [this OSM tag](https://wiki.openstreetmap.org/wiki/Key:smoothness) is user recorded so may not be 100% accurate but it is somewhat reflective of reality. 

![Day 7 Map](maps/day7/day7.png)

---

## Stack

- QGIS
- Mapbox GL JS
- Mapbox Tilesets  
- Python / GeoPandas  
- HTML + CSS  
- Kepler.gl
- Photoshop (for touch ups)

---

## Data

- OSM
- [RESOLVE Ecoregions Dataset (2017) dataset](https://developers.google.com/earth-engine/datasets/catalog/RESOLVE_ECOREGIONS_2017)
- [LINZ 8m DEM data (2012)](https://data.linz.govt.nz/layer/51768-nz-8m-digital-elevation-model-2012/)
- [GEBCO Ocean Bathymetry Data](https://www.gebco.net/data-products/gridded-bathymetry-data)
- [OBIS Whale Sighting Data](https://obis.org/data/access/)
