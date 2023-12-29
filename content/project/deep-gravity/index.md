---
title: Generating Mobility Flow Using Deep Gravity Learning Model
summary: Predicting Human Mobility with Deep Learning
tags:
  - Mobility
  - ML Stats
date: '2023-08-16'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: 
  focal_point: Smart

links:

---
In this project, we developed a deep neural network model to predict human mobility flows between locations in cities. Understanding these flows is crucial for transportation planning and urban design.

We used a device-level mobile positioning dataset from PlaceIQ to create a ground truth mobility flow network at the 3-km grid level. We also incorporated external weather data on temperature and precipitation interpolated across our study area.

![weather](weather.jpg)

Our model architecture follows previous work, with multiple parallel neural network structures. For each origin-destination pair, we input place characteristics (e.g. land use, points of interest) and weather conditions. The output is a score representing the likelihood of a trip occurring.

We compare this deep learning approach to a gravity model, a standard method that decreases predicted flows with distance and increases them with population size.

![diagram](diagram.jpg)

The deep learning model outperformed gravity on Common Part of Commuters (CPC) and Pearson correlation coefficient(<i>r</i>). Incorporating weather data further improved the neural network's performance. This shows both urban features and environmental factors influence human movement.

The codes and detailed documents can be retrieved via my [GitHub Repo](https://github.com/YaxuanSeanZhang/deep-gravity).
