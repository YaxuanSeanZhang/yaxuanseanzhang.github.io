---
title: Invasive Species Geo-simulation System
summary: An example of using the in-built project page.
tags:
  - Data Pipeline
date: '2023-04-30'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: 
  focal_point: Smart

links:

---
This project developes a real-time pipeline system to monitor the spread of the stink bug in Minnesota. The pipeline leverages three distinct models - Gravity, Monte Carlo, and Huff - to simulate the potential dispersion patterns of this invasive species on a monthly basis.

The automated system processes the simulation outputs and subsequently uploads the results to a <i>PostGIS</i> database. It employs <i>Google Cloud</i> service and <i>Flask</i> application to host the resulting map layers. The final spread pattern map is presented in GeoJSON format and uploaded to <i>ArcGIS Online</i> for easy access and visualization.

The codes and detailed documents can be retrieved via my [GitHub Repo](https://github.com/YaxuanSeanZhang/Geo-simulation-System).

