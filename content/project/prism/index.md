---
title: SpatioTemporal Mobility Pattern Analytics
summary: Examining Home and Work Anchors in Daily Life Using GPS Data
tags:
  - Mobility
  - ML Stats
  - Research
date: '2023-10-16'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: 
  focal_point: Smart

links:

links:
url_pdf: 'https://link.springer.com/article/10.1007/s11116-022-10352-2'

---
New research I conducted examines whether home and work activities can serve as “anchors” that structure people’s daily schedules. Using GPS-enabled survey data collected in Minnesota and Beijing, I developed methods to extract personalized home and work anchors for each person based on the spatial and temporal fixity of these activities across multiple days.

The framework is illustrated as the figure below:

![framework](framework.jpg)

The methods involve:

* Analyzing GPS trajectory shapes to identify stationary vs non-stationary activities
* Grouping stationary activity locations using clustering algorithms
* Calculating the repetitive ratio of activities across days
* Detecting repetitive intervals of activities at each location
* Together, these steps determine if an activity repetitively occurs at fixed location(s) and can serve as an anchor.

The key findings suggest that:

* Not everyone has clear home or work anchors. About 10% of people perform home activities outside their reported neighborhood.
* People with similar demographics tend to have similar anchor patterns. For example, full-time employees are most likely to have work anchors.
* Some people have multiple home or work anchors, challenging the assumption that everyone has a single, fixed home and workplace.

Accounting for personalized anchors better captures the complexity of daily mobility patterns. I illustrated how using multiple home and work anchors expands the measured person-based accessibility space.

![accessibility](accessibility.jpg)

The codes and detailed documents can be retrieved via my [GitHub Repo](https://github.com/YaxuanSeanZhang/Spatial-Temporal-Prism).

Click to access the [full-text article](https://link.springer.com/article/10.1007/s11116-022-10352-2)
