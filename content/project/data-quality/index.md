---
title: Data-driven GPS Travel Survey Data Quality Control
summary: A data-driven post-processing framework to enhance the data quality of smartphone-based travel survey data
tags:
  - Mobility
  - ML Stats
  - Research
date: '2023-10-15'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: 
  focal_point: Smart

links:
url_pdf: 'https://doi.org/10.1111/tgis.12865'
  
---
Smartphones are increasingly being used to collect detailed data on people's daily activities and trips. However, these smartphone-based travel surveys introduce new data quality issues compared to traditional paper or phone surveys. In this project, I developed a framework to systematically detect and address various quality issues in smartphone survey data.

The key data quality issues I focused on were <b>attribute completeness</b> (whether all required information is present for each trip/activity) and <b>logical consistency</b> (whether consecutive trips and activities align properly in time and space). 

My framework takes a data-driven approach to classify invalid records into groups using statistical methods, such as mixture models, clustering, and thematic transition matrix. Then tailored solutions are proposed for each group - like splitting short temporal gaps or extending spatial trajectories. I demonstrated this framework on a smartphone survey dataset from the Twin Cities and improved the data quality significantly.

For example, over 5,000 invalid records were systematically handled, reducing maximum speeds for car trips from nearly 25,000 m/s to reasonable values. Overall, this research enables more accurate analysis on daily mobility behaviors from emerging smartphone-based surveys.

The codes and detailed documents can be retrieved via my [GitHub Repo](https://github.com/YaxuanSeanZhang/GPS-Data-Quality).

Click to access the [full-text article](https://doi.org/10.1111/tgis.12865)
