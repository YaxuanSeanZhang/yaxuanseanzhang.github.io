---
title: Traffic Data Pulling and Forecasting
summary: Real-time traffic data pulling and modeling for trend comparision before and after Covid. 
tags:
  - Mobility
  - Data Pipeline
date: '2023-08-27'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: ''
  focal_point: Smart

links:
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''
---

In this project, I built a comprehensive pipeline based on the [`{tc.sensor}`](https://github.com/Metropolitan-Council/tc.sensors) for retrieving data from the MnDOT loop detectors, which are installed across the Minnesota Freeway system.

The pipeline operates on a nightly basis, facilitating the **aggregation** and **forecasting** of traffic volume. It enables the study of traffic trends throughout the Twin Cities freeway system, both before and after the COVID-19 pandemic. The resulting data is prepared to be seamlessly integrated into the [Rshiny app](https://metrotransitmn.shinyapps.io/freeway-traffic-trends/).

To estimate traffic that is robust to temporal fluctuations, the model relies on generalized additive models (GAM).The traffic trend GAMs consider three trends. 1) Travel typically increases in summer and decreases in winter annually. 2) Weekly, Friday sees the highest travel, while Sunday experiences the lowest. 3) Hourly models analyze traffic variations every 24 hours.


![The traffic trend GAMs consider three trends.](scale-plot.JPG)  

The codes and detailed documents can be retrieved via my [GitHub Repo](https://github.com/YaxuanSeanZhang/Traffic-Data-Pipeline).
